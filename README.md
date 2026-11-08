# LLM Wiki｜生物實驗科普

本專案為靜態網站，包含三篇已發布的簡報式生物實驗介紹。

## 已發布文章
1. Western blotting（西方墨點法）
2. RT-qPCR（定量反轉錄即時 PCR）
3. MTT assay（MTT 細胞活性分析）

## 本機預覽
建議使用 VS Code Live Server，或在專案資料夾啟動簡易本機伺服器後開啟 `index.html`。

## 專案結構
- `index.html`：網站首頁與投影片閱讀介面
- `agent.md`：AI Agent 工作規則
- `wiki/index.json`：分類、文章卡片資訊與搜尋關鍵字
- `wiki/*.md`：三篇簡報式文章內容
- `wiki/source-records.json`：來源對應與發布紀錄（不顯示於投影片）
- `versions/v1-draft/`：發布前第一版草稿備份
- `asset/`：圖片素材資料夾

## 來源
本批內容依使用者授權，使用 `wiki/source-records.json` 列出的維基百科頁面整理。維基百科條目可能更新，使用時宜回到來源頁面核對。

## 限制
這是一個靜態網站，不包含登入、私人審核區或真正的 AI Agent 執行環境。GitHub Pages 不會執行 AI Agent，也不能安全保存 API 金鑰。


## 單檔 HTML 版本（v3）

三篇已發布文章（Western blotting、RT-qPCR、MTT assay）的標題、分類、關鍵字及完整投影片文字，現在都直接內嵌於 `index.html`。首頁不再需要讀取 `wiki/index.json` 或 Markdown 檔案，因此只要開啟 `index.html` 即可閱讀三篇文章；`wiki/` 內的原始 Markdown 與來源紀錄仍保留作為編輯與版本管理備份。
