# VS Code 2025年5月更新 (版本 1.101)

## 📅 發佈日期
2025年5月（6月12日發佈）

---

## 🌟 主要功能摘要

| 類別 | 功能名稱 | 說明 |
|------|----------|------|
| **MCP** | Prompts 支援 | MCP 伺服器可以定義可重用嘅提示片段 |
| **MCP** | Resources 支援 | MCP 伺服器可以返回資源 |
| **MCP** | Sampling 支援 | MCP 伺服器可以向模型發出請求 |
| **MCP** | Auth 支援 | 支援需要認證嘅 MCP 伺服器 |
| **MCP** | 開發模式 | 支援 MCP 伺服器除錯同監視 |
| **Chat** | 工具集 | 將相關工具分組為工具集 |
| **Chat** | 自訂 Chat 模式 | 定義自己嘅 Chat 模式 |
| **源碼控制** | Copilot Coding Agent 整合 | 喺 VS Code 中分配同追蹤 Copilot Agent 任務 |

---

## 📝 詳細功能列表

### MCP (Model Context Protocol)

| 功能 | 描述 | 用法 |
|------|------|------|
| Prompts 支援 | MCP 伺服器定義嘅可重用提示 | `/mcp.servername.promptname` |
| Resources 支援 | 附加、保存、瀏覽 MCP 資源 | Add Context > MCP Resources |
| Sampling 支援 (實驗性) | MCP 伺服器可以向模型發出請求 | - |
| Auth 支援 | 支援 2025-3-26 規範同草案規範認證 | - |
| 開發模式 | 監視檔案變更重啟伺服器、除錯支援 | `dev.watch`、`dev.debug` |
| 擴充功能 API | 擴充功能可以發布 MCP 伺服器集合 | - |

### Chat - 工具集

| 功能 | 描述 | 用法 |
|------|------|------|
| 定義工具集 | 通過 API 或 UI 定義工具集合 | Configure Tool Sets 命令 |
| 使用工具集 | 用 `#` 引用或從工具選擇器選擇 | `#gh-news` |
| 圖標同描述 | 為工具集設定圖標同描述 | JSON 設定 |

### Chat - 自訂 Chat 模式 (預覽)

| 功能 | 描述 | 設定 |
|------|------|------|
| 定義自訂模式 | 建立 `*.chatprompt.md` 檔案定義模式 | Chat: Configure Chat Modes |
| 模式指令 | 為 LLM 提供具體指引 | Markdown 內容 |
| 可用工具 | 指定模式中可用嘅工具 | `tools` 標頭 |

### Chat - UI 改進

| 功能 | 描述 |
|------|------|
| 用戶訊息樣式 | 用戶訊息更易區分 |
| 復原請求 | 懸停選擇 X 復原請求 |
| 更高效應用編輯 | 根據檔案大小選擇重寫或小編輯策略 |
| 隱式上下文 | 當前檔案作為建議上下文項目 |
| 修復任務設定錯誤 | 任務設定錯誤時提供 Fix with Copilot 操作 |
| 任務診斷感知 | Agent 知道問題匹配器識別嘅錯誤 |
| 終端 cwd 上下文 | Agent 知道終端當前工作目錄 |
| 浮動視窗改進 | Chat 浮動視窗新增 Dock 同 New Chat 操作 |
| Fetch 工具確認 | 提示潛在 prompt injection 警告 |
| 自訂更多內建工具 | 可以啟用/禁用所有內建工具 |

### Chat - 對齊快捷鍵

| 操作 | 快捷鍵 |
|------|--------|
| Keep 單個變更 | Ctrl+Y |
| Undo 單個變更 | Ctrl+N |
| Keep 所有變更 | Ctrl+Shift+Y |
| Undo 所有變更 | Ctrl+Shift+N |

### 無障礙功能

| 功能 | 描述 | 設定 |
|------|------|------|
| 需要用戶操作音效 | Chat 需要用戶操作時嘅音效 | `accessibility.signals.chatUserActionRequired` |
| 新代碼操作音效 | 觸發同應用代碼操作嘅音效 | `accessibility.signals.codeActionTriggered` |
| Agent 模式改進 | 確認對話框包含豐富資訊 | - |

### 編輯器體驗

| 功能 | 描述 | 設定 |
|------|------|------|
| 輸入時尋找 | 控制尋找控制項是否輸入時搜索 | `editor.find.findOnType` |
| 自訂選單樣式 | 選擇 native、custom 或 inherit | `window.menuStyle` |
| Linux 原生視窗上下文選單 | 右鍵應用圖標顯示原生選單 | - |
| Process Explorer 網頁支援 | 連接到遠端時支援 | - |
| Windows Shell 環境發現 | 繼承 PowerShell 設定檔環境 | - |
| 未發布擴充功能警告 | 已安裝擴充功能唔再喺 Marketplace 可用時顯示警告 | - |
| 設定搜索建議 | AI 搜索尋找語義相似結果 | `workbench.settings.showAISearchToggle` |
| 搜索關鍵字建議 | 性能提升 ~5 倍 | `search.searchView.keywordSuggestions` |
| 語義搜索行為 | 控制何時觸發語義搜索 | `search.searchView.semanticSearchBehavior` |
| Edit Context | 預設啟用 EditContext API | `editor.editContext` |

### 代碼編輯

| 功能 | 描述 | 設定 |
|------|------|------|
| NES 匯入建議 | Python 檔案支援、改進準確性 | `github.copilot.nextEditSuggestions.fixes` |
| NES 接受流程 | 改進鍵盤導航 | - |

### 筆記本

| 功能 | 描述 | 設定 |
|------|------|------|
| 跟隨模式 | 自動滾動到 Agent 執行嘅儲存格 | `github.copilot.chat.notebook.followCellExecution.enabled` |
| 設定筆記本工具 | 確保 Kernel 已選擇並準備好 | - |
| 長時間運行工作流 | 摘要工具保持 Agent 上下文準確 | - |
| 運行確認儲存格預覽 | 顯示儲存格代碼片段 | - |

### 源碼控制

| 功能 | 描述 |
|------|------|
| Copilot Coding Agent 整合 | 分配 PR/Issue 俾 Copilot、Copilot on My Behalf 查詢、查看 Agent 狀態 |
| 歷史項目詳情 | 選擇 Graph 項目顯示資源 |
| 添加歷史項目到 Chat 上下文 | 將提交或 PR 作為 Chat 上下文 |

### 任務

| 功能 | 描述 |
|------|------|
| 實例策略 | `instancePolicy` 屬性控制達到 `instanceLimit` 時嘅行為 |

### 終端機

| 功能 | 描述 | 設定 |
|------|------|------|
| 語言伺服器終端建議 | Python REPL 會話中嘅語言完成 | `terminal.integrated.suggest.enabled` + Pylance 設定 |

### Python

| 功能 | 描述 |
|------|------|
| Python Chat 工具 | 獲取環境資訊、安裝包、設定環境工具 |
| 從模板建立專案 | 建立 Python 包或腳本 |
| PyEnv 同 Poetry 支援 | 環境同包管理支援 |

### 擴充功能開發

| 功能 | 描述 |
|------|------|
| MCP 擴充功能 API | 擴充功能可以發布 MCP 伺服器集合 |
| 打包時密鑰掃描 | VSCE 掃描潛在密鑰 |
| 網頁環境偵測 | Node.js 更新到 v22，支援 navigator 全局對象 |

### 工程

| 功能 | 描述 |
|------|------|
| Electron 35 更新 | Chromium 134、Node.js 22.15.1 |
| 真實擴充功能採用 ESM | GitHub Issue Notebooks 採用 ESM |

---

## 🔧 重要設定

```json
{
  "github.copilot.chat.notebook.followCellExecution.enabled": true,
  "search.searchView.keywordSuggestions": true,
  "search.searchView.semanticSearchBehavior": "auto",
  "editor.find.findOnType": true
}
```

---

## 📚 參考連結

- [官方發佈說明](https://code.visualstudio.com/updates/v1_101)
- [MCP 擴充功能開發指南](https://code.visualstudio.com/api/extension-guides/mcp)
- [工具集文檔](https://code.visualstudio.com/docs/copilot/chat/chat-agent-mode#_define-tool-sets)
