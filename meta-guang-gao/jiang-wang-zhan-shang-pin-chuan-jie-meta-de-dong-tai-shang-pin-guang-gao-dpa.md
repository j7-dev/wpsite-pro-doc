---
icon: rectangle-vertical-history
---

# 將網站商品串接Meta的動態商品廣告(DPA)

動態商品廣告，最常見的做法是用在再行銷，提醒用戶下單

Meta廣告可以自動偵測用戶在你網站上看了哪些商品，然後直接對該用戶廣告他剛剛看過的商品

例如我們上了某個網站，看了某商品，結果馬上就在臉書動態上看到該商品的廣告，就是DPA的作用

以下是設置教學，雖然步驟有點多，但只要串接好一次，之後下DPA就會很方便了！

## <mark style="color:blue;">1. 取得商品目錄網址</mark>

首先要確認網站有安裝&啟用 Pixel Cat外掛

找到網站後台 Pixel Cat / E-commerce / Product Feed，啟用這個選項

並複製 Feed URL

下方點擊儲存Save All Setting

<figure><img src="../.gitbook/assets/image (92).png" alt=""><figcaption></figcaption></figure>

## <mark style="color:blue;">2. 新增商品目錄</mark>

在臉書的廣告後台，找到這個「商務管理工具」

或是直接點擊這個連結 [https://business.facebook.com/commerce/](https://business.facebook.com/commerce/)

<figure><img src="../.gitbook/assets/image (93).png" alt=""><figcaption></figcaption></figure>

選擇 電子商務

<figure><img src="../.gitbook/assets/image (94).png" alt=""><figcaption></figcaption></figure>

選擇 上傳商品資料，選擇對應的擁有者，並幫目錄取名字，例如「某網站全商品」

<figure><img src="../.gitbook/assets/image (95).png" alt=""><figcaption></figcaption></figure>

這樣就順利建立目錄了，點擊「查看目錄」

<figure><img src="../.gitbook/assets/image (96).png" alt=""><figcaption></figcaption></figure>

## <mark style="color:blue;">3. 串接商品資料來源</mark>

在目錄的裡面，點擊 資料來源 → 資料摘要 → 繼續

<figure><img src="../.gitbook/assets/image (97).png" alt=""><figcaption></figcaption></figure>

選擇「使用網址或Google試算表」 → 貼上Pixel Cat提供的Feed URL → 繼續

<figure><img src="../.gitbook/assets/image (98).png" alt=""><figcaption></figcaption></figure>

選擇正確的幣別

頻率的部分，如果很頻繁修改商品資訊，可以用每小時。如果不常修改，就用每日

時間隨意

然後點擊 上傳

<figure><img src="../.gitbook/assets/image (99).png" alt=""><figcaption></figcaption></figure>

然後就會看到這個畫面，等他建立

<figure><img src="../.gitbook/assets/image (100).png" alt=""><figcaption></figcaption></figure>

這樣就是建立成功了

<figure><img src="../.gitbook/assets/image (101).png" alt=""><figcaption></figcaption></figure>

## <mark style="color:blue;">4. 將目錄連結像素</mark>

現在我們建立好了目錄，但是還沒有連結 像素

要連結像素，並且像素要連結廣告帳號，才會在那個廣告帳號裡面看到商品目錄，才能下DPA廣告

前往 企業管理平台設定

<figure><img src="../.gitbook/assets/image (102).png" alt=""><figcaption></figcaption></figure>

點擊目錄 → 選擇剛剛建立的目錄 → 確認目錄編號正確 → 確認自己有在相關人員列表

點擊「連結來源」

<figure><img src="../.gitbook/assets/image (103).png" alt=""><figcaption></figcaption></figure>

會出現這個視窗

選擇要連結的像素，並打開連結，儲存

<figure><img src="../.gitbook/assets/image (104).png" alt=""><figcaption></figcaption></figure>

## <mark style="color:blue;">5. 將像素連結廣告帳號</mark>

如果之前還沒有將像素連結廣告帳號，就要連結一下

如果已經連過，則可以跳過此步驟

在企業管理平台設定 點擊 資料集 → 選擇剛剛連結的像素 → 點擊 指派資產

<figure><img src="../.gitbook/assets/image (105).png" alt=""><figcaption></figcaption></figure>

會出現這個視窗，選擇要連結的廣告帳號，按新增

<figure><img src="../.gitbook/assets/image (106).png" alt=""><figcaption></figcaption></figure>

## <mark style="color:blue;">6. 建立DPA廣告</mark>

接著就可以到 廣告管理員，建立一個新廣告

點擊建立 → 選擇 銷售 → 繼續

<figure><img src="../.gitbook/assets/image (107).png" alt=""><figcaption></figcaption></figure>

可以自行選擇 高效速成或是手動設定，都可以

<figure><img src="../.gitbook/assets/image (109).png" alt=""><figcaption></figcaption></figure>

以高效速成為例，在廣告的層級

要選擇 建立廣告(預設就是)，並點選 目錄

<figure><img src="../.gitbook/assets/image (110).png" alt=""><figcaption></figcaption></figure>

往下滑一點，會看到 目錄

可以點開目錄，確認編號是否正確

<figure><img src="../.gitbook/assets/image (111).png" alt=""><figcaption></figcaption></figure>

剩下的就是一般的Meta廣告設定，設定好投放方式跟文案等，就可以投放DPA動態商品廣告囉
