Window/Linux雙系統安裝
======

+ 準備一隻隨身碟，隨身碟資料先進行備份，因為隨身碟裡面必須是空的沒東西

+ 找一塊未使用Disk的空間來裝Ubuntu

### 創建硬碟空間

+ 首先在設定打開CMD，輸入diskmgmt.msc，會跑出以下畫面，選擇Ubuntu要裝設的槽，這邊用系統槽C為例，點選壓縮磁碟區

![markdown-viewer](image/1.png)

+ 接下來選擇要給Ubuntu安裝大小空間，1GB等於1024MB，這邊是用40GB給Ubuntu，因此打40960

![markdown-viewer](image/2.png)

### 將快速關機關閉

+ 若桌機可跳過這步，筆電需要進入控制台->控制台->硬體和音效->電源選項→(左手邊)按下電源按鈕時的行為->(小盾牌)變更目前無法使用的設定->開啟快速啟動 (建議選項)取消勾選->儲存變更

![markdown-viewer](image/3.png)

![markdown-viewer](image/4.png)


+ 若沒有關閉快速關機，每次使用者關機時，OS會將每次需要開機資料先存入Memory中，讓下次開機時OS不用到DISK內撈資料，以達成加速開機，而為了等等安裝Ubuntu可以進入BIOS，因此需要關閉

### 下載