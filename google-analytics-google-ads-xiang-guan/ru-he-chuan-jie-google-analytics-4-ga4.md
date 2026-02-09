---
icon: magnifying-glass-chart
---

# 如何串接Google Analytics 4 (GA4)

如果還沒有GA帳號，先到這註冊 [https://analytics.google.com/](https://analytics.google.com/)

照著他的指示，建立一個資源

點擊左下角的齒輪，進入 管理

然後點擊 資料串流

<figure><img src="../.gitbook/assets/image (74).png" alt=""><figcaption></figcaption></figure>

點擊 新增串流 / 網站

<figure><img src="../.gitbook/assets/image (75).png" alt=""><figcaption></figcaption></figure>

填寫你的網址、網站名稱，按建立並繼續

<figure><img src="../.gitbook/assets/image (76).png" alt=""><figcaption></figcaption></figure>

就會出現在這個列表，點下去

<figure><img src="../.gitbook/assets/image (77).png" alt=""><figcaption></figcaption></figure>

找到「評估ID」，複製下來

<figure><img src="../.gitbook/assets/image (78).png" alt=""><figcaption></figcaption></figure>

回到網站，後台左側尋找Pixel Cat外掛，點擊Add Pixel

<figure><img src="../.gitbook/assets/image (79).png" alt=""><figcaption></figcaption></figure>

Type of Pixel選擇 GA4，並在Property ID輸入剛剛複製的評估ID

<figure><img src="../.gitbook/assets/image (80).png" alt=""><figcaption></figcaption></figure>

再來如果網站有裝WooCommerce購物車，要到Pixel Cat左側的 E-commerce

把這個選項開啟到 ON

<figure><img src="../.gitbook/assets/image (81).png" alt=""><figcaption></figcaption></figure>

這樣就完成串接囉
