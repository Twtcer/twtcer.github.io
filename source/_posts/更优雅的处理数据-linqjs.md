---
title: 更优雅的处理数据-linqjs
date: 2018-01-29 23:09
tags:
categories:
  - &#24494;&#20449;&#24320;&#21457;
  - linq
  - js
  - &#25968;&#25454;&#22788;&#29702;
---
原文地址:</br><a href="http://www.cnblogs.com/LandWind/articles/8379929.html" style="font-size: 24px;color: #9900FF;">http://www.cnblogs.com/LandWind/articles/8379929.html</a>
<h2 id="题记--由于前端需要处理数据筛选排序等操作之前在c后端都是各种linq方便遂寻找类似的实现">&#39064;&#35760;--&#30001;&#20110;&#21069;&#31471;&#38656;&#35201;&#22788;&#29702;&#25968;&#25454;&#31579;&#36873;&#12289;&#25490;&#24207;&#31561;&#25805;&#20316;&#65292;&#20043;&#21069;&#22312;C#&#21518;&#31471;&#37117;&#26159;&#21508;&#31181;Linq&#26041;&#20415;&#65292;&#36930;&#23547;&#25214;&#31867;&#20284;&#30340;&#23454;&#29616;</h2>
<h2 id="然后在园子找到了js的linq实现封装了我们常用的各类数据操作链接-httplinqjs.codeplex.com">&#28982;&#21518;&#22312;&#22253;&#23376;&#25214;&#21040;&#20102;js&#30340;linq&#23454;&#29616;&#65292;&#23553;&#35013;&#20102;&#25105;&#20204;&#24120;&#29992;&#30340;&#21508;&#31867;&#25968;&#25454;&#25805;&#20316;&#12290;&#38142;&#25509; <a class="uri" href="http://linqjs.codeplex.com/">http://linqjs.codeplex.com/</a></h2>
<h2 id="同时支持jquery和js实现实现了诸如查询排序选择等操作支持列表详见-httpneue.ccreference.htm">&#21516;&#26102;&#25903;&#25345;jquery&#21644;js&#23454;&#29616;,&#23454;&#29616;&#20102;&#35832;&#22914;&#65292;&#26597;&#35810;&#65292;&#25490;&#24207;&#65292;&#36873;&#25321;&#31561;&#25805;&#20316;&#65292;&#25903;&#25345;&#21015;&#34920;&#35814;&#35265; <a class="uri" href="http://neue.cc/reference.htm">http://neue.cc/reference.htm</a></h2>
<h3 id="下面是简单实例">&#19979;&#38754;&#26159;&#31616;&#21333;&#23454;&#20363;&#65306;</h3>
<p>function demo() {<br>
var jsonArray = [<br>
{ &quot;StuID&quot;: 1, &quot;StuName&quot;: &quot;James&quot;, &quot;Age&quot;: 30, &quot;Country&quot;: &quot;USA&quot; },<br>
{ &quot;StuID&quot;: 2, &quot;StuName&quot;: &quot;Byant&quot;, &quot;Age&quot;: 36, &quot;Country&quot;: &quot;USA&quot; },<br>
{ &quot;StuID&quot;: 3, &quot;StuName&quot;: &quot;Lin&quot;, &quot;Age&quot;: 30, &quot;Country&quot;: &quot;Taiwan&quot; },<br>
{ &quot;StuID&quot;: 4, &quot;StuName&quot;: &quot;Yao&quot;, &quot;Age&quot;: 30, &quot;Country&quot;: &quot;Shanghai&quot; }<br>
];</p>
<pre><code>        var querResult = $.Enumerable.From(jsonArray)
            .Where(function (x) { return x.Age &lt;= 30; })
            .OrderBy(function (x) { return x.StuID; })
            .ToArray()
            .forEach(function (i) {
                document.write(i.StuID + &quot;;&quot; + i.StuName + &quot;;&quot; + i.Age + &quot;;&quot; + i.Country + &quot;&lt;br/&gt;&quot;);
            });

        document.write(&quot;====================================&quot; + &quot;&lt;br/&gt;&quot;);


        var queryResult2 = $.Enumerable.From(jsonArray)
            .Where(&quot;$.Age&lt;=30&quot;) 
            .OrderBy(&quot;$.StuID&quot;)
            .ToArray()
            .forEach(function (i) {
                document.write(i.StuID + &quot;;&quot; + i.StuName + &quot;;&quot; + i.Age + &quot;;&quot; + i.Country + &quot;&lt;br/&gt;&quot;);
            });
    }</code></pre>
<h3 id="个人感觉作为学习应该学习linqjs的设计思想了解后应该自己原生实现试试ps.先挖个坑后面来补齐">&#20010;&#20154;&#24863;&#35273;&#65292;&#20316;&#20026;&#23398;&#20064;&#65292;&#24212;&#35813;&#23398;&#20064;linqjs&#30340;&#35774;&#35745;&#24605;&#24819;&#65292;&#20102;&#35299;&#21518;&#24212;&#35813;&#33258;&#24049;&#21407;&#29983;&#23454;&#29616;&#35797;&#35797;(ps.&#20808;&#25366;&#20010;&#22353;&#65292;&#21518;&#38754;&#26469;&#34917;&#40784;&#12290;)</h3>

