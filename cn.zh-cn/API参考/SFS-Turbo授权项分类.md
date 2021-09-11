# SFS Turbo授权项分类<a name="sfs_02_0083"></a>

## 文件系统<a name="section481420011409"></a>

<a name="table1830616174017"></a>
<table><thead align="left"><tr id="row7830161610409"><th class="cellrowborder" valign="top" width="15.861586158615863%" id="mcps1.1.7.1.1"><p id="p1283121634019"><a name="p1283121634019"></a><a name="p1283121634019"></a>权限</p>
</th>
<th class="cellrowborder" valign="top" width="19.451945194519453%" id="mcps1.1.7.1.2"><p id="p1983111166405"><a name="p1983111166405"></a><a name="p1983111166405"></a>对应API接口</p>
</th>
<th class="cellrowborder" valign="top" width="19.751975197519755%" id="mcps1.1.7.1.3"><p id="p148311316124019"><a name="p148311316124019"></a><a name="p148311316124019"></a>授权项</p>
</th>
<th class="cellrowborder" valign="top" width="22.842284228422844%" id="mcps1.1.7.1.4"><p id="p174771151102511"><a name="p174771151102511"></a><a name="p174771151102511"></a>依赖的授权项</p>
</th>
<th class="cellrowborder" valign="top" width="10.571057105710572%" id="mcps1.1.7.1.5"><p id="p582634616355"><a name="p582634616355"></a><a name="p582634616355"></a>IAM项目</p>
<p id="p7826346153516"><a name="p7826346153516"></a><a name="p7826346153516"></a><span>(Project)</span></p>
</th>
<th class="cellrowborder" valign="top" width="11.521152115211523%" id="mcps1.1.7.1.6"><p id="p4489550143514"><a name="p4489550143514"></a><a name="p4489550143514"></a>企业项目</p>
<p id="p174891150173516"><a name="p174891150173516"></a><a name="p174891150173516"></a><span>(Enterprise Project)</span></p>
</th>
</tr>
</thead>
<tbody><tr id="row1383151634015"><td class="cellrowborder" valign="top" width="15.861586158615863%" headers="mcps1.1.7.1.1 "><p id="p16500181116469"><a name="p16500181116469"></a><a name="p16500181116469"></a>创建文件系统</p>
</td>
<td class="cellrowborder" valign="top" width="19.451945194519453%" headers="mcps1.1.7.1.2 "><p id="p1371195992817"><a name="p1371195992817"></a><a name="p1371195992817"></a>POST /v1/{project_id}/sfs-turbo/shares</p>
</td>
<td class="cellrowborder" valign="top" width="19.751975197519755%" headers="mcps1.1.7.1.3 "><p id="p5549110143515"><a name="p5549110143515"></a><a name="p5549110143515"></a>sfsturbo:shares:createShare</p>
</td>
<td class="cellrowborder" valign="top" width="22.842284228422844%" headers="mcps1.1.7.1.4 "><a name="ul420112173913"></a><a name="ul420112173913"></a><ul id="ul420112173913"><li>创建SFS Turbo实例时，需要vpc相关权限，包括校验vpc、子网、安全组，创建vip以及port，创建安全组规则等，需要增加授权项：<a name="ul167997133916"></a><a name="ul167997133916"></a><ul id="ul167997133916"><li>"vpc:*:*"</li></ul>
</li><li>加密实例需要在项目上配置<span>KMS Administrator权限</span></li><li>专属场景，需要增加授权项：<a name="ul25581814153914"></a><a name="ul25581814153914"></a><ul id="ul25581814153914"><li>"dss:*:get",</li><li>"dss:*:list",</li><li>"dss:*:count"</li></ul>
</li></ul>
</td>
<td class="cellrowborder" valign="top" width="10.571057105710572%" headers="mcps1.1.7.1.5 "><p id="p17772123773415"><a name="p17772123773415"></a><a name="p17772123773415"></a>√</p>
</td>
<td class="cellrowborder" valign="top" width="11.521152115211523%" headers="mcps1.1.7.1.6 "><p id="p461814614365"><a name="p461814614365"></a><a name="p461814614365"></a>√</p>
</td>
</tr>
<tr id="row450081117466"><td class="cellrowborder" valign="top" width="15.861586158615863%" headers="mcps1.1.7.1.1 "><p id="p450013117466"><a name="p450013117466"></a><a name="p450013117466"></a>查询所有文件系统详细信息</p>
</td>
<td class="cellrowborder" valign="top" width="19.451945194519453%" headers="mcps1.1.7.1.2 "><p id="p15365716203010"><a name="p15365716203010"></a><a name="p15365716203010"></a>GET /v1/{project_id}/sfs-turbo/shares/detail</p>
</td>
<td class="cellrowborder" valign="top" width="19.751975197519755%" headers="mcps1.1.7.1.3 "><p id="p3109812103516"><a name="p3109812103516"></a><a name="p3109812103516"></a>sfsturbo:shares:getAllShares</p>
</td>
<td class="cellrowborder" valign="top" width="22.842284228422844%" headers="mcps1.1.7.1.4 "><p id="p647716513254"><a name="p647716513254"></a><a name="p647716513254"></a>-</p>
</td>
<td class="cellrowborder" valign="top" width="10.571057105710572%" headers="mcps1.1.7.1.5 "><p id="p97721537173415"><a name="p97721537173415"></a><a name="p97721537173415"></a>√</p>
</td>
<td class="cellrowborder" valign="top" width="11.521152115211523%" headers="mcps1.1.7.1.6 "><p id="p119371938361"><a name="p119371938361"></a><a name="p119371938361"></a>√</p>
</td>
</tr>
<tr id="row450021115461"><td class="cellrowborder" valign="top" width="15.861586158615863%" headers="mcps1.1.7.1.1 "><p id="p0444153655015"><a name="p0444153655015"></a><a name="p0444153655015"></a>查询单个文件系统详细信息</p>
</td>
<td class="cellrowborder" valign="top" width="19.451945194519453%" headers="mcps1.1.7.1.2 "><p id="p351333193217"><a name="p351333193217"></a><a name="p351333193217"></a>GET /v1/{project_id}/sfs-turbo/shares/{<span>share_id</span>}</p>
</td>
<td class="cellrowborder" valign="top" width="19.751975197519755%" headers="mcps1.1.7.1.3 "><p id="p1244171414353"><a name="p1244171414353"></a><a name="p1244171414353"></a>sfsturbo:shares:getShare</p>
</td>
<td class="cellrowborder" valign="top" width="22.842284228422844%" headers="mcps1.1.7.1.4 "><p id="p11477155172514"><a name="p11477155172514"></a><a name="p11477155172514"></a>-</p>
</td>
<td class="cellrowborder" valign="top" width="10.571057105710572%" headers="mcps1.1.7.1.5 "><p id="p87711937103419"><a name="p87711937103419"></a><a name="p87711937103419"></a>√</p>
</td>
<td class="cellrowborder" valign="top" width="11.521152115211523%" headers="mcps1.1.7.1.6 "><p id="p080442175111"><a name="p080442175111"></a><a name="p080442175111"></a>√</p>
</td>
</tr>
<tr id="row58051141154818"><td class="cellrowborder" valign="top" width="15.861586158615863%" headers="mcps1.1.7.1.1 "><p id="p1350031154610"><a name="p1350031154610"></a><a name="p1350031154610"></a>删除文件系统</p>
</td>
<td class="cellrowborder" valign="top" width="19.451945194519453%" headers="mcps1.1.7.1.2 "><p id="p1013914431334"><a name="p1013914431334"></a><a name="p1013914431334"></a>DELETE /v1/{project_id}/sfs-turbo/shares/{share_id}</p>
</td>
<td class="cellrowborder" valign="top" width="19.751975197519755%" headers="mcps1.1.7.1.3 "><p id="p14668515153516"><a name="p14668515153516"></a><a name="p14668515153516"></a>sfsturbo:shares:deleteShare</p>
</td>
<td class="cellrowborder" valign="top" width="22.842284228422844%" headers="mcps1.1.7.1.4 "><a name="ul1321202718399"></a><a name="ul1321202718399"></a><ul id="ul1321202718399"><li>删除SFS Turbo实例时，需要vpc相关权限，包括删除vip以及port，删除安全组规则等，需要增加授权项：<a name="ul07373017398"></a><a name="ul07373017398"></a><ul id="ul07373017398"><li>"vpc:*:*"</li></ul>
</li><li>如果是专属场景，需要增加授权项：<a name="ul1960163203917"></a><a name="ul1960163203917"></a><ul id="ul1960163203917"><li>"dss:*:get",</li><li>"dss:*:list",</li><li>"dss:*:count"</li></ul>
</li></ul>
</td>
<td class="cellrowborder" valign="top" width="10.571057105710572%" headers="mcps1.1.7.1.5 "><p id="p877103783413"><a name="p877103783413"></a><a name="p877103783413"></a>√</p>
</td>
<td class="cellrowborder" valign="top" width="11.521152115211523%" headers="mcps1.1.7.1.6 "><p id="p103771847195115"><a name="p103771847195115"></a><a name="p103771847195115"></a>√</p>
</td>
</tr>
</tbody>
</table>

## 扩容文件系统<a name="section149921655204019"></a>

<a name="table16855386414"></a>
<table><thead align="left"><tr id="row7855982418"><th class="cellrowborder" valign="top" width="17.09%" id="mcps1.1.6.1.1"><p id="p15995635193911"><a name="p15995635193911"></a><a name="p15995635193911"></a>权限</p>
</th>
<th class="cellrowborder" valign="top" width="21.529999999999998%" id="mcps1.1.6.1.2"><p id="p8300204914392"><a name="p8300204914392"></a><a name="p8300204914392"></a>对应API接口</p>
</th>
<th class="cellrowborder" valign="top" width="21.27%" id="mcps1.1.6.1.3"><p id="p1598114373919"><a name="p1598114373919"></a><a name="p1598114373919"></a>授权项</p>
</th>
<th class="cellrowborder" valign="top" width="19.77%" id="mcps1.1.6.1.4"><p id="p6694175416398"><a name="p6694175416398"></a><a name="p6694175416398"></a>IAM项目</p>
<p id="p1469425419398"><a name="p1469425419398"></a><a name="p1469425419398"></a><span>(Project)</span></p>
</th>
<th class="cellrowborder" valign="top" width="20.34%" id="mcps1.1.6.1.5"><p id="p7821858153919"><a name="p7821858153919"></a><a name="p7821858153919"></a>企业项目</p>
<p id="p98211158113915"><a name="p98211158113915"></a><a name="p98211158113915"></a><span>(Enterprise Project)</span></p>
</th>
</tr>
</thead>
<tbody><tr id="row885512864119"><td class="cellrowborder" valign="top" width="17.09%" headers="mcps1.1.6.1.1 "><p id="p024410387394"><a name="p024410387394"></a><a name="p024410387394"></a>扩容文件系统</p>
</td>
<td class="cellrowborder" valign="top" width="21.529999999999998%" headers="mcps1.1.6.1.2 "><p id="p5503121925812"><a name="p5503121925812"></a><a name="p5503121925812"></a>POST /v1/{project_id}/sfs-turbo/shares/{share_id}/action</p>
</td>
<td class="cellrowborder" valign="top" width="21.27%" headers="mcps1.1.6.1.3 "><p id="p11613114483918"><a name="p11613114483918"></a><a name="p11613114483918"></a>sfsturbo:shares:shareAction</p>
</td>
<td class="cellrowborder" valign="top" width="19.77%" headers="mcps1.1.6.1.4 "><p id="p197801429402"><a name="p197801429402"></a><a name="p197801429402"></a>√</p>
</td>
<td class="cellrowborder" valign="top" width="20.34%" headers="mcps1.1.6.1.5 "><p id="p670956124011"><a name="p670956124011"></a><a name="p670956124011"></a>√</p>
</td>
</tr>
</tbody>
</table>

## Console引用<a name="section6221921163313"></a>

<a name="table107154723316"></a>
<table><thead align="left"><tr id="row1981475338"><th class="cellrowborder" valign="top" width="17.65%" id="mcps1.1.7.1.1"><p id="p1618412118339"><a name="p1618412118339"></a><a name="p1618412118339"></a>权限</p>
</th>
<th class="cellrowborder" valign="top" width="12.25%" id="mcps1.1.7.1.2"><p id="p218442133318"><a name="p218442133318"></a><a name="p218442133318"></a>对应API接口</p>
</th>
<th class="cellrowborder" valign="top" width="22.09%" id="mcps1.1.7.1.3"><p id="p2184142110336"><a name="p2184142110336"></a><a name="p2184142110336"></a>授权项</p>
</th>
<th class="cellrowborder" valign="top" width="24.32%" id="mcps1.1.7.1.4"><p id="p149551159111411"><a name="p149551159111411"></a><a name="p149551159111411"></a>依赖的授权项</p>
</th>
<th class="cellrowborder" valign="top" width="10.9%" id="mcps1.1.7.1.5"><p id="p844613854111"><a name="p844613854111"></a><a name="p844613854111"></a>IAM项目</p>
<p id="p04469387416"><a name="p04469387416"></a><a name="p04469387416"></a><span>(Project)</span></p>
</th>
<th class="cellrowborder" valign="top" width="12.790000000000001%" id="mcps1.1.7.1.6"><p id="p1815420429418"><a name="p1815420429418"></a><a name="p1815420429418"></a>企业项目</p>
<p id="p1515464264118"><a name="p1515464264118"></a><a name="p1515464264118"></a><span>(Enterprise Project)</span></p>
</th>
</tr>
</thead>
<tbody><tr id="row158104713331"><td class="cellrowborder" valign="top" width="17.65%" headers="mcps1.1.7.1.1 "><p id="p91845216333"><a name="p91845216333"></a><a name="p91845216333"></a>更改安全组</p>
</td>
<td class="cellrowborder" valign="top" width="12.25%" headers="mcps1.1.7.1.2 "><p id="p131841821113312"><a name="p131841821113312"></a><a name="p131841821113312"></a>Console引用</p>
</td>
<td class="cellrowborder" valign="top" width="22.09%" headers="mcps1.1.7.1.3 "><p id="p198450148414"><a name="p198450148414"></a><a name="p198450148414"></a>sfsturbo:shares:shareAction</p>
</td>
<td class="cellrowborder" valign="top" width="24.32%" headers="mcps1.1.7.1.4 "><p id="p179559592148"><a name="p179559592148"></a><a name="p179559592148"></a>更改安全组需要安全组相关权限：</p>
<a name="ul144155112392"></a><a name="ul144155112392"></a><ul id="ul144155112392"><li><span>vpc:securityGroups:*</span></li><li><span>vpc:securityGroupRules:*</span></li></ul>
</td>
<td class="cellrowborder" valign="top" width="10.9%" headers="mcps1.1.7.1.5 "><p id="p759010518415"><a name="p759010518415"></a><a name="p759010518415"></a>√</p>
</td>
<td class="cellrowborder" valign="top" width="12.790000000000001%" headers="mcps1.1.7.1.6 "><p id="p1218515215335"><a name="p1218515215335"></a><a name="p1218515215335"></a>√</p>
</td>
</tr>
<tr id="row712164733319"><td class="cellrowborder" valign="top" width="17.65%" headers="mcps1.1.7.1.1 "><p id="p4189421113318"><a name="p4189421113318"></a><a name="p4189421113318"></a>查询sfs turbo配额</p>
</td>
<td class="cellrowborder" valign="top" width="12.25%" headers="mcps1.1.7.1.2 "><p id="p17189102116336"><a name="p17189102116336"></a><a name="p17189102116336"></a>Console引用</p>
</td>
<td class="cellrowborder" valign="top" width="22.09%" headers="mcps1.1.7.1.3 "><p id="p149181629104120"><a name="p149181629104120"></a><a name="p149181629104120"></a>sfsturbo:shares:getQuota</p>
</td>
<td class="cellrowborder" valign="top" width="24.32%" headers="mcps1.1.7.1.4 "><p id="p1395645931416"><a name="p1395645931416"></a><a name="p1395645931416"></a>-</p>
</td>
<td class="cellrowborder" valign="top" width="10.9%" headers="mcps1.1.7.1.5 "><p id="p125835519410"><a name="p125835519410"></a><a name="p125835519410"></a>√</p>
</td>
<td class="cellrowborder" valign="top" width="12.790000000000001%" headers="mcps1.1.7.1.6 "><p id="p151901621173311"><a name="p151901621173311"></a><a name="p151901621173311"></a>√</p>
</td>
</tr>
<tr id="row1912134715337"><td class="cellrowborder" valign="top" width="17.65%" headers="mcps1.1.7.1.1 "><p id="p16190721183315"><a name="p16190721183315"></a><a name="p16190721183315"></a>获取可用区信息</p>
</td>
<td class="cellrowborder" valign="top" width="12.25%" headers="mcps1.1.7.1.2 "><p id="p18190112119339"><a name="p18190112119339"></a><a name="p18190112119339"></a>Console引用</p>
</td>
<td class="cellrowborder" valign="top" width="22.09%" headers="mcps1.1.7.1.3 "><p id="p1959110313419"><a name="p1959110313419"></a><a name="p1959110313419"></a>sfsturbo:shares:getAZInfo</p>
</td>
<td class="cellrowborder" valign="top" width="24.32%" headers="mcps1.1.7.1.4 "><p id="p395615951417"><a name="p395615951417"></a><a name="p395615951417"></a>-</p>
</td>
<td class="cellrowborder" valign="top" width="10.9%" headers="mcps1.1.7.1.5 "><p id="p058311554114"><a name="p058311554114"></a><a name="p058311554114"></a>√</p>
</td>
<td class="cellrowborder" valign="top" width="12.790000000000001%" headers="mcps1.1.7.1.6 "><p id="p8190182113337"><a name="p8190182113337"></a><a name="p8190182113337"></a>√</p>
</td>
</tr>
<tr id="row14121947133320"><td class="cellrowborder" valign="top" width="17.65%" headers="mcps1.1.7.1.1 "><p id="p619011217338"><a name="p619011217338"></a><a name="p619011217338"></a>获取sfs turbo规格信息</p>
</td>
<td class="cellrowborder" valign="top" width="12.25%" headers="mcps1.1.7.1.2 "><p id="p1819082183315"><a name="p1819082183315"></a><a name="p1819082183315"></a>Console引用</p>
</td>
<td class="cellrowborder" valign="top" width="22.09%" headers="mcps1.1.7.1.3 "><p id="p211933104110"><a name="p211933104110"></a><a name="p211933104110"></a>sfsturbo:shares:getFlavors</p>
</td>
<td class="cellrowborder" valign="top" width="24.32%" headers="mcps1.1.7.1.4 "><p id="p795675910147"><a name="p795675910147"></a><a name="p795675910147"></a>-</p>
</td>
<td class="cellrowborder" valign="top" width="10.9%" headers="mcps1.1.7.1.5 "><p id="p85821351410"><a name="p85821351410"></a><a name="p85821351410"></a>√</p>
</td>
<td class="cellrowborder" valign="top" width="12.790000000000001%" headers="mcps1.1.7.1.6 "><p id="p13811350124216"><a name="p13811350124216"></a><a name="p13811350124216"></a>√</p>
</td>
</tr>
<tr id="row71334714331"><td class="cellrowborder" valign="top" width="17.65%" headers="mcps1.1.7.1.1 "><p id="p1719162113337"><a name="p1719162113337"></a><a name="p1719162113337"></a>检查文件系统名称</p>
</td>
<td class="cellrowborder" valign="top" width="12.25%" headers="mcps1.1.7.1.2 "><p id="p101911121163311"><a name="p101911121163311"></a><a name="p101911121163311"></a>Console引用</p>
</td>
<td class="cellrowborder" valign="top" width="22.09%" headers="mcps1.1.7.1.3 "><p id="p1586953312419"><a name="p1586953312419"></a><a name="p1586953312419"></a>sfsturbo:shares:checkShareName</p>
</td>
<td class="cellrowborder" valign="top" width="24.32%" headers="mcps1.1.7.1.4 "><p id="p39565599141"><a name="p39565599141"></a><a name="p39565599141"></a>-</p>
</td>
<td class="cellrowborder" valign="top" width="10.9%" headers="mcps1.1.7.1.5 "><p id="p1158135174117"><a name="p1158135174117"></a><a name="p1158135174117"></a>√</p>
</td>
<td class="cellrowborder" valign="top" width="12.790000000000001%" headers="mcps1.1.7.1.6 "><p id="p3191142113336"><a name="p3191142113336"></a><a name="p3191142113336"></a>√</p>
</td>
</tr>
</tbody>
</table>

