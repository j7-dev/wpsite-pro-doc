---
icon: hammer
---

# 使用WP網站下Meta廣告，如何設置轉換事件

### <mark style="color:blue;">轉換的類型</mark>

常見的轉換類型有 結帳/填寫表單/點擊特定按鈕

其他輔助型的轉換，有在頁面上待超過N秒/捲動超過頁面的N%等

通過設置轉換事件，我們可以讓Meta知道我們想要優化的廣告目標是什麼，進而優化廣告成效

同時也可以針對目標受眾做分眾，例如針對有加入過購物車的受眾，對他們下再行銷的廣告

### <mark style="color:blue;">結帳&購物車相關的轉換事件</mark>

只要在Pixel Cat / Ecommerce 設定裡面，把這幾個打勾就可以，第一個是一定要打勾，後面兩個看狀況：

<figure><img src="../.gitbook/assets/CleanShot 2025-03-14 at 12.42.31 (1).jpg" alt=""><figcaption></figcaption></figure>



### <mark style="color:blue;">填寫表單的轉換事件</mark>

如果要讓成功填寫表單，成為一個轉換事件，建議的方法是創建一個「感謝頁」，讓用戶在填完表單後就跳轉去那個感謝頁，然後在感謝頁上設置轉換事件。



首先在Pixel Cat新增Facebook Event

<figure><img src="../.gitbook/assets/CleanShot 2025-03-14 at 12.51.51 (1).jpg" alt=""><figcaption></figcaption></figure>

Trigger選擇 Page Visit，然後指定某個感謝頁，這樣只要用戶跳轉到那個感謝頁時，就會觸發這個轉換事件了

<figure><img src="../.gitbook/assets/CleanShot 2025-03-14 at 12.51.42.jpg" alt=""><figcaption></figcaption></figure>



### <mark style="color:blue;">點擊特定按鈕的轉換事件</mark>

要在按鈕上觸發轉換事件，首先要在按鈕上加上CSS Class名稱，以Elementor為例，就是在這個按鈕的進階設定/CSS類別這邊，輸入你要的Class名稱，可自訂名稱，使用英文，不要有空格

<figure><img src="../.gitbook/assets/CleanShot 2025-03-14 at 12.57.18.jpg" alt=""><figcaption></figcaption></figure>



然後在Pixel Cat 新增Facebook Event，Trigger選擇 Click on Element

Css target 就輸入你的Class名稱，前面加上 .

Event 選擇 Custom Event 自訂事件

Event Name就是會在Meta那邊顯示的轉換事件名稱，建議用英文

<figure><img src="../.gitbook/assets/CleanShot 2025-03-14 at 12.56.30.jpg" alt=""><figcaption></figcaption></figure>

### <mark style="color:blue;">輔助類型的轉換事件</mark>

輔助類型的轉換，通常就是用來獲得更多資訊，比較不會是廣告優化的主要目標

也有一種做法是，針對目標受眾做分眾，例如對在頁面待超過10秒的受眾，下再行銷的廣告

#### <mark style="color:blue;">在頁面上待超過N秒的轉換事件</mark>

在Pixel Cat 新增Facebook Event，Trigger選擇Page Visit。其他設定如圖所示：

<figure><img src="../.gitbook/assets/CleanShot 2025-03-14 at 13.06.02.jpg" alt=""><figcaption></figcaption></figure>

#### <mark style="color:blue;">捲動超過頁面N%的轉換事件</mark>

在Pixel Cat 新增Facebook Event，Trigger選擇Page Visit。其他設定如圖所示：

<figure><img src="../.gitbook/assets/CleanShot 2025-03-14 at 13.06.28.jpg" alt=""><figcaption></figcaption></figure>



