# 台灣近海魚種分析系統

本儲存庫用於部署台灣近海魚種分析系統。

## GitHub Pages
網站由 GitHub Actions 部署。靜態網站包含魚種圖鑑、搜尋、形態比對、瀏覽器本機紀錄、CSV/JSON 匯入匯出及 PWA 離線快取。

AI 照片辨識需要獨立後端；GitHub Pages 不會執行 `api/*.js`。請勿將 API 金鑰提交至公開儲存庫。

部署網站來源封裝檔：`site-source.zip`。
