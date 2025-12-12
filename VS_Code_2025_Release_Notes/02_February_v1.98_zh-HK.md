# VS Code 2025年2月更新 (版本 1.98)

## 📅 發佈日期
2025年2月

---

## 🌟 主要功能摘要

| 類別 | 功能名稱 | 說明 |
|------|----------|------|
| **GitHub Copilot** | Agent 模式改進 | 代理可以自動搜索工作區、編輯檔案、執行終端命令 |
| **GitHub Copilot** | 筆記本支援 | Copilot Edits 支援編輯 Jupyter 筆記本 |
| **GitHub Copilot** | Copilot Vision | 附加同互動圖片喺 Chat 提示中 |
| **GitHub Copilot** | 自訂指令正式版 | `.github/copilot-instructions.md` 功能正式推出 |
| **GitHub Copilot** | 模型選擇 | GPT 4.5 同 Claude 3.7 Sonnet 現已可用 |
| **工作區** | Linux 自訂標題欄 | Linux 預設啟用自訂標題欄 |
| **工作區** | 次要側欄標籤 | 次要側欄顯示標籤而唔係圖標 |
| **終端機** | IntelliSense 預覽 | 大幅改進終端機自動完成功能 |
| **源碼控制** | 診斷提交掛鉤 | 有未解決診斷時提示用戶 |

---

## 📝 詳細功能列表

### GitHub Copilot

| 功能 | 描述 | 設定 |
|------|------|------|
| Agent 模式改進 | 終端命令行內顯示、可編輯命令、Ctrl+Enter 確認 | `chat.agent.enabled` |
| 筆記本 Copilot Edits | 支援編輯筆記本、建立新筆記本、修改儲存格 | VS Code Insiders |
| 精緻編輯器整合 | 應用變更時唔再滾動、重命名操作為「保留」同「復原」 | - |
| 刷新 UI | 附件同修改檔案嘅新用戶體驗 | - |
| 移除限制 | 移除 10 個檔案附件限制同客戶端速率限制 | - |
| 自訂指令正式版 | 使用 `.github/copilot-instructions.md` 自訂 Copilot | `github.copilot.chat.codeGeneration.useInstructionFiles` |
| 更流暢認證流程 | 喺 Chat 中顯示認證確認而唔係模態對話框 | - |
| 進階代碼庫搜索 | `#codebase` 可以執行文字搜索、檔案搜索等工具 | `github.copilot.chat.codesearch.enabled` |
| 附加問題作為上下文 | 將問題面板嘅項目附加到 Chat | `#problems` |
| 附加資料夾作為上下文 | 使用 `#folder:` 附加資料夾 | - |
| NES 摺疊模式 | 只顯示指示器，按 Tab 顯示建議 | `editor.inlineSuggest.edits.showCollapsed` |
| 更改完成模型 | 為行內建議選擇不同模型 | - |
| GPT 4.5 (Preview) | OpenAI 最新 GPT-4.5 模型 | Enterprise 用戶 |
| Claude 3.7 Sonnet | 支援思考同非思考模式 | 付費 Copilot 計劃 |
| Copilot Vision | 附加圖片到 Chat 提示 | GPT 4o 模型 |
| Copilot 狀態概覽 | 狀態欄顯示 Copilot 狀態同設定 | `chat.experimental.statusIndicator.enabled` |
| TypeScript 上下文 | 增強 TypeScript 行內完成上下文 | `chat.languageContext.typescript.enabled` |
| PR 標題描述自訂指令 | 為 PR 標題同描述生成提供自訂指令 | `github.copilot.chat.pullRequestDescriptionGeneration.instructions` |

### 無障礙功能

| 功能 | 描述 |
|------|------|
| Copilot Edits 無障礙 | 修改檔案音效、無障礙差異檢視器 |
| activeEditorState 視窗標題變數 | 喺標題中顯示編輯器狀態 |

### 工作區

| 功能 | 描述 | 設定 |
|------|------|------|
| Linux 自訂標題欄 | 預設啟用自訂標題欄 | `window.titleBarStyle` |
| 次要側欄標籤 | 顯示標籤而唔係圖標 | `workbench.secondarySideBar.showLabels` |
| 設定編輯器鍵匹配算法 | 新嘅加權鍵搜索 | `workbench.settings.useWeightedKeySearch` |
| 隱藏點檔案選項 | 喺簡單檔案選擇器中隱藏點檔案 | - |

### 編輯器

| 功能 | 描述 |
|------|------|
| Peek 引用拖放 | 可以從 Peek 視圖拖放項目開啟為獨立編輯器 |
| 出現高亮延遲 | 預設設為 0 | `editor.occurrencesHighlightDelay` |

### 源碼控制

| 功能 | 描述 | 設定 |
|------|------|------|
| 更新視圖標題 | 「Repositories」、「Changes」、「Graph」 | - |
| 丟棄未追蹤變更改進 | 丟棄未追蹤檔案時移到垃圾桶 | `git.discardUntrackedChangesToTrash` |
| 診斷提交掛鉤 | 有未解決診斷時提示 | `git.diagnosticsCommitHook.Enabled` |

### 筆記本

| 功能 | 描述 | 設定 |
|------|------|------|
| 行內差異視圖 | 支援筆記本行內差異視圖 | `notebook.diff.experimental.toggleInline` |
| 行內數值懸停 | 截斷裝飾嘅豐富懸停 | - |

### 終端機 IntelliSense (預覽)

| 功能 | 描述 | 設定 |
|------|------|------|
| 增強 Fig 完成支援 | 支援更多 CLI 工具嘅智能完成 | `terminal.integrated.suggest.enabled` |
| 可設定快速建議 | 控制何時顯示快速建議 | `terminal.integrated.suggest.quickSuggestions` |
| 行內建議偵測 | 偵測 shell 行內建議 | `terminal.integrated.suggest.inlineSuggestion` |
| 詳細命令完成 | bash、zsh、PowerShell 命令詳細資訊 | - |
| CDPATH 支援 | 支援 $CDPATH 環境變數 | `terminal.integrated.suggest.cdPath` |
| 別名支援 | 偵測 bash、zsh、fish 別名 | - |

### 語言

| 功能 | 描述 |
|------|------|
| TypeScript 5.8 | 包含 TypeScript 5.8.2 |

### Python

| 功能 | 描述 |
|------|------|
| 自動引號插入 | 斷開長字串時自動插入引號 |
| Pylance 記憶體優化 | 改進記憶體消耗 |
| Shell 整合改進 | 修改設定後唔需要重載 |
| 自動測試發現模式 | 指定檔案模式進行測試發現 |

---

## 🔧 重要設定

```json
{
  "chat.agent.enabled": true,
  "github.copilot.chat.codeGeneration.useInstructionFiles": true,
  "terminal.integrated.suggest.enabled": true,
  "git.discardUntrackedChangesToTrash": true,
  "window.titleBarStyle": "custom"
}
```

---

## 📚 參考連結

- [官方發佈說明](https://code.visualstudio.com/updates/v1_98)
- [Agent 模式文檔](https://code.visualstudio.com/docs/copilot/chat/copilot-edits#_use-agent-mode-preview)
