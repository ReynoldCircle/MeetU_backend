# MeetU: 聚會交友平台_管理員後臺

### 使用者前台
[MeetU](https://github.com/HollaWord/SpringBoot-Vue3-MSSQL-WebSocket.git)

### 專案目的
我們是一群剛開始學習程式設計的學生，這個專案是我們的期末專題。**MeetU管理後台** 讓網站管理者可以更便利的進行管理。

### 專案成員
[Emerald](https://github.com/HollaWord) , [Benson](https://github.com/chengyu9072) , [Noel](https://github.com/Noelyan1995), [Jayson](https://github.com/jaysonyang503) , [ReynoldYuan](https://github.com/ReynoldCircle)

**MeetU管理後台** 包含以下功能：
- **所有會員帳號管理**
- **所有系統通知列表查看、編輯與刪除**
- **對被檢舉之用戶、活動、評論進行審核**

### 技術堆疊
- **後端**: Spring Boot
- **前端**: Vue 3
- **資料庫**: Microsoft SQL Server (MSSQL)

# 細節請參閱我們的 MeetU.pptx 和展示影片
因PPT包含影片檔造成檔案較大，請直接於下方網址查看：</br>
https://1drv.ms/p/s!Ark_lrwm9EcYgbFvUlWK7K1gZgVTtw?e=LRsKnx

### 安裝說明
按照以下步驟設置並運行此專案：

1. **更新 MSSQL 配置**：
   在 `application.properties` 文件中，修改 MSSQL 的連接配置，包括port、用戶名和密碼。

2. **創建資料庫結構**：
   在 MSSQL 中執行 `data.sql` 腳本，以建立必要的資料表和結構。</br>
   或者可直接使用 `MeetU.bak` 建立預設資料 (請注意,部分圖片可能無法正常顯示，建議直接透過網頁前台做修改)

3. **安裝依賴包**：
   在專案根目錄下運行以下命令以安裝必要的依賴包：
   ```bash
   npm install

4. **啟動開發伺服器**：
   依賴包安裝完成後，使用以下命令啟動開發伺服器：
   ```bash
   npm run dev

# 已知問題
由於時間限制，部分功能僅部分實現。<br>

