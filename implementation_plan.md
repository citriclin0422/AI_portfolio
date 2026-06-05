# 佈署個人作品集網頁至 GitHub Pages 計劃

這個計畫的目標是協助您建立一個美觀、具備現代感（如深色模式風格、平滑動畫與微互動）的個人作品集網頁，並將其佈署到 GitHub Pages 上，讓其他人可以透過網址瀏覽。

## Proposed Changes

我們將在您的工作資料夾 `c:\AI_class\HW2_personinfo` 中建立以下網站基礎檔案：

### 網站前端架構

#### [NEW] index.html
建立網站的主要結構，包含：
- **導覽列 (Navbar)**：方便頁面跳轉。
- **首頁介紹區 (Hero Section)**：包含您的名字、職業/專長以及引人注目的標語。
- **關於我 (About Me)**：簡介您的背景與技能。
- **作品集區塊 (Projects)**：展示您過去的作品。
- **聯絡方式 (Contact)**：您的信箱或社群連結。

#### [NEW] styles.css
不使用外部框架，純手工撰寫高品質的 CSS，包含：
- 現代化的深色主題 (Dark Theme) 與高對比文字。
- 順暢的頁面捲動與元件懸停 (Hover) 動畫。
- 響應式設計 (RWD)，確保在手機和電腦上都看起來很完美。

#### [NEW] script.js
加入一些基礎的互動邏輯，例如：
- 導覽列捲動特效。
- 簡單的進入畫面動畫。

### Git 佈署流程

撰寫完程式碼後，我們將執行以下指令將其推送到您的 GitHub 儲存庫 `citriclin0422/L2-DIC1-github`：
1. `git init` 初始化本地儲存庫。
2. `git add .` 與 `git commit` 提交檔案。
3. `git branch -M main` 設定主要分支。
4. `git remote add origin https://github.com/citriclin0422/L2-DIC1-github.git` 連接您的 GitHub 儲存庫。
5. `git push -u origin main` 推送程式碼。

## User Review Required

> [!IMPORTANT]
> - 請問您希望在作品集中放入哪些**具體的個人資訊**？（例如：您的名字、專長職稱、想展示的 1~2 個專案名稱等）。如果您還沒有準備好，我可以先幫您填入精美的佔位符 (Placeholder)，之後您可以再自行修改。
> - 在程式碼推送到 GitHub 後，您需要手動在 GitHub 網站的 **Settings > Pages** 中，將來源 (Source) 設定為 `main` 分支，即可完成發佈。

## Verification Plan

### Manual Verification
- 在本地端開啟 `index.html`，確認網頁設計是否符合「令人驚豔」的高質感標準。
- 確認終端機 Git 指令成功推送到遠端儲存庫。
- 待您在 GitHub 上設定好 Pages 後，確認網頁可公開存取。
