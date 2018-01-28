---
title: Github 搭建个人博客
date: 2018-01-04 20:45
tags:
---
原文地址:<a href="http://www.cnblogs.com/LandWind/articles/8195861.html" style="font-size: 200%;color: #000;">http://www.cnblogs.com/LandWind/articles/8195861.html</a>
<h1 class="csdn_top" style="text-align: left">&#36716;&#33258; &#65306;http://hifor.net/2015/07/01/&#38646;&#22522;&#30784;&#20813;&#36153;&#25645;&#24314;&#20010;&#20154;&#21338;&#23458;-hexo-github/</h1>
<p style="text-align: left">&nbsp;</p>
<p style="text-align: left">&#20351;&#29992;hexo&#29983;&#25104;&#38745;&#24577;&#21338;&#23458;&#24182;&#26550;&#35774;&#22312;&#20813;&#36153;&#30340;github page&#24179;&#21488;&nbsp;</p>
<h2 style="text-align: left" id="准备"><a name="t0"></a>&#20934;&#22791;</h2>
<p style="text-align: left">&#31995;&#32479;:&nbsp;<br>* Window 7 64&#20301;</p>
<p style="text-align: left">&#20351;&#29992;&#36719;&#20214;:&nbsp;<br>* Git v1.9.5&nbsp;<br>[&#19979;&#36733;&#22320;&#22336;]&nbsp;<a href="http://pan.baidu.com/s/1c0rroje" target="_blank">&#30334;&#24230;&#20113;</a>&nbsp;<a href="http://yunpan.cn/cQbXP6aytfC4w" target="_blank">360&#20113;&#30424; &#35775;&#38382;&#23494;&#30721; d269</a>&nbsp;<a href="http://git-scm.com/download/" target="_blank">Git&#23448;&#32593;</a>&nbsp;<br>* Node.js v0.12.5 x64&nbsp;<br>[&#19979;&#36733;&#22320;&#22336;]&nbsp;<a href="http://pan.baidu.com/s/1o6opb9g" target="_blank">&#30334;&#24230;&#20113;</a>&nbsp;<a href="http://yunpan.cn/cQbGMDsq7DruS" target="_blank">360&#20113;&#30424; &#35775;&#38382;&#23494;&#30721; 608f</a>&nbsp;<a href="https://nodejs.org/download/" target="_blank">node.js&#23448;&#32593;</a>&nbsp;<br>32&#20301;&#25110;64&#20301;&#25353;&#33258;&#24049;&#30005;&#33041;&#30340;&#31995;&#32479;&#26469;&#36873;&#25321;&#65292;&#22914;&#26524;&#19981;&#28165;&#26970;&#65292;&#21487;&#20197;&#30452;&#25509;&#22312;&#23448;&#32593;&#19979;&#36733;32&#20301;&#30340;&#65292;&#21487;&#20197;&#20860;&#23481;64&#20301;&#31995;&#32479;</p>
<p style="text-align: left">&#22791;&#27880;:&nbsp;<br>&#19981;&#21516;&#36719;&#20214;&#29256;&#26412;&#30340;&#23433;&#35013;&#19982;&#20351;&#29992;&#20250;&#26377;&#24046;&#24322;&#65292;&#35831;&#23613;&#37327;&#19982;&#26412;&#25945;&#31243;&#20445;&#25345;&#19968;&#33268;</p>
<h2 style="text-align: left" id="安装git"><a name="t1"></a>&#23433;&#35013;Git</h2>
<ul style="text-align: left">
<li>&#22823;&#37096;&#20998;&#25353;&#40664;&#35748;&#23433;&#35013;&#65292;&#19968;&#36335;&#28857;&#20987;&#8221;Next&#8221;&nbsp;<br><img title src="http://7xjzgy.com1.z0.glb.clouddn.com/image/20150701/hexo20150701001.png" alt></li>
<li>&#36825;&#37324;&#36873;&#25321;&#23545;&#24212;&#30340;windows&#36873;&#39033;&#65292;&#22914;&#19979;&#22270;&nbsp;<br><img title src="http://7xjzgy.com1.z0.glb.clouddn.com/image/20150701/hexo20150701006.png" alt>&nbsp;<br><img title src="http://7xjzgy.com1.z0.glb.clouddn.com/image/20150701/hexo20150701007.png" alt></li>
<li>&#31561;&#24453;&#23433;&#35013;&#23436;&#25104;&nbsp;<br><img title src="http://7xjzgy.com1.z0.glb.clouddn.com/image/20150701/hexo20150701008.png" alt></li>

</ul>
<h2 style="text-align: left" id="安装nodejs"><a name="t2"></a>&#23433;&#35013;Node.js</h2>
<ul style="text-align: left">
<li>Node&#23433;&#35013;&#26356;&#21152;&#31616;&#21333;&#65292;&#36824;&#26159;&#19968;&#36335;&#8221;Next&#8221;,&#26368;&#21518;&#31561;&#24453;&#23433;&#35013;&#23436;&#25104;&#21363;&#21487;&nbsp;<br><img title src="http://7xjzgy.com1.z0.glb.clouddn.com/image/20150701/hexo20150701010.png" alt>&nbsp;<br><img title src="http://7xjzgy.com1.z0.glb.clouddn.com/image/20150701/hexo20150701015.png" alt></li>

</ul>
<h2 style="text-align: left" id="验证软件正确安装"><a name="t3"></a>&#39564;&#35777;&#36719;&#20214;&#27491;&#30830;&#23433;&#35013;</h2>
<ul style="text-align: left">
<li>&#21516;&#26102;&#25353;&#19979;Win&#38190;&#21644;R&#38190;&#65288;&#25110;&#32773;&#28857;&#20987;&#8220;&#24320;&#22987;&#33756;&#21333;&#8221;-&gt;&#28857;&#20987;&#8220;&#36816;&#34892;&#8221;&#65289;,&#25171;&#24320;&#36816;&#34892;&#31383;&#21475;,&#36755;&#20837;&#8220;cmd&#8221;&nbsp;<br>&#28982;&#21518;&#36755;&#20837;&#20197;&#19979;&#21629;&#20196;&#65292;&#32467;&#26524;&#19982;&#19979;&#22270;&#30456;&#21516;&#21017;&#35828;&#26126;&#23433;&#35013;&#27491;&#30830;&#65292;&#33509;&#19981;&#27491;&#30830;&#21487;&#20197;&#21368;&#36733;&#36719;&#20214;&#37325;&#26032;&#23433;&#35013;</li>

</ul>
<pre class="prettyprint"><code class="language-bash hljs has-numbering">git --version
node -v
npm -v</code></pre>
<ul class="pre-numbering" style="text-align: left">
<li>1</li>
<li>2</li>
<li>3</li>
</ul>
<p style="text-align: left"><img title src="http://7xjzgy.com1.z0.glb.clouddn.com/image/20150701/hexo20150701016.png" alt></p>
<h2 style="text-align: left" id="申请github"><a name="t4"></a>&#30003;&#35831;GitHub</h2>
<ul style="text-align: left">
<li>&#28857;&#20987;-&gt;<a href="https://github.com/" target="_blank">GitHub</a>&#36827;&#20837;&#23448;&#32593;&#27880;&#20876;&#24080;&#21495;</li>
<li>&#25353;&#19979;&#22270;&#20998;&#21035;&#36755;&#20837;&#29992;&#25143;&#21517;&#12289;&#37038;&#31665;&#12289;&#23494;&#30721;&#65292;&#28982;&#21518;&#28857;&#20987;&#27880;&#20876;&nbsp;<br><img title src="http://7xjzgy.com1.z0.glb.clouddn.com/image/20150701/hexo20150701017.png" alt></li>
<li>&#25353;&#40664;&#35748;&#28857;&#20987;&#8220;Finish sign up&#8221;&nbsp;<br><img title src="http://7xjzgy.com1.z0.glb.clouddn.com/image/20150701/hexo20150701018.png" alt></li>
<li>&#28857;&#20987;&#8221;New repository&#8221;&#65292;&#26032;&#24314;&#19968;&#20010;&#29256;&#26412;&#24211;&nbsp;<br><img title src="http://7xjzgy.com1.z0.glb.clouddn.com/image/20150701/hexo20150701019.png" alt></li>
<li>&#36755;&#20837;Repository name:yourname.github.io(yourname&#19982;&#20320;&#30340;&#27880;&#20876;&#29992;&#25143;&#21517;&#19968;&#33268;,&#36825;&#20010;&#23601;&#26159;&#20320;&#21338;&#23458;&#30340;&#22495;&#21517;&#20102;)&nbsp;<br><img title src="http://7xjzgy.com1.z0.glb.clouddn.com/image/20150701/hexo20150701020.png" alt>&nbsp;<br>&#21040;&#27492;github&#24080;&#21495;&#30003;&#35831;&#23436;&#25104;&nbsp;<br><img title src="http://7xjzgy.com1.z0.glb.clouddn.com/image/20150701/hexo20150701021.png" alt></li>
<li>&#21551;&#29992;GitHub Page&nbsp;<br>&#28857;&#20987;&#21491;&#36793;&#30340;&#8220;Setting&#8221;&#33756;&#21333;&#36827;&#20837;&#35774;&#32622;,&#28857;&#20987;&#8221;Launch automatic page generator&#8221;&nbsp;<br><img title src="http://7xjzgy.com1.z0.glb.clouddn.com/image/20150701/hexo20150701021-1.png" alt>&nbsp;<br>&#28857;&#20987;&#24213;&#37096;&#30340;&#8221;Continue to layouts&#8221;&nbsp;<br><img title src="http://7xjzgy.com1.z0.glb.clouddn.com/image/20150701/hexo20150701021-2.png" alt>&nbsp;<br>&#26368;&#21518;&#28857;&#20987;&#8221;Publish page&#8221;,&#21457;&#24067;github&#40664;&#35748;&#29983;&#25104;&#30340;&#19968;&#20010;&#38745;&#24577;&#31449;&#28857;&nbsp;<br><img title src="http://7xjzgy.com1.z0.glb.clouddn.com/image/20150701/hexo20150701021-3.png" alt></li>
<li>&#39564;&#35777;&#37038;&#31665;&nbsp;<br>&#28857;&#20987;&#20010;&#20154;&#35774;&#32622;&nbsp;<br><img title src="http://7xjzgy.com1.z0.glb.clouddn.com/image/20150701/hexo20150701021-4.png" alt>&nbsp;<br>&#28857;&#20987;&#8221;Send verification Email&#8221;&#21457;&#36865;&#39564;&#35777;&#37038;&#20214;&nbsp;<br><img title src="http://7xjzgy.com1.z0.glb.clouddn.com/image/20150701/hexo20150701021-5.png" alt><br>&#36827;&#20837;&#20320;&#30340;&#37038;&#31665;&#65292;&#26597;&#25910;&#39564;&#35777;&#37038;&#20214;&#36827;&#34892;&#39564;&#35777;&nbsp;<br><img title src="http://7xjzgy.com1.z0.glb.clouddn.com/image/20150701/hexo20150701021-6.png" alt></li>

</ul>
<h2 style="text-align: left" id="安装hexo"><a name="t5"></a>&#23433;&#35013;Hexo</h2>
<p style="text-align: left">hexo&#26159;&#22522;&#20110;node.js&#30340;&#38745;&#24577;&#21338;&#23458;&#65292;<a href="https://hexo.io/zh-cn/" target="_blank">&#23448;&#32593;</a>&#20063;&#26159;&#25645;&#24314;&#22312;GitHub&#19978;&nbsp;<br>* &#22312;&#30005;&#33041;&#19978;&#26032;&#24314;&#19968;&#20010;blog&#25991;&#20214;&#22841;,&#35813;&#25991;&#20214;&#22841;&#29992;&#20110;&#23384;&#25918;&#20320;&#30340;&#21338;&#23458;&#25991;&#20214;,&#28982;&#21518;&#21491;&#38190;&#21333;&#20987;&#36873;&#25321;&#8220;Git Bash&#8221;&nbsp;<br><img title src="http://7xjzgy.com1.z0.glb.clouddn.com/image/20150701/hexo20150701022.png" alt>&nbsp;<br>* &#22823;&#23478;&#20272;&#35745;&#37117;&#26377;&#34987;&#8220;&#22681;&#8221;&#30340;&#32463;&#21382;&#65292;&#23433;&#35013;hexo&#20026;&#20102;&#36991;&#20813;&#20986;&#29616;&#31867;&#20284;&#24773;&#20917;&#65292;&#25105;&#20351;&#29992;<a href="http://npm.taobao.org/" target="_blank">&#28120;&#23453;NPM&#38236;&#20687;</a>,&#36755;&#20837;&#20197;&#19979;&#21629;&#20196;&#31561;&#24453;&#23433;&#35013;&#23436;&#25104;</p>
<pre class="prettyprint"><code class="language-bash hljs has-numbering">$ npm install -g cnpm --registry=https://registry.npm.taobao.org</code></pre>
<ul class="pre-numbering" style="text-align: left">
<li>1</li>
</ul>
<p style="text-align: left"><img title src="http://7xjzgy.com1.z0.glb.clouddn.com/image/20150701/hexo20150701023.png" alt>&nbsp;<br>* &#20351;&#29992;&#28120;&#23453;NPM&#23433;&#35013;Hexo</p>
<pre class="prettyprint"><code class="language-bash hljs has-numbering">$ cnpm install -g hexo-cli</code></pre>
<ul class="pre-numbering" style="text-align: left">
<li>1</li>
</ul>
<p style="text-align: left">&#19982;&#21407;&#20808;&#30340;npm&#23436;&#20840;&#19968;&#26679;&#65292;&#21482;&#26159;&#21629;&#20196;&#25913;&#20026;cnpm,&#19968;&#26679;&#31561;&#24453;hexo&#23433;&#35013;&#23436;&#25104;&nbsp;<br><img title src="http://7xjzgy.com1.z0.glb.clouddn.com/image/20150701/hexo20150701024.png" alt>&nbsp;<br>&#20986;&#29616;&#30340;WARN&#21487;&#20197;&#19981;&#29992;&#29702;&#20250;&nbsp;<br>&#32487;&#32493;&#36755;&#20837;&#20197;&#19979;&#21629;&#20196;</p>
<pre class="prettyprint"><code class="language-bash hljs has-numbering">$ cnpm install hexo --save</code></pre>
<ul class="pre-numbering" style="text-align: left">
<li>1</li>
</ul>
<p style="text-align: left">&#23433;&#35013;&#23436;&#25104;&#21518;&#65292;&#22312;&#36755;&#20837;&#21629;&#20196;&#65292;&#39564;&#35777;&#26159;&#21542;&#23433;&#35013;&#27491;&#30830;</p>
<pre class="prettyprint"><code class="language-bash hljs has-numbering">$ hexo -v</code></pre>
<ul class="pre-numbering" style="text-align: left">
<li>1</li>
</ul>
<p style="text-align: left"><img title src="http://7xjzgy.com1.z0.glb.clouddn.com/image/20150701/hexo20150701025.png" alt></p>
<h2 style="text-align: left" id="本地运行hexo"><a name="t6"></a>&#26412;&#22320;&#36816;&#34892;hexo</h2>
<ul style="text-align: left">
<li>&#21021;&#22987;&#21270;hexo</li>
</ul>
<pre class="prettyprint"><code class="language-bash hljs has-numbering">$ hexo init</code></pre>
<ul class="pre-numbering" style="text-align: left">
<li>1</li>
</ul>
<p style="text-align: left"><img title src="http://7xjzgy.com1.z0.glb.clouddn.com/image/20150701/hexo20150701026.png" alt>&nbsp;<br>* &#23433;&#35013;&#29983;&#25104;&#22120;</p>
<pre class="prettyprint"><code class="language-bash hljs has-numbering">$ cnpm install</code></pre>
<ul class="pre-numbering" style="text-align: left">
<li>1</li>
</ul>
<p style="text-align: left"><img title src="http://7xjzgy.com1.z0.glb.clouddn.com/image/20150701/hexo20150701027.png" alt>&nbsp;<br>* &#36816;&#34892;hexo,&#20197;&#21518;&#35201;&#22312;&#26412;&#22320;&#36816;&#34892;&#21338;&#23458;&#21482;&#35201;&#36755;&#20837;&#35813;&#21629;&#20196;&#21363;&#21487;</p>
<pre class="prettyprint"><code class="language-bash hljs has-numbering">$ hexo s -g</code></pre>
<ul class="pre-numbering" style="text-align: left">
<li>1</li>
</ul>
<p style="text-align: left"><img title src="http://7xjzgy.com1.z0.glb.clouddn.com/image/20150701/hexo20150701028.png" alt>&nbsp;<br>&#25171;&#24320;&#27983;&#35272;&#22120;&#65292;&#36755;&#20837;localhost:4000,&#23601;&#21487;&#20197;&#22312;&#26412;&#22320;&#30475;&#21040;&#20320;&#30340;&#20010;&#20154;&#21338;&#23458;&#20102;&nbsp;<br><img title src="http://7xjzgy.com1.z0.glb.clouddn.com/image/20150701/hexo20150701029.png" alt>&nbsp;<br>* &#20572;&#27490;&#36816;&#34892;&nbsp;<br>&#25353;&#20303;Ctrl+C&#38190;&#21363;&#21487;&#20572;&#27490;</p>
<h2 style="text-align: left" id="管理博客"><a name="t7"></a>&#31649;&#29702;&#21338;&#23458;</h2>
<ul style="text-align: left">
<li>&#37197;&#32622;&#20449;&#24687;&nbsp;<br>&#20351;&#29992;<a href="http://pan.baidu.com/s/1pJFruER" target="_blank">Sublime_Text</a>&#32534;&#36753;&#22120;&#65288;&#32511;&#33394;&#36719;&#20214;&#26080;&#38656;&#23433;&#35013;&#65292;&#35299;&#21387;&#21363;&#21487;&#20351;&#29992;&#65289;&#25171;&#24320;blog/_config.yml&#25991;&#20214;&#65292;&#36827;&#34892;&#37197;&#32622;&nbsp;<br><img title src="http://7xjzgy.com1.z0.glb.clouddn.com/image/20150701/hexo20150701030.png" alt></li>

</ul>
<pre class="prettyprint"><code class="language-yaml hljs avrasm has-numbering"><span class="hljs-preprocessor">#&#21338;&#23458;&#21517;&#31216;
<span class="hljs-label">title: &#25105;&#30340;&#21338;&#23458;
<span class="hljs-preprocessor">#&#21103;&#26631;&#39064;
<span class="hljs-label">subtitle: &#19968;&#22825;&#36827;&#27493;&#19968;&#28857;
<span class="hljs-preprocessor">#&#31616;&#20171;
<span class="hljs-label">description: &#35760;&#24405;&#29983;&#27963;&#28857;&#28404;
<span class="hljs-preprocessor">#&#21338;&#23458;&#20316;&#32773;
<span class="hljs-label">author: John Doe
<span class="hljs-preprocessor">#&#21338;&#23458;&#35821;&#35328;
<span class="hljs-label">language: <span class="hljs-built_in">zh-CN
<span class="hljs-preprocessor">#&#26102;&#21306;
<span class="hljs-label">timezone:

<span class="hljs-preprocessor">#&#21338;&#23458;&#22320;&#22336;,&#19982;&#30003;&#35831;&#30340;GitHub&#19968;&#33268;
<span class="hljs-label">url: http://elfwalk<span class="hljs-preprocessor">.github<span class="hljs-preprocessor">.io
<span class="hljs-label">root: /
<span class="hljs-preprocessor">#&#21338;&#23458;&#38142;&#25509;&#26684;&#24335;
<span class="hljs-label">permalink: :year/:month/:day/:title/
<span class="hljs-label">permalink_defaults:

<span class="hljs-label">source_dir: source
<span class="hljs-label">public_dir: public
<span class="hljs-label">tag_dir: tags
<span class="hljs-label">archive_dir: archives
<span class="hljs-label">category_dir: categories
<span class="hljs-label">code_dir: downloads/code
<span class="hljs-label">i18n_dir: :lang
<span class="hljs-label">skip_render:

<span class="hljs-label">new_post_name: :title<span class="hljs-preprocessor">.md <span class="hljs-preprocessor"># File name of new posts
<span class="hljs-label">default_layout: post
<span class="hljs-label">titlecase: false <span class="hljs-preprocessor"># Transform title into titlecase
<span class="hljs-label">external_link: true <span class="hljs-preprocessor"># Open external links in new tab
<span class="hljs-label">filename_case: <span class="hljs-number">0
<span class="hljs-label">render_drafts: false
<span class="hljs-label">post_asset_folder: false
<span class="hljs-label">relative_link: false
<span class="hljs-label">future: true
<span class="hljs-label">highlight:
  enable: true
  line_number: true
  auto_detect: true
  tab_replace:

<span class="hljs-label">default_category: uncategorized
<span class="hljs-label">category_map:
<span class="hljs-label">tag_map:

<span class="hljs-preprocessor">#&#26085;&#26399;&#26684;&#24335;
<span class="hljs-label">date_format: YYYY-MM-DD
<span class="hljs-label">time_format: HH:mm:ss

<span class="hljs-preprocessor">#&#20998;&#39029;&#65292;&#27599;&#39029;&#25991;&#31456;&#25968;&#37327;
<span class="hljs-label">per_page: <span class="hljs-number">10
<span class="hljs-label">pagination_dir: page

<span class="hljs-preprocessor">#&#21338;&#23458;&#20027;&#39064;
<span class="hljs-label">theme: landscape

<span class="hljs-preprocessor">#&#21457;&#24067;&#35774;&#32622;
<span class="hljs-label">deploy: 
  type: git
  <span class="hljs-preprocessor">#elfwalk&#25913;&#20026;&#20320;&#30340;github&#29992;&#25143;&#21517;
  repository: https://github<span class="hljs-preprocessor">.com/elfwalk/elfwalk<span class="hljs-preprocessor">.github<span class="hljs-preprocessor">.io<span class="hljs-preprocessor">.git
  branch: master</span></span></span></span></span></span></span></span></span></span></span></span></span></span></span></span></span></span></span></span></span></span></span></span></span></span></span></span></span></span></span></span></span></span></span></span></span></span></span></span></span></span></span></span></span></span></span></span></span></span></span></span></span></span></span></span></span></span></span></span></span></span></span></code></pre>
<ul class="pre-numbering" style="text-align: left">
<li>1</li>
<li>2</li>
<li>3</li>
<li>4</li>
<li>5</li>
<li>6</li>
<li>7</li>
<li>8</li>
<li>9</li>
<li>10</li>
<li>11</li>
<li>12</li>
<li>13</li>
<li>14</li>
<li>15</li>
<li>16</li>
<li>17</li>
<li>18</li>
<li>19</li>
<li>20</li>
<li>21</li>
<li>22</li>
<li>23</li>
<li>24</li>
<li>25</li>
<li>26</li>
<li>27</li>
<li>28</li>
<li>29</li>
<li>30</li>
<li>31</li>
<li>32</li>
<li>33</li>
<li>34</li>
<li>35</li>
<li>36</li>
<li>37</li>
<li>38</li>
<li>39</li>
<li>40</li>
<li>41</li>
<li>42</li>
<li>43</li>
<li>44</li>
<li>45</li>
<li>46</li>
<li>47</li>
<li>48</li>
<li>49</li>
<li>50</li>
<li>51</li>
<li>52</li>
<li>53</li>
<li>54</li>
<li>55</li>
<li>56</li>
<li>57</li>
<li>58</li>
<li>59</li>
<li>60</li>
<li>61</li>
<li>62</li>
<li>63</li>
<li>64</li>
<li>65</li>
</ul>
<ul style="text-align: left">
<li>&#20889;&#19968;&#31687;&#25991;&#31456;&nbsp;<br>&#36755;&#20837;&#21019;&#24314;&#25991;&#31456;&#21629;&#20196;&#65292;&#29983;&#25104;&#19968;&#20010;md&#25991;&#20214;(/blog/source/_posts/)</li>

</ul>
<pre class="prettyprint"><code class="language-bash hljs has-numbering">$ hexo new <span class="hljs-string">&quot;hello&quot;</span></code></pre>
<ul class="pre-numbering" style="text-align: left">
<li>1</li>
</ul>
<p style="text-align: left"><img title src="http://7xjzgy.com1.z0.glb.clouddn.com/image/20150701/hexo20150701031.png" alt>&nbsp;<br>&#29992;&#32534;&#36753;&#22120;&#25171;&#24320;hello.md&#25991;&#20214;,&#32534;&#20889;&#23436;&#21518;&#20445;&#23384;</p>
<pre class="prettyprint"><code class="language-bash hljs has-numbering">title: hello
date: <span class="hljs-number">2015-<span class="hljs-number">07-<span class="hljs-number">01 <span class="hljs-number">22:<span class="hljs-number">37:<span class="hljs-number">23
categories:
  - &#26085;&#24535;
  - &#20108;&#32423;&#30446;&#24405;
tags:
  - hello
---

&#25688;&#35201;:
&lt;!--more--&gt;
&#27491;&#25991;:</span></span></span></span></span></span></code></pre>
<ul class="pre-numbering" style="text-align: left">
<li>1</li>
<li>2</li>
<li>3</li>
<li>4</li>
<li>5</li>
<li>6</li>
<li>7</li>
<li>8</li>
<li>9</li>
<li>10</li>
<li>11</li>
<li>12</li>
</ul>
<h2 style="text-align: left" id="发布博客"><a name="t8"></a>&#21457;&#24067;&#21338;&#23458;</h2>
<ul style="text-align: left">
<li>&#35774;&#32622;git&#36523;&#20221;&#20449;&#24687;</li>
</ul>
<pre class="prettyprint"><code class="language-bash hljs has-numbering">$ git config --global user.name <span class="hljs-string">&quot;&#20320;&#30340;&#29992;&#25143;&#21517;&quot;
$ git config --global user.email <span class="hljs-string">&quot;&#20320;&#30340;&#37038;&#31665;&quot;</span></span></code></pre>
<ul class="pre-numbering" style="text-align: left">
<li>1</li>
<li>2</li>
</ul>
<p style="text-align: left"><img title src="http://7xjzgy.com1.z0.glb.clouddn.com/image/20150701/hexo20150701032.png" alt>&nbsp;<br>* &#23433;&#35013;hexo git&#25554;&#20214;</p>
<pre class="prettyprint"><code class="language-bash hljs has-numbering">$ cnpm install hexo-deployer-git --save</code></pre>
<ul class="pre-numbering" style="text-align: left">
<li>1</li>
</ul>
<p style="text-align: left"><img title src="http://7xjzgy.com1.z0.glb.clouddn.com/image/20150701/hexo20150701033.png" alt>&nbsp;<br>* &#21457;&#24067;&#26356;&#26032;&#21338;&#23458;</p>
<pre class="prettyprint"><code class="language-bash hljs has-numbering">$ hexo d -g</code></pre>
<ul class="pre-numbering" style="text-align: left">
<li>1</li>
</ul>
<p style="text-align: left">&#21457;&#24067;&#26102;&#38656;&#35201;&#36755;&#20837;github&#30340;&#24080;&#21495;&#21644;&#23494;&#30721;&#65292;&#36755;&#20837;&#23494;&#30721;&#26102;&#26159;&#30475;&#19981;&#21040;&#33258;&#24049;&#36755;&#20837;&#30340;&#20869;&#23481;&#30340;&nbsp;<br><img title src="http://7xjzgy.com1.z0.glb.clouddn.com/image/20150701/hexo20150701034.png" alt>&nbsp;<br>&#21457;&#24067;&#25104;&#21151;&#21518;&#65292;&#35775;&#38382;yourname.github.io&#30475;&#19979;&#25104;&#26524;</p>
