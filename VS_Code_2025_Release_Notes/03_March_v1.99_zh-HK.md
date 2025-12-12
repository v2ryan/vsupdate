# VS Code 2025年3月更新 (版本 1.99)

## 📅 發佈日期
2025年3月

---

## 🌟 主要功能摘要

| 類別 | 功能名稱 | 說明 |
|------|----------|------|
| **Chat** | Agent 模式正式可用 | Agent 模式喺 VS Code Stable 正式推出 |
| **Chat** | MCP 伺服器支援 | 支援 Model Context Protocol (MCP) 伺服器 |
| **Chat** | 統一 Chat 視圖 | 合併 Chat 同 Copilot Edits 視圖 |
| **Chat** | BYOK (自帶密鑰) | 支援自帶 API 密鑰使用其他模型 |
| **代碼編輯** | NES 正式版 | Next Edit Suggestions 正式推出 |
| **代碼編輯** | 行內建議語法高亮 | 行內建議預設啟用語法高亮 |
| **筆記本** | AI 筆記本編輯 | 筆記本支援 Agent 模式同 Edit 模式 |
| **終端機** | Agent 模式可靠性 | 改進終端工具可靠性 |

---

## 📝 詳細功能列表

### Chat

| 功能 | 描述 | 設定 |
|------|------|------|
| Agent 模式正式可用 | 自動搜索工作區、編輯檔案、執行終端命令 | `chat.agent.enabled` |
| MCP 伺服器支援 | 整合 Model Context Protocol 伺服器工具 | `.vscode/mcp.json` |
| 統一 Chat 視圖 | Ask、Edit、Agent 三種模式喺單一視圖中切換 | - |
| BYOK (自帶密鑰) | 支援 Azure、Anthropic、Gemini、OpenAI、Ollama、Open Router | 模型選擇器 > Manage Models |
| 思考工具 (實驗性) | 俾任何模型喺工具調用之間思考嘅機會 | `github.copilot.chat.agent.thinkingTool` |
| Fetch 工具 | 喺提示中包含公開網頁內容 | `#fetch` |
| Usages 工具 | 查找函數、類、介面嘅引用同實現 | `#usages` |
| 建立新工作區 | 使用 Agent 模式搭建新工作區 | `github.copilot.chat.newWorkspaceCreation.enabled` |
| 擴充功能工具 | 支援擴充功能貢獻嘅語言模型工具 | - |
| 工具審批 | 可以記住工具審批決定 | `chat.tools.autoApprove` |
| 可重用提示檔案 | 改進 `.prompt.md` 檔案支援 | `chat.promptFilesLocations` |
| 改進視覺支援 | 支援從瀏覽器拖放圖片 | GPT-4o |

### Agent 模式工具

| 工具 | 描述 |
|------|------|
| 思考工具 | 俾模型喺工具調用之間思考 |
| Fetch 工具 | 獲取公開網頁內容 |
| Usages 工具 | 查找引用、實現、定義 |

### 配置編輯器

| 功能 | 描述 | 設定 |
|------|------|------|
| 統一 Chat 體驗 | Ask、Edit、Agent 模式喺單一視圖中 | - |
| 即時索引 | 自動建立遠端工作區索引 | - |
| Copilot 狀態選單 | 顯示工作區索引狀態、完成狀態等 | - |
| 開箱即用 Copilot 設定 | 首次發送請求時引導登入 | `chat.setupFromDialog` |
| 語義文字搜索改進 | 預設啟用 AI 語義搜索 | `github.copilot.chat.search.semanticTextResults` |
| 視窗控制設定 | 自訂視窗控制樣式 | `window.controlsStyle` |

### 代碼編輯

| 功能 | 描述 | 設定 |
|------|------|------|
| NES 正式版 | Next Edit Suggestions 正式推出 | `github.copilot.nextEditSuggestions.enabled` |
| AI 編輯改進 | 編輯時靜音診斷事件、明確保存檔案 | - |
| 工具式編輯模式 | Edit 模式使用同 Agent 模式相同嘅工具方法 | `chat.edits2.enabled` |
| 行內建議語法高亮 | 預設啟用 ghost text 語法高亮 | `editor.inlineSuggest.syntaxHighlightingEnabled` |
| Tree-Sitter 語法高亮 | CSS 同 TypeScript 正則表達式嘅 Tree-Sitter 高亮 | `editor.experimental.preferTreeSitter.css` |

### 筆記本

| 功能 | 描述 | 設定 |
|------|------|------|
| AI 筆記本編輯 | 支援 Agent 模式同 Edit 模式編輯筆記本 | - |
| 新筆記本工具 | 從 Chat 直接建立新筆記本 | `/newNotebook` |
| 導航 AI 編輯 | 使用差異工具欄遍歷儲存格編輯 | - |
| 復原 AI 編輯 | 復原命令回滾整個筆記本級別嘅變更 | - |
| 輸出支援 | 將儲存格輸出（文字、錯誤、圖片）添加到 Chat | - |
| nbformat 版本 4.5 | 預設設定儲存格 ID 以改進差異計算 | - |

### 無障礙功能

| 功能 | 描述 |
|------|------|
| Agent 模式改進 | 需要手動操作時通知用戶、新嘅無障礙幫助對話框 |
| 編輯操作音效 | 保留或復原 AI 編輯時嘅音效信號 |
| 改進 ARIA 標籤 | 建議控制項目更豐富嘅描述性資訊 |

### 源碼控制

| 功能 | 描述 | 設定 |
|------|------|------|
| 引用選擇器改進 | 顯示最後提交詳情、前後資訊 | `git.showReferenceDetails` |
| 倉庫狀態欄項目 | 多倉庫工作區顯示活動倉庫 | - |
| Git blame 編輯器裝飾改進 | 導航時才顯示「尚未提交」裝飾 | - |
| 提交輸入游標自訂 | 支援游標樣式同寬度設定 | - |

### 終端機

| 功能 | 描述 |
|------|------|
| Agent 模式可靠性 | 改進終端工具可靠性同兼容性 |
| 終端 IntelliSense 改進 | 增強 code CLI、自動刷新、魚 shell 完成等 |
| 簡化標籤懸停 | 新嘅簡化同詳細標籤懸停 |
| 簽名 PowerShell Shell 整合 | PowerShell 腳本已簽名 |
| 終端 Shell 類型 API | 擴充功能可以存取用戶當前 shell 類型 |

### Python

| 功能 | 描述 | 設定 |
|------|------|------|
| 可編輯安裝支援 | Pylance 支援 PEP 660 可編輯安裝 | `python.analysis.enableEditableInstalls` |
| 更快診斷體驗 | 改進 Pylance 診斷準確性同響應性 | `python.analysis.usePullDiagnostics` |
| 自訂 Node.js 參數 | 傳遞自訂參數到 Pylance Node.js | `python.analysis.nodeArguments` |

---

## 🔧 重要設定

```json
{
  "chat.agent.enabled": true,
  "github.copilot.nextEditSuggestions.enabled": true,
  "editor.inlineSuggest.syntaxHighlightingEnabled": true,
  "github.copilot.chat.search.semanticTextResults": true
}
```

---

## 📚 參考連結

- [官方發佈說明](https://code.visualstudio.com/updates/v1_99)
- [Agent 模式文檔](https://code.visualstudio.com/docs/copilot/chat/chat-agent-mode)
- [MCP 伺服器文檔](https://code.visualstudio.com/docs/copilot/chat/mcp-servers)
