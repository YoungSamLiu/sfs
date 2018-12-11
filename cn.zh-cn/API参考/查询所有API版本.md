# 查询所有API版本<a name="ZH-CN_TOPIC_0093905226"></a>

## 功能介绍<a name="section922844914513"></a>

查询所有API版本。

>![](public_sys-resources/icon-note.gif) **说明：**   
>该接口无需鉴权。  

## URI<a name="section1665327514513"></a>

-   GET /
-   参数说明

无

## 请求<a name="section5063604914513"></a>

-   参数说明

    无

-   请求样例

    无


## 响应<a name="section6408307814513"></a>

-   参数说明

    <a name="table1204662914513"></a>
    <table><thead align="left"><tr id="row5640646814513"><th class="cellrowborder" valign="top" width="19.72%" id="mcps1.1.4.1.1"><p id="p552118914513"><a name="p552118914513"></a><a name="p552118914513"></a>参数</p>
    </th>
    <th class="cellrowborder" valign="top" width="22.54%" id="mcps1.1.4.1.2"><p id="p5284375514513"><a name="p5284375514513"></a><a name="p5284375514513"></a>参数类型</p>
    </th>
    <th class="cellrowborder" valign="top" width="57.74%" id="mcps1.1.4.1.3"><p id="p5248579414513"><a name="p5248579414513"></a><a name="p5248579414513"></a>描述</p>
    </th>
    </tr>
    </thead>
    <tbody><tr id="row2349088414513"><td class="cellrowborder" valign="top" width="19.72%" headers="mcps1.1.4.1.1 "><p id="p2371346714513"><a name="p2371346714513"></a><a name="p2371346714513"></a>versions</p>
    </td>
    <td class="cellrowborder" valign="top" width="22.54%" headers="mcps1.1.4.1.2 "><p id="p2571578314513"><a name="p2571578314513"></a><a name="p2571578314513"></a>list&lt;version&gt;</p>
    </td>
    <td class="cellrowborder" valign="top" width="57.74%" headers="mcps1.1.4.1.3 "><p id="p1868846815102"><a name="p1868846815102"></a><a name="p1868846815102"></a>所有可用的API版本列表对象。</p>
    </td>
    </tr>
    </tbody>
    </table>


-   version字段说明：

    <a name="table6612891614513"></a>
    <table><thead align="left"><tr id="row2416468614513"><th class="cellrowborder" valign="top" width="20%" id="mcps1.1.4.1.1"><p id="p17124101410431"><a name="p17124101410431"></a><a name="p17124101410431"></a>参数</p>
    </th>
    <th class="cellrowborder" valign="top" width="22.36%" id="mcps1.1.4.1.2"><p id="p312416148432"><a name="p312416148432"></a><a name="p312416148432"></a>参数类型</p>
    </th>
    <th class="cellrowborder" valign="top" width="57.64%" id="mcps1.1.4.1.3"><p id="p3124181464318"><a name="p3124181464318"></a><a name="p3124181464318"></a>描述</p>
    </th>
    </tr>
    </thead>
    <tbody><tr id="row5473431214513"><td class="cellrowborder" valign="top" width="20%" headers="mcps1.1.4.1.1 "><p id="p429429114513"><a name="p429429114513"></a><a name="p429429114513"></a>id</p>
    </td>
    <td class="cellrowborder" valign="top" width="22.36%" headers="mcps1.1.4.1.2 "><p id="p5623047814513"><a name="p5623047814513"></a><a name="p5623047814513"></a>string</p>
    </td>
    <td class="cellrowborder" valign="top" width="57.64%" headers="mcps1.1.4.1.3 "><p id="p5837483014513"><a name="p5837483014513"></a><a name="p5837483014513"></a>所使用版本的公用名称。</p>
    </td>
    </tr>
    <tr id="row5561142314513"><td class="cellrowborder" valign="top" width="20%" headers="mcps1.1.4.1.1 "><p id="p823140914513"><a name="p823140914513"></a><a name="p823140914513"></a>status</p>
    </td>
    <td class="cellrowborder" valign="top" width="22.36%" headers="mcps1.1.4.1.2 "><p id="p5074995814513"><a name="p5074995814513"></a><a name="p5074995814513"></a>string</p>
    </td>
    <td class="cellrowborder" valign="top" width="57.64%" headers="mcps1.1.4.1.3 "><p id="p5875536214030"><a name="p5875536214030"></a><a name="p5875536214030"></a>API 版本的状态。其值为：</p>
    <a name="ul7010819214058"></a><a name="ul7010819214058"></a><ul id="ul7010819214058"><li>当前版本：当前API使用的首选版本。</li><li>支持版本：以前的版本, 但仍然支持的当前API使用。</li><li>弃用版本：当前API将要删除弃用的版本。</li></ul>
    </td>
    </tr>
    <tr id="row1598568214513"><td class="cellrowborder" valign="top" width="20%" headers="mcps1.1.4.1.1 "><p id="p1977187214513"><a name="p1977187214513"></a><a name="p1977187214513"></a>links</p>
    </td>
    <td class="cellrowborder" valign="top" width="22.36%" headers="mcps1.1.4.1.2 "><p id="p182455114513"><a name="p182455114513"></a><a name="p182455114513"></a>array</p>
    </td>
    <td class="cellrowborder" valign="top" width="57.64%" headers="mcps1.1.4.1.3 "><p id="p26535624151532"><a name="p26535624151532"></a><a name="p26535624151532"></a>共享链接。</p>
    </td>
    </tr>
    <tr id="row5502948014513"><td class="cellrowborder" valign="top" width="20%" headers="mcps1.1.4.1.1 "><p id="p2820292414513"><a name="p2820292414513"></a><a name="p2820292414513"></a>media-types</p>
    </td>
    <td class="cellrowborder" valign="top" width="22.36%" headers="mcps1.1.4.1.2 "><p id="p2024960914513"><a name="p2024960914513"></a><a name="p2024960914513"></a>object</p>
    </td>
    <td class="cellrowborder" valign="top" width="57.64%" headers="mcps1.1.4.1.3 "><p id="p2960561814513"><a name="p2960561814513"></a><a name="p2960561814513"></a>API支持的媒介类型。</p>
    </td>
    </tr>
    <tr id="row6512397414513"><td class="cellrowborder" valign="top" width="20%" headers="mcps1.1.4.1.1 "><p id="p4055052114513"><a name="p4055052114513"></a><a name="p4055052114513"></a>version</p>
    </td>
    <td class="cellrowborder" valign="top" width="22.36%" headers="mcps1.1.4.1.2 "><p id="p3243232014513"><a name="p3243232014513"></a><a name="p3243232014513"></a>string</p>
    </td>
    <td class="cellrowborder" valign="top" width="57.64%" headers="mcps1.1.4.1.3 "><p id="p977226014513"><a name="p977226014513"></a><a name="p977226014513"></a>如果当前版本的API支持microversions，此处为支持的microversion的最大版本。如果不支持microversions，这将会是空字符串。</p>
    </td>
    </tr>
    <tr id="row2084148314513"><td class="cellrowborder" valign="top" width="20%" headers="mcps1.1.4.1.1 "><p id="p1043858314513"><a name="p1043858314513"></a><a name="p1043858314513"></a>min_version</p>
    </td>
    <td class="cellrowborder" valign="top" width="22.36%" headers="mcps1.1.4.1.2 "><p id="p3650774114513"><a name="p3650774114513"></a><a name="p3650774114513"></a>string</p>
    </td>
    <td class="cellrowborder" valign="top" width="57.64%" headers="mcps1.1.4.1.3 "><p id="p433706314513"><a name="p433706314513"></a><a name="p433706314513"></a>如果当前版本的API支持microversions, 此处为支持的microversion的最小版本。如果不支持microversions, 这将会是空字符串。</p>
    </td>
    </tr>
    </tbody>
    </table>


-   响应样例

    ```
    {
      "versions": [
        {
          "status": "CURRENT",
          "updated": "2015-08-27T11:33:21Z",
          "links": [
            {
              "href": "http://docs.openstack.org/",
              "type": "text/html",
              "rel": "describedby"
            },
            {
              "href": "https://sfs.region.www.t-systems.com/v2/",
              "rel": "self"
            }
          ],
          "min_version": "2.0",
          "version": "2.28",
          "media-types": [
            {
              "base": "application/json",
              "type": "application/vnd.openstack.share+json;version=1"
            }
          ],
          "id": "v2.0"
        }
      ]
    }
    ```


## 状态码<a name="section4959408514513"></a>

-   正常

    202、300

-   异常

    <a name="table6245403714513"></a>
    <table><thead align="left"><tr id="row1507735814513"><th class="cellrowborder" valign="top" width="43.43%" id="mcps1.1.3.1.1"><p id="p1330652014513"><a name="p1330652014513"></a><a name="p1330652014513"></a>状态码</p>
    </th>
    <th class="cellrowborder" valign="top" width="56.57%" id="mcps1.1.3.1.2"><p id="p408636314513"><a name="p408636314513"></a><a name="p408636314513"></a>说明</p>
    </th>
    </tr>
    </thead>
    <tbody><tr id="row6255996614513"><td class="cellrowborder" valign="top" width="43.43%" headers="mcps1.1.3.1.1 "><p id="p3419245714513"><a name="p3419245714513"></a><a name="p3419245714513"></a>400 Bad Request</p>
    </td>
    <td class="cellrowborder" valign="top" width="56.57%" headers="mcps1.1.3.1.2 "><p id="p1812563714513"><a name="p1812563714513"></a><a name="p1812563714513"></a>服务器未能处理请求。</p>
    </td>
    </tr>
    <tr id="row2891300914513"><td class="cellrowborder" valign="top" width="43.43%" headers="mcps1.1.3.1.1 "><p id="p6025236014513"><a name="p6025236014513"></a><a name="p6025236014513"></a>400 Bad Request</p>
    </td>
    <td class="cellrowborder" valign="top" width="56.57%" headers="mcps1.1.3.1.2 "><p id="p4860301214513"><a name="p4860301214513"></a><a name="p4860301214513"></a>无效输入：缩容后的大小必须大于0并小于当前大小（当前：XX，新大小：XX）</p>
    </td>
    </tr>
    <tr id="row3477393214513"><td class="cellrowborder" valign="top" width="43.43%" headers="mcps1.1.3.1.1 "><p id="p6522508214513"><a name="p6522508214513"></a><a name="p6522508214513"></a>400 Bad Request</p>
    </td>
    <td class="cellrowborder" valign="top" width="56.57%" headers="mcps1.1.3.1.2 "><p id="p4874025614513"><a name="p4874025614513"></a><a name="p4874025614513"></a>无效输入：扩容后的大小必须大于当前大小（当前：XX，新大小：XX）</p>
    </td>
    </tr>
    <tr id="row3600912414513"><td class="cellrowborder" valign="top" width="43.43%" headers="mcps1.1.3.1.1 "><p id="p3105792214513"><a name="p3105792214513"></a><a name="p3105792214513"></a>401 Unauthorized</p>
    </td>
    <td class="cellrowborder" valign="top" width="56.57%" headers="mcps1.1.3.1.2 "><p id="p3266375714513"><a name="p3266375714513"></a><a name="p3266375714513"></a>被请求的页面需要用户名和密码。</p>
    </td>
    </tr>
    <tr id="row2553835814513"><td class="cellrowborder" valign="top" width="43.43%" headers="mcps1.1.3.1.1 "><p id="p5534113514513"><a name="p5534113514513"></a><a name="p5534113514513"></a>403 Forbidden</p>
    </td>
    <td class="cellrowborder" valign="top" width="56.57%" headers="mcps1.1.3.1.2 "><p id="p5344692014513"><a name="p5344692014513"></a><a name="p5344692014513"></a>对被请求页面的访问被禁止。</p>
    </td>
    </tr>
    <tr id="row1126023214513"><td class="cellrowborder" valign="top" width="43.43%" headers="mcps1.1.3.1.1 "><p id="p3966357214513"><a name="p3966357214513"></a><a name="p3966357214513"></a>404 Not Found</p>
    </td>
    <td class="cellrowborder" valign="top" width="56.57%" headers="mcps1.1.3.1.2 "><p id="p5863278914513"><a name="p5863278914513"></a><a name="p5863278914513"></a>服务器无法找到被请求的页面。</p>
    </td>
    </tr>
    <tr id="row5793306114513"><td class="cellrowborder" valign="top" width="43.43%" headers="mcps1.1.3.1.1 "><p id="p6206638414513"><a name="p6206638414513"></a><a name="p6206638414513"></a>405 Method Not Allowed</p>
    </td>
    <td class="cellrowborder" valign="top" width="56.57%" headers="mcps1.1.3.1.2 "><p id="p6132122014513"><a name="p6132122014513"></a><a name="p6132122014513"></a>请求中指定的方法不被允许。</p>
    </td>
    </tr>
    <tr id="row1502006814513"><td class="cellrowborder" valign="top" width="43.43%" headers="mcps1.1.3.1.1 "><p id="p866599114513"><a name="p866599114513"></a><a name="p866599114513"></a>406 Not Acceptable</p>
    </td>
    <td class="cellrowborder" valign="top" width="56.57%" headers="mcps1.1.3.1.2 "><p id="p3085667914513"><a name="p3085667914513"></a><a name="p3085667914513"></a>服务器生成的响应无法被客户端所接受。</p>
    </td>
    </tr>
    <tr id="row927465714513"><td class="cellrowborder" valign="top" width="43.43%" headers="mcps1.1.3.1.1 "><p id="p1304973414513"><a name="p1304973414513"></a><a name="p1304973414513"></a>407 Proxy Authentication Required</p>
    </td>
    <td class="cellrowborder" valign="top" width="56.57%" headers="mcps1.1.3.1.2 "><p id="p5039554814513"><a name="p5039554814513"></a><a name="p5039554814513"></a>用户必须首先使用代理服务器进行验证，这样请求才会被处理。</p>
    </td>
    </tr>
    <tr id="row5090675314513"><td class="cellrowborder" valign="top" width="43.43%" headers="mcps1.1.3.1.1 "><p id="p2980630614513"><a name="p2980630614513"></a><a name="p2980630614513"></a>408 Request Timeout</p>
    </td>
    <td class="cellrowborder" valign="top" width="56.57%" headers="mcps1.1.3.1.2 "><p id="p6550061714513"><a name="p6550061714513"></a><a name="p6550061714513"></a>请求超出了服务器的等待时间。</p>
    </td>
    </tr>
    <tr id="row5263464114513"><td class="cellrowborder" valign="top" width="43.43%" headers="mcps1.1.3.1.1 "><p id="p3554751314513"><a name="p3554751314513"></a><a name="p3554751314513"></a>409 Conflict</p>
    </td>
    <td class="cellrowborder" valign="top" width="56.57%" headers="mcps1.1.3.1.2 "><p id="p6077628114513"><a name="p6077628114513"></a><a name="p6077628114513"></a>由于冲突，请求无法被完成。</p>
    </td>
    </tr>
    <tr id="row1011562214513"><td class="cellrowborder" valign="top" width="43.43%" headers="mcps1.1.3.1.1 "><p id="p1405905414513"><a name="p1405905414513"></a><a name="p1405905414513"></a>500 Internal Server Error</p>
    </td>
    <td class="cellrowborder" valign="top" width="56.57%" headers="mcps1.1.3.1.2 "><p id="p6504160314513"><a name="p6504160314513"></a><a name="p6504160314513"></a>请求未完成。服务异常。</p>
    </td>
    </tr>
    <tr id="row4850351714513"><td class="cellrowborder" valign="top" width="43.43%" headers="mcps1.1.3.1.1 "><p id="p3647083214513"><a name="p3647083214513"></a><a name="p3647083214513"></a>501 Not Implemented</p>
    </td>
    <td class="cellrowborder" valign="top" width="56.57%" headers="mcps1.1.3.1.2 "><p id="p134739514513"><a name="p134739514513"></a><a name="p134739514513"></a>请求未完成。服务器不支持所请求的功能。</p>
    </td>
    </tr>
    <tr id="row1212655614513"><td class="cellrowborder" valign="top" width="43.43%" headers="mcps1.1.3.1.1 "><p id="p4272696214513"><a name="p4272696214513"></a><a name="p4272696214513"></a>502 Bad Gateway</p>
    </td>
    <td class="cellrowborder" valign="top" width="56.57%" headers="mcps1.1.3.1.2 "><p id="p3833193414513"><a name="p3833193414513"></a><a name="p3833193414513"></a>请求未完成。服务器从上游服务器收到一个无效的响应。</p>
    </td>
    </tr>
    <tr id="row944308614513"><td class="cellrowborder" valign="top" width="43.43%" headers="mcps1.1.3.1.1 "><p id="p2669253114513"><a name="p2669253114513"></a><a name="p2669253114513"></a>503 Service Unavailable</p>
    </td>
    <td class="cellrowborder" valign="top" width="56.57%" headers="mcps1.1.3.1.2 "><p id="p1461142514513"><a name="p1461142514513"></a><a name="p1461142514513"></a>请求未完成。系统暂时异常。</p>
    </td>
    </tr>
    <tr id="row6439396214513"><td class="cellrowborder" valign="top" width="43.43%" headers="mcps1.1.3.1.1 "><p id="p4852843914513"><a name="p4852843914513"></a><a name="p4852843914513"></a>504 Gateway Timeout</p>
    </td>
    <td class="cellrowborder" valign="top" width="56.57%" headers="mcps1.1.3.1.2 "><p id="p3848950514513"><a name="p3848950514513"></a><a name="p3848950514513"></a>网关超时。</p>
    </td>
    </tr>
    </tbody>
    </table>


