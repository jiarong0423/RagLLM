# RagLLM

這是一個靜態展示專案，已將你的 HTML 視覺頁面加入倉庫，並設定 GitHub Pages 自動部署工作流程。

## 專案內容

- `index.html`：主網站檔案，包含 2026 年七巨頭 LLM 戰略與 SSD 擴展架構的視覺化儀表板。
- `.github/workflows/pages.yml`：GitHub Actions 工作流程，用於在推送到 `main` 分支後自動部署 GitHub Pages。

## 使用方式

1. 將變更提交並推送到 `main`：
   ```bash
   git add index.html .github/workflows/pages.yml
   git commit -m "Add static site and GitHub Pages deployment"
   git push origin main
   ```
2. GitHub Pages 會在推送後自動部署，部署完成後即可透過以下網址存取（若你的 GitHub Pages 已啟用）：
   ```text
   https://jiarong0423.github.io/RagLLM/
   ```

## 備註

- 如果你想要更換頁面標題、內容或樣式，可直接編輯 `index.html`。
- 若需進一步設定自訂網域或 GitHub Pages 配置，可在倉庫的 `Settings > Pages` 中調整。
