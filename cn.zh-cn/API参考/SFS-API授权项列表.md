# SFS API授权项列表<a name="zh-cn_topic_0136979281"></a>

## 查询API版本<a name="section118729382365"></a>

<a name="table10500201144614"></a>
<table><thead align="left"><tr id="row1550061113461"><th class="cellrowborder" valign="top" width="22.61%" id="mcps1.1.5.1.1"><p id="p16500911184611"><a name="p16500911184611"></a><a name="p16500911184611"></a>API</p>
</th>
<th class="cellrowborder" valign="top" width="21.4%" id="mcps1.1.5.1.2"><p id="p550041124613"><a name="p550041124613"></a><a name="p550041124613"></a>API功能</p>
</th>
<th class="cellrowborder" valign="top" width="18.57%" id="mcps1.1.5.1.3"><p id="p1550071117468"><a name="p1550071117468"></a><a name="p1550071117468"></a>授权项</p>
</th>
<th class="cellrowborder" valign="top" width="37.419999999999995%" id="mcps1.1.5.1.4"><p id="p17500711194618"><a name="p17500711194618"></a><a name="p17500711194618"></a>授权作用域</p>
</th>
</tr>
</thead>
<tbody><tr id="row1850081111469"><td class="cellrowborder" valign="top" width="22.61%" headers="mcps1.1.5.1.1 "><p id="p20585121416312"><a name="p20585121416312"></a><a name="p20585121416312"></a>GET /</p>
</td>
<td class="cellrowborder" valign="top" width="21.4%" headers="mcps1.1.5.1.2 "><p id="p6677132217547"><a name="p6677132217547"></a><a name="p6677132217547"></a>查询API版本（OpenStack原生）</p>
</td>
<td class="cellrowborder" valign="top" width="18.57%" headers="mcps1.1.5.1.3 "><p id="p148261930155517"><a name="p148261930155517"></a><a name="p148261930155517"></a>-</p>
</td>
<td class="cellrowborder" valign="top" width="37.419999999999995%" headers="mcps1.1.5.1.4 "><a name="ul143880422544"></a><a name="ul143880422544"></a><ul id="ul143880422544"><li>不支持：</li></ul>
<p id="p1338944217541"><a name="p1338944217541"></a><a name="p1338944217541"></a><span>项目</span><span>(Project)</span></p>
<a name="ul16389542195416"></a><a name="ul16389542195416"></a><ul id="ul16389542195416"><li>不支持：</li></ul>
<p id="p123901424545"><a name="p123901424545"></a><a name="p123901424545"></a><span>企业项目</span><span>(Enterprise Project)</span></p>
</td>
</tr>
<tr id="row696204811540"><td class="cellrowborder" valign="top" width="22.61%" headers="mcps1.1.5.1.1 "><p id="p39712482545"><a name="p39712482545"></a><a name="p39712482545"></a>GET /{api_version}/</p>
</td>
<td class="cellrowborder" valign="top" width="21.4%" headers="mcps1.1.5.1.2 "><p id="p5979489542"><a name="p5979489542"></a><a name="p5979489542"></a>查询API版本（OpenStack原生）</p>
</td>
<td class="cellrowborder" valign="top" width="18.57%" headers="mcps1.1.5.1.3 "><p id="p597134845414"><a name="p597134845414"></a><a name="p597134845414"></a>-</p>
</td>
<td class="cellrowborder" valign="top" width="37.419999999999995%" headers="mcps1.1.5.1.4 "><a name="ul12403132435517"></a><a name="ul12403132435517"></a><ul id="ul12403132435517"><li>不支持：</li></ul>
<p id="p1640313248552"><a name="p1640313248552"></a><a name="p1640313248552"></a><span>项目</span><span>(Project)</span></p>
<a name="ul1740432418558"></a><a name="ul1740432418558"></a><ul id="ul1740432418558"><li>不支持：</li></ul>
<p id="p5405424195519"><a name="p5405424195519"></a><a name="p5405424195519"></a><span>企业项目</span><span>(Enterprise Project)</span></p>
</td>
</tr>
</tbody>
</table>

## 文件共享<a name="section481420011409"></a>

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
<tbody><tr id="row1383151634015"><td class="cellrowborder" valign="top" width="22.45%" headers="mcps1.1.5.1.1 "><p id="p18500171112464"><a name="p18500171112464"></a><a name="p18500171112464"></a>POST /v2/{project_id}/shares</p>
</td>
<td class="cellrowborder" valign="top" width="21.43%" headers="mcps1.1.5.1.2 "><p id="p16500181116469"><a name="p16500181116469"></a><a name="p16500181116469"></a>创建共享</p>
<p id="p369615322438"><a name="p369615322438"></a><a name="p369615322438"></a>（OpenStack原生）</p>
</td>
<td class="cellrowborder" valign="top" width="19.38%" headers="mcps1.1.5.1.3 "><a name="ul5221162535419"></a><a name="ul5221162535419"></a><ul id="ul5221162535419"><li>sfs:shares:createShare</li></ul>
</td>
<td class="cellrowborder" valign="top" width="36.74%" headers="mcps1.1.5.1.4 "><a name="ul17920152735612"></a><a name="ul17920152735612"></a><ul id="ul17920152735612"><li>支持：</li></ul>
<p id="p79206276568"><a name="p79206276568"></a><a name="p79206276568"></a><span>项目</span><span>(Project)</span></p>
<p id="p16920172713564"><a name="p16920172713564"></a><a name="p16920172713564"></a><span>企业项目</span><span>(Enterprise Project)</span></p>
</td>
</tr>
<tr id="row450081117466"><td class="cellrowborder" valign="top" width="22.45%" headers="mcps1.1.5.1.1 "><p id="p165005111464"><a name="p165005111464"></a><a name="p165005111464"></a>GET /v2/{project_id}/shares/detail</p>
</td>
<td class="cellrowborder" valign="top" width="21.43%" headers="mcps1.1.5.1.2 "><p id="p450013117466"><a name="p450013117466"></a><a name="p450013117466"></a>查询所有共享详细信息</p>
<p id="p995633012565"><a name="p995633012565"></a><a name="p995633012565"></a>（OpenStack原生）</p>
</td>
<td class="cellrowborder" valign="top" width="19.38%" headers="mcps1.1.5.1.3 "><a name="ul9472431185413"></a><a name="ul9472431185413"></a><ul id="ul9472431185413"><li>sfs:shares:getAllSharesDetail</li></ul>
</td>
<td class="cellrowborder" valign="top" width="36.74%" headers="mcps1.1.5.1.4 "><a name="ul269215404514"></a><a name="ul269215404514"></a><ul id="ul269215404514"><li>支持：</li></ul>
<p id="p12692240135115"><a name="p12692240135115"></a><a name="p12692240135115"></a><span>项目</span><span>(Project)</span></p>
<p id="p1692440125115"><a name="p1692440125115"></a><a name="p1692440125115"></a><span>企业项目</span><span>(Enterprise Project)</span></p>
</td>
</tr>
<tr id="row450021115461"><td class="cellrowborder" valign="top" width="22.45%" headers="mcps1.1.5.1.1 "><p id="p12197116134811"><a name="p12197116134811"></a><a name="p12197116134811"></a>GET /v2/{project_id}/shares/{share_id}</p>
</td>
<td class="cellrowborder" valign="top" width="21.43%" headers="mcps1.1.5.1.2 "><p id="p0444153655015"><a name="p0444153655015"></a><a name="p0444153655015"></a>查询单个共享详细信息</p>
<p id="p8722183212561"><a name="p8722183212561"></a><a name="p8722183212561"></a>（OpenStack原生）</p>
</td>
<td class="cellrowborder" valign="top" width="19.38%" headers="mcps1.1.5.1.3 "><a name="ul1339423215418"></a><a name="ul1339423215418"></a><ul id="ul1339423215418"><li>sfs:shares:getShareDetail</li></ul>
</td>
<td class="cellrowborder" valign="top" width="36.74%" headers="mcps1.1.5.1.4 "><a name="ul178015427519"></a><a name="ul178015427519"></a><ul id="ul178015427519"><li>支持：</li></ul>
<p id="p1680164217513"><a name="p1680164217513"></a><a name="p1680164217513"></a><span>项目</span><span>(Project)</span></p>
<p id="p080442175111"><a name="p080442175111"></a><a name="p080442175111"></a><span>企业项目</span><span>(Enterprise Project)</span></p>
</td>
</tr>
<tr id="row150013119462"><td class="cellrowborder" valign="top" width="22.45%" headers="mcps1.1.5.1.1 "><p id="p1150091134613"><a name="p1150091134613"></a><a name="p1150091134613"></a>GET /v2/{project_id}/shares/{share_id}/export_locations</p>
</td>
<td class="cellrowborder" valign="top" width="21.43%" headers="mcps1.1.5.1.2 "><p id="p1550018112467"><a name="p1550018112467"></a><a name="p1550018112467"></a>查询共享挂载路径</p>
<p id="p7190163511569"><a name="p7190163511569"></a><a name="p7190163511569"></a>（OpenStack原生）</p>
</td>
<td class="cellrowborder" valign="top" width="19.38%" headers="mcps1.1.5.1.3 "><a name="ul1589310514552"></a><a name="ul1589310514552"></a><ul id="ul1589310514552"><li>sfs:shares:getShareExportLocations</li></ul>
</td>
<td class="cellrowborder" valign="top" width="36.74%" headers="mcps1.1.5.1.4 "><a name="ul1076744405110"></a><a name="ul1076744405110"></a><ul id="ul1076744405110"><li>支持：</li></ul>
<p id="p1476774495113"><a name="p1476774495113"></a><a name="p1476774495113"></a><span>项目</span><span>(Project)</span></p>
<p id="p9767194495117"><a name="p9767194495117"></a><a name="p9767194495117"></a><span>企业项目</span><span>(Enterprise Project)</span></p>
</td>
</tr>
<tr id="row35004115467"><td class="cellrowborder" valign="top" width="22.45%" headers="mcps1.1.5.1.1 "><p id="p12500161164619"><a name="p12500161164619"></a><a name="p12500161164619"></a>PUT /v2/{project_id}/shares/{share_id}</p>
</td>
<td class="cellrowborder" valign="top" width="21.43%" headers="mcps1.1.5.1.2 "><p id="p10500311114617"><a name="p10500311114617"></a><a name="p10500311114617"></a>修改共享</p>
<p id="p259718363561"><a name="p259718363561"></a><a name="p259718363561"></a>（OpenStack原生）</p>
</td>
<td class="cellrowborder" valign="top" width="19.38%" headers="mcps1.1.5.1.3 "><a name="ul1675345245517"></a><a name="ul1675345245517"></a><ul id="ul1675345245517"><li>sfs:shares:updateShare</li></ul>
</td>
<td class="cellrowborder" valign="top" width="36.74%" headers="mcps1.1.5.1.4 "><a name="ul9689145165111"></a><a name="ul9689145165111"></a><ul id="ul9689145165111"><li>支持：</li></ul>
<p id="p14689104510512"><a name="p14689104510512"></a><a name="p14689104510512"></a><span>项目</span><span>(Project)</span></p>
<p id="p9689124518515"><a name="p9689124518515"></a><a name="p9689124518515"></a><span>企业项目</span><span>(Enterprise Project)</span></p>
</td>
</tr>
<tr id="row58051141154818"><td class="cellrowborder" valign="top" width="22.45%" headers="mcps1.1.5.1.1 "><p id="p875816553487"><a name="p875816553487"></a><a name="p875816553487"></a>DELETE /v2/{project_id}/shares/{share_id}</p>
</td>
<td class="cellrowborder" valign="top" width="21.43%" headers="mcps1.1.5.1.2 "><p id="p1350031154610"><a name="p1350031154610"></a><a name="p1350031154610"></a>删除共享</p>
<p id="p109683819562"><a name="p109683819562"></a><a name="p109683819562"></a>（OpenStack原生）</p>
</td>
<td class="cellrowborder" valign="top" width="19.38%" headers="mcps1.1.5.1.3 "><a name="ul91291455135519"></a><a name="ul91291455135519"></a><ul id="ul91291455135519"><li>sfs:shares:deleteShare</li></ul>
</td>
<td class="cellrowborder" valign="top" width="36.74%" headers="mcps1.1.5.1.4 "><a name="ul15345184725110"></a><a name="ul15345184725110"></a><ul id="ul15345184725110"><li>支持：</li></ul>
<p id="p937724715119"><a name="p937724715119"></a><a name="p937724715119"></a><span>项目</span><span>(Project)</span></p>
<p id="p103771847195115"><a name="p103771847195115"></a><a name="p103771847195115"></a><span>企业项目</span><span>(Enterprise Project)</span></p>
</td>
</tr>
</tbody>
</table>

## 共享访问规则<a name="section9212172264017"></a>

<a name="table19339133774014"></a>
<table><thead align="left"><tr id="row15339153713403"><th class="cellrowborder" valign="top" width="22.48%" id="mcps1.1.5.1.1"><p id="p14339837174018"><a name="p14339837174018"></a><a name="p14339837174018"></a>API</p>
</th>
<th class="cellrowborder" valign="top" width="21.27%" id="mcps1.1.5.1.2"><p id="p17340837134017"><a name="p17340837134017"></a><a name="p17340837134017"></a>API功能</p>
</th>
<th class="cellrowborder" valign="top" width="19.11%" id="mcps1.1.5.1.3"><p id="p1134033744011"><a name="p1134033744011"></a><a name="p1134033744011"></a>授权项</p>
</th>
<th class="cellrowborder" valign="top" width="37.14%" id="mcps1.1.5.1.4"><p id="p153401837114019"><a name="p153401837114019"></a><a name="p153401837114019"></a>授权作用域</p>
</th>
</tr>
</thead>
<tbody><tr id="row17340133734016"><td class="cellrowborder" valign="top" width="22.48%" headers="mcps1.1.5.1.1 "><p id="p133401637114010"><a name="p133401637114010"></a><a name="p133401637114010"></a>POST /v2/{project_id}/shares/{share_id}/action</p>
</td>
<td class="cellrowborder" valign="top" width="21.27%" headers="mcps1.1.5.1.2 "><p id="p115916441615"><a name="p115916441615"></a><a name="p115916441615"></a>添加共享访问规则</p>
<p id="p1234053784010"><a name="p1234053784010"></a><a name="p1234053784010"></a>（OpenStack原生）</p>
</td>
<td class="cellrowborder" valign="top" width="19.11%" headers="mcps1.1.5.1.3 "><a name="ul173405370406"></a><a name="ul173405370406"></a><ul id="ul173405370406"><li>sfs:shares:ShareAction</li></ul>
</td>
<td class="cellrowborder" valign="top" width="37.14%" headers="mcps1.1.5.1.4 "><a name="ul7340237124013"></a><a name="ul7340237124013"></a><ul id="ul7340237124013"><li>支持：</li></ul>
<p id="p1234053717407"><a name="p1234053717407"></a><a name="p1234053717407"></a><span>项目</span><span>(Project)</span></p>
<p id="p15340537144017"><a name="p15340537144017"></a><a name="p15340537144017"></a><span>企业项目</span><span>(Enterprise Project)</span></p>
</td>
</tr>
<tr id="row8340637104013"><td class="cellrowborder" valign="top" width="22.48%" headers="mcps1.1.5.1.1 "><p id="p1834043774015"><a name="p1834043774015"></a><a name="p1834043774015"></a>POST /v2/{project_id}/shares/{share_id}/action</p>
</td>
<td class="cellrowborder" valign="top" width="21.27%" headers="mcps1.1.5.1.2 "><p id="p43401937114016"><a name="p43401937114016"></a><a name="p43401937114016"></a>删除共享访问规则</p>
<p id="p17341153717404"><a name="p17341153717404"></a><a name="p17341153717404"></a>（OpenStack原生）</p>
</td>
<td class="cellrowborder" valign="top" width="19.11%" headers="mcps1.1.5.1.3 "><a name="ul23411737154014"></a><a name="ul23411737154014"></a><ul id="ul23411737154014"><li>sfs:shares:ShareAction</li></ul>
</td>
<td class="cellrowborder" valign="top" width="37.14%" headers="mcps1.1.5.1.4 "><a name="ul4341193715405"></a><a name="ul4341193715405"></a><ul id="ul4341193715405"><li>支持：</li></ul>
<p id="p7341937154015"><a name="p7341937154015"></a><a name="p7341937154015"></a><span>项目</span><span>(Project)</span></p>
<p id="p1434143754013"><a name="p1434143754013"></a><a name="p1434143754013"></a><span>企业项目</span><span>(Enterprise Project)</span></p>
</td>
</tr>
<tr id="row13411637144012"><td class="cellrowborder" valign="top" width="22.48%" headers="mcps1.1.5.1.1 "><p id="p12341193718405"><a name="p12341193718405"></a><a name="p12341193718405"></a>POST /v2/{project_id}/shares/{share_id}/action</p>
</td>
<td class="cellrowborder" valign="top" width="21.27%" headers="mcps1.1.5.1.2 "><p id="p673073516199"><a name="p673073516199"></a><a name="p673073516199"></a>查询共享访问规则</p>
<p id="p1934111374401"><a name="p1934111374401"></a><a name="p1934111374401"></a>（OpenStack原生）</p>
</td>
<td class="cellrowborder" valign="top" width="19.11%" headers="mcps1.1.5.1.3 "><a name="ul634113764017"></a><a name="ul634113764017"></a><ul id="ul634113764017"><li>sfs:shares:ShareAction</li></ul>
</td>
<td class="cellrowborder" valign="top" width="37.14%" headers="mcps1.1.5.1.4 "><a name="ul8341103715407"></a><a name="ul8341103715407"></a><ul id="ul8341103715407"><li>支持：</li></ul>
<p id="p6341237144016"><a name="p6341237144016"></a><a name="p6341237144016"></a><span>项目</span><span>(Project)</span></p>
<p id="p2341133784015"><a name="p2341133784015"></a><a name="p2341133784015"></a><span>企业项目</span><span>(Enterprise Project)</span></p>
</td>
</tr>
</tbody>
</table>

## 配额管理<a name="section14448942124020"></a>

<a name="table116315524408"></a>
<table><thead align="left"><tr id="row16314529400"><th class="cellrowborder" valign="top" width="22.61%" id="mcps1.1.5.1.1"><p id="p0631195210407"><a name="p0631195210407"></a><a name="p0631195210407"></a>API</p>
</th>
<th class="cellrowborder" valign="top" width="21.4%" id="mcps1.1.5.1.2"><p id="p663175274020"><a name="p663175274020"></a><a name="p663175274020"></a>API功能</p>
</th>
<th class="cellrowborder" valign="top" width="18.57%" id="mcps1.1.5.1.3"><p id="p1763110525401"><a name="p1763110525401"></a><a name="p1763110525401"></a>授权项</p>
</th>
<th class="cellrowborder" valign="top" width="37.419999999999995%" id="mcps1.1.5.1.4"><p id="p14631195274015"><a name="p14631195274015"></a><a name="p14631195274015"></a>授权作用域</p>
</th>
</tr>
</thead>
<tbody><tr id="row106311352174019"><td class="cellrowborder" valign="top" width="22.61%" headers="mcps1.1.5.1.1 "><p id="p66311052104014"><a name="p66311052104014"></a><a name="p66311052104014"></a>GET /v2/{project_id}/os-quota-sets/{project_id}</p>
</td>
<td class="cellrowborder" valign="top" width="21.4%" headers="mcps1.1.5.1.2 "><p id="p76311352104011"><a name="p76311352104011"></a><a name="p76311352104011"></a>查询租户配额</p>
<p id="p196311352114020"><a name="p196311352114020"></a><a name="p196311352114020"></a>（OpenStack原生）</p>
</td>
<td class="cellrowborder" valign="top" width="18.57%" headers="mcps1.1.5.1.3 "><a name="ul663135212401"></a><a name="ul663135212401"></a><ul id="ul663135212401"><li>sfs:quotas:getOSQuotaSets</li></ul>
</td>
<td class="cellrowborder" valign="top" width="37.419999999999995%" headers="mcps1.1.5.1.4 "><a name="ul663115214011"></a><a name="ul663115214011"></a><ul id="ul663115214011"><li>支持：</li></ul>
<p id="p46311152114013"><a name="p46311152114013"></a><a name="p46311152114013"></a><span>项目</span><span>(Project)</span></p>
<a name="ul20725732629"></a><a name="ul20725732629"></a><ul id="ul20725732629"><li>不支持：</li></ul>
<p id="p20632852184014"><a name="p20632852184014"></a><a name="p20632852184014"></a><span>企业项目</span><span>(Enterprise Project)</span></p>
</td>
</tr>
</tbody>
</table>

## 扩容缩容<a name="section149921655204019"></a>

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
<tbody><tr id="row885512864119"><td class="cellrowborder" valign="top" width="23.150000000000002%" headers="mcps1.1.5.1.1 "><p id="zh-cn_topic_0076901182_li61346876p0"><a name="zh-cn_topic_0076901182_li61346876p0"></a><a name="zh-cn_topic_0076901182_li61346876p0"></a>POST /v2/{project_id}/shares/{share_id}/action</p>
</td>
<td class="cellrowborder" valign="top" width="20.73%" headers="mcps1.1.5.1.2 "><p id="p261925114518"><a name="p261925114518"></a><a name="p261925114518"></a>扩容共享</p>
<p id="p78551084418"><a name="p78551084418"></a><a name="p78551084418"></a>（OpenStack原生）</p>
</td>
<td class="cellrowborder" valign="top" width="19.650000000000002%" headers="mcps1.1.5.1.3 "><a name="ul1285513816415"></a><a name="ul1285513816415"></a><ul id="ul1285513816415"><li>sfs:shares:ShareAction</li></ul>
</td>
<td class="cellrowborder" valign="top" width="36.47%" headers="mcps1.1.5.1.4 "><a name="ul78561582415"></a><a name="ul78561582415"></a><ul id="ul78561582415"><li>支持：</li></ul>
<p id="p1685614813415"><a name="p1685614813415"></a><a name="p1685614813415"></a><span>项目</span><span>(Project)</span></p>
<p id="p1856198184113"><a name="p1856198184113"></a><a name="p1856198184113"></a><span>企业项目</span><span>(Enterprise Project)</span></p>
</td>
</tr>
<tr id="row2085688154112"><td class="cellrowborder" valign="top" width="23.150000000000002%" headers="mcps1.1.5.1.1 "><p id="p12885124412512"><a name="p12885124412512"></a><a name="p12885124412512"></a>POST /v2/{project_id}/shares/{share_id}/action</p>
</td>
<td class="cellrowborder" valign="top" width="20.73%" headers="mcps1.1.5.1.2 "><p id="p208561086417"><a name="p208561086417"></a><a name="p208561086417"></a>缩容共享</p>
<p id="p17856282414"><a name="p17856282414"></a><a name="p17856282414"></a>（OpenStack原生）</p>
</td>
<td class="cellrowborder" valign="top" width="19.650000000000002%" headers="mcps1.1.5.1.3 "><a name="ul0856189416"></a><a name="ul0856189416"></a><ul id="ul0856189416"><li>sfs:shares:ShareAction</li></ul>
</td>
<td class="cellrowborder" valign="top" width="36.47%" headers="mcps1.1.5.1.4 "><a name="ul68561587417"></a><a name="ul68561587417"></a><ul id="ul68561587417"><li>支持：</li></ul>
<p id="p1485617815412"><a name="p1485617815412"></a><a name="p1485617815412"></a><span>项目</span><span>(Project)</span></p>
<p id="p1685712864110"><a name="p1685712864110"></a><a name="p1685712864110"></a><span>企业项目</span><span>(Enterprise Project)</span></p>
</td>
</tr>
</tbody>
</table>

## 共享标签<a name="section1023861411419"></a>

<a name="table89899314416"></a>
<table><thead align="left"><tr id="row2989173119414"><th class="cellrowborder" valign="top" width="23.419999999999998%" id="mcps1.1.5.1.1"><p id="p1198993114113"><a name="p1198993114113"></a><a name="p1198993114113"></a>API</p>
</th>
<th class="cellrowborder" valign="top" width="20.73%" id="mcps1.1.5.1.2"><p id="p1799043117412"><a name="p1799043117412"></a><a name="p1799043117412"></a>API功能</p>
</th>
<th class="cellrowborder" valign="top" width="20.19%" id="mcps1.1.5.1.3"><p id="p13990113112411"><a name="p13990113112411"></a><a name="p13990113112411"></a>授权项</p>
</th>
<th class="cellrowborder" valign="top" width="35.66%" id="mcps1.1.5.1.4"><p id="p1299043194119"><a name="p1299043194119"></a><a name="p1299043194119"></a>授权作用域</p>
</th>
</tr>
</thead>
<tbody><tr id="row999013112411"><td class="cellrowborder" valign="top" width="23.419999999999998%" headers="mcps1.1.5.1.1 "><p id="li6064234314513p0"><a name="li6064234314513p0"></a><a name="li6064234314513p0"></a>POST /v2/{project_id}/sfs/{share_id}/tags</p>
</td>
<td class="cellrowborder" valign="top" width="20.73%" headers="mcps1.1.5.1.2 "><p id="p3222554171319"><a name="p3222554171319"></a><a name="p3222554171319"></a>添加共享标签</p>
</td>
<td class="cellrowborder" valign="top" width="20.19%" headers="mcps1.1.5.1.3 "><a name="ul16990133110411"></a><a name="ul16990133110411"></a><ul id="ul16990133110411"><li>sfs:tags:addShareTags</li></ul>
</td>
<td class="cellrowborder" valign="top" width="35.66%" headers="mcps1.1.5.1.4 "><a name="ul6990143134116"></a><a name="ul6990143134116"></a><ul id="ul6990143134116"><li>支持：</li></ul>
<p id="p899073184114"><a name="p899073184114"></a><a name="p899073184114"></a><span>项目</span><span>(Project)</span></p>
<a name="ul2990153104116"></a><a name="ul2990153104116"></a><ul id="ul2990153104116"><li>不支持</li></ul>
<p id="p130264410128"><a name="p130264410128"></a><a name="p130264410128"></a><span>企业项目</span><span>(Enterprise Project)</span></p>
</td>
</tr>
<tr id="row199043114112"><td class="cellrowborder" valign="top" width="23.419999999999998%" headers="mcps1.1.5.1.1 "><p id="p13843182131216"><a name="p13843182131216"></a><a name="p13843182131216"></a>DELETE /v2/{project_id}/sfs/{share_id}/tags/{key}</p>
</td>
<td class="cellrowborder" valign="top" width="20.73%" headers="mcps1.1.5.1.2 "><p id="p1699112315412"><a name="p1699112315412"></a><a name="p1699112315412"></a>删除共享标签</p>
</td>
<td class="cellrowborder" valign="top" width="20.19%" headers="mcps1.1.5.1.3 "><a name="ul299123184119"></a><a name="ul299123184119"></a><ul id="ul299123184119"><li>sfs:tags:deleteShareTags</li></ul>
</td>
<td class="cellrowborder" valign="top" width="35.66%" headers="mcps1.1.5.1.4 "><a name="ul783348181215"></a><a name="ul783348181215"></a><ul id="ul783348181215"><li>支持：</li></ul>
<p id="p2083144814123"><a name="p2083144814123"></a><a name="p2083144814123"></a><span>项目</span><span>(Project)</span></p>
<a name="ul3991487122"></a><a name="ul3991487122"></a><ul id="ul3991487122"><li>不支持</li></ul>
<p id="p2991231174119"><a name="p2991231174119"></a><a name="p2991231174119"></a><span>企业项目</span><span>(Enterprise Project)</span></p>
</td>
</tr>
<tr id="row1299153184112"><td class="cellrowborder" valign="top" width="23.419999999999998%" headers="mcps1.1.5.1.1 "><p id="p1374164161210"><a name="p1374164161210"></a><a name="p1374164161210"></a>GET /v2/{project_id}/sfs/{share_id}/tags</p>
</td>
<td class="cellrowborder" valign="top" width="20.73%" headers="mcps1.1.5.1.2 "><p id="p099163110417"><a name="p099163110417"></a><a name="p099163110417"></a>查询共享标签</p>
</td>
<td class="cellrowborder" valign="top" width="20.19%" headers="mcps1.1.5.1.3 "><a name="ul171516164124"></a><a name="ul171516164124"></a><ul id="ul171516164124"><li>sfs:tags:getShareTags</li></ul>
</td>
<td class="cellrowborder" valign="top" width="35.66%" headers="mcps1.1.5.1.4 "><a name="ul1176125118124"></a><a name="ul1176125118124"></a><ul id="ul1176125118124"><li>支持：</li></ul>
<p id="p1119218519125"><a name="p1119218519125"></a><a name="p1119218519125"></a><span>项目</span><span>(Project)</span></p>
<a name="ul319255161216"></a><a name="ul319255161216"></a><ul id="ul319255161216"><li>不支持</li></ul>
<p id="p141921451201219"><a name="p141921451201219"></a><a name="p141921451201219"></a><span>企业项目</span><span>(Enterprise Project)</span></p>
</td>
</tr>
<tr id="row1999153124110"><td class="cellrowborder" valign="top" width="23.419999999999998%" headers="mcps1.1.5.1.1 "><p id="p43133541176"><a name="p43133541176"></a><a name="p43133541176"></a>GET /v2/{project_id}/sfs/tags</p>
</td>
<td class="cellrowborder" valign="top" width="20.73%" headers="mcps1.1.5.1.2 "><p id="p4991931194112"><a name="p4991931194112"></a><a name="p4991931194112"></a>查询租户所有共享标签</p>
</td>
<td class="cellrowborder" valign="top" width="20.19%" headers="mcps1.1.5.1.3 "><a name="ul9991143114111"></a><a name="ul9991143114111"></a><ul id="ul9991143114111"><li>sfs:tags:getAllTags</li></ul>
</td>
<td class="cellrowborder" valign="top" width="35.66%" headers="mcps1.1.5.1.4 "><a name="ul3989175451212"></a><a name="ul3989175451212"></a><ul id="ul3989175451212"><li>支持：</li></ul>
<p id="p79895548127"><a name="p79895548127"></a><a name="p79895548127"></a><span>项目</span><span>(Project)</span></p>
<a name="ul159897546121"></a><a name="ul159897546121"></a><ul id="ul159897546121"><li>不支持：</li></ul>
<p id="p6989145410129"><a name="p6989145410129"></a><a name="p6989145410129"></a><span>企业项目</span><span>(Enterprise Project)</span></p>
</td>
</tr>
<tr id="row2992131204110"><td class="cellrowborder" valign="top" width="23.419999999999998%" headers="mcps1.1.5.1.1 "><p id="p1495318561213"><a name="p1495318561213"></a><a name="p1495318561213"></a>POST /v2/{project_id}/sfs/{share_id}/tags/action</p>
</td>
<td class="cellrowborder" valign="top" width="20.73%" headers="mcps1.1.5.1.2 "><p id="p2992113112414"><a name="p2992113112414"></a><a name="p2992113112414"></a>批量添加共享标签</p>
</td>
<td class="cellrowborder" valign="top" width="20.19%" headers="mcps1.1.5.1.3 "><a name="ul89927318412"></a><a name="ul89927318412"></a><ul id="ul89927318412"><li>sfs:tags:batchShareTags</li></ul>
</td>
<td class="cellrowborder" valign="top" width="35.66%" headers="mcps1.1.5.1.4 "><a name="ul1888015171318"></a><a name="ul1888015171318"></a><ul id="ul1888015171318"><li>支持：</li></ul>
<p id="p10896115133"><a name="p10896115133"></a><a name="p10896115133"></a><span>项目</span><span>(Project)</span></p>
<a name="ul28961911138"></a><a name="ul28961911138"></a><ul id="ul28961911138"><li>不支持</li></ul>
<p id="p1789611161310"><a name="p1789611161310"></a><a name="p1789611161310"></a><span>企业项目</span><span>(Enterprise Project)</span></p>
</td>
</tr>
<tr id="row5992123115415"><td class="cellrowborder" valign="top" width="23.419999999999998%" headers="mcps1.1.5.1.1 "><p id="p94681771125"><a name="p94681771125"></a><a name="p94681771125"></a>POST /v2/{project_id}/sfs/{share_id}/tags/action</p>
</td>
<td class="cellrowborder" valign="top" width="20.73%" headers="mcps1.1.5.1.2 "><p id="p1499233194118"><a name="p1499233194118"></a><a name="p1499233194118"></a>批量删除共享标签</p>
</td>
<td class="cellrowborder" valign="top" width="20.19%" headers="mcps1.1.5.1.3 "><a name="ul5609141841215"></a><a name="ul5609141841215"></a><ul id="ul5609141841215"><li>sfs:tags:batchShareTags</li></ul>
</td>
<td class="cellrowborder" valign="top" width="35.66%" headers="mcps1.1.5.1.4 "><a name="ul1925535191312"></a><a name="ul1925535191312"></a><ul id="ul1925535191312"><li>支持：</li></ul>
<p id="p425517510138"><a name="p425517510138"></a><a name="p425517510138"></a><span>项目</span><span>(Project)</span></p>
<a name="ul72551752132"></a><a name="ul72551752132"></a><ul id="ul72551752132"><li>不支持：</li></ul>
<p id="p1625515581311"><a name="p1625515581311"></a><a name="p1625515581311"></a><span>企业项目</span><span>(Enterprise Project)</span></p>
</td>
</tr>
<tr id="row17992103117419"><td class="cellrowborder" valign="top" width="23.419999999999998%" headers="mcps1.1.5.1.1 "><p id="p599363113419"><a name="p599363113419"></a><a name="p599363113419"></a>POST /v2/{project_id}/sfs/resource_instances/action</p>
</td>
<td class="cellrowborder" valign="top" width="20.73%" headers="mcps1.1.5.1.2 "><p id="p699353117414"><a name="p699353117414"></a><a name="p699353117414"></a>根据标签查询共享详情</p>
</td>
<td class="cellrowborder" valign="top" width="20.19%" headers="mcps1.1.5.1.3 "><a name="ul7187152161213"></a><a name="ul7187152161213"></a><ul id="ul7187152161213"><li>sfs:tags:getShareByTags</li></ul>
</td>
<td class="cellrowborder" valign="top" width="35.66%" headers="mcps1.1.5.1.4 "><a name="ul441118816133"></a><a name="ul441118816133"></a><ul id="ul441118816133"><li>支持：</li></ul>
<p id="p1041114871312"><a name="p1041114871312"></a><a name="p1041114871312"></a><span>项目</span><span>(Project)</span></p>
<a name="ul144113861314"></a><a name="ul144113861314"></a><ul id="ul144113861314"><li>不支持：</li></ul>
<p id="p541113801313"><a name="p541113801313"></a><a name="p541113801313"></a><span>企业项目</span><span>(Enterprise Project)</span></p>
</td>
</tr>
<tr id="row1880715532815"><td class="cellrowborder" valign="top" width="23.419999999999998%" headers="mcps1.1.5.1.1 "><p id="p1286961893"><a name="p1286961893"></a><a name="p1286961893"></a>POST /v2/{project_id}/sfs/resource_instances/action</p>
</td>
<td class="cellrowborder" valign="top" width="20.73%" headers="mcps1.1.5.1.2 "><p id="p86215284104"><a name="p86215284104"></a><a name="p86215284104"></a>根据标签查询共享个数</p>
</td>
<td class="cellrowborder" valign="top" width="20.19%" headers="mcps1.1.5.1.3 "><a name="ul44681323111213"></a><a name="ul44681323111213"></a><ul id="ul44681323111213"><li>sfs:tags:getShareByTags</li></ul>
</td>
<td class="cellrowborder" valign="top" width="35.66%" headers="mcps1.1.5.1.4 "><a name="ul1597411101316"></a><a name="ul1597411101316"></a><ul id="ul1597411101316"><li>支持：</li></ul>
<p id="p15974161151319"><a name="p15974161151319"></a><a name="p15974161151319"></a><span>项目</span><span>(Project)</span></p>
<a name="ul797418114133"></a><a name="ul797418114133"></a><ul id="ul797418114133"><li>不支持：</li></ul>
<p id="p1197431121315"><a name="p1197431121315"></a><a name="p1197431121315"></a><span>企业项目</span><span>(Enterprise Project)</span></p>
</td>
</tr>
</tbody>
</table>

## 可用区<a name="section736510362416"></a>

<a name="table13349104974110"></a>
<table><thead align="left"><tr id="row173491449134119"><th class="cellrowborder" valign="top" width="23.150000000000002%" id="mcps1.1.5.1.1"><p id="p73501649114111"><a name="p73501649114111"></a><a name="p73501649114111"></a>API</p>
</th>
<th class="cellrowborder" valign="top" width="20.86%" id="mcps1.1.5.1.2"><p id="p1335084954114"><a name="p1335084954114"></a><a name="p1335084954114"></a>API功能</p>
</th>
<th class="cellrowborder" valign="top" width="20.86%" id="mcps1.1.5.1.3"><p id="p535064924119"><a name="p535064924119"></a><a name="p535064924119"></a>授权项</p>
</th>
<th class="cellrowborder" valign="top" width="35.13%" id="mcps1.1.5.1.4"><p id="p83503496418"><a name="p83503496418"></a><a name="p83503496418"></a>授权作用域</p>
</th>
</tr>
</thead>
<tbody><tr id="row0350194994114"><td class="cellrowborder" valign="top" width="23.150000000000002%" headers="mcps1.1.5.1.1 "><a name="ul48183041112946"></a><a name="ul48183041112946"></a><ul id="ul48183041112946"><li>GET /v2/{project_id}/availability-zones?share_az={share_az}</li></ul>
</td>
<td class="cellrowborder" valign="top" width="20.86%" headers="mcps1.1.5.1.2 "><p id="p13350184974113"><a name="p13350184974113"></a><a name="p13350184974113"></a>查询可用区</p>
<p id="p163501149114112"><a name="p163501149114112"></a><a name="p163501149114112"></a>（OpenStack原生）</p>
</td>
<td class="cellrowborder" valign="top" width="20.86%" headers="mcps1.1.5.1.3 "><a name="ul8350249134120"></a><a name="ul8350249134120"></a><ul id="ul8350249134120"><li>sfs:availabilityZones:getAvailabilityZones</li></ul>
</td>
<td class="cellrowborder" valign="top" width="35.13%" headers="mcps1.1.5.1.4 "><a name="ul035094954111"></a><a name="ul035094954111"></a><ul id="ul035094954111"><li>支持：</li></ul>
<p id="p14350154917413"><a name="p14350154917413"></a><a name="p14350154917413"></a><span>项目</span><span>(Project)</span></p>
<a name="ul103513495415"></a><a name="ul103513495415"></a><ul id="ul103513495415"><li>不支持：</li></ul>
<p id="p53511749124110"><a name="p53511749124110"></a><a name="p53511749124110"></a><span>企业项目</span><span>(Enterprise Project)</span></p>
</td>
</tr>
</tbody>
</table>

