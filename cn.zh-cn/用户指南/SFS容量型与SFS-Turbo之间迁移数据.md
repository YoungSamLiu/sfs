# SFS容量型与SFS Turbo之间迁移数据<a name="sfs_01_0117"></a>

## 背景说明<a name="section38323714281"></a>

用户可以将SFS容量型文件系统中的数据迁移至SFS Turbo文件系统中，也可以将SFS Turbo文件系统中的数据迁移至SFS容量型文件系统中，进行云上业务拓展。

此方案通过创建一台Linux操作系统的云服务器，来连接SFS容量型文件系统和SFS Turbo文件系统的通信。

## 约束与限制<a name="section2217941193119"></a>

-   仅支持使用Linux系统的云服务器进行数据迁移。
-   Linux系统云服务器、SFS容量型文件系统和SFS Turbo文件系统需在同一VPC下。

## 操作前提<a name="section1689695774314"></a>

-   已创建一台操作系统为Linux的云服务器。
-   已创建SFS容量型和SFS Turbo文件系统，并获取到文件系统的挂载地址。

## 操作步骤<a name="section4954112712376"></a>

1.  登录弹性云服务器管理控制台。
2.  登录已创建好的Linux系统云服务器，用于同时访问SFS容量型文件系统和SFS Turbo文件系统。
3.  输入以下挂载命令，用于访问文件系统1。文件系统1可以是SFS容量型文件系统或SFS Turbo文件系统。

    ```
    mount -t nfs -o vers=3,timeo=600,noresvport,nolock 文件系统1挂载地址 /mnt/src
    ```

4.  输入以下挂载命令，用于访问文件系统2。文件系统2可以是SFS容量型文件系统或SFS Turbo文件系统。

    ```
    mount -t nfs -o vers=3,timeo=600,noresvport,nolock 文件系统2挂载地址 /mnt/dst 
    ```

5.  在Linux云服务器中执行以下命令安装rclone工具。

    ```
    wget https://downloads.rclone.org/v1.53.4/rclone-v1.53.4-linux-amd64.zip --no-check-certificate
    unzip rclone-v1.53.4-linux-amd64.zip
    chmod 0755 ./rclone-*/rclone
    cp ./rclone-*/rclone /usr/bin/
    rm -rf ./rclone-*
    ```

6.  执行以下命令，进行数据同步。

    ```
    rclone copy /mnt/src /mnt/dst -P --transfers 32 --checkers 64
    ```

    >![](public_sys-resources/icon-note.gif) **说明：** 
    >参数说明如下，transfers和checkers数目可以根据系统规格自行配置：
    >-   transfers：传输文件的并发数目。
    >-   checkers：扫描文件的并发数目。
    >-   P：数据拷贝进度。

    等待数据完成同步后，可前往目标文件系统查看是否已成功迁移。


