# AI 學習補給站｜AI Study Hub

一個以繁體中文整理生成式 AI、提示工程與 AI Agent 入門概念的響應式知識網站。專案重點不只是完成首頁，而是透過 `AGENTS.md` 建立可重複使用的 AI 協作規則，讓未來新增頁面時能延續相同的內容格式、視覺風格與檔案結構。

## 專案特色
- 原生 HTML、CSS、JavaScript，無需安裝套件或建置。
- 響應式版面，支援手機、平板與桌面。
- 首頁包含學習路線、知識卡與專案介紹。
- `AGENTS.md` 明確定義設計規範、內容格式、檔案命名、新增頁面流程與驗收清單。

## 專案結構
```text
ai-study-hub/
├── index.html
├── AGENTS.md
├── README.md
├── .nojekyll
└── assets/
    ├── style.css
    └── main.js
```

## 本機預覽
直接以瀏覽器開啟 `index.html` 即可。也可在 VS Code 使用 Live Server 預覽。

## 部署到 GitHub Pages
1. 在 GitHub 建立一個新的 **Public** repository，例如 `ai-study-hub`。
2. 將本專案所有檔案上傳至 repository 的 `main` 分支根目錄。
3. 開啟 repository 的 **Settings → Pages**。
4. 在 **Build and deployment** 選擇 **Deploy from a branch**。
5. Branch 選 `main`，資料夾選 `/(root)`，按下 Save。
6. 等待 GitHub Actions 部署完成，再由 Pages 頁面開啟網站。

預設網址格式：`https://你的GitHub帳號.github.io/ai-study-hub/`

## 如何用 AI 延伸專案
請先讓 AI 閱讀 `AGENTS.md`，再提出新增主題的需求。例如：

> 請先閱讀 AGENTS.md。依照本專案規則新增「RAG 是什麼？」知識頁，檔名為 `pages/rag-basics.html`。內容需包含定義、運作流程、初學者例子、實作提醒與參考資料，沿用共用 CSS，並在首頁新增入口。完成後依驗收清單檢查。

AI 便能依照已定義的內容結構、色彩、字體、命名與檢查流程擴充網站，而不必每次重新描述整個專案。

## 專案規則
完整規則請見 [`AGENTS.md`](AGENTS.md)。
