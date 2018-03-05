---
title: 小米路由mini开启ssh
date: 2017-12-31 21:04
tags:
categories:
  - &#36335;&#30001;&#21047;&#26426;
  - &#23567;&#31859;&#36335;&#30001;mini
  - ssh
  - &#21047;&#26426;
---
原文地址:</br><a href="http://www.cnblogs.com/LandWind/articles/8159010.html" style="font-size: 24px;color: #9900FF;">http://www.cnblogs.com/LandWind/articles/8159010.html</a>
<ol>
<li>
<p><span style='font-family: "Microsoft YaHei"'>&nbsp;<span style="color: magenta">&#20934;&#22791;&#24037;&#20316;</span></span></p>
<span style="font-size: 18px"><br><span style='font-family: "Microsoft YaHei"'><span style="color: blue"><br><br></span></span></span>
<ul>
<li>
<div align="left"><span style='font-size: large; font-family: "Microsoft YaHei"'>&#30830;&#20445;&#20320;&#30340;&#23567;&#31859;&#36335;&#30001;&#22120;mini&#22266;&#20214;&#20026;&#24320;&#21457;&#29256;0.3.84&#21450;&#20197;&#19978;&#12290;<span style="color: red">&#27880;&#24847;&#65306;&#31283;&#23450;&#29256;&#19981;&#25903;&#25345;&#12290;</span></span></div>

</li>

</ul>
<ul class="litype_1" type="1">
<ul class="litype_1" type="1">
<li>
<div align="left"><span style='font-size: large; font-family: "Microsoft YaHei"'>&#24050;&#20351;&#29992;&#25163;&#26426;&#23567;&#31859;&#36335;&#30001;&#22120;APP&#32465;&#23450;&#27492;&#21488;&#23567;&#31859;&#36335;&#30001;&#22120;mini&#12290;</span><br><span style='font-family: "Microsoft YaHei"'><img class="zoom" id="aimg_kDKKb" src="http://www.miui.com/static/image/hrline/1.gif" alt width="370" height="13" border="0"></span><br><br><span style='font-family: "Microsoft YaHei"'>&nbsp; &nbsp;&nbsp; &nbsp;&nbsp; &nbsp;&nbsp; &nbsp;&nbsp; &nbsp;&nbsp; &nbsp;&nbsp; &nbsp;&nbsp; &nbsp;&nbsp; &nbsp;&nbsp; &nbsp;&nbsp; &nbsp;&nbsp; &nbsp;&nbsp; &nbsp;&nbsp; &nbsp;&nbsp; &nbsp;&nbsp; &nbsp;&nbsp; &nbsp;&nbsp; &nbsp;&nbsp; &nbsp;&nbsp; &nbsp;&nbsp; &nbsp;&nbsp; &nbsp;&nbsp; &nbsp;<span style="font-size: large"><span style="color: magenta">&#24320;&#21551;&#26041;&#27861;</span></span></span></div>
<span style='font-family: "Microsoft YaHei"'>
<span style="font-size: medium"><span style="color: blue"><br></span></span></span></li>
<li>
<div align="left"><span style='font-family: "Microsoft YaHei"'><span style="font-size: medium"><span style="color: blue"><span style="font-size: large">&#30331;&#38470;&nbsp;</span><a href="http://www1.miwifi.com/miwifi_open.html" target="_blank"><span style="font-size: large">http://www1.miwifi.com/miwifi_open.html</span></a><span style="font-size: large">&nbsp; &nbsp; &#28857;&#20987;&#8220;&#24320;&#21551;SSH&#24037;&#20855;&#8221;&#12290;<br></span></span></span></span><br><span style='font-family: "Microsoft YaHei"'>&nbsp; &nbsp;&nbsp; &nbsp;&nbsp; &nbsp;&nbsp; &nbsp;&nbsp; &nbsp;&nbsp; &nbsp;&nbsp; &nbsp;&nbsp; &nbsp;&nbsp; &nbsp;&nbsp; &nbsp;&nbsp; &nbsp;&nbsp; &nbsp;&nbsp; &nbsp;&nbsp; &nbsp;&nbsp; &nbsp;&nbsp; &nbsp;&nbsp; &nbsp;&nbsp; &nbsp;&nbsp; &nbsp;&nbsp; &nbsp;&lt;ignore_js_op&gt;<img id="aimg_2144696" src="https://attach.bbs.miui.com/forum/201409/13/070315t9dd2sbu1dv5hp9j.jpg.thumb.jpg" alt></span></div>

</li>
<li>
<div align="left"><span style='font-family: "Microsoft YaHei"'><span style="font-size: large"><span style="color: mediumturquoise"><span style="color: royalblue">&#36755;&#20837;&#24744;&#30340;&#23567;&#31859;&#36134;&#21495;&#21644;&#23494;&#30721;&#65292;&#30331;&#38470;</span></span><span style="color: red">&#65288;&#35831;&#30830;&#20445;&#24050;&#32463;&#32465;&#23450;&#20102;&#24744;&#30340;&#23567;&#31859;&#36335;&#30001;&#22120;&#65289;&#12290;</span></span><span style="font-size: large"><span style="color: red"><br>&nbsp; &nbsp;&nbsp; &nbsp;&nbsp; &nbsp;&nbsp; &nbsp;&nbsp; &nbsp;&nbsp; &nbsp;&nbsp; &nbsp;&nbsp; &nbsp;&nbsp; &nbsp;&nbsp; &nbsp;&nbsp; &nbsp;&nbsp; &nbsp;&nbsp; &nbsp;&nbsp; &nbsp;&nbsp; &nbsp;&nbsp; &nbsp;&nbsp; &nbsp;&lt;ignore_js_op&gt;<img id="aimg_2144698" src="https://attach.bbs.miui.com/forum/201409/13/070805djzw8kg8gjnto836.jpg.thumb.jpg" alt></span></span></span></div>

</li>
<li>
<div align="left"><span style='font-size: large; font-family: "Microsoft YaHei"'>&#19979;&#36733;&#24037;&#20855;&#21253;</span><br><span style='font-family: "Microsoft YaHei"'>&nbsp; &nbsp;&nbsp; &nbsp;&nbsp; &nbsp;&nbsp; &nbsp;&nbsp; &nbsp;&nbsp; &nbsp;&nbsp; &nbsp;&nbsp; &nbsp;&nbsp; &nbsp;&nbsp; &nbsp;&nbsp; &nbsp;&nbsp; &nbsp;&nbsp; &nbsp;&nbsp; &nbsp;&nbsp; &nbsp;&nbsp; &nbsp;&nbsp; &nbsp;&nbsp; &nbsp;&nbsp; &nbsp;&nbsp; &nbsp;&nbsp; &nbsp;&nbsp; &nbsp;&nbsp; &nbsp;&nbsp; &nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&lt;ignore_js_op&gt;<img id="aimg_2144705" src="https://attach.bbs.miui.com/forum/201409/13/071405zkytxyckaatxayy2.jpg.thumb.jpg" alt></span></div>

</li>
<li>
<div align="left"><span style='font-size: large; font-family: "Microsoft YaHei"'><span style="color: deepskyblue">&#25353;&#29031;&#25552;&#31034;&#24320;&#24515;&#30340;&#21047;&#26426;</span>&#65281;&#65288;<span style="color: red">root&#23494;&#30721;&#20026;&#39029;&#38754;&#26174;&#31034;&#30340;&#23494;&#30721;</span>&#65289;</span></div>

</li>
<li>
<div align="left"><span style='font-family: "Microsoft YaHei"'>&#21040;&#27492;&#20320;&#30340;&#23567;&#31859;&#36335;&#30001;&#22120;mini&#24050;&#32463;&#33719;&#24471;ROOT&#26435;&#38480;&#65292;&#24819;&#35201;&#24590;&#26679;&#25240;&#33150;&#23427;&#37117;&#38543;&#20320;&#20102;&#65281;</span></div>

</li>

</ul>
</ul>
</li>
</ol>
