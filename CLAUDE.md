# hbox-system 工作規則

## 使用者
- 行業：房仲（台灣）
- 溝通：用繁體中文，回覆只講重點，盡量減少字數。

## 授權
- 已授權自動執行所有任務，不需逐項確認。
- 例外：**方案要修改時，一定要先問我**，我同意才改。

## 資料夾結構（本機 `C:\Users\user\hbox-system`，大環境，本身不是 repo）
- `hbox-data/`：公開，可公開內容、追蹤台連結 → GitHub 公開 repo `hbox-data`
- `hbox-system-private/`：私人，客戶資料、機密設定 → GitHub 私人 repo `hbox-system-private`
- 其他部分放在 `hbox-system/` 下，另建資料夾。

## 工作流程
1. 所有任務、修改、工作相關資料，都存在 `hbox-system` 資料夾內。
2. 完成後 commit 並推上 GitHub（帳號 `gary19940110`）。
3. 私人資料只能進 `hbox-system-private`，**絕不可推到公開 repo**。推送前檢查路徑。
4. commit 訊息簡短，說明改了什麼。
5. `CLAUDE.md` 的備份副本放在 `hbox-data/CLAUDE.md`，修改時兩處同步。
