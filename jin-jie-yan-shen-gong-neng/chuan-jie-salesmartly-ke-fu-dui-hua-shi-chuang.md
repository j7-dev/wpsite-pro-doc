---
icon: comment-dots
---

# 串接SaleSmartly客服對話視窗

[95折申請連結](https://share.salesmartly.com/xk78nV)

## 網站右下角對話框

<figure><img src="../.gitbook/assets/image (39).png" alt=""><figcaption></figcaption></figure>

<figure><img src="../.gitbook/assets/image (40).png" alt=""><figcaption></figcaption></figure>

{% stepper %}
{% step %}
### 建立聊天插件後，複製程式碼

<figure><img src="../.gitbook/assets/image (45).png" alt=""><figcaption></figcaption></figure>

<figure><img src="../.gitbook/assets/image (48).png" alt=""><figcaption></figcaption></figure>
{% endstep %}

{% step %}
### 安裝好能自訂 Javascript 的外掛後，把程式碼放進去

[安裝外掛方法](../wordpress-kuai-su-ru-men/an-zhuang-wai-gua.md)

<figure><img src="../.gitbook/assets/image (44).png" alt=""><figcaption><p>*此處以 Simple Custom CSS and JS 為例</p></figcaption></figure>
{% endstep %}
{% endstepper %}



## 串接官方Line

<figure><img src="../.gitbook/assets/image (41).png" alt=""><figcaption></figcaption></figure>

<figure><img src="../.gitbook/assets/image (42).png" alt=""><figcaption></figcaption></figure>

### 1# 添加Line到集成，並輸入Channel資訊

<figure><img src="../.gitbook/assets/image (43).png" alt=""><figcaption></figcaption></figure>

<figure><img src="../.gitbook/assets/image (169).png" alt=""><figcaption></figcaption></figure>

<figure><img src="../.gitbook/assets/image (170).png" alt=""><figcaption><p>Channel資訊位置</p></figcaption></figure>

{% hint style="info" %}
如果以前沒設定過，會出現"創建Messaging API"按紐，按它並照流程設定
{% endhint %}

### 2# 設定Line回應設定

<figure><img src="../.gitbook/assets/image (172).png" alt=""><figcaption></figcaption></figure>

### 3# 前往 LINE Developers 開啟 Use Webhook

前往[ LINE Developers 頁面](https://developers.line.biz/console)

<figure><img src="../.gitbook/assets/image (33).png" alt=""><figcaption></figcaption></figure>

<figure><img src="../.gitbook/assets/image (34).png" alt=""><figcaption></figcaption></figure>

<figure><img src="../.gitbook/assets/image (35).png" alt=""><figcaption></figcaption></figure>

### 4# 在網站上顯示

<figure><img src="../.gitbook/assets/image (36).png" alt=""><figcaption></figcaption></figure>

<figure><img src="../.gitbook/assets/image (37).png" alt=""><figcaption></figcaption></figure>

<figure><img src="../.gitbook/assets/image (38).png" alt=""><figcaption></figcaption></figure>

{% hint style="info" %}
如果不需知道訪客瀏覽連結，不用進行後面步驟
{% endhint %}

<figure><img src="../.gitbook/assets/image (23).png" alt=""><figcaption></figcaption></figure>

### 5# 建立LINE Login

前往[ LINE Developers 頁面](https://developers.line.biz/console)

<figure><img src="../.gitbook/assets/image (173).png" alt=""><figcaption></figcaption></figure>

<figure><img src="../.gitbook/assets/image (174).png" alt=""><figcaption></figcaption></figure>

* Region to provide the service：Taiwan
* Company or owner's country or region：Taiwan
* Channel icon (非必填)：放你的logo
* Channel name：填頻道名稱
* Channel description：填頻道簡介
* App types：Web app
* Email address：填你的mail
* Privacy policy URL (非必填)：填網站的"隱私權政策"頁面連結
* Terms of use URL (非必填)：填網站的"服務條款"頁面連結

<figure><img src="../.gitbook/assets/image (25).png" alt=""><figcaption></figcaption></figure>

Callback URL：[https://api.salesmartly.com/client/line/callback](https://api.salesmartly.com/client/line/callback)

<figure><img src="../.gitbook/assets/image (27).png" alt=""><figcaption></figcaption></figure>

### 6# 創建LIFF app

<figure><img src="../.gitbook/assets/image (180).png" alt=""><figcaption></figcaption></figure>

* LIFF app name：頻道名稱
* Size：Full
* Endpoint URL：https://api.salesmartly.com/client/line/auth-redirect
* Scopes：全打勾
* Add friend option：On
* Scan QR：打開

### 7# 把資料填到salesmartly

<div data-full-width="false"><figure><img src="../.gitbook/assets/image (29).png" alt="" width="538"><figcaption></figcaption></figure></div>

<figure><img src="../.gitbook/assets/image (30).png" alt=""><figcaption></figcaption></figure>

<figure><img src="../.gitbook/assets/image (31).png" alt=""><figcaption></figcaption></figure>

<figure><img src="../.gitbook/assets/image (32).png" alt=""><figcaption></figcaption></figure>
