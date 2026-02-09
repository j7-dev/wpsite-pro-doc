---
icon: message-dollar
---

# Paynow 立吉付 金流 / 物流 / 電子發票

## <mark style="color:blue;">優惠費率申請</mark>

請先到[官網註冊會員](https://gateway.paynow.com.tw/register)，再填表單

{% embed url="https://docs.google.com/forms/d/e/1FAIpQLSc_gH5IZori5Bsm0QqQeIZJaBq2OMXF9KPTpDa6MqUcjrKF-Q/viewform" %}

## <mark style="color:blue;">金流</mark>

### <mark style="color:purple;">啟用金流</mark>

從後台 / woocommerce / 好用版擴充設定，啟用 Paynow 立吉付金流

### <mark style="color:purple;">設定串接資料</mark>

1. 登入[PayNow金流](https://gateway.paynow.com.tw/)後台 ，找到串接資料〔商家帳號、商家交易碼、商家名稱〕
   * 商家交易碼：賣家功能→功能設定→技術參數修改 中查看或變更
   * 商家帳號(公司統編或身分證字號)與商家名稱：賣家功能→功能設定→商家資料修改 中查看
2. 從後台 / woocommerce / 金流設定，找到立吉付，輸入串接資料〔商家帳號、商家交易碼、商家名稱〕

### <mark style="color:purple;">設定PayNow交易回傳網址參數</mark>

至 [PayNow金流](https://gateway.paynow.com.tw/)後台→賣家功能→功能設定→技術參數修改，進行設定

💡將 [_yoursite.com_](http://yoursite.com) 替換成您的網址

1.  交易結果接收網址 & 3D交易結果接收網址：

    https://[_yoursite.com_](http://yoursite.com)/wc-api/paynow\_payment
2.  離線付款回傳網址：

    https://[_yoursite.com_](http://yoursite.com)/wc-api/paynow\_payment\_offline

<figure><img src="../.gitbook/assets/image (128).png" alt=""><figcaption></figcaption></figure>

### <mark style="color:purple;">**啟用付款方式**</mark>

從後台 / woocommerce / 付款，[設定金流 - 付款方式](../woocommerce-shang-dian-gou-wu-ju/she-ding-jin-liu-fu-kuan-fang-shi.md)



## <mark style="color:blue;">物流</mark>

### <mark style="color:purple;">啟用物流</mark>

從後台 / woocommerce / 好用版擴充設定，[設定物流](https://www.notion.so/868317ca76a74bce971b6ca3576a3f6d?pvs=21)

### <mark style="color:purple;">設定串接資料</mark>

1. 登入[PAYNOW物流](https://logistic.paynow.com.tw/)後台 >分店管理 > 修改&#x20;

找到串接資料〔使用者帳號、API密碼〕

<figure><img src="../.gitbook/assets/image (131).png" alt=""><figcaption></figcaption></figure>

2. 從後台 / woocommerce / 物流設定，找到立吉付，輸入串接資料〔使用者帳號、API密碼〕

💡API密碼需為8或16碼

### <mark style="color:purple;">**設定PAYNOW回傳路徑**</mark>

至 [PAYNOW物流](https://logistic.paynow.com.tw/)後台 > 分店管理 > 修改 >分店物流服務設定，設定**店號網址**與**貨態回傳網址**

https://[_yoursite.com_](http://yoursite.com)/wc-api/paynow\_shipping\_order\_callback

💡將 yoursite.com 替換成您的網址

<figure><img src="../.gitbook/assets/image (132).png" alt=""><figcaption></figcaption></figure>

儲存後 輸入框格將會自動清空，此為正常現象

<figure><img src="../.gitbook/assets/image (133).png" alt=""><figcaption></figcaption></figure>

### <mark style="color:purple;">**啟用運送方式**</mark>

從後台 / woocommerce / 付款，打開需要的運送方式

### <mark style="color:purple;">電子發票</mark>

#### 啟用電子發票

從後台 / woocommerce / 好用版擴充設定，啟用 Paynow 立吉付電子發票

### <mark style="color:purple;">設定串接資料</mark>

從後台 / woocommerce / 電子發票設定，找到立吉付，輸入串接資料〔商家帳號、商家密碼〕

* 商家帳號：電子發票後台的帳號
* 商家密碼：電子發票後台的密碼
