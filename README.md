# 2026 AI 產業生態與供應鏈矩陣 🌐

這是一個基於純原生網頁技術（Vanilla Web Technologies）打造的互動式資料視覺化面板。旨在清晰、直覺地展示全球七大科技巨頭（Magnificent 7）的 AI 軟硬體需求，並將其向下對應至台灣股市（台股）的關鍵受惠產業鏈與代表性企業。

## ✨ 核心特色 (Features)

* 100% 純原生開發：無需安裝 Node.js、NPM 或任何前端框架（如 React/Vue）。零依賴，極致輕量。
* 動態互動連動 (Interactive Hover Matrix)：
    * 當游標懸停於上方科技巨頭（如 OpenAI、NVIDIA）時，會自動高亮其依賴的底層硬體管線（算力、記憶體、儲存）。
    * 當游標懸停於下方供應鏈管線（如 Storage Layer）時，會反向高亮受惠於此技術區塊的科技巨頭。
    * 非相關區塊會自動觸發暗化（Dimmed）效果，視覺焦點明確。
* 深色科技感 UI (Cyberpunk / Neon UI)：採用暗黑背景（Dark Mode）搭配高對比度的霓虹色彩（Neon Blue, Green, Purple, Gold），完美契合 AI 與硬體科技主題。
* 流暢的轉場動畫：精心調校的 `cubic-bezier` 過渡效果與光暈陰影（Box Shadow），提升操作手感與質感。
* 自適應無滾動條設計：嚴格控制畫面溢出，確保在主流桌面解析度下能一屏完美展示（100% 視窗高度適配）。

## 🏗️ 架構與資料對應 (Data Mapping)

本圖表將 AI 產業鏈分為三大核心層級：

1.  頂層：需求驅動端 (The Magnificent 7)
    * 涵蓋：OpenAI, Google, Microsoft, Amazon, Meta, Apple, NVIDIA
    * 標示其軟體生態（如 RAG, Gemini, Copilot）與硬體需求。
2.  中層：全球核心技術管線 (Global Tech Pipeline)
    * Compute Layer (算力與網路層)：GPU, AI Server, 網通設備 (綠色視覺)
    * Memory Layer (高頻寬內存層)：HBM, DRAM (紫色視覺)
    * Storage Layer (向量儲存與檢索層)：SSD, RAG Vector DB (金色視覺)
3.  底層：台股受惠產業鏈 (Taiwan Supply Chain)
    * 將中層技術精準對應至台灣上市櫃公司（如：廣達、緯創、智邦、南亞科、群聯等）。

## 🚀 快速開始 (Getting Started)

本專案隨插即用，沒有任何繁瑣的環境建置步驟。

1. 將原始碼保存為 `index.html`。
2. 使用任何現代瀏覽器（Google Chrome, Microsoft Edge, Safari, Firefox）雙擊打開該檔案即可運行。

## 🛠️ 技術棧 (Tech Stack)

* HTML5: 語意化結構與自訂資料屬性 (`data-links`, `data-target`) 驅動互動邏輯。
* CSS3: CSS Grid 排版、CSS 變數 (`:root`) 主題管理、豐富的虛擬元素 (`::before`) 與漸層背景。
* JavaScript (ES6+): 原生 DOM 操作與事件監聽 (`mouseenter`, `mouseleave`)，實現雙向矩陣聯動過濾。

## 📝 授權條款 (License)

This project is open-source and available under the [MIT License](LICENSE). 歡迎自由修改、擴充資料庫或應用於個人投資研究簡報。
