# Data-science-term-project
## Project Intro
投資股票時，股價的變化受到多種因素的影響，包括公司基本面、宏觀經濟
和技術分析等。然而，研究表明市場情緒也對投資者的認知產生影響，進而間接
導致公司股價的波動。因此，市場情緒也可以作為預測股價漲跌的參考指標之一。
為了獲取市場情緒資訊，人們常使用各種方式，例如查看 VIX 指數、Google 趨
勢等。其中，一種常見的方法是通過自然語言處理（NLP）分析文字消息，如新
聞標題或社交媒體文章。
然而，僅憑交易決策資訊是不夠的，設計一套適合自己且能夠獲利的交易策
略也至關重要。交易策略通常根據投資者的風險承受能力、資產配置等因素進行
設計，並通過回測來評估演算法的優劣。近年來，隨著深度學習的快速發展，強
化學習已經成為一種有潛力的方法，可以利用神經網絡作為策略來學習更加複雜
的行為，並根據快速變動的市場環境做出更好的決策。這種優勢使得強化學習在
交易策略的開發上具有巨大的潛力。相較於傳統的算法設計，使用強化學習能夠
通過在大量歷史資料中學習，自動發現最佳的交易策略。
資產配置是交易投資中的一個重要議題，它涉及根據股市價格變化、市場情
緒以及總體經濟狀況等因素來調整資金配置，以達到超越大盤表現的獲利目標。
本專題的主題是資產配置，並將運用強化學習方法進行資產配置最佳化，同時考
慮市場情緒的影響，以達到更好的投資決策。通過結合強化學習和市場情緒分析，
我們旨在開發出一套能夠自主學習、適應不同市場環境並持續優化的投資策略，
以提升投資組合的效能和績效。藉由這樣的研究，我們期望能夠探索和發展出更
具智能化和靈活性的資產配置方法，以在投資市場中獲得更穩健的回報。

## File 
* **crawl.ipynb**:
  
  爬取10間公司的新聞標題與Google trend SVI volume，並透過Sentiment analysis得到標題內容是正面、中立還是負面，每支股票每天都會計算一個 Sentiment score ，分數分
別為+1(正面)、-1(負面)與 0(中立)
* **FinRL_summer_trading folder**:
  
  進行RL Portofolio training
## Project Full Report
https://drive.google.com/file/d/1P2EEsd5n_9G0bOwH9UaNJsNN4HewrFZH/view?usp=drive_link
