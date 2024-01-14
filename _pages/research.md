---
title: "HPSC Center at National Taiwan University - Research"
layout: textlay
excerpt: "HPSC Center at National Taiwan University: Research"
sitemap: false
permalink: /research/
---

# Research

Our overarching goal is to explore and understand new quantum states of electronic matter on the atomic scale. To do so, we use and develop novel spectroscopic-imaging scanning tunneling microscopy (SI-STM) tools to visualize the relevant quantum mechanical degrees of freedom.

台灣大學 高效能與科學運算中心

Our goal is to build instruments and develop techniques that enable us to address the questions we find most interesting. This is possible thanks also to Milan's broad background with different research themes and technologies: he learned his trade in [Seamus Davis’ SI-STM lab](http://davisgroup.lassp.cornell.edu/) and with [Felix Baumberger](http://dpmc.unige.ch/gr_baumberger/index.html), and later moved as an [ETH fellow](http://www.ethfellows.ethz.ch/) to [Andreas Wallraff’s qudev lab](http://www.qudev.ethz.ch/) where he investigated coupled cavity arrays in circuit QED. We further have group members with different background and interests, working together on physics and instrumentation.

Here are some themes and techniques that we currently work on:

**全同態加密演算法（Fully Homomorphic Encryption, FHE）之硬體加速器以及系統軟體框架 - 緯創資通**

與緯創資通合作，設計全同態加密演算法（Fully Homomorphic Encryption, FHE）之硬體加速器以及系統軟體框架，可在保護資料隱私的同時，同時運用GPU/FPGA提供高效能（100~1000X）的加密計算，快速完成加密推論（Encrypted Inference）。<br>
資料擁有者可將機密資料以FHE加密後送出，讓服務者在不能得知資料內容的情況下運算，實際解決精準健康、人工智慧應用亟待突破的隱私保護、資料取得問題。<br>
發表於MobiSec 2023<br>

![]({{ site.url }}{{ site.baseurl }}/images/respic/2023Huang-1.png){: style="width: 80%; float: center; margin: 10px"}

**軟體定義車輛架構 - 凌華電腦** 
自駕車系統的計算核心從分散式架構朝高效能多核心系統發展，以因應日漸複雜的軟體定義車輛架構。<br>
此一產學合作案研究與開發軟體定義車輛的高效能計算架構以及敏感性時序網路(Time Sensitive Network, TSN)之核心技術，包含：多容器之效能分析工具，TSN 效能分析以及分散式共識決策。主要的成果包含：<br>
<ul>
<li> 多容器的混合虛擬計算環境： 針對車內的複雜計算負載，已建置兩套實驗環境，一套能夠模模擬 Autoware 執行環境，另一套能藉由Hypervisor設定虛擬機器。</li>
<li> 在 TSN 層對排程進行時序性質分析工具: 當車內網路以時效性網路取代目前的控制匯流排(CAN Bus)網路時，其具有更複雜的排程(scheduling)與時間分析(timing analysis)，本計畫完成近似最佳解之排程演算法。 </li>
<li> 自動生成的 TSN 訊息傳遞排程: 本計劃以 Zenoh 開源跨域中介訊息軟體為基礎，開發 TSN 訊息傳遞排程，使其支援多方跨域即時訊息傳遞。</li>
</ul>
![]({{ site.url }}{{ site.baseurl }}/images/respic/2023Shih-1.png){: style="width: 70%; float: center; margin: 10px"}
![]({{ site.url }}{{ site.baseurl }}/images/respic/2023Shih-2.png){: style="width: 70%; float: center; margin: 10px"}

**基於Edge AI技術之次世代行動影像平台 - 動見科技.** 
藉由行車紀錄器所錄製的影像資料，進行商業車隊管理 (如: 駕駛行為偵測/分析等)<br>
以輕量化邊緣雲技術部署產品所使用之服務，並根據客戶所在區域特性動態決策偕同運算策略<br>
導入雲霧協作技術，將行動影像轉換成具商業價值的資訊供第三方使用(動態圖資更新、智慧城市)<br>
已與全球連鎖物流車隊合作，拓展至南亞印度市場<br>
![]({{ site.url }}{{ site.baseurl }}/images/respic/2021Pang-1.png){: style="width: 20%; float: center; margin: 10px"}
![]({{ site.url }}{{ site.baseurl }}/images/respic/2021Pang-2.png){: style="width: 20%; float: center; margin: 10px"}
![]({{ site.url }}{{ site.baseurl }}/images/respic/2021Pang-3.png){: style="width: 20%; float: center; margin: 10px"}

**醫療影像處理 - 雲象科技合作**.
與雲象科技合作，利用超高解析度影像訓練深度神經網路改進實際醫療場域中癌細胞淋巴系統轉移的偵測方法，採用本研究團隊發展的深度神經網路架構以及平行計算、效能優化的策略，提高計算速度、降低記憶體需求、達成較高的準確度。<br>

協助雲象科技在相當短的時間內訓練出高精準度的醫學影像判讀軟體，在實際醫療場域中顯著改進殘留癌腫瘤透過淋巴系統的微小轉移。<br>

發表於Nature Communications頂級期刊（2020年影響因子為14.919）<br>

Huang, SC., Chen, CC., Lan, J. et al. Deep neural network trained on gigapixel images improves lymph node metastasis detection in clinical settings. Nat Commun 13, 3347 (2022). <br>

![]({{ site.url }}{{ site.baseurl }}/images/respic/2022Huang.png){: style="width: 70%; float: center; margin: 10px"}


**Magnetic fluctuations and electron spin resonance.**
![]({{ site.url }}{{ site.baseurl }}/images/respic/SpinFluc.png){: style="width: 70%; float: center; margin: 10px"}

**Twisted bilayer graphene and other material with super-periodicities.**
We have proposed that artificial super-periodicities can lead to improved superconductivity, both because of increased density of states and because of phase space arguments (see image from our SciPost publication below). Perhaps for different reasons, twisted bilayer graphene has been shown to superconduct! We are investigate this material with the groups of Efetov, Baumberger, and van der Molen.

![]({{ site.url }}{{ site.baseurl }}/images/respic/SciPost.png){: style="width: 70%; float: center; margin: 0px"}

### ... and more.
