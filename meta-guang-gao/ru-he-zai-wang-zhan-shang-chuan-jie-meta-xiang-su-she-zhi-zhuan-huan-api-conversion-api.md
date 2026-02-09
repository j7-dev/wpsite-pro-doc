---
icon: objects-align-center-vertical
---

# 如何在網站上串接Meta像素 & 設置轉換API (Conversion API)

像素，後來Meta合併到 資料集 的裡面，現在的設定，都要到「資料集」



在 [Meta商家資產管理的後台](https://business.facebook.com/latest/settings/events_dataset) 點擊資料集，並點擊新增

<figure><img src="../.gitbook/assets/CleanShot 2025-03-03 at 22.43.28.jpg" alt=""><figcaption></figcaption></figure>



然後幫像素取個名稱，點擊建立

<figure><img src="../.gitbook/assets/CleanShot 2025-03-03 at 22.44.33.jpg" alt=""><figcaption></figcaption></figure>





點選剛剛建立的像素，找到右邊的點點，並點擊 在事件管理工具中開啟

<figure><img src="../.gitbook/assets/CleanShot 2025-03-03 at 22.44.56.jpg" alt=""><figcaption></figcaption></figure>





到了事件管理工具後，選擇剛剛建立的像素，並且把資料集編號記錄下來，待會會用到

然後點擊 設定

<figure><img src="../.gitbook/assets/CleanShot 2025-03-03 at 22.45.17.jpg" alt=""><figcaption></figcaption></figure>





在設定中，往下滑，找到「產生存取權杖」，它不是很顯眼，要努力找一下

<figure><img src="../.gitbook/assets/CleanShot 2025-03-03 at 22.47.12.jpg" alt=""><figcaption></figcaption></figure>





點擊藍色的區域，把權杖複製起來，待會會用到

<figure><img src="../.gitbook/assets/CleanShot 2025-03-03 at 22.47.29.jpg" alt=""><figcaption></figcaption></figure>





到你的網站後台，我們串接Meta像素使用的外掛叫做Pixel Cat\
如果你的網站沒有這個外掛，請聯絡架站小幫手處理

在Pixel Cat的設定裡面點擊 Add Pixel

<figure><img src="../.gitbook/assets/CleanShot 2025-03-03 at 22.58.37.jpg" alt=""><figcaption></figcaption></figure>





在這個視窗，Type of Pixel選擇 Facebook Conversions API

然後填入資料集編號(就是像素ID)，以及剛剛複製的權杖

點擊儲存

<figure><img src="../.gitbook/assets/CleanShot 2025-03-03 at 22.59.03.jpg" alt=""><figcaption></figcaption></figure>



這樣就串接成功了

你可以使用 Chrome瀏覽器的一個擴充 [Meta Pixel Helper](https://chromewebstore.google.com/detail/meta-pixel-helper/fdgfkebogiimcoedlicjlajpkdmockpc)，到網站前台看看像素有沒有安裝成功

如果像畫面這樣，就代表已經成功了

注意像素的數據不會那麼快顯示在Meta的後台，所以暫時在Meta後台沒看到數據是正常的，只要Meta Pixel Helper顯示有，就是有安裝成功喔



<figure><img src="../.gitbook/assets/CleanShot 2025-03-03 at 22.59.52.jpg" alt=""><figcaption></figcaption></figure>
