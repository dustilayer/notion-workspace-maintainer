[English](README.md) · [中文简介](README.zh-CN.md) · [繁體中文](README.zh-TW.md)

# Notion Workspace Maintainer

幫助助手維護 Notion 頁面、數據庫視圖和佈局的 Skill。這是操作說明，不是獨立運行的網站或程序。

## 第一次使用

從 [SKILL.md](SKILL.md) 開始。無需 npm 或構建；所需連接器由使用這個 Skill 的助手提供。

下載倉庫，把 SKILL.md、agents 和 references 保持在同一技能目錄中，再由支持 Skill 的助手加載。連接 Notion 後，先給出一個具體頁面和小任務，檢查結果再擴大範圍。公開版本不含私人工作區映射。源碼文件是最新編輯入口；倉庫 ZIP 是歷史打包快照，使用前核對版本。

## 讀代碼或修改時看哪裡

| 文件 | 作用 |
|---|---|
| `SKILL.md` | 完整操作規則 |
| `references/reliable-editing.md` | 可靠編輯和驗證步驟 |
| `references/page-design.md` | 佈局與視圖選擇 |

## 詳細參考

[原有說明](README.original.md) 保留歷史細節和來源署名，語言保持原樣。部分描述屬於舊版本；有差異時以當前源碼和本入口說明為準。
