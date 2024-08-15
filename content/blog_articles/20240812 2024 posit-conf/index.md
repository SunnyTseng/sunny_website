---
title: 2024 posit::conf in Seattle
subtitle:
summary: 

date: 2024-08-12
math: true
diagram: true
# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Placement options: 1 = Full column width, 2 = Out-set, 3 = Screen-width
# Focal point options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
image:
  placement: 2
  caption: ''
  focal_point: ""
  preview_only: true
---

### Opportunity Scholar 

這次獲得了 2024 posit::conf opportunity scholar 的機會，POSIT (之前叫做 RStudio) 直接提供了會議的參與費用、機票、所有食宿費用，覺得 POSIT 非常富有。這次來到了西雅圖開會，是第一次參加由公司舉辦的會議，POSIT 本身雖然提供了許多 open source 的服務，像是最多人熟悉的 RStudio IDE，同時地也在付費的服務上提供大型公司所需要的 Posit cloud connect 等等，並以此為主要的收入來源。

Opportunity Scholar 不限職業，只要是對 open source data science 有興趣的都可以申請，全球每年有 40 個名額，是個很好的機會來看看 POSIT 的氣魄。

來到會場之後，整個驚為天人。POSIT 直接包下整個西雅圖市中心的飯店，從三到七樓都是會議場地，而同個飯店就是與會者的住宿地點。從前身叫做 RStudio 就可以推測，大部分的 workshop 與 session 都以 R 為主，連註冊的小本本都是一整冊的 cheatsheets! 直接深深的切中我心 :heart_eyes:。同時也有很多 Python 的 talk。

身為一個 RStudio 與 Open source 的熱愛者，和兩千位擁有同樣熱情的軟體工程師共同參與的會議，和今年稍早參加的鳥鳥會議，或是生物聲學會議完全不同的氣氛，簡直像來到另一個世界。

### R Package development workshop

自從加入 rOpenSci 開發 R package 以來，已經將近半年的時間，在 R package 的世界裡有無限的可能。有在寫 R package 的人大概都知道 [R Packages (2e)](https://r-pkgs.org/) 這本書，由 Hadley Wickham 與 Jennifer Bryan 共同撰寫。這次的 package development 就是 Jenny 主講，我整個是小粉絲參拜明星的心態。

整個 workshop 的 Github repo 在此: 




從一開始的主要 function 建造、到後來的 workflow, 


### Keynote: POSIT update

1. Quarto Live
2. 

POSIT 的主要 product: 
- Rstudio IDE
- Shinny 
- Shinny Server
- R packages (tidyverse, tidyvermodels, ggplot2, etc.)
- Quarto

### Positron 

Just got updated 6 weeks ago. 

### How to make Great Tables

- gt
- gtsummary

### Keynote: Use GenAI for Data Science



### Keynote: The Future of Data Science 

這次上台的是個老先生 Allen Downey，話說我對 Data Science 裡面的人物其實所知不多(畢竟我也是半路出家)，剛剛聽完 keynote 一上網查才知道人家是赫赫有名的 Think Stat 的作者，這裡先附上人家的 [Github](https://github.com/AllenDowney?tab=repositories) 。

聽講之前我才想怎麼會把主題定的這麼廣，這個 title 真的是要講甚麼都可以。但不愧是有經驗的講者，一下就擄獲全場人心。

第一個段落提到他和太太在懷第一個小孩的時候，不知道第一胎是不是比起其他的嬰兒更容易晚生，與其直接 Google 看個人案例，他去找了 data base 來做統計分析，發現其實第二胎之後的寶寶更容易 delay。特別引人注目的是，他在分享這個發現到個人部落格上之後，竟然被媒體轉發，瞬間變成了孕婦產期的專家(?)。

The key of data science is to transform "unanswered" to "answered". 

接著對於 Data Science 的期望之後，又提到 statistics 和 computer science 並不是同一件事情，不是把彼此加起來就會變成 Data Science。我們在一個資訊爆炸的世代，[Doomscrolling](https://en.wikipedia.org/wiki/Doomscrolling#:~:text=Doomscrolling%20or%20doomsurfing%20is%20the,the%20web%20and%20social%20media.) 加上近十年來的錯誤分析、資訊洩漏、個資外洩等等的醜聞，讓大家對於 Data Science 的認知偏向負面，但適當的遠離負面資訊以及藉由資料認識世界，是個很好的開始，介紹了一些書籍:

- [Factfulness](https://www.amazon.com/Factfulness-Reasons-World-Things-Better/dp/1250107814)
- [Not the end of the World](https://www.amazon.com/Not-End-World-Generation-Sustainable/dp/031653675X)
- [Element of Data Science](https://allendowney.github.io/ElementsOfDataScience/index.html)
- [Probably Overthinking It](https://www.amazon.com/Probably-Overthinking-Questions-Statistical-Decisions/dp/0226822583?crid=1OPZI2WEGNPTA&keywords=probably+overthinking+it&qid=1681258805&sprefix=probably+overt,aps,212&sr=8-1&linkCode=sl1&tag=greenteapre01-20&linkId=7cf54619116fbf7a0e8312c4daf08619&language=en_US&ref_=as_li_ss_tl)

介紹的 Ted 短講和用資料認識世界的網站:
- [Our World in Data](https://ourworldindata.org/)
- [Hans Rosling's 200 Countries, 200 Years, 4 Minutes](https://www.youtube.com/watch?v=jbkSRLYSojo)

最讓人印象深刻的是他對於世界的正向心態，並不是無知的正向心態，而是完整的藉由資料來提供客觀的證據，藉此建立起自己世界觀的信心。在 QA 中被問到 "你身為白人男性的身分影響你對世界的看法，你要如何抽離這樣身分造成的的偏差"，在我聽來非常尖銳的提問。

他只是簡單地承認自己身為白人男性的確是擁有了很多優勢，但是他所提供的這些想法是他盡量找到的客觀知識，同時他也提到了，這些推論都是自己的想法，很樂意聽大家的想法與討論。他也說，鼓勵有這些疑問的人，可以思考一下自己為什麼自己會有這樣的情緒出現。

幾段想記錄的話:
- Data science exists because statistics missed the boat on computers. 
- Wanting to know the truth is the key for defeating confirmation bias.

### Keynote: DockDB

會議進行到這個時候，已經呈現知識疲勞狀態，從早上七點起床到傍晚十點回到飯店房間，大概只有十分鐘是可以好好休息的時間。大腦一直維持在興奮狀態，不是在