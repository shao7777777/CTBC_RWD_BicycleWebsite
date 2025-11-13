# RWD 應用實踐：自行車主題多頁面網站

專案說明 (Project Description)
--
本專案為一個**多頁面** (Multi-Page) 的自行車主題網站，旨在挑戰處理更為複雜的網頁結構與導航系統。核心目標是實現在多個頁面間一致且響應式的導航體驗，並利用 Bootstrap 的排版系統來建立穩定的 RWD 佈局。

核心技術與設計理念
--
1. 技術棧 (Tech Stack)
 - 語言： HTML5, CSS3, 基礎 JavaScript (用於漢堡選單互動)
 - 框架/佈局： Bootstrap 5 (排版與元件), RWD (Responsive Web Design), Flexbox/Grid 輔助佈局。

2. 設計理念 (Design Philosophy)
 - **多頁面一致性**： 確保網站的 Header/Footer 在所有子頁面中具備統一的 RWD 邏輯，並統一使用 Bootstrap 的 Grid System 進行佈局。
 - **導航優化**： 專注於將複雜的導覽列在手機版上優化為隱藏式漢堡選單，並確保其點擊區域與存取性。
 - **結構強化**： 程式碼結構清晰，實現邏輯分離，易於未來功能擴展。

專案架構 (Project Structure)
--
ˋˋˋ
/CTBC_RWD_BicycleWebsite
├── css/
│   ├── about.css
│   ├── bootstrap-grid.min.css # Bootstrap Grid System
│   ├── bootstrap-reboot.min.css # Bootstrap Reset
│   ├── contact.css
│   ├── guide.css
│   ├── news.css
│   ├── product.css
│   ├── share.css  # 共同樣式
│   └── style.css  # 核心樣式
├── img/           # 圖片資源
├── pages/
│   ├── about.html
│   ├── contact.html
│   ├── guide.html
│   ├── news.html
│   └── product.html
├── index.html     # 網站主頁面結構
├── main.js        # 漢堡選單等主要 JS 邏輯
└── README.md
ˋˋˋ

介面預覽 (Preview)
--
<img width="1024" height="798" alt="螢幕擷取畫面 2025-11-11 114024" src="https://github.com/user-attachments/assets/98ee18d2-f9ba-4c38-a863-a260933dbd94" />  
<img width="425" height="809" alt="螢幕擷取畫面 2025-11-11 114122" src="https://github.com/user-attachments/assets/adf09c0f-2aaf-491c-953a-866d8ca64e6e" />  

連結 (Links)
--
[GitHub Page] https://shao7777777.github.io/CTBC_RWD_BicycleWebsite/  

[GitHub Repository] https://github.com/shao7777777/CTBC_RWD_BicycleWebsite.git  
