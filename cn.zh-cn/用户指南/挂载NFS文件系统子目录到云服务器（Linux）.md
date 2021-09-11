# 挂载NFS文件系统子目录到云服务器（Linux）<a name="sfs_01_0127"></a>

本章节介绍如何将NFS文件系统的子目录挂载至Linux云服务器上。

## 前提条件<a name="section1650431101913"></a>

已参考[挂载NFS文件系统到云服务器（Linux）](https://support.huaweicloud.com/qs-sfs/zh-cn_topic_0034428728.html)成功将文件系统挂载至Linux云服务器上。

## 操作步骤<a name="section189412146193"></a>

1.  执行如下命令，在本地路径下创建文件系统的子目录。

    **mkdir** _本地路径__/子目录_

    >![](public_sys-resources/icon-note.gif) **说明：** 
    >本地路径：云服务器上用于挂载文件系统的本地路径，例如“/local\_path“。与挂载根目录时的本地路径保持一致。

2.  执行如下命令，将文件系统子目录挂载到与文件系统所属VPC相同的云服务器上。文件系统目前仅支持NFSv3协议挂载到Linux云服务器。

    **mount -t nfs -o vers=3,timeo=600,noresvport,nolock** _文件系统域名或IP:/子目录_ _本地路径_

    >![](public_sys-resources/icon-note.gif) **说明：** 
    >-   文件文件系统域名或IP：可以从文件系统列表或详情中获取。
    >    -   SFS容量型：example.com:/share-xxx/子目录
    >    -   SFS Turbo：xx.xx.xx.xx:/子目录
    >-   子目录：上一步骤创建的子目录
    >-   本地路径：云服务器上用于挂载文件系统的本地路径，例如“/local\_path“。与挂载根目录时的本地路径保持一致。

3.  挂载完成后，执行如下命令，查看已挂载的文件系统。

    **mount -l**

    如果回显包含如下类似信息，说明挂载成功。

    ```
    挂载地址 on /local_path type nfs (rw,vers=3,timeo=600,nolock,addr=)
    ```

4.  挂载成功后，用户可以在云服务器上访问文件系统的子目录，执行读取或写入操作。

