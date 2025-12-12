# VS Code 2025年9月更新 (版本 1.105)

## 📅 發佈日期
2025年9月

---

## 🌟 主要功能摘要

| 類別 | 功能名稱 | 說明 |
|------|----------|------|
| **Agent** | Plan Agent | 先規劃後執行嘅 Agent 模式 |
| **Agent** | Handoffs | Agent 之間嘅任務交接 |
| **模型** | OpenAI Codex | 支援 OpenAI Codex 模型 |
| **MCP** | MCP Marketplace | 瀏覽同安裝 MCP 伺服器 |
| **Chat** | 改進工作流程 | 更流暢嘅 Chat 體驗 |
| **編輯器** | 性能提升 | 顯著嘅性能改進 |

---

## 📝 詳細功能列表

### Plan Agent

| 功能 | 描述 | 用法 |
|------|------|------|
| 規劃模式 | Agent 先制定計劃再執行 | 選擇 Plan 模式 |
| 步驟預覽 | 顯示將要執行嘅步驟 | - |
| 用戶確認 | 每個步驟前確認 | - |
| 計劃調整 | 可以修改計劃 | - |
| 更可預測 | 減少意外變更 | - |

### Handoffs (任務交接)

| 功能 | 描述 |
|------|------|
| Agent 交接 | 將任務從一個 Agent 交接到另一個 |
| 上下文傳遞 | 保持完整嘅上下文 |
| 專業化 Agent | 使用專門嘅 Agent 處理特定任務 |
| 工作流程自動化 | 建立複雜嘅 Agent 工作流程 |

### OpenAI Codex 支援

| 功能 | 描述 | 設定 |
|------|------|------|
| Codex 模型 | 支援 OpenAI Codex | 模型選擇器 |
| 代碼專精 | 專為代碼優化 | - |
| 更快回應 | 減少等待時間 | - |

### MCP Marketplace

| 功能 | 描述 | 用法 |
|------|------|------|
| 瀏覽 MCP 伺服器 | 發現社區創建嘅伺服器 | MCP 視圖 |
| 一鍵安裝 | 輕鬆安裝伺服器 | Install 按鈕 |
| 評分同評論 | 查看社區評價 | - |
| 分類瀏覽 | 按類別尋找伺服器 | - |

### Chat 改進

| 功能 | 描述 |
|------|------|
| 更流暢體驗 | 改進嘅用戶界面 |
| 更快回應 | 減少延遲 |
| 更好嘅上下文 | 改進上下文收集 |
| 錯誤恢復 | 更智能嘅錯誤處理 |

### NES 改進

| 功能 | 描述 |
|------|------|
| 觸發速度 | 更快嘅觸發 |
| 建議質量 | 更準確嘅建議 |
| 語言支援 | 更多語言支援 |

### 編輯器體驗

| 功能 | 描述 | 設定 |
|------|------|------|
| 性能提升 | 顯著嘅性能改進 | - |
| 記憶體優化 | 減少記憶體使用 | - |
| 啟動速度 | 更快嘅啟動 | - |
| 大檔案支援 | 更好嘅大檔案處理 | - |

### 終端機

| 功能 | 描述 | 設定 |
|------|------|------|
| 語言建議 | 改進嘅終端完成 | `terminal.integrated.suggest.enabled` |
| 命令歷史 | 更好嘅歷史管理 | - |
| Shell 整合 | 增強 Shell 整合 | - |

### 源碼控制

| 功能 | 描述 |
|------|------|
| Git 改進 | 更好嘅 Git 支援 |
| PR 流程 | 改進嘅 PR 體驗 |
| 衝突解決 | 更易解決衝突 |

### Python

| 功能 | 描述 |
|------|------|
| 除錯改進 | 更好嘅除錯體驗 |
| 測試支援 | 改進嘅測試功能 |
| 環境管理 | 更好嘅環境支援 |

### 擴充功能開發

| 功能 | 描述 |
|------|------|
| API 更新 | 新增同更新 API |
| MCP API | MCP 開發改進 |
| 文檔改進 | 更好嘅開發文檔 |

---

## 🔧 重要設定

```json
{
  "github.copilot.chat.agent.plan.enabled": true,
  "terminal.integrated.suggest.enabled": true,
  "github.copilot.chat.mcp.marketplace.enabled": true
}
```

---

## 📚 參考連結

- [官方發佈說明](https://code.visualstudio.com/updates/v1_105)
- [Plan Agent 文檔](https://code.visualstudio.com/docs/copilot/chat/chat-agent-mode#_plan-mode)
- [MCP Marketplace](https://code.visualstudio.com/docs/copilot/chat/mcp-servers)
