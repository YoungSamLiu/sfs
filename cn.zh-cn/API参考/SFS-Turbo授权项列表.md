# SFS Turbo授权项列表<a name="sfs_02_0083"></a>

## 文件系统<a name="section481420011409"></a>

<a name="table1830616174017"></a>
<table><thead align="left"><tr id="row7830161610409"><th class="cellrowborder" valign="top" width="22.45%" id="mcps1.1.5.1.1"><p id="p1983111166405"><a name="p1983111166405"></a><a name="p1983111166405"></a>API</p>
</th>
<th class="cellrowborder" valign="top" width="21.43%" id="mcps1.1.5.1.2"><p id="p1283121634019"><a name="p1283121634019"></a><a name="p1283121634019"></a>API功能</p>
</th>
<th class="cellrowborder" valign="top" width="19.38%" id="mcps1.1.5.1.3"><p id="p148311316124019"><a name="p148311316124019"></a><a name="p148311316124019"></a>授权项</p>
</th>
<th class="cellrowborder" valign="top" width="36.74%" id="mcps1.1.5.1.4"><p id="p148311016154012"><a name="p148311016154012"></a><a name="p148311016154012"></a>授权作用域</p>
</th>
</tr>
</thead>
<tbody><tr id="row1383151634015"><td class="cellrowborder" valign="top" width="22.45%" headers="mcps1.1.5.1.1 "><p id="p1371195992817"><a name="p1371195992817"></a><a name="p1371195992817"></a>POST /v1/{project_id}/sfs-turbo/shares</p>
</td>
<td class="cellrowborder" valign="top" width="21.43%" headers="mcps1.1.5.1.2 "><p id="p16500181116469"><a name="p16500181116469"></a><a name="p16500181116469"></a>创建文件系统</p>
</td>
<td class="cellrowborder" valign="top" width="19.38%" headers="mcps1.1.5.1.3 "><a name="ul5221162535419"></a><a name="ul5221162535419"></a><ul id="ul5221162535419"><li>sfsturbo:shares:createShare</li></ul>
</td>
<td class="cellrowborder" valign="top" width="36.74%" headers="mcps1.1.5.1.4 "><a name="ul17920152735612"></a><a name="ul17920152735612"></a><ul id="ul17920152735612"><li>支持：</li></ul>
<p id="p79206276568"><a name="p79206276568"></a><a name="p79206276568"></a><span>项目</span><span>(Project)</span></p>
<p id="p16920172713564"><a name="p16920172713564"></a><a name="p16920172713564"></a><span>企业项目</span><span>(Enterprise Project)</span></p>
</td>
</tr>
<tr id="row450081117466"><td class="cellrowborder" valign="top" width="22.45%" headers="mcps1.1.5.1.1 "><p id="p15365716203010"><a name="p15365716203010"></a><a name="p15365716203010"></a>GET /v1/{project_id}/sfs-turbo/shares/detail</p>
</td>
<td class="cellrowborder" valign="top" width="21.43%" headers="mcps1.1.5.1.2 "><p id="p450013117466"><a name="p450013117466"></a><a name="p450013117466"></a>查询所有文件系统详细信息</p>
</td>
<td class="cellrowborder" valign="top" width="19.38%" headers="mcps1.1.5.1.3 "><a name="ul9472431185413"></a><a name="ul9472431185413"></a><ul id="ul9472431185413"><li>sfsturbo:shares:getAllShares</li></ul>
</td>
<td class="cellrowborder" valign="top" width="36.74%" headers="mcps1.1.5.1.4 "><a name="ul269215404514"></a><a name="ul269215404514"></a><ul id="ul269215404514"><li>支持：</li></ul>
<p id="p12692240135115"><a name="p12692240135115"></a><a name="p12692240135115"></a><span>项目</span><span>(Project)</span></p>
<p id="p1692440125115"><a name="p1692440125115"></a><a name="p1692440125115"></a><span>企业项目</span><span>(Enterprise Project)</span></p>
</td>
</tr>
<tr id="row450021115461"><td class="cellrowborder" valign="top" width="22.45%" headers="mcps1.1.5.1.1 "><p id="p351333193217"><a name="p351333193217"></a><a name="p351333193217"></a>GET /v1/{project_id}/sfs-turbo/shares/{<span>share_id</span>}</p>
</td>
<td class="cellrowborder" valign="top" width="21.43%" headers="mcps1.1.5.1.2 "><p id="p0444153655015"><a name="p0444153655015"></a><a name="p0444153655015"></a>查询单个文件系统详细信息</p>
</td>
<td class="cellrowborder" valign="top" width="19.38%" headers="mcps1.1.5.1.3 "><a name="ul1339423215418"></a><a name="ul1339423215418"></a><ul id="ul1339423215418"><li>sfsturbo:shares:getShare</li></ul>
</td>
<td class="cellrowborder" valign="top" width="36.74%" headers="mcps1.1.5.1.4 "><a name="ul178015427519"></a><a name="ul178015427519"></a><ul id="ul178015427519"><li>支持：</li></ul>
<p id="p1680164217513"><a name="p1680164217513"></a><a name="p1680164217513"></a><span>项目</span><span>(Project)</span></p>
<p id="p080442175111"><a name="p080442175111"></a><a name="p080442175111"></a><span>企业项目</span><span>(Enterprise Project)</span></p>
</td>
</tr>
<tr id="row58051141154818"><td class="cellrowborder" valign="top" width="22.45%" headers="mcps1.1.5.1.1 "><p id="p1013914431334"><a name="p1013914431334"></a><a name="p1013914431334"></a>DELETE /v1/{project_id}/sfs-turbo/shares/{share_id}</p>
</td>
<td class="cellrowborder" valign="top" width="21.43%" headers="mcps1.1.5.1.2 "><p id="p1350031154610"><a name="p1350031154610"></a><a name="p1350031154610"></a>删除文件系统</p>
</td>
<td class="cellrowborder" valign="top" width="19.38%" headers="mcps1.1.5.1.3 "><a name="ul91291455135519"></a><a name="ul91291455135519"></a><ul id="ul91291455135519"><li>sfsturbo:shares:deleteShare</li></ul>
</td>
<td class="cellrowborder" valign="top" width="36.74%" headers="mcps1.1.5.1.4 "><a name="ul15345184725110"></a><a name="ul15345184725110"></a><ul id="ul15345184725110"><li>支持：</li></ul>
<p id="p937724715119"><a name="p937724715119"></a><a name="p937724715119"></a><span>项目</span><span>(Project)</span></p>
<p id="p103771847195115"><a name="p103771847195115"></a><a name="p103771847195115"></a><span>企业项目</span><span>(Enterprise Project)</span></p>
</td>
</tr>
</tbody>
</table>

## 扩容文件系统<a name="section149921655204019"></a>

<a name="table16855386414"></a>
<table><thead align="left"><tr id="row7855982418"><th class="cellrowborder" valign="top" width="23.150000000000002%" id="mcps1.1.5.1.1"><p id="p085518164118"><a name="p085518164118"></a><a name="p085518164118"></a>API</p>
</th>
<th class="cellrowborder" valign="top" width="20.73%" id="mcps1.1.5.1.2"><p id="p1285512814117"><a name="p1285512814117"></a><a name="p1285512814117"></a>API功能</p>
</th>
<th class="cellrowborder" valign="top" width="19.650000000000002%" id="mcps1.1.5.1.3"><p id="p485518114115"><a name="p485518114115"></a><a name="p485518114115"></a>授权项</p>
</th>
<th class="cellrowborder" valign="top" width="36.47%" id="mcps1.1.5.1.4"><p id="p1585516811411"><a name="p1585516811411"></a><a name="p1585516811411"></a>授权作用域</p>
</th>
</tr>
</thead>
<tbody><tr id="row885512864119"><td class="cellrowborder" valign="top" width="23.150000000000002%" headers="mcps1.1.5.1.1 "><p id="p5503121925812"><a name="p5503121925812"></a><a name="p5503121925812"></a>POST /v1/{project_id}/sfs-turbo/shares/{share_id}/action</p>
</td>
<td class="cellrowborder" valign="top" width="20.73%" headers="mcps1.1.5.1.2 "><p id="p261925114518"><a name="p261925114518"></a><a name="p261925114518"></a>扩容文件系统</p>
</td>
<td class="cellrowborder" valign="top" width="19.650000000000002%" headers="mcps1.1.5.1.3 "><a name="ul1285513816415"></a><a name="ul1285513816415"></a><ul id="ul1285513816415"><li>sfsturbo:shares:shareAction</li></ul>
</td>
<td class="cellrowborder" valign="top" width="36.47%" headers="mcps1.1.5.1.4 "><a name="ul78561582415"></a><a name="ul78561582415"></a><ul id="ul78561582415"><li>支持：</li></ul>
<p id="p1685614813415"><a name="p1685614813415"></a><a name="p1685614813415"></a><span>项目</span><span>(Project)</span></p>
<p id="p1856198184113"><a name="p1856198184113"></a><a name="p1856198184113"></a><span>企业项目</span><span>(Enterprise Project)</span></p>
</td>
</tr>
</tbody>
</table>

## Console引用<a name="section6221921163313"></a>

<a name="table107154723316"></a>
<table><thead align="left"><tr id="row1981475338"><th class="cellrowborder" valign="top" width="23.02%" id="mcps1.1.5.1.1"><p id="p218442133318"><a name="p218442133318"></a><a name="p218442133318"></a>API</p>
</th>
<th class="cellrowborder" valign="top" width="21.029999999999998%" id="mcps1.1.5.1.2"><p id="p1618412118339"><a name="p1618412118339"></a><a name="p1618412118339"></a>API功能</p>
</th>
<th class="cellrowborder" valign="top" width="19.59%" id="mcps1.1.5.1.3"><p id="p2184142110336"><a name="p2184142110336"></a><a name="p2184142110336"></a>授权项</p>
</th>
<th class="cellrowborder" valign="top" width="36.36%" id="mcps1.1.5.1.4"><p id="p131841321103313"><a name="p131841321103313"></a><a name="p131841321103313"></a>授权作用域</p>
</th>
</tr>
</thead>
<tbody><tr id="row158104713331"><td class="cellrowborder" valign="top" width="23.02%" headers="mcps1.1.5.1.1 "><p id="p131841821113312"><a name="p131841821113312"></a><a name="p131841821113312"></a>Console引用</p>
</td>
<td class="cellrowborder" valign="top" width="21.029999999999998%" headers="mcps1.1.5.1.2 "><p id="p91845216333"><a name="p91845216333"></a><a name="p91845216333"></a>更改安全组</p>
</td>
<td class="cellrowborder" valign="top" width="19.59%" headers="mcps1.1.5.1.3 "><a name="ul1418462118337"></a><a name="ul1418462118337"></a><ul id="ul1418462118337"><li>sfsturbo:shares:shareAction</li></ul>
</td>
<td class="cellrowborder" valign="top" width="36.36%" headers="mcps1.1.5.1.4 "><a name="ul91854211336"></a><a name="ul91854211336"></a><ul id="ul91854211336"><li>支持：</li></ul>
<p id="p2185122123314"><a name="p2185122123314"></a><a name="p2185122123314"></a><span>项目</span><span>(Project)</span></p>
<p id="p1218515215335"><a name="p1218515215335"></a><a name="p1218515215335"></a><span>企业项目</span><span>(Enterprise Project)</span></p>
</td>
</tr>
<tr id="row13812477332"><td class="cellrowborder" valign="top" width="23.02%" headers="mcps1.1.5.1.1 "><p id="p4185021183320"><a name="p4185021183320"></a><a name="p4185021183320"></a>Console引用</p>
</td>
<td class="cellrowborder" valign="top" width="21.029999999999998%" headers="mcps1.1.5.1.2 "><p id="p118532153319"><a name="p118532153319"></a><a name="p118532153319"></a>检查备份名称</p>
</td>
<td class="cellrowborder" valign="top" width="19.59%" headers="mcps1.1.5.1.3 "><a name="ul17185152173315"></a><a name="ul17185152173315"></a><ul id="ul17185152173315"><li>sfsturbo:shares:backupCheckName</li></ul>
</td>
<td class="cellrowborder" valign="top" width="36.36%" headers="mcps1.1.5.1.4 "><a name="ul518516217338"></a><a name="ul518516217338"></a><ul id="ul518516217338"><li>支持：</li></ul>
<p id="p318562193316"><a name="p318562193316"></a><a name="p318562193316"></a><span>项目</span><span>(Project)</span></p>
<p id="p71855215334"><a name="p71855215334"></a><a name="p71855215334"></a><span>企业项目</span><span>(Enterprise Project)</span></p>
</td>
</tr>
<tr id="row299473335"><td class="cellrowborder" valign="top" width="23.02%" headers="mcps1.1.5.1.1 "><p id="p1018572143313"><a name="p1018572143313"></a><a name="p1018572143313"></a>Console引用</p>
</td>
<td class="cellrowborder" valign="top" width="21.029999999999998%" headers="mcps1.1.5.1.2 "><p id="p1518542113336"><a name="p1518542113336"></a><a name="p1518542113336"></a>创建备份</p>
</td>
<td class="cellrowborder" valign="top" width="19.59%" headers="mcps1.1.5.1.3 "><a name="ul1418592163311"></a><a name="ul1418592163311"></a><ul id="ul1418592163311"><li>sfsturbo:shares:createBackup</li></ul>
</td>
<td class="cellrowborder" valign="top" width="36.36%" headers="mcps1.1.5.1.4 "><a name="ul818515219339"></a><a name="ul818515219339"></a><ul id="ul818515219339"><li>支持：</li></ul>
<p id="p12186102113311"><a name="p12186102113311"></a><a name="p12186102113311"></a><span>项目</span><span>(Project)</span></p>
<p id="p318682115336"><a name="p318682115336"></a><a name="p318682115336"></a><span>企业项目</span><span>(Enterprise Project)</span></p>
</td>
</tr>
<tr id="row15912474336"><td class="cellrowborder" valign="top" width="23.02%" headers="mcps1.1.5.1.1 "><p id="p1518672113311"><a name="p1518672113311"></a><a name="p1518672113311"></a>Console引用</p>
</td>
<td class="cellrowborder" valign="top" width="21.029999999999998%" headers="mcps1.1.5.1.2 "><p id="p191866219332"><a name="p191866219332"></a><a name="p191866219332"></a>查询备份列表</p>
</td>
<td class="cellrowborder" valign="top" width="19.59%" headers="mcps1.1.5.1.3 "><a name="ul18186162123318"></a><a name="ul18186162123318"></a><ul id="ul18186162123318"><li>sfsturbo:shares:getAllBackups</li></ul>
</td>
<td class="cellrowborder" valign="top" width="36.36%" headers="mcps1.1.5.1.4 "><a name="ul918662193311"></a><a name="ul918662193311"></a><ul id="ul918662193311"><li>支持：</li></ul>
<p id="p918692118333"><a name="p918692118333"></a><a name="p918692118333"></a><span>项目</span><span>(Project)</span></p>
<p id="p218682115336"><a name="p218682115336"></a><a name="p218682115336"></a><span>企业项目</span><span>(Enterprise Project)</span></p>
</td>
</tr>
<tr id="row49947173310"><td class="cellrowborder" valign="top" width="23.02%" headers="mcps1.1.5.1.1 "><p id="p3186421113310"><a name="p3186421113310"></a><a name="p3186421113310"></a>Console引用</p>
</td>
<td class="cellrowborder" valign="top" width="21.029999999999998%" headers="mcps1.1.5.1.2 "><p id="p2186152116339"><a name="p2186152116339"></a><a name="p2186152116339"></a>查询单个备份</p>
</td>
<td class="cellrowborder" valign="top" width="19.59%" headers="mcps1.1.5.1.3 "><a name="ul918672123317"></a><a name="ul918672123317"></a><ul id="ul918672123317"><li>sfsturbo:shares:getBackup</li></ul>
</td>
<td class="cellrowborder" valign="top" width="36.36%" headers="mcps1.1.5.1.4 "><a name="ul14187221123316"></a><a name="ul14187221123316"></a><ul id="ul14187221123316"><li>支持：</li></ul>
<p id="p5187192193319"><a name="p5187192193319"></a><a name="p5187192193319"></a><span>项目</span><span>(Project)</span></p>
<p id="p161871121133317"><a name="p161871121133317"></a><a name="p161871121133317"></a><span>企业项目</span><span>(Enterprise Project)</span></p>
</td>
</tr>
<tr id="row1210164718333"><td class="cellrowborder" valign="top" width="23.02%" headers="mcps1.1.5.1.1 "><p id="p5187192112334"><a name="p5187192112334"></a><a name="p5187192112334"></a>Console引用</p>
</td>
<td class="cellrowborder" valign="top" width="21.029999999999998%" headers="mcps1.1.5.1.2 "><p id="p17187192143313"><a name="p17187192143313"></a><a name="p17187192143313"></a>根据备份恢复文件系统</p>
</td>
<td class="cellrowborder" valign="top" width="19.59%" headers="mcps1.1.5.1.3 "><a name="ul18187321113318"></a><a name="ul18187321113318"></a><ul id="ul18187321113318"><li>sfsturbo:shares:restoreShare</li></ul>
</td>
<td class="cellrowborder" valign="top" width="36.36%" headers="mcps1.1.5.1.4 "><a name="ul1918715215337"></a><a name="ul1918715215337"></a><ul id="ul1918715215337"><li>支持：</li></ul>
<p id="p19187152133317"><a name="p19187152133317"></a><a name="p19187152133317"></a>项目(Project)</p>
<p id="p101871221133314"><a name="p101871221133314"></a><a name="p101871221133314"></a>企业项目(Enterprise Project)</p>
</td>
</tr>
<tr id="row17101947173314"><td class="cellrowborder" valign="top" width="23.02%" headers="mcps1.1.5.1.1 "><p id="p12187121173315"><a name="p12187121173315"></a><a name="p12187121173315"></a>Console引用</p>
</td>
<td class="cellrowborder" valign="top" width="21.029999999999998%" headers="mcps1.1.5.1.2 "><p id="p3187121133314"><a name="p3187121133314"></a><a name="p3187121133314"></a>删除备份</p>
</td>
<td class="cellrowborder" valign="top" width="19.59%" headers="mcps1.1.5.1.3 "><a name="ul131875212337"></a><a name="ul131875212337"></a><ul id="ul131875212337"><li>sfsturbo:shares:deleteBackup</li></ul>
</td>
<td class="cellrowborder" valign="top" width="36.36%" headers="mcps1.1.5.1.4 "><a name="ul1018762153319"></a><a name="ul1018762153319"></a><ul id="ul1018762153319"><li>支持：</li></ul>
<p id="p418742143312"><a name="p418742143312"></a><a name="p418742143312"></a><span>项目</span><span>(Project)</span></p>
<p id="p111881421103310"><a name="p111881421103310"></a><a name="p111881421103310"></a><span>企业项目</span><span>(Enterprise Project)</span></p>
</td>
</tr>
<tr id="row01174718336"><td class="cellrowborder" valign="top" width="23.02%" headers="mcps1.1.5.1.1 "><p id="p1818812163310"><a name="p1818812163310"></a><a name="p1818812163310"></a>Console引用</p>
</td>
<td class="cellrowborder" valign="top" width="21.029999999999998%" headers="mcps1.1.5.1.2 "><p id="p2188621193311"><a name="p2188621193311"></a><a name="p2188621193311"></a>设置自动备份策略</p>
</td>
<td class="cellrowborder" valign="top" width="19.59%" headers="mcps1.1.5.1.3 "><a name="ul16188122117330"></a><a name="ul16188122117330"></a><ul id="ul16188122117330"><li>sfsturbo:shares:createAutoBackup</li></ul>
</td>
<td class="cellrowborder" valign="top" width="36.36%" headers="mcps1.1.5.1.4 "><a name="ul518815211333"></a><a name="ul518815211333"></a><ul id="ul518815211333"><li>支持：</li></ul>
<p id="p1718832193319"><a name="p1718832193319"></a><a name="p1718832193319"></a><span>项目</span><span>(Project)</span></p>
<p id="p14188182153311"><a name="p14188182153311"></a><a name="p14188182153311"></a><span>企业项目</span><span>(Enterprise Project)</span></p>
</td>
</tr>
<tr id="row811104719334"><td class="cellrowborder" valign="top" width="23.02%" headers="mcps1.1.5.1.1 "><p id="p13188102111335"><a name="p13188102111335"></a><a name="p13188102111335"></a>Console引用</p>
</td>
<td class="cellrowborder" valign="top" width="21.029999999999998%" headers="mcps1.1.5.1.2 "><p id="p8188182114333"><a name="p8188182114333"></a><a name="p8188182114333"></a>删除自动备份策略</p>
</td>
<td class="cellrowborder" valign="top" width="19.59%" headers="mcps1.1.5.1.3 "><a name="ul1618818216334"></a><a name="ul1618818216334"></a><ul id="ul1618818216334"><li>sfsturbo:shares:deleteAutoBackup</li></ul>
</td>
<td class="cellrowborder" valign="top" width="36.36%" headers="mcps1.1.5.1.4 "><a name="ul2188821103315"></a><a name="ul2188821103315"></a><ul id="ul2188821103315"><li>支持：</li></ul>
<p id="p1518852103315"><a name="p1518852103315"></a><a name="p1518852103315"></a><span>项目</span><span>(Project)</span></p>
<p id="p10189021173310"><a name="p10189021173310"></a><a name="p10189021173310"></a><span>企业项目</span><span>(Enterprise Project)</span></p>
</td>
</tr>
<tr id="row2011154719336"><td class="cellrowborder" valign="top" width="23.02%" headers="mcps1.1.5.1.1 "><p id="p2018912210336"><a name="p2018912210336"></a><a name="p2018912210336"></a>Console引用</p>
</td>
<td class="cellrowborder" valign="top" width="21.029999999999998%" headers="mcps1.1.5.1.2 "><p id="p13189192153310"><a name="p13189192153310"></a><a name="p13189192153310"></a>查询自动备份策略</p>
</td>
<td class="cellrowborder" valign="top" width="19.59%" headers="mcps1.1.5.1.3 "><a name="ul5189321153315"></a><a name="ul5189321153315"></a><ul id="ul5189321153315"><li>sfsturbo:shares:getAutoBackup</li></ul>
</td>
<td class="cellrowborder" valign="top" width="36.36%" headers="mcps1.1.5.1.4 "><a name="ul16189192163313"></a><a name="ul16189192163313"></a><ul id="ul16189192163313"><li>支持：</li></ul>
<p id="p9189112153315"><a name="p9189112153315"></a><a name="p9189112153315"></a><span>项目</span><span>(Project)</span></p>
<p id="p918942193313"><a name="p918942193313"></a><a name="p918942193313"></a><span>企业项目</span><span>(Enterprise Project)</span></p>
</td>
</tr>
<tr id="row712164733319"><td class="cellrowborder" valign="top" width="23.02%" headers="mcps1.1.5.1.1 "><p id="p17189102116336"><a name="p17189102116336"></a><a name="p17189102116336"></a>Console引用</p>
</td>
<td class="cellrowborder" valign="top" width="21.029999999999998%" headers="mcps1.1.5.1.2 "><p id="p4189421113318"><a name="p4189421113318"></a><a name="p4189421113318"></a>查询sfs turbo配额</p>
</td>
<td class="cellrowborder" valign="top" width="19.59%" headers="mcps1.1.5.1.3 "><a name="ul9189122112338"></a><a name="ul9189122112338"></a><ul id="ul9189122112338"><li>sfsturbo:shares:getQuota</li></ul>
</td>
<td class="cellrowborder" valign="top" width="36.36%" headers="mcps1.1.5.1.4 "><a name="ul12189112143316"></a><a name="ul12189112143316"></a><ul id="ul12189112143316"><li>支持：</li></ul>
<p id="p418962113339"><a name="p418962113339"></a><a name="p418962113339"></a><span>项目</span><span>(Project)</span></p>
<p id="p151901621173311"><a name="p151901621173311"></a><a name="p151901621173311"></a><span>企业项目</span><span>(Enterprise Project)</span></p>
</td>
</tr>
<tr id="row1912134715337"><td class="cellrowborder" valign="top" width="23.02%" headers="mcps1.1.5.1.1 "><p id="p18190112119339"><a name="p18190112119339"></a><a name="p18190112119339"></a>Console引用</p>
</td>
<td class="cellrowborder" valign="top" width="21.029999999999998%" headers="mcps1.1.5.1.2 "><p id="p16190721183315"><a name="p16190721183315"></a><a name="p16190721183315"></a>获取可用区信息</p>
</td>
<td class="cellrowborder" valign="top" width="19.59%" headers="mcps1.1.5.1.3 "><a name="ul7190721193313"></a><a name="ul7190721193313"></a><ul id="ul7190721193313"><li>sfsturbo:shares:getAZInfo</li></ul>
</td>
<td class="cellrowborder" valign="top" width="36.36%" headers="mcps1.1.5.1.4 "><a name="ul19190172173312"></a><a name="ul19190172173312"></a><ul id="ul19190172173312"><li>支持：</li></ul>
<p id="p219017213333"><a name="p219017213333"></a><a name="p219017213333"></a><span>项目</span><span>(Project)</span></p>
<p id="p8190182113337"><a name="p8190182113337"></a><a name="p8190182113337"></a><span>企业项目</span><span>(Enterprise Project)</span></p>
</td>
</tr>
<tr id="row14121947133320"><td class="cellrowborder" valign="top" width="23.02%" headers="mcps1.1.5.1.1 "><p id="p1819082183315"><a name="p1819082183315"></a><a name="p1819082183315"></a>Console引用</p>
</td>
<td class="cellrowborder" valign="top" width="21.029999999999998%" headers="mcps1.1.5.1.2 "><p id="p619011217338"><a name="p619011217338"></a><a name="p619011217338"></a>获取sfs turbo规格信息</p>
</td>
<td class="cellrowborder" valign="top" width="19.59%" headers="mcps1.1.5.1.3 "><a name="ul119102111332"></a><a name="ul119102111332"></a><ul id="ul119102111332"><li>sfsturbo:shares:getFlavors</li></ul>
</td>
<td class="cellrowborder" valign="top" width="36.36%" headers="mcps1.1.5.1.4 "><a name="ul819182163314"></a><a name="ul819182163314"></a><ul id="ul819182163314"><li>支持：</li></ul>
<p id="p719142118336"><a name="p719142118336"></a><a name="p719142118336"></a><span>项目</span><span>(Project)</span></p>
<p id="p1719115212338"><a name="p1719115212338"></a><a name="p1719115212338"></a><span>企业项目</span><span>(Enterprise Project)</span></p>
</td>
</tr>
<tr id="row71334714331"><td class="cellrowborder" valign="top" width="23.02%" headers="mcps1.1.5.1.1 "><p id="p101911121163311"><a name="p101911121163311"></a><a name="p101911121163311"></a>Console引用</p>
</td>
<td class="cellrowborder" valign="top" width="21.029999999999998%" headers="mcps1.1.5.1.2 "><p id="p1719162113337"><a name="p1719162113337"></a><a name="p1719162113337"></a>检查文件系统名称</p>
</td>
<td class="cellrowborder" valign="top" width="19.59%" headers="mcps1.1.5.1.3 "><a name="ul181917218332"></a><a name="ul181917218332"></a><ul id="ul181917218332"><li>sfsturbo:shares:checkShareName</li></ul>
</td>
<td class="cellrowborder" valign="top" width="36.36%" headers="mcps1.1.5.1.4 "><a name="ul61911821143317"></a><a name="ul61911821143317"></a><ul id="ul61911821143317"><li>支持：</li></ul>
<p id="p21911214336"><a name="p21911214336"></a><a name="p21911214336"></a><span>项目</span><span>(Project)</span></p>
<p id="p3191142113336"><a name="p3191142113336"></a><a name="p3191142113336"></a><span>企业项目</span><span>(Enterprise Project)</span></p>
</td>
</tr>
</tbody>
</table>

