---
title: BirdNET publication
subtitle: 
summary: 

date: 2025-03-11
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

### 整體來說

博士研究的第二篇文章正式出場啦!燒燙燙、燙燙燒，是非常喜歡的 BirdNET 研究，同樣也是在心愛的期刊 Journal of Ornithology! (心愛期刊的標準是排版要漂亮)。

正式上線其實已經是一個月前了，但無奈這幾周被鄰居的總統鬧場，整個楓葉國都翻滾地沸沸揚揚，直到現在才稍微安定一些，可以安靜地寫寫東西。

這篇文章在投稿初期，我可以說是信心滿滿，覺得這篇研究是過去發表的研究中最有應用價值、且推廣性最高的，還以為投稿的過程會一切順利、拿個 minor revision 一次搞定。沒想到不僅遇到被 Ornithological Applications 退稿、還在同儕審稿的第二輪時，遇到了意志堅定的 reviewer no2，說這個研究和另一篇剛發表的研究太像了、沒有創新，讓我寫 reviewer report 的時候整個燃燒起來 (目中有火)，卯起來強調這個研究的科學貢獻。

不過說真的，最後大改之後的結果 (包含改用 GLM 以及補上的 R Shiny、R markdown)，連自己都很喜歡。順利發表之後，也收到了幾封想要拿全文的、來自遠方的研究人員來信，說這篇研究很有幫助，真的會心暖暖。

在一開始和水獺先生因為想法不同而對於研究方法遲遲不能決定，後來毅然決然堅持自己的方法，在研討會上發表後引起興趣，特別是 BirdNET 的工程師也說他們也很有興趣知道結果。在發表的路程上跌跌撞撞，不僅要和 reviewer、editor 打交道，還要跟 coauthors 解釋研究內容。邊改 review 邊看極光、收 posit 的包裹、邊傳訊息跟遠方的朋友討論到底要怎麼和善的跟人類溝通 (特別感謝 Lisa、Jasmine 和 Jerome 聆聽我的內心澎湃小劇場)。

發表科學研究到國際期刊的經驗，到這邊是第四篇了耶，只能說收穫最多的，還是過程中的甘苦淚水汗水，只要最後可以當成好笑的故事提起這些瑣碎的回憶，就是最棒的了。

PS. 想到這幾年在野外調查設樣區時，又是騎 ATV、又是開船的，還要住在自己燒柴的木屋裡，真的是一輩子的回憶。

![alt text](image.png)


### 跟水獺先生說 "I can't write something that I don't believe."
一開始跟水獺先生提案，要想做關於 BirdNET 對各物種的表現分析時，研究方法就是抽取幾個物種，每個物種分別看他們的聲音特徵和偵測表現，其實跟最後的分析大同小異。但當初，水獺先生一直說服我不要做這種複雜的 evaluation， 他提出了一個幾乎完全相反的對策，"妳要去看 BirdNET 的表現，就直接用 Audacity 去做 mock up 的音檔，在可控制的狀態下，更可以去看不同場合之間的表現變化，甚至最後，妳還可以提出一個 universal threshold，生態學家都喜歡簡單的方法，這篇文章一定會被大量的引用。"

我當時光聽就知道行不通。第一是 mock up 的音檔想起來是可操控沒錯，但根本沒有任何一種 mock up 的音檔是可以模仿到真實世界的錄音場景，那如果 BirdNET 總是使用在真實的場景，這樣的 evaluation 又有甚麼用。更何況，我真的壓根不相信會有所謂的 universal threshold，可以毫不思考的應用在每個物種上。

就這樣來來回回了好多次，每次講到這個研究我們都會意見不同，有幾次甚至還讓我氣哭了。那次他生病，剛好身體狀況不好，情緒比較不穩定所以說話很重，他說他要直接把這個題目給另一個學生做。我氣得想 "好啊! 那正合我意"。我也撂了狠話 "I can't write something I don't believe."，就是說我非常不認同會有 universal threshold 這種東西。

![](IMG_2191.jpg)

### 邊玩邊做的研究
從 2022 九月 proposal defense 之後，一直到 2023 年中都在忙貓頭鷹文章，2024 年初回台灣 (Gintas 有來那次)，都在很多 conference 場合上發表了，不論是 2024 CABE、Ecoacoustic Congress、或是在 Peoria 的 SCO-SOC，甚至還在 SCO-SOC 的會議上獲得過 presentation award，到這個時候我大概就知道這篇文章有多重要了。尤其是在 Ecoacoustic Congress 上看到有很多人都還不太清楚 BirdNET confidence 到底是甚麼，就知道這個領域有多新!

參加會議結束後，特別是 Ecoacoustic Congress，見到 BirdNET 的工程師們對於這個方法的好奇，回到家之後趕緊快馬加鞭地趕工投稿。

![](IMG_2903.jpg)

### 半路殺出程咬金的 BirdNET official paper
這篇文章先是投到 Ornithological Application。還記得是 2024 年八月，當時人在 SCO-SOO，同樣發表的這篇研究獲得了 Presentation Award，還在跟 Jenn 慶祝的時候，就收到了 Ornithological Application 的 rejection。真的是，我當時還超有自信地想，"AOS 眼光欠佳，錯失了一篇好文章"。

說道發表的崎嶇，不得不提一下 (Wood & Kahl 2024) 在講 BirdNET score，他們的方法，跟我的研究步驟超級像，這篇文章在 Journal of Ornithology 發表，時間就在我完稿前兩個月，我在被 AOS 拒絕後，二話不說文章都沒改，就直接投到了一樣的期刊，當時真的是心臟很大，我直接跟 Editor 說這兩篇文章搭在一起會有多適合。沒想到這個看似聰明的舉動，就引發了接下來 review process 的激烈戰況。

![](IMG_3128.jpg)



### Reviewer No.2 到底是誰

是誰也不重要了，但 reviewer 從一開始的評論，就很不喜歡我的研究方法，一直說我是看了 BirdNET 的研究才模仿，但根本不是這樣的! 兩個研究是獨立發起的，一個是理論，一個是應用這套方法在實際的物種上，怎麼會一樣。況且，正是因為 BirdNET 才剛興起不久，需要有許多的研究來探討要如何更有效正確的使用，才更凸顯了這類研究的重要性。

這次和 reviewer 2 打交道，整整寫了快五千字的回文，一在地強調兩個研究不一樣，我們可以想辦法讓整個文章變更完整，但沒有想要更改主要的研究目的的意思。最後，是 editor 跳出來說，"雖然 reviewer 2 可能還是不滿意作者的回覆，但我認為 BirdNET 的現況是需要有大量的研究支持他的應用，因此我將接受這篇文章。"

![](IMG_3029.jpg)


### 如果就這樣剛剛好到達了，不是最棒的了嗎

剛剛在回想跟這篇研究有關的回憶，從 PhD 一開始的 PG、野外調查、回到溫哥華、再來野外調查、各式各樣的豐富回憶。不知不覺的，就這樣剛剛好的到達了終點。

![](featured.jpg)


