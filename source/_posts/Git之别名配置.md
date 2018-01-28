---
title: Git之别名配置
date: 2018-01-08 10:34
tags:
---
原文地址:<a href="http://www.cnblogs.com/LandWind/articles/8241361.html" style="font-size: 200%;color: #000;">http://www.cnblogs.com/LandWind/articles/8241361.html</a>
<p><span style="font-size: 18px">### &#30001;&#20110;Git&#25351;&#20196;&#23481;&#26131;&#25171;&#38169;&#65292;&#19979;&#38754;&#21363;&#26159;&#21457;&#25381;&#25042;&#20154;&#30284;&#30340;&#26041;&#27861;&#65306;</span></p>
<p><span style="font-size: 14pt">##&nbsp;git status&nbsp;</span></p>
<p>&nbsp;</p>
<div class="cnblogs_code">
<pre>$ git config --<span style="color: #0000ff">global</span> alias.st status</pre>
</div>
<p>&nbsp;</p>
<p>## &#20854;&#20182;&#24120;&#29992;&#25351;&#20196;&#21035;&#21517;&#35774;&#32622;</p>
<div class="cnblogs_code">
<pre>$ git config --<span style="color: #0000ff">global</span><span style="color: #000000"> alias.co checkout //
$ git config </span>--<span style="color: #0000ff">global</span><span style="color: #000000"> alias.ci commit
$ git config </span>--<span style="color: #0000ff">global</span> alias.br branch</pre>
</div>
<p>## &#26085;&#24535;&#26597;&#30475;</p>
<div class="cnblogs_code">
<pre>git config --<span style="color: #0000ff">global</span> alias.lg <span style="color: #800000">&quot;</span><span style="color: #800000">log --color --graph --pretty=format:'%Cred%h%Creset -%C(yellow)%d%Creset %s %Cgreen(%cr) %C(bold blue)&lt;%an&gt;%Creset' --abbrev-commit</span><span style="color: #800000">&quot;</span></pre>
</div>
<p>&nbsp;</p>
<p>## &#27880;&#24847;&#28857;&nbsp;</p>
<p><code>--global</code>&#21442;&#25968;&#26159;&#20840;&#23616;&#21442;&#25968;&#65292;&#20063;&#23601;&#26159;&#36825;&#20123;&#21629;&#20196;&#22312;&#36825;&#21488;&#30005;&#33041;&#30340;&#25152;&#26377;Git&#20179;&#24211;&#19979;&#37117;&#26377;&#29992;&#12290;</p>
<p>##&nbsp;&nbsp;&#37197;&#32622;&#25991;&#20214;</p>
<p>&#37197;&#32622;Git&#30340;&#26102;&#20505;&#65292;&#21152;&#19978;<code>--global</code>&#26159;&#38024;&#23545;&#24403;&#21069;&#29992;&#25143;&#36215;&#20316;&#29992;&#30340;&#65292;&#22914;&#26524;&#19981;&#21152;&#65292;&#37027;&#21482;&#38024;&#23545;&#24403;&#21069;&#30340;&#20179;&#24211;&#36215;&#20316;&#29992;&#12290;</p>
<p>&#37197;&#32622;&#25991;&#20214;&#25918;&#21738;&#20102;&#65311;&#27599;&#20010;&#20179;&#24211;&#30340;Git&#37197;&#32622;&#25991;&#20214;&#37117;&#25918;&#22312;<code>.git/config</code>&#25991;&#20214;&#20013;&#65306;</p>
<div class="cnblogs_code">
<pre>$ cat .git/<span style="color: #000000">config 
[core]
    repositoryformatversion </span>= <span style="color: #800080">0</span><span style="color: #000000">
    filemode </span>= <span style="color: #0000ff">true</span><span style="color: #000000">
    bare </span>= <span style="color: #0000ff">false</span><span style="color: #000000">
    logallrefupdates </span>= <span style="color: #0000ff">true</span><span style="color: #000000">
    ignorecase </span>= <span style="color: #0000ff">true</span><span style="color: #000000">
    precomposeunicode </span>= <span style="color: #0000ff">true</span><span style="color: #000000">
[remote </span><span style="color: #800000">&quot;</span><span style="color: #800000">origin</span><span style="color: #800000">&quot;</span><span style="color: #000000">]
    url </span>= git@github.com:michaelliao/<span style="color: #000000">learngit.git
    fetch </span>= +refs/heads<span style="color: #008000">/*</span><span style="color: #008000">:refs/remotes/origin/*
[branch &quot;master&quot;]
    remote = origin
    merge = refs/heads/master
[alias]
    last = log -1</span></pre>
</div>
<p>&#21035;&#21517;&#23601;&#22312;<code>[alias]</code>&#21518;&#38754;&#65292;&#35201;&#21024;&#38500;&#21035;&#21517;&#65292;&#30452;&#25509;&#25226;&#23545;&#24212;&#30340;&#34892;&#21024;&#25481;&#21363;&#21487;&#12290;</p>
<p>&#32780;&#24403;&#21069;&#29992;&#25143;&#30340;Git&#37197;&#32622;&#25991;&#20214;&#25918;&#22312;&#29992;&#25143;&#20027;&#30446;&#24405;&#19979;&#30340;&#19968;&#20010;&#38544;&#34255;&#25991;&#20214;<code>.gitconfig</code>&#20013;&#65306;</p>
<div class="cnblogs_code">
<pre><span style="color: #000000">$ cat .gitconfig
[alias]
    co </span>=<span style="color: #000000"> checkout
    ci </span>=<span style="color: #000000"> commit
    br </span>=<span style="color: #000000"> branch
    st </span>=<span style="color: #000000"> status
[user]
    name </span>=<span style="color: #000000"> Your Name
    email </span>= your@email.com</pre>
</div>
<p>&#37197;&#32622;&#21035;&#21517;&#20063;&#21487;&#20197;&#30452;&#25509;&#20462;&#25913;&#36825;&#20010;&#25991;&#20214;&#65292;&#22914;&#26524;&#25913;&#38169;&#20102;&#65292;&#21487;&#20197;&#21024;&#25481;&#25991;&#20214;&#37325;&#26032;&#36890;&#36807;&#21629;&#20196;&#37197;&#32622;&#12290;</p>
<p>&nbsp;</p>
<p>&#21442;&#32771;&#25991;&#31456;&#65306;</p>
<p>&#12288;&#12288;1.<a title="git别名配置" href="https://www.liaoxuefeng.com/wiki/0013739516305929606dd18361248578c67b8067c8c017b000/001375234012342f90be1fc4d81446c967bbdc19e7c03d3000" target="_blank">&#37197;&#32622;&#21035;&#21517;</a></p>
<p>&nbsp;</p>
