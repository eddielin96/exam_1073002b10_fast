# 網頁設計乙級術科題庫分析

(108年度技術士技能檢定-考試速寫版 ver2)

---

# 關於本解析

>作者：Loki Jiang × 修訂：108/10/09

* 解析教學：[https://b17300.lokiui.com/](https://b17300.lokiui.com/)
* 程式碼下載：[https://github.com/summer10920/skill-edu_107300_fast/](https://github.com/summer10920/skill-edu_107300_fast/)
* 完成網站範例：
  * [01-卓越科技大學校園資訊系統](http://b17300demo.lokiui.com/web01/)
  * [02-健康促進網社群平台](http://b17300demo.lokiui.com/web02/)
  * [03-ABC影城](http://b17300demo.lokiui.com/web03/)
  * [04-精品電子商務](http://b17300demo.lokiui.com/web04/)

---

# 作者的教材筆記
本教材內容取自『泰山職訓網乙考照班』之教材([by Github.Kento](https://github.com/rogeraabbccdd/))為參考。確保術科時間內完成考試以及符合題目示意要求為不扣分標準，重新編譯簡化與功能性，並根據時間完成與功能指示之兩項要點設計的考照筆記(作者證照取得之編號為No.43)，在此分享給有心人使用。

## 證照有效力

給想要考取網頁設計乙級的人。這張證照考取率難度高可視為挑戰。民間報考人數普遍不多，絕大部分的原因在於：該證照的術科教材不易取得；業界或職能者來說過於陌生且未聽聞過考題內容；程式敲打速度的熟悉度與邏輯性不足。

但對於想要實力證明的考生而言仍然是有效價值的表現方式。自民國103年度首辦發照人數自今仍不到百位(也就全國只有不到100個人持有)，因此不論業界是否審視此證照的有效價值，最大的自我價值在於您能否有能力取得這張證照，別怕別人是否認同此證照能否代表你的能力，至少你擁有了別人沒有的東西。

## 考試重點

作者的考試經驗做為分享，考試分為三階段，初階段90分鐘進行座位抽籤+環境測試，中階段4小時進行題目抽籤+實作解答，後階段不計時的驗收評分。所以三段時間可以分別規劃並做心理準備與時間分配。

* **初階段準備：**
  1. 安裝與測試環境，將你的XMPP+PHP+MYSQL安裝起來，並將題庫==版型放入正確位置並加以整理檔案內容==。
  2. 規畫你的==函式庫==，根據您的練習經驗或程式習慣，==簡化你的程式作答==，先建立好自訂函式，作答上越快越好。
  3. 未知抽考題目之前提下，先將4組題目的所有==已知資料手動處理到SQL==，這能減少你作答時的資料建立。
  
* **中階段準備：**
  取得作答題目後，開始正式編寫網頁。題目上沒有出現的動作就不用去完整設計。題目採取扣分制度。多做的功能是不計分的，你的任務是四小時內完成。只要作答題目上有要求的動作即可，示意參考圖是可以不用特別去跟著規範設計走（也就是美觀與UIUX是不影響計分）。舉例來說，像是對某項目進行修改內容，你可以不必帶出舊資料讓人修改，直接空的欄位顯示讓人修改就好，只要能夠進行修改，是否讓人覺得操作合理人性這點是不必要考量的。如果希望這是你的作品之一可以另外做完整版本，考試拚的是時間內完成的速成版本。

* **後階段驗收：**
  作答完還剩時間就回頭檢查所有評分動作，考官不會接觸你的電腦設備，由考官進行口頭動作要求，你來負責操作示範。所以如果自己知道有程式瑕疵，就自己操作上技巧迴避。若時間上的能力不能提早完成，可適時放棄步驟繁多但扣分少的要求，100分開始倒扣，60分及格，每一動作未達則扣5分，所以你可以放棄部分動作\(還有其他嚴重扣分不在此話內\)。你可以作答到最後，完整4小時鐘響後才進行驗收，不用擔心驗收時間屬於作答時間內。
  
  另外還有惡魔技巧是，考場會分配多位驗收官，如果你閒暇之餘去分析場上氣氛去分析很嚴或很鬆的考官。利用考官正幫某人驗收速度時去分析考官是好是壞，並想辦法抓好時機就近讓好考官去幫你驗收。
