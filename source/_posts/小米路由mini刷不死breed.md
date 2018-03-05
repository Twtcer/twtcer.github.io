---
title: 小米路由mini刷不死breed
date: 2017-12-31 21:16
tags:
categories:
  - &#36335;&#30001;&#21047;&#26426;
---
原文地址:</br><a href="http://www.cnblogs.com/LandWind/articles/8159045.html" style="font-size: 24px;color: #9900FF;">http://www.cnblogs.com/LandWind/articles/8159045.html</a>
<h1><span style='font-family: "Microsoft YaHei"; font-size: 14pt'>&#20934;&#22791;</span></h1>
<h1><span style="font-size: 14pt">&nbsp;</span></h1>
<ol>
<li><ol>
<li>
<h1><span style="font-size: 14pt">&#31995;&#32479;&#24050;&#32463;&#24320;&#21551;ssh</span></h1>
</li>
<li>
<h1><span style="font-size: 14pt">&#19979;&#36733;breed &#22320;&#22336;&#65306;<a href="https://breed.hackpascal.net/" target="_blank">https://breed.hackpascal.net/</a>&#65292;&#25628;&#32034;&#20851;&#38190;&#23383;&nbsp;breed-mt7620-xiaomi-mini.bin&nbsp;</span></h1>
</li>
<li>
<h1 align="left"><span style="font-size: 14pt">&#20351;&#29992;WinSCP&#24037;&#20855;&#23558;breed&#22266;&#20214;&#19978;&#20256;&#21040;/tmp&#30446;&#24405;&#65292;&#26041;&#27861;&#26159;&#25171;&#24320;WinSCP&#65292;&#21491;&#19978;&#35282;&#28857;&#20987;&#26032;&#24314;&#28155;&#21152;&#38142;&#25509;192.168.31.1&#65292;&#23494;&#30721;&#23601;&#26159;&#21018;&#25165;SSH&#39029;&#38754;&#26174;&#31034;&#30340;&#23494;&#30721;&#65292;&#22914;&#26524;&#35760;&#19981;&#20303;&#23601;&#20351;&#29992;&#21629;&#20196;passwd&#26469;&#20462;&#25913;&#23494;&#30721;&#12290;</span></h1>
<h1 align="left"><span style="font-size: 14pt">&nbsp; &nbsp; &#36828;&#31243;&#30331;&#24405;&#20027;&#26426;&#65292;&#22312;&#24038;&#36793;&#30340;&#26412;&#22320;&#31649;&#29702;&#20013;&#25214;&#21040;&#25105;&#20204;&#30340;breed-mt7620-xiaomi-mini.bin&#22266;&#20214;&#65292;&#30452;&#25509;&#23558;&#20854;&#25302;&#25341;&#33267;&#21491;&#36793;&#30340;/tmp&#30446;</span></h1>
</li>
<li>
<h2>&#26368;&#20851;&#38190;&#30340;&#37096;&#20998;</h2>
<ol>
<li><span style="background-color: #ccffff; color: #ff0000">&#12288;&#12288;&#19968;&#23450;&#20808;&#22791;&#20221;&#36335;&#30001; &#65292;&#33509;&#19981;&#22791;&#20221;&#21017;&#21047;&#22238;&#23448;&#26041;rom&#21017;&#26080;&#27861;&#20351;&#29992;APP</span>
<div align="left">#&nbsp;&#26597;&#30475;MTD&#20998;&#21306;</div>
<div align="left">cat /proc/mtd</div>
<span><span><span><br></span></span></span>
<div align="left">#&nbsp;&#22791;&#20221;</div>
<div align="left"># /extdisks/sda1&nbsp;&#23601;&#26159;&#22806;&#37096;&#23384;&#20648;&#35774;&#22791;&#30340;&#36335;&#24452;</div>


<span><span><span><span><br></span></span></span></span>
<div align="left">dd if=/dev/mtd0 of=/extdisks/sda1/rom/ALL.bin</div>
<div align="left">dd if=/dev/mtd1 of=/extdisks/sda1/rom/Bootloader.bin</div>
<div align="left">dd if=/dev/mtd2 of=/extdisks/sda1/rom/Config.bin</div>
<div align="left">dd if=/dev/mtd3 of=/extdisks/sda1/rom/Factory.bin</div>
<div align="left">dd if=/dev/mtd4 of=/extdisks/sda1/rom/OS1.bin</div>
<div align="left">dd if=/dev/mtd5 of=/extdisks/sda1/rom/rootfs.bin</div>
<div align="left">dd if=/dev/mtd6 of=/extdisks/sda1/rom/OS2.bin</div>
<div align="left">dd if=/dev/mtd7 of=/extdisks/sda1/rom/overlay.bin</div>
<div align="left">dd if=/dev/mtd8 of=/extdisks/sda1/rom/crash.bin</div>
<div align="left">dd if=/dev/mtd9 of=/extdisks/sda1/rom/reserved.bin</div>
<div align="left">dd if=/dev/mtd10 of=/extdisks/sda1/rom/Bdata.bin</div>
<div align="left">dd if=/dev/mtd11 of=/extdisks/sda1/rom/firmware.bin</div>


</li>
<li>
<div align="left">#&nbsp;&#24674;&#22797;&#22791;&#20221;</div>


<br>
<div align="left">mtd -r write /extdisks/sda1/rom/Bootloader.binBootloader</div>
<div align="left">mtd -r write /extdisks/sda1/rom/Config.bin Config</div>
<div align="left">mtd -r write /extdisks/sda1/rom/Factory.bin Factory</div>
<div align="left">mtd -r write /extdisks/sda1/rom/OS1.bin OS1</div>
<div align="left">mtd -r write /extdisks/sda1/rom/rootfs.bin rootfs</div>
<div align="left">mtd -r write /extdisks/sda1/rom/OS2.bin OS2</div>
<div align="left">mtd -r write /extdisks/sda1/rom/overlay.bin overlay</div>
<div align="left">mtd -r write /extdisks/sda1/rom/crash.bin crash</div>
<div align="left">mtd -r write /extdisks/sda1/rom/reserved.bin reserved</div>
<div align="left">mtd -r write /extdisks/sda1/rom/Bdata.bin Bdata</div>
<div align="left">mtd -r write /extdisks/sda1/rom/firmware.bin firmware</div>


</li>


</ol></li>


</ol></li>


</ol>
<h1><span style="font-size: 14pt">&nbsp;</span></h1>
<h1><span style="font-size: 14pt">&#12288;&#12288;&#12288;&#12288;&#12288;&#12288;&#12288;&#12288;&#23436;&#20840;&#24674;&#22797;&#23567;&#31859;&#22266;&#20214;&#27493;&#39588;</span></h1>
<h1><span style="font-size: 14pt">&nbsp;</span></h1>
<h1><span style="font-size: 14pt">&#12288;&#12288;&#12288;&#12288;&#12288;&#12288;&#12288;&#12288;&#25353;&#29031;&#19978;&#36848;&#26041;&#27861;&#36827; Breed Web &#24674;&#22797;&#25511;&#21046;&#21488;</span></h1>
<h1><span style="font-size: 14pt">&nbsp;</span></h1>
<h1 align="left"><span style="font-size: 14pt">&#12288;&#12288;&#12288;&#12288;&#12288;&#12288;&#12288;&#12288;&#21333;&#21047;&#22791;&#20221;&#30340;&#23567;&#31859;ROM&#37324;&#38754;&#30340;&nbsp;&nbsp;Bootloader.bin &#37325;&#21551;</span></h1>
<h1><span style="font-size: 14pt">&nbsp;</span></h1>
<h1 align="left"><span style="font-size: 14pt">&#12288;&#12288;&#12288;&#12288;&#12288;&#12288;&#12288;&#12288;&#25353;&#29031;&#23448;&#26041;&#30340;&#22238;&#22797;&#26041;&#27861;&#65292;&#25226;&#22266;&#20214;&#20889;&#22312;U&#30424;&#37325;&#21629;&#21517;miwifi.bin&#65292;&#29992;&#30828;&#29289;&#39030;&#20303;mini&#30340;reset&#38190;&#24320;&#26426;&#65292;&#31561;&#21040;mini&#30340;&#28783;&#29378;&#38378;&#30340;&#26102;&#20505;&#65292;&#26494;&#24320;reset&#38190;&#65292;5-10&#20998;&#38047;&#24674;&#22797;&#21407;&#29256;&#22266;&#20214;&#23436;&#25104;&#12290;</span></h1>
<h1 align="left"><span style="font-size: 14pt">&nbsp;</span></h1>
<h1><span style='font-family: "Microsoft YaHei"; font-size: 14pt'>&nbsp;</span></h1>
