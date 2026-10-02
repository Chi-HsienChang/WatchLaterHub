# WatchLaterHub 隱私權政策

最後更新：2026 年 10 月 2 日

WatchLaterHub（以下稱「本擴充功能」）是一個 Chrome 新分頁擴充功能。本政策說明本擴充功能會存取哪些資料、如何使用，以及不會做的事。

## 一、本擴充功能存取的資料

| 資料 | 用途 | 存放位置 |
|---|---|---|
| Google 帳號名稱、Email、大頭貼 | 在畫面上顯示目前登入的帳號 | 只存在你的瀏覽器（chrome.storage） |
| Google OAuth 存取權杖 | 呼叫 YouTube Data API | 只存在你的瀏覽器 |
| YouTube 按讚的影片與播放清單（`youtube.readonly`） | 在新分頁隨機顯示一部收藏影片 | 只存在你的瀏覽器 |
| 你手動加入的影片、TODO 待辦、計時器、設定 | 提供待辦、提醒、計時等功能 | 只存在你的瀏覽器 |
| Chrome 書籤 | 顯示、新增、編輯、排序書籤 | 由 Chrome 管理，本擴充功能不另外保存 |
| Chrome 瀏覽紀錄（最近 30 筆網址與標題） | 在「最近」面板列出近期瀏覽的網頁 | 只存在你的瀏覽器 |
| 位置（只在你按「使用目前位置」時） | 查詢當地天氣 | 只存在你的瀏覽器 |

## 二、資料傳送到哪裡

本擴充功能**沒有自己的伺服器**，不會把你的資料傳給開發者。只有在提供功能時，才會直接從你的瀏覽器連到下列服務：

- **Google（YouTube Data API、Google OAuth）**：登入，並以唯讀權限（`youtube.readonly`）讀取你的 YouTube 收藏。本擴充功能不會修改你的 YouTube 帳號內容。
- **Open-Meteo、BigDataCloud、OpenStreetMap Nominatim**：查詢天氣與地名。只會送出經緯度或你輸入的城市名稱，不包含任何身分資訊。
- **YouTube oEmbed / 縮圖、Google 網站圖示服務**：顯示影片標題、縮圖與網站圖示。

## 三、我們不會做的事

- 不出售、不出租、不轉讓你的資料給任何第三方
- 不把資料用於廣告、信用評估或與本擴充功能單一用途無關的目的
- 不追蹤你的瀏覽行為、不做分析統計
- 不存取你的 Gmail 或其他 Google 服務資料（只使用 YouTube 唯讀權限）

本擴充功能使用 Google API 取得的資料，遵守 [Google API 服務使用者資料政策](https://developers.google.com/terms/api-services-user-data-policy)，包括「有限使用」（Limited Use）規範。

## 四、刪除資料與撤銷授權

- 在「收藏」視窗按「登出」，會撤銷 Google 授權並刪除權杖
- 移除本擴充功能，會刪除它存在瀏覽器裡的所有資料
- 你也可以隨時到 [Google 帳戶權限頁面](https://myaccount.google.com/permissions) 撤銷授權

## 五、聯絡方式

有任何問題，請到 GitHub Issues 回報，或寄信至：salimachchang@gmail.com
