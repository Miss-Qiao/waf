# WAF使用概览<a name="waf_01_0071"></a>

开通Web应用防火墙（WAF）服务后并将您的网站域名接入WAF，使网站的访问流量全部流转到WAF进行监控防护。

Web应用防火墙的使用概览如[表1](#table186068221358)所示。

**表 1**  Web应用防火墙的使用概览

<a name="table186068221358"></a>
<table><thead align="left"><tr id="row760782211359"><th class="cellrowborder" valign="top" width="29.03%" id="mcps1.2.3.1.1"><p id="p560712263512"><a name="p560712263512"></a><a name="p560712263512"></a>子流程</p>
</th>
<th class="cellrowborder" valign="top" width="70.97%" id="mcps1.2.3.1.2"><p id="p196074222353"><a name="p196074222353"></a><a name="p196074222353"></a>说明</p>
</th>
</tr>
</thead>
<tbody><tr id="row181711555123513"><td class="cellrowborder" valign="top" width="29.03%" headers="mcps1.2.3.1.1 "><p id="p1717265511351"><a name="p1717265511351"></a><a name="p1717265511351"></a>开通WAF</p>
</td>
<td class="cellrowborder" valign="top" width="70.97%" headers="mcps1.2.3.1.2 "><p id="p121726559354"><a name="p121726559354"></a><a name="p121726559354"></a>支持包年包月的计费方式开通WAF。</p>
<a name="ul137817184114"></a><a name="ul137817184114"></a><ul id="ul137817184114"><li><b><span class="cmdname" id="cmdname5737344117"><a name="cmdname5737344117"></a><a name="cmdname5737344117"></a>计费模式：</span></b>包年包月模式。</li><li><b><span class="cmdname" id="cmdname1586154061114"><a name="cmdname1586154061114"></a><a name="cmdname1586154061114"></a>计费项：</span></b>按所选购的服务版本、扩展包以及产品专家服务计费。</li><li><b><span class="cmdname" id="cmdname1646411463114"><a name="cmdname1646411463114"></a><a name="cmdname1646411463114"></a>付费方式：</span></b>预付费。</li><li><b><span class="cmdname" id="cmdname20536165018118"><a name="cmdname20536165018118"></a><a name="cmdname20536165018118"></a>计费周期：</span></b>按月/年计费，购买时生成账单付费。</li><li><b><span class="cmdname" id="cmdname11697854111115"><a name="cmdname11697854111115"></a><a name="cmdname11697854111115"></a>扣费周期：</span></b>自购买当日起，根据所选择的购买时长（月/年）计算，一次性选购1年即可享受8.3折优惠。</li><li><b><span class="cmdname" id="cmdname1247916071218"><a name="cmdname1247916071218"></a><a name="cmdname1247916071218"></a>到期说明：</span></b>当您购买的防护服务到期时，域名将会被冻结15天。</li></ul>
<p id="p201266375458"><a name="p201266375458"></a><a name="p201266375458"></a>详细操作请参见<a href="开通WAF.md">开通WAF</a>。</p>
</td>
</tr>
<tr id="row16607422173517"><td class="cellrowborder" valign="top" width="29.03%" headers="mcps1.2.3.1.1 "><p id="p14746935173916"><a name="p14746935173916"></a><a name="p14746935173916"></a>添加防护域名</p>
</td>
<td class="cellrowborder" valign="top" width="70.97%" headers="mcps1.2.3.1.2 "><p id="p193095914285"><a name="p193095914285"></a><a name="p193095914285"></a>添加需要防护的域名或网站。详细操作请参见<a href="添加防护域名.md">添加防护域名</a>。</p>
</td>
</tr>
<tr id="row460742212359"><td class="cellrowborder" valign="top" width="29.03%" headers="mcps1.2.3.1.1 "><p id="p260772263514"><a name="p260772263514"></a><a name="p260772263514"></a>开启WAF防护</p>
</td>
<td class="cellrowborder" valign="top" width="70.97%" headers="mcps1.2.3.1.2 "><p id="p6607202215355"><a name="p6607202215355"></a><a name="p6607202215355"></a>添加防护域名后，可开启WAF防护，保护网站业务安全稳定。</p>
<div class="note" id="note012284223119"><a name="note012284223119"></a><a name="note012284223119"></a><span class="notetitle"> 说明： </span><div class="notebody"><a name="ul697716015340"></a><a name="ul697716015340"></a><ul id="ul697716015340"><li>WAF引擎不是运行在客户的Web服务器上的，所以对客户的Web服务器的资源性能没有影响。</li><li>接入WAF之后，根据请求页面的大小和数量，会有几十毫秒的延迟。</li></ul>
</div></div>
</td>
</tr>
<tr id="row1960762215351"><td class="cellrowborder" valign="top" width="29.03%" headers="mcps1.2.3.1.1 "><p id="p19607112220359"><a name="p19607112220359"></a><a name="p19607112220359"></a>配置自定义规则</p>
</td>
<td class="cellrowborder" valign="top" width="70.97%" headers="mcps1.2.3.1.2 "><p id="p12607112215352"><a name="p12607112215352"></a><a name="p12607112215352"></a>WAF除了内置的防护规则外，还提供了丰富全面的自定义防护配置规则，全方位的防护您的网站。详细操作请参见<a href="配置防护规则.md">配置防护规则</a>。</p>
</td>
</tr>
<tr id="row16914191884019"><td class="cellrowborder" valign="top" width="29.03%" headers="mcps1.2.3.1.1 "><p id="p209141418104019"><a name="p209141418104019"></a><a name="p209141418104019"></a>开启告警通知</p>
</td>
<td class="cellrowborder" valign="top" width="70.97%" headers="mcps1.2.3.1.2 "><p id="p1491512181402"><a name="p1491512181402"></a><a name="p1491512181402"></a>开启告警通知后，用户可以第一时间接收被拦截和仅记录的攻击日志。详细操作请参见<a href="开启告警通知.md">开启告警通知</a>。</p>
</td>
</tr>
<tr id="row758655211510"><td class="cellrowborder" valign="top" width="29.03%" headers="mcps1.2.3.1.1 "><p id="p0924629858"><a name="p0924629858"></a><a name="p0924629858"></a>处理误报事件</p>
</td>
<td class="cellrowborder" valign="top" width="70.97%" headers="mcps1.2.3.1.2 "><p id="p1955314388418"><a name="p1955314388418"></a><a name="p1955314388418"></a>WAF拦截或者记录的攻击事件为误报时，可对误报进行屏蔽处理。详细操作请参见<a href="处理误报事件.md">处理误报事件</a>。</p>
</td>
</tr>
<tr id="row1999341519405"><td class="cellrowborder" valign="top" width="29.03%" headers="mcps1.2.3.1.1 "><p id="p299315156400"><a name="p299315156400"></a><a name="p299315156400"></a>安全总览</p>
</td>
<td class="cellrowborder" valign="top" width="70.97%" headers="mcps1.2.3.1.2 "><p id="p1199319156407"><a name="p1199319156407"></a><a name="p1199319156407"></a>可查看到昨天、今天、3天、7天或者30天范围内的访问与攻击统计次数、攻击分布、受攻击域名 TOP10、攻击源IP TOP10和受攻击URL TOP10的次数。详细操作请参见<a href="安全总览.md">安全总览</a>。</p>
</td>
</tr>
</tbody>
</table>

网站域名接入WAF的操作流程图如[图1](#fig1251423693315)所示。

**图 1**  网站域名接入WAF的操作流程图<a name="fig1251423693315"></a>  
![](figures/网站域名接入WAF的操作流程图.png "网站域名接入WAF的操作流程图")

