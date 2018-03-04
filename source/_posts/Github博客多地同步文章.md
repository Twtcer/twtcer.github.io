---
title: Github博客多地同步文章
date: 2018-01-07 21:55
tags:
---
原文地址:</br><a href="http://www.cnblogs.com/LandWind/articles/8202896.html" style="font-size: 24px;color: #9900FF;">http://www.cnblogs.com/LandWind/articles/8202896.html</a>
<p><span style="font-size: 14pt">&#35299;&#20915;&#26041;&#26696;&#65306;</span></p>
<p><span style="font-size: 14pt">&#12288;&#12288;&#23558;hexo&#28304;&#25991;&#20214;&#21516;&#27493;&#21040;&#21338;&#23458;&#20998;&#25903;&#65292;&#29992;hexo&#20998;&#25903;&#20316;&#20026;&#20013;&#36716;&#65292;&#20854;&#20182;&#35774;&#22791;&#38656;&#35201;&#32534;&#36753;&#26102;&#26412;&#22320;clone&#19968;&#20221;&#65292;&#23433;&#35013;hexo&#24517;&#39035;&#25991;&#20214;&#21518;&#21363;&#21487;&#37096;&#32626;</span></p>
<p><span style="font-size: 14pt">&#20851;&#38190;&#28857;&#65306;</span></p>
<p><span style="font-size: 14pt">&#12288;&#12288;## &#21019;&#24314;hexo&#20998;&#25903;&#24182;&#25552;&#20132;&#25991;&#20214;</span></p>
<div class="cnblogs_Highlighter">
<pre class="brush:csharp;gutter:true;"><strong>// &#26032;&#24314;&#20998;&#25903;&#24182;&#20999;&#25442;&#21040;&#26032;&#24314;&#30340;&#20998;&#25903;
git checkout -b &#20998;&#25903;&#21517;</strong></pre>
<pre class="hljs cpp"><strong><code class="cpp"><span class="hljs-comment">// &#28155;&#21152;&#25152;&#26377;&#26412;&#22320;&#25991;&#20214;&#21040;git
git add .
<span class="hljs-comment">// git&#25552;&#20132;
git commit -m <span class="hljs-string">&quot;&quot;
<span class="hljs-comment">// &#25991;&#20214;&#25512;&#36865;&#21040;hexo&#20998;&#25903;
git push origin hexo</span></span></span></span></code></strong></pre>
<pre class="hljs cpp"></pre>
</div>
<p><span style="font-size: 14pt">&#12288;&#12288;##&nbsp;&#20854;&#20182;&#35774;&#22791;&#19978;clone&#19979;Github&#19978;&#26032;&#24314;&#30340;&#20998;&#25903;&#30340;&#25991;&#20214;&#21040;&#26412;&#22320;</span></p>
<p>&#12288;&#12288;</p>
<div class="cnblogs_code">
<pre><span style="color: #008000">//</span><span style="color: #008000"> &#20811;&#38534;&#25991;&#20214;&#21040;&#26412;&#22320;</span>
git clone -b &#20998;&#25903;&#21517; https:<span style="color: #008000">//</span><span style="color: #008000">github.com/&#29992;&#25143;&#21517;/&#20179;&#24211;&#21517;.git</span></pre>
</div>
<p>&nbsp;</p>
<p><span style="font-size: 14pt">&#12288;&#12288;##&nbsp;&#37096;&#32626;&#21040;Github</span></p>
<p><span style="font-size: 14pt">&#12288;&#12288;</span></p>
<div class="cnblogs_code">
<pre><span style="color: #008000">//</span><span style="color: #008000"> &#23433;&#35013;hexo</span>
<span style="color: #000000">npm install hexo
</span><span style="color: #008000">//</span><span style="color: #008000"> &#27880;&#24847;&#36825;&#37324;&#19981;&#38656;&#35201;hexo&#21021;&#22987;&#21270;&#65306;hexo init&#65307;&#21542;&#21017;&#20043;&#21069;&#30340;hexo&#37197;&#32622;&#21442;&#25968;&#20250;&#37325;&#32622;
</span><span style="color: #008000">//</span><span style="color: #008000"> &#23433;&#35013;&#20381;&#36182;&#24211;</span>
<span style="color: #000000">npm install
</span><span style="color: #008000">//</span><span style="color: #008000"> &#23433;&#35013;&#37096;&#32626;&#30456;&#20851;&#37197;&#32622;</span>
npm install hexo-deployer-git<br><br>//&#21457;&#24067;&#21040;master&#20998;&#25903;<br>hexo d -g</pre>
</div>
<p>&nbsp;</p>
