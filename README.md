# AI Agents 入門 Wiki 與教學簡報

繁體中文初學者教材：Agent 定義、運作循環、工具、架構、評估與安全，另附互動式 HTML 簡報。

## 專案檔案
- `index.html`：網站入口
- `slides.html`：教學簡報（按鈕或鍵盤左右鍵切頁）
- `wiki/`：知識頁與引用來源
- `sources/`：來源索引、匯入和執行紀錄
- `AGENTS.md`、`workflow.md`：內容規則和 loop/graph 設計

## 上傳並發布
1. 在 GitHub 建立 **Public** Repository，將本資料夾內所有檔案上傳至 Repository 根目錄。
2. 開啟 **Settings → Pages**，選 **Deploy from a branch**、`main`、`/(root)`，按 **Save**。
3. 網站入口：`https://你的帳號.github.io/Repository名稱/`；簡報：網址後加 `slides.html`。

## LLM Wiki ingest
請將 `sources/sources.md` 的原始資料逐篇匯入課堂使用的 LLM Wiki 平台，至少五篇，並在 `sources/ingest-log.md` 記錄實際結果。倉庫 Wiki Markdown 是整理稿與來源索引，不能單獨證明外部平台已完成 ingest。完成後將分享連結填入 `wiki/README.md`。

提交前請補上平台連結、GitHub 網址、真實執行紀錄與製作截圖。