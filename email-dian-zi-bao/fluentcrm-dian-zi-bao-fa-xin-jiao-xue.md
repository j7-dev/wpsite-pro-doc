---
icon: newspaper
---

# FluentCRM電子報發信教學

## FluentCRM 介紹

FluentCRM 簡單來說就是我們用來發電子報的一個介面

要先自行串接SMTP才能使用唷，可申請 [Mailgun](https://app.mailgun.com/)

<figure><img src="../.gitbook/assets/image (55).png" alt=""><figcaption></figcaption></figure>

### 發信流程

如果你想新增一個 campaign ( 郵件活動 )

就從左方的選單 「 campaigns 」 點選右方的藍色按鈕後

在對話框輸入「取名名稱」開始編輯

<figure><img src="../.gitbook/assets/image (56).png" alt=""><figcaption></figcaption></figure>

進入編輯器後這裡的介面也非常簡單，可以直接輸入文字及加入連結

編輯好你的Email內容後，點選右方的藍色按鈕 「 Continue (Subject & Settings) 」

<figure><img src="../.gitbook/assets/image (57).png" alt=""><figcaption></figcaption></figure>

編輯好你的Email內容後，點選右方的藍色按鈕 「 Continue (Subject & Settings) 」

<figure><img src="../.gitbook/assets/image (58).png" alt=""><figcaption></figcaption></figure>

輸入完主題後，點選右下方的 Continue To Next Step \[Recipients ] 進入下一頁

<figure><img src="../.gitbook/assets/image (141).png" alt=""><figcaption></figcaption></figure>

發信清單：這邊會有清單，正常一開始會是空的，之後會講如何把你的客戶名單導入

而右上的 Contacts 有幾個顧客類別分類，匯入顧客名單後也從這個分類中做管理

{% hint style="info" %}
All Contacts：所有聯絡人

Lists： 用Lists設定聯絡人清單(群組)

Tags： 用Tag標籤聯絡人

Segments：設定更進一步的區隔，可以把Lists再作進一步的分類，例如：買過特定商品的顧客
{% endhint %}

以下會介紹三種發信的選擇，依照你的需求選擇即可

第一種發信選項： List & tag

<figure><img src="../.gitbook/assets/image (142).png" alt=""><figcaption></figcaption></figure>

第二種發信選項： Segment，選擇已經篩選好的分類直接點選就可以

<figure><img src="../.gitbook/assets/image (143).png" alt=""><figcaption></figcaption></figure>

第三種發信選項： 那如果說你是臨時起意，想要發給買過某一個商品的人，但是之前沒有用「Segment」篩選過，就可以用 「 Advanced Filter 」 直接來選

可以透過細部的篩選例如：最後購買時間、購買的商品、訂單金額⋯⋯等等，篩選後可以精準發給這個客戶（目前示意圖是灰色，是因為還沒有匯入清單整合）

<figure><img src="../.gitbook/assets/image (144).png" alt=""><figcaption></figcaption></figure>

以上三種篩選方式選好就可以進行下一步發信簡單送出群組信件

但這種新的發信帳號需要點時間培養，也要注意幾點事情培養 Email 在發信的信任度評分

### 培養郵件評分（避免成為垃圾信）

* [x] **發信顧客**：\
  盡量發給已經有在追蹤你的人增加開信率，不要濫發廣告信發給陌生客戶，避免被太多人回報為垃圾信件後，之後發的信會直接被判斷為垃圾信（請客戶回報非垃圾信後也能慢慢加回評分）
* [x] **發信時間**：\
  群發信都有點時間差，例如：一萬封信會分批發，有些人會早收到，有些人會晚收到
* [x] **減少連結**：\
  多一個連結就多一個機會進到垃圾郵件，所以盡量不要用太多商品連結
* [x] **銷售字眼**：\
  避免太多促銷、折扣、免費這些內文文字

### 匯入顧客名單

接下來到 Contacts 匯入

從外部匯入選點選 Import

<figure><img src="../.gitbook/assets/image (145).png" alt=""><figcaption></figcaption></figure>

Import 匯入 CSV 檔案 、或從現有的 WooCommerce 直接整合資料（以下以WooCommerce 為例）

<figure><img src="../.gitbook/assets/image (146).png" alt=""><figcaption></figcaption></figure>

確認匯入的顧客資料後，可以從這裡開始先建立一些分類 Lists，Tag、Segments

這裡可以先建立一些簡單的基礎

Lists：建立簡單分類如ex：「付費學員」

Tag：做大分類時先不用設定

Segments ：選擇 Subscribe 匯入是已經訂閱的會員（取消訂閱的不建議再發信）

以上設定沒問題後，就可以按藍色按鈕到下一頁

<figure><img src="../.gitbook/assets/image (147).png" alt=""><figcaption><p>匯入後就會直接有完整的客戶名單（這之間不會有任何通知或發信通知）</p></figcaption></figure>

### 建立自動化流程

在建立自動化流程之前，要先在 Lists，Tag、Segments 這三個分類當中建立一些客戶分類條件，這樣才能讓自動化篩選

以下以 Segments 為例：點選 Add 開始設定條件

<figure><img src="../.gitbook/assets/image (149).png" alt=""><figcaption></figcaption></figure>

將例如買過某些商品、購物到多少錢以上的顧客做篩選

<figure><img src="../.gitbook/assets/image (150).png" alt=""><figcaption></figcaption></figure>

{% hint style="warning" %}
⚠️ 這裡要注意， 在設定完之前的顧客不會自動導入，設定完之後判斷的才會被分類篩選到。

如果要導入之前 「 有買過的客戶 」，要先 「 創立完這個分類」後，再 「 手動加入 」 。
{% endhint %}

從左方選單點選 Automations 點選右方藍色按鈕，新增新的自動化流程

<figure><img src="../.gitbook/assets/image (151).png" alt=""><figcaption></figcaption></figure>

點開後會看到幾個條件篩選

<figure><img src="../.gitbook/assets/image (152).png" alt=""><figcaption></figcaption></figure>

<figure><img src="../.gitbook/assets/image (153).png" alt=""><figcaption></figcaption></figure>

<figure><img src="../.gitbook/assets/image (154).png" alt=""><figcaption></figcaption></figure>

這裡先做一個範例

例如他加入 「 某一個清單 」

<figure><img src="../.gitbook/assets/image (155).png" alt=""><figcaption></figcaption></figure>

這邊要先選擇是加入哪一個清單會觸發

<figure><img src="../.gitbook/assets/image (156).png" alt=""><figcaption></figcaption></figure>

勾選這個：觸發一樣的條件，就會再重新篩選一次（通常會選）

<figure><img src="../.gitbook/assets/image (157).png" alt=""><figcaption></figcaption></figure>

設定完成跳選下個按鈕後，會跳到這個工作區看到剛剛設定完的「模組」

點選這個模組可以直接寄送給滿足 Segments 條件的顧客

<figure><img src="../.gitbook/assets/image (54).png" alt=""><figcaption></figcaption></figure>





接下來的設定請見影片（有內嵌字幕可以開啟）

💡影片區

{% embed url="https://youtu.be/Oi2yxS1JUl4?si=5nV5K_6qoTnKrvtz" %}
