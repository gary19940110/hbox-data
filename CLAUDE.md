# hbox-system 工作規則

## 使用者
- 行業：房仲（台灣）
- 溝通：用繁體中文，回覆只講重點，盡量減少字數。

## 預設環境
- 所有對話預設在 `hbox-system` 環境開啟。
- 所有房地產相關工作（物件、客戶、帶看、斡旋、實登、社區分析等）一律在此環境執行。
- Remote Control 預設開啟（手機、電腦皆然）。

## 授權
- 已授權自動執行所有任務，不需逐項確認。
- 例外：**方案要修改時，一定要先問我**，我同意才改。

## 資料夾結構（本機 `C:\Users\user\hbox-system`，大環境，本身不是 repo）
- `hbox-data/`：公開，可公開內容、追蹤台連結 → GitHub 公開 repo `hbox-data`
- `hbox-system-private/`：私人，客戶資料、機密設定 → GitHub 私人 repo `hbox-system-private`
- `hbox-system-private/customer-tracker/`：客戶追蹤台（含客戶資料，僅限私人）
- `threads-bot/`：Threads 自動發文系統 → GitHub 公開 repo `threads-bot`（GitHub Actions 運作中，中控台 https://gary19940110.github.io/threads-bot/；專案自己的 `CLAUDE.md` 有詳細說明；機器人每小時自動 commit，改之前先 `git pull`）
- 其他部分放在 `hbox-system/` 下，另建資料夾。

## 工作流程
1. 所有任務、修改、工作相關資料，都存在 `hbox-system` 資料夾內。
2. 完成後 commit 並推上 GitHub（帳號 `gary19940110`）。
3. 私人資料只能進 `hbox-system-private`，**絕不可推到公開 repo**。推送前檢查路徑。
4. commit 訊息簡短，說明改了什麼。
5. 在 `hbox-system` 下新建資料夾時，自動建對應 GitHub repo 並推上去（預設私人，確定可公開才建公開），並更新上方資料夾結構。
6. `CLAUDE.md` 的備份副本放在 `hbox-data/CLAUDE.md`，修改時兩處同步。
