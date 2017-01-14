---
title       : 標案天眼通
subtitle    : DSP data chanllenge
author      : Dan & Ricky
job         : 
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : [mathjax, quiz, bootstrap, interactive] 
# {mathjax, quiz, bootstrap}
ext_widgets : {rCharts: [libraries/nvd3, libraries/leaflet, libraries/dygraphs]}
mode        : selfcontained # {standalone, draft}
knit        : slidify::knit2slides
logo        : Analytics-512.png
assets      : {assets: ../../assets}
--- .class #id

<style type="text/css">
body {background:grey transparent;
}
</style>

## Outline

1. Introduction

2. Blacklist

3. Tender Question on Company

4. Tender Question on Government

5. Demo

--- .segue bg:grey

# 那就先來自我介紹吧～

--- &twocol w1:60% w2:40%

## Ricky  

Professional field at Data analysis and data mining

*** =left

- NTUST  

- Internship: 
  Chocolab  : 
   data ETL  
   report automation  
   recommender system  

- Current works :   
  Kinpo AI engineer 

*** =right

<img src="./assets/img/ricky.jpg" title="plot of chunk unnamed-chunk-1" alt="plot of chunk unnamed-chunk-1" width="400px" />

--- &twocol w1:60% w2:40%

## Dan   

Professional field at Data analysis and Big data analysis

*** =left


- NTUST  
  
  
- Internship : 
  III  
    Sentiment Analysis
  Micron  
    Using Social Network on QC 
  kkbox  
    Crawler , ELK
  Yuanta      
    Predict futures
  
  
- Current works :   
  Telecommunications' Big data engineer  
  
  
*** =right

<img src="./assets/img/dan.jpg" title="plot of chunk unnamed-chunk-2" alt="plot of chunk unnamed-chunk-2" width="400px" />

--- .segue bg:grey

# 黑名單分析

---

## 黑名單分析

<img src="./assets/img/tender_flo.png" title="plot of chunk unnamed-chunk-3" alt="plot of chunk unnamed-chunk-3" width="800px" style="display: block; margin: auto;" />

---

## 黑名單分析

<iframe src="dt1.html" width=100% height=100% allowtransparency="true"> </iframe>

--- .segue bg:grey

# 決標標案分析 - 廠商

--- &twocol w1:60% w2:40%

## 決標標案分析 - 廠商
*** =left
   
- Data: 決標 -> 撤銷公告    
  
- Time: 2014 ~ 2016  

*** =right

<img src="./assets/img/tender.png" title="plot of chunk unnamed-chunk-4" alt="plot of chunk unnamed-chunk-4" width="800px" />

--- 

## 撤銷公告問題
  
從 "撤銷公告原因及依據法條" 可看到一些有趣的事情
  
- 廠商問題:
撤銷公告原因及依據法條   
  
- 本案得標廠商「XXXX」未依規定履行契約，且經本局數次聯絡皆表示無履約意願   
- XXXX有限公司得標後拒不簽約   
- 廠商之信用證明逾期   
- XXXX公司登記證已於105年4月13日註銷，應撤銷決標、終止契約或解除契約，並得追償損失。   

--- 

## Top 5 機關遭雷



<iframe src="wp.html" width=100% height=10% allowtransparency="true"> </iframe>
  
---

--- &twocol

## 決標方式 ＆ 類別

*** =left



<iframe src="wp1.html" width=100% height=10% allowtransparency="true"> </iframe>

*** =right  
  

<iframe src="wp2.html" width=100% height=10% allowtransparency="true"> </iframe>

--- 

## 被雷金額

母體介於 30萬至 140萬之間  
大多較有問題的標案大多range僅在 20萬到60萬之間  
  
<img src="figure/unnamed-chunk-9-1.png" title="plot of chunk unnamed-chunk-9" alt="plot of chunk unnamed-chunk-9" style="display: block; margin: auto;" />

--- .segue bg:grey

# 決標標案分析 - 政府  

---

## 政府問題

- 大多為資料填錯導致流標

- 尤其是'案號'誤繕等

- 是否效率或是SOP等需要改善

---

## 單位填錯排名

仍為台灣大學以及中國石油！！！  

<img src="figure/unnamed-chunk-10-1.png" title="plot of chunk unnamed-chunk-10" alt="plot of chunk unnamed-chunk-10" style="display: block; margin: auto;" />

--- &twocol

## 決標方式 ＆ 類別

*** =left



<iframe src="wp4.html" width=100% height=10% allowtransparency="true"> </iframe>

*** =right  
  

<iframe src="wp5.html" width=100% height=10% allowtransparency="true"> </iframe>

---

## 流廢標價位

- 金額  
  
因失誤導致流廢標金額約在20萬到200萬之間，最高有到16億  
  
<img src="figure/unnamed-chunk-14-1.png" title="plot of chunk unnamed-chunk-14" alt="plot of chunk unnamed-chunk-14" style="display: block; margin: auto;" />


---

## Summary

- 廠商失能  
  
  較多出現於，財務類。金額約於20萬～60萬  
  
  -> 可能因金額較少，所以在監督上較少著墨。  
  
- 政府失能  
  
  在分析後我們覺得，應是常態性的失誤。
  
  -> 所有分配皆接近母體。可能在於SOP或是資料填寫上需要有一些防呆機制。  
    

--- .segue bg:grey

# Other things...... 

---  
   
## 接案王

- 決標 -> 決標公告
<img src="figure/unnamed-chunk-15-1.png" title="plot of chunk unnamed-chunk-15" alt="plot of chunk unnamed-chunk-15" style="display: block; margin: auto;" />

---

## 大熱門

- 決標 -> 決標公告  
hot = 投標公司比率  
(勞務類&最有利標)
<img src="figure/unnamed-chunk-16-1.png" title="plot of chunk unnamed-chunk-16" alt="plot of chunk unnamed-chunk-16" style="display: block; margin: auto;" />

--- .segue bg:grey

# [Demo](https://rickychang.shinyapps.io/DSP_opendata_project/)




