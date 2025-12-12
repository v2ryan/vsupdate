# VS Code 2025年8月更新 (版本 1.104)

## 📅 發佈日期
2025年8月

---

## 🌟 主要功能摘要

| 類別 | 功能名稱 | 說明 |
|------|----------|------|
| **模型** | 自動模型選擇 | 系統自動選擇最佳模型 |
| **Agent** | AGENTS.md 支援 | 用 Markdown 定義 Agent 行為 |
| **Chat** | Todo List 工具 | 管理同追蹤任務 |
| **編輯器** | AI 懸停 | 懸停時顯示 AI 輔助資訊 |
| **終端** | 終端語言建議 | 終端中嘅程式語言完成 |
| **NES** | 改進修復建議 | 更準確嘅錯誤修復 |

---

## 📝 詳細功能列表

### 自動模型選擇

| 功能 | 描述 | 設定 |
|------|------|------|
| 智能選擇 | 系統根據任務自動選擇最佳模型 | `github.copilot.chat.autoModelSelection` |
| 任務分析 | 分析任務複雜度選擇模型 | - |
| 成本優化 | 平衡性能同成本 | - |
| 手動覆蓋 | 仍可手動選擇模型 | - |

### AGENTS.md 支援

| 功能 | 描述 | 用法 |
|------|------|------|
| 行為定義 | 用 Markdown 定義 Agent 行為 | 建立 `.github/AGENTS.md` |
| 專案規則 | 為專案設定具體規則 | 寫入規則到檔案 |
| 團隊協作 | 團隊共享 Agent 配置 | 提交到版本控制 |
| 自動載入 | 自動讀取同應用規則 | - |

### Todo List 工具

| 功能 | 描述 |
|------|------|
| 任務追蹤 | Agent 可以建立同追蹤任務 |
| 進度顯示 | 顯示任務完成進度 |
| 結構化工作 | 將複雜任務分解為步驟 |
| 狀態更新 | 實時更新任務狀態 |

### AI 懸停

| 功能 | 描述 | 設定 |
|------|------|------|
| 智能提示 | 懸停時顯示 AI 輔助資訊 | `editor.hover.aiAssist` |
| 代碼解釋 | 解釋代碼片段 | - |
| 建議操作 | 提供改進建議 | - |

### 終端語言建議

| 功能 | 描述 | 設定 |
|------|------|------|
| Python 完成 | Python REPL 中嘅完成 | 需要 Pylance |
| 語言感知 | 識別不同語言環境 | - |
| 智能建議 | 基於上下文嘅建議 | `terminal.integrated.suggest.enabled` |

### NES 改進

| 功能 | 描述 |
|------|------|
| 修復建議 | 更準確嘅錯誤修復 |
| 快速觸發 | 減少延遲 |
| 語法高亮 | 完整嘅內聯語法高亮 |
| 多行建議 | 更好嘅多行編輯支援 |

### Chat 改進

| 功能 | 描述 |
|------|------|
| 對話記憶 | 更長嘅上下文記憶 |
| 工具優化 | 更高效嘅工具調用 |
| 錯誤恢復 | 更好嘅錯誤處理 |

### 編輯器體驗

| 功能 | 描述 | 設定 |
|------|------|------|
| 性能提升 | 改進整體性能 | - |
| 記憶體優化 | 減少記憶體使用 | - |
| UI 改進 | 視覺細節調整 | - |

### 源碼控制

| 功能 | 描述 |
|------|------|
| Git 增強 | 改進 Git 整合 |
| PR 體驗 | 更好嘅 Pull Request 流程 |
| 差異檢視 | 改進差異顯示 |

### 擴充功能開發

| 功能 | 描述 |
|------|------|
| API 更新 | 新增 API |
| MCP 增強 | MCP 功能擴展 |
| 測試改進 | 更好嘅擴充功能測試 |

---

## 🔧 重要設定

```json
{
  "github.copilot.chat.autoModelSelection": true,
  "editor.hover.aiAssist": true,
  "terminal.integrated.suggest.enabled": true
}
```

---

## 📚 參考連結

- [官方發佈說明](https://code.visualstudio.com/updates/v1_104)
- [AGENTS.md 規範](https://docs.github.com/en/copilot/customizing-copilot/adding-repository-custom-instructions)
- [Todo List 工具文檔](https://code.visualstudio.com/docs/copilot/chat/chat-agent-mode)
