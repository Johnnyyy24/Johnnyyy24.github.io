+++
title = "從 DraftKings 財報看 Polymarket 及預測市場"
date = 2026-01-11T11:45:36+08:00
draft = false
series = ["Crypto"]
description = "分析 DraftKings 財報背後的獲利邏輯，拆解 Polymarket 等預測市場該如何從「工具」進化成「生意」。"
+++


最近預測市場（Prediction Markets）在社群上紅透半邊天，Polymarket 的交易量屢創新高，大家似乎都認為這就是 web3 的殺手級應用。然而，在激情過後，身為投資人我們得問一個最俗氣的問題：**這東西到底怎麼變成一門賺錢的生意？**

很多人以為預測市場就是「讓大家賭一把」，但如果我們把視角轉向體育博彩巨頭 DraftKings ($DKNG) 的 Financials，會發現真正的「賺錢密碼」藏在更底層的數學結構裡。

在這篇文章中，我想要透過 DraftKings 的真實財報數字（Handle, Hold, Margin），來幫大家 Reverse Engineer 預測市場未來的 Playbook。同時，我也將點出目前預測市場模式中，那些被過度忽略的結構性風險。

### TL;DR

我認為目前的預測市場雖然流量巨大，但從 Business Model 的角度來看極度 Under-monetized。市場正微過度買單「群眾智慧」的敘事，卻忽略了 DraftKings 已經驗證過的真理：單純的 Binary Option（是非題）是很難賺錢的。

DraftKings 25Q3 的數據告訴我們，真正的 Alpha 來自於 Structure Hold（結構性持有率）以及 Cross-sell to iGaming。如果預測市場不能從「單一事件預測」轉型為「複雜敘事組合（Parlay）」，那它充其量只是下一個低利潤的造市商，而非我們期待的 Cash Cow。

## DraftKings 的生意本質：Volume is Vanity, Hold is Sanity
DraftKings 的生意模式非常簡單粗暴：**用體育賽事當作流量入口，透過操盤手的賠率優勢（Vig）賺取穩定價差，再把用戶導流去玩利潤更高的賭場遊戲。**

將 DraftKings 25Q3 的財報攤開來看，這季的數字非常誠實地揭露了這個行業的底層邏輯：

* Revenue (Topline): $1.14B (年增 4.4%)

* Sportsbook Handle (總流水): $11.4B

* Net Revenue Margin (Take Rate): ~5.2%

這個數據告訴我們什麼？DraftKings 創造了 114 億美金的流水，才換來約 6 億美金 的體育博彩營收。這是一個典型的「高流水、低毛利」生意。

用資產管理的模式來思考，目前 Polymarket 這種預測市場大多只收取極低的交易費（或是依賴 USDC 的利息做 Treasury Management 的套利），這就像是在做 Charity。如果只靠 1-2% 的費用，你需要天文數字的交易量才能支撐一家獨角獸公司。

*⮕ Lesson 1: 預測市場不能只做「訊息發現的工具」，必須進化成「高流動性的交易引擎」。沒有百億級別的 Handle，就沒有具備規模的 Revenue。*

## 那為什麼 DraftKings 能賺錢？

### Alpha #1：逃離 "Vig" 的陷阱，擁抱 Parlay
我們都知道標準的博彩賠率（例如兩邊 -110）內建的數學優勢（Vig）大約只有 **4.76%**。這就是 DraftKings 的地板。

但在 Earnings Call 中，管理層反覆強調一個詞：*Structure Hold (結構性持有率)*。 為什麼 DraftKings 能把 Margin 做高？靠的不是單場比賽的 Vig，而是 **Same Game Parlay (SGP, 同場過關)**。

* 單注 (Single Bet): 低 Margin (~5%)，玩家容易贏，賭場賺辛苦錢。

* 串關 (Parlay/SGP): 極高 Margin (20-30%)，將多個低機率事件打包。

這給預測市場的啟示是： 現在的預測市場大多是 Binary（川普贏/輸）。這就像早期的體育博彩，Margin 極低。 未來的預測市場若要賺大錢，必須推出 "Prediction Parlays" (敘事組合包)。

舉個例子，現在大部分的預測市場都問 <br> "川普會當選嗎？" (Yes/No)。而未來的組合會是 "川普當選 AND 比特幣年底破 10萬 AND 聯準會降息"。這種「敘事打包」不僅能滿足用戶的宏觀預測慾望（Degen 心理），更能大幅拉高平台的 Take Rate。這才是從 Tool 變成 Casino 的關鍵躍遷。

### Alpha #2：iGaming 是隱藏的金礦 (The Backend Monetization)
這一點可能很多人沒注意到。在 DraftKings Q3 的 $1.14B 營收中，雖然體育博彩 (Sportsbook) 佔了 ~52%，但 **iGaming (線上賭場) 貢獻了驚人的 ~40%**，且 iGaming 的利潤率通常更高、波動更小。

這揭示了一個殘酷的現實：體育（或政治預測）是用來獲客 (Acquire) 的，**賭場是用來變現 (Monetize) 的**。

預測市場目前面臨「事件枯竭期」（例如選後流量暴跌）。成功的平台最終可能會演化成：前端用高熱度的社會議題（戰爭、選舉）吸流量，後端提供**高頻率的金融衍生品或 Crypto 投機產品（類似 iGaming 的角色）**。

## 風險：預測市場面臨的 Headwinds
講完了 DraftKings 給的 Playbook，現在來講一下投資或參與預測市場本身的一些風險來平衡報導。

### 風險一：流動性碎片化的死結
DraftKings 的優勢在於，NBA 就是 NBA，所有人的盤口都差不多，流動性是集中的。但預測市場的問題在於「定義」。

"Will Bitcoin hit 100k?" 和 "Will Bitcoin hit 100k on Binance?" 可能是兩個完全不同的合約。當題目可以無限生成，流動性就會被無限稀釋。對於想要做大 Handle 的平台來說，流動性碎片化 (Fragmentation) 會導致造市商 (MM) 的成本極高，進而影響用戶的體驗（Spread 變大）。

### 風險二：缺乏 Recurring Revenue 的事件驅動特性
體育博彩之所以能成為上市公司，是因為 NBA、NFL 每年都會打，它有穩定的 Seasonality。

但預測市場目前高度依賴「黑天鵝」或「大選」。2024 大選過後，Polymarket 的流量肉眼可見地回調。如果沒有建立起類似 iGaming 那種 High-frequency 的常態性賭局，預測市場很難撐起像 DraftKings 這樣穩定的股價表現。

### 風險三：監管的達摩克利斯之劍
DraftKings 之所以能做大，是因為它花了無數資源在 State-by-State 的合規上。目前預測市場大多還在 Grey Area 遊走（如 CFTC 對 Kalshi 的態度反反覆覆）。

一旦 GENIUS 法案或是其他監管框架落地，合規成本將會大幅壓縮 Margin。這時候，那些沒有強大 Legal Team 或足夠 Cash Reserve 的小型預測平台，很有可能會直接被洗出場。

## 結語
Don't get me wrong, 我堅定相信預測市場會是 Crypto 極為少數的 PMF 之一（PMF 三原色：數位黃金、炒作、穩定幣及支付）。而見其終於有了出圈的跡象是非常欣慰的。這代表我們離 Efficient Market Hypothesis 更近了一步。

然而，Call back 到我通篇的論點：流量不等於利潤。未來的預測市場贏家，不會是那個題目最多的平台。成功把用戶 attention 轉化成各種額外高毛利賭博的人才會是贏家。