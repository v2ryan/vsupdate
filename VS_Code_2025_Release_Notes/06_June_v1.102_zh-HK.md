# VS Code 2025年6月更新 (版本 1.102)

## 📅 發佈日期
2025年6月

---

## 🌟 主要功能摘要

| 類別 | 功能名稱 | 說明 |
|------|----------|------|
| **開源** | Copilot Chat 開源 | VS Code Copilot Chat 擴充功能嘅原始碼公開 |
| **MCP** | MCP 正式可用 | Model Context Protocol 支援正式發佈 |
| **Chat** | Claude Sonnet 4 | 新增 Claude Sonnet 4 模型 |
| **Chat** | 終端自動批准 | 自動批准 Agent 終端命令 |
| **Chat** | 建議 Chat 模式 | 自動選擇適合嘅 Chat 模式 |
| **NES** | 內聯語法高亮 | 內聯建議嘅語法高亮 |
| **編輯器** | 統一 Quick Fix 菜單 | 合併 Quick Fix 同 NES 菜單 |

---

## 📝 詳細功能列表

### Copilot Chat 開源

| 功能 | 描述 |
|------|------|
| 開放原始碼 | GitHub Copilot Chat 擴充功能喺 [github.com/microsoft/vscode-copilot-chat](https://github.com/microsoft/vscode-copilot-chat) 開源 |
| 透明度 | 提高透明度同社區協作 |
| 貢獻 | 歡迎社區貢獻同回饋 |

### MCP - 正式可用

| 功能 | 描述 | 設定 |
|------|------|------|
| GA 發佈 | MCP 支援正式可用 | - |
| 連接狀態 | 右鍵快速重啟失敗嘅伺服器 | - |
| 重試機制 | 伺服器中斷後自動重試 | - |
| 擴充功能 MCP | 擴充功能可以貢獻 MCP 伺服器 | - |

### Chat 改進

| 功能 | 描述 | 設定 |
|------|------|------|
| Claude Sonnet 4 | 新增 Claude Sonnet 4 模型 | - |
| 用戶回應通知 | 需要用戶輸入時發送通知 | `chat.notifyOnUserInputRequired` |
| 建議 Chat 模式 | 自動建議適合嘅模式 | - |
| 內聯 Chat 輸入框 | 無輸入框，直接輸入 | - |
| 改進上下文收集 | 更少依賴 Agent 控制嘅工具 | - |

### 終端自動批准

| 功能 | 描述 | 設定 |
|------|------|------|
| 即時終端批准 | 自動批准 Agent 終端命令 | `github.copilot.chat.terminal.autoApprove.commands` |
| 僅限 Agent 模式 | 只喺 Agent 模式中有效 | - |

### NES 改進

| 功能 | 描述 |
|------|------|
| 內聯語法高亮 | NES 建議有語法高亮 |
| 統一 Quick Fix | 合併 Quick Fix 同 NES 建議菜單 |
| 觸發改進 | 更快、更準確嘅觸發 |

### 編輯器體驗

| 功能 | 描述 | 設定 |
|------|------|------|
| 工作區檔案編輯 | 開啟任何工作區檔案進行編輯 | - |
| 歡迎選項卡標題 | 自訂歡迎選項卡標題 | `workbench.welcomePage.tabTitle` |
| 瀏覽器預設索引頁面 | 喺 vscode.dev 自訂著陸頁 | `workbench.browser.defaultIndexPage` |
| 檔案關聯 | 將 .copilot-codegeneration 關聯到 Markdown | - |

### 源碼控制

| 功能 | 描述 |
|------|------|
| Coding Agent 整合 | 深入整合 GitHub Copilot Coding Agent |
| 狀態追蹤 | 查看 Agent 進度同狀態 |
| PR 指派 | 將 Issue/PR 指派俾 Copilot |

### 終端機

| 功能 | 描述 | 設定 |
|------|------|------|
| 殼層整合增強 | 改進終端外觀同行為 | - |
| 語言建議 | 終端中嘅語言完成 | `terminal.integrated.suggest.enabled` |

### Python

| 功能 | 描述 |
|------|------|
| 完整嘅 Debug 支援 | 改進除錯功能 |
| 測試探索 | 更好嘅測試發現 |

### 擴充功能開發

| 功能 | 描述 |
|------|------|
| MCP 伺服器 API | 穩定嘅擴充功能 API |
| 工具回呼 | 工具可以返回多個結果 |

---

## 🔧 重要設定

```json
{
  "github.copilot.chat.terminal.autoApprove.commands": ["npm test", "npm run build"],
  "chat.notifyOnUserInputRequired": true,
  "workbench.welcomePage.tabTitle": "自訂標題"
}
```

---

## 📚 參考連結

- [官方發佈說明](https://code.visualstudio.com/updates/v1_102)
- [Copilot Chat GitHub Repository](https://github.com/microsoft/vscode-copilot-chat)
- [MCP 支援文檔](https://code.visualstudio.com/docs/copilot/chat/mcp-servers)
