# VS Code 2025年10月更新 (版本 1.106)

## 📅 發佈日期
2025年10月

---

## 🌟 主要功能摘要

| 類別 | 功能名稱 | 說明 |
|------|----------|------|
| **Agent** | Agent Sessions 視圖 | 管理同追蹤 Agent 會話 |
| **Agent** | Cloud Agents | 雲端 Agent 執行 |
| **終端** | Terminal IntelliSense GA | 終端智能建議正式可用 |
| **Chat** | 改進嘅模型選擇 | 更好嘅模型選擇體驗 |
| **編輯器** | 性能增強 | 持續嘅性能改進 |
| **MCP** | MCP 改進 | MCP 功能增強 |

---

## 📝 詳細功能列表

### Agent Sessions 視圖

| 功能 | 描述 | 用法 |
|------|------|------|
| 會話管理 | 查看所有 Agent 會話 | Agent Sessions 視圖 |
| 歷史追蹤 | 追蹤過去嘅會話 | - |
| 恢復會話 | 從之前嘅會話繼續 | 點擊會話 |
| 狀態顯示 | 顯示會話狀態 | - |
| 清理管理 | 管理同刪除會話 | - |

### Cloud Agents

| 功能 | 描述 |
|------|------|
| 雲端執行 | Agent 可以喺雲端執行 |
| 持續運行 | 即使關閉 VS Code 仍繼續 |
| 資源共享 | 使用雲端資源 |
| 結果同步 | 完成後同步結果 |

### Terminal IntelliSense GA

| 功能 | 描述 | 設定 |
|------|------|------|
| 正式可用 | 終端智能建議正式發佈 | `terminal.integrated.suggest.enabled` |
| 命令完成 | 智能命令建議 | - |
| 參數建議 | 命令參數提示 | - |
| 歷史整合 | 基於歷史嘅建議 | - |
| 語言完成 | Python 等語言完成 | 需要語言伺服器 |

### Chat 改進

| 功能 | 描述 |
|------|------|
| 模型選擇 | 改進嘅模型選擇 UI |
| 對話管理 | 更好嘅對話組織 |
| 上下文處理 | 更智能嘅上下文管理 |
| 工具效率 | 更高效嘅工具調用 |

### MCP 改進

| 功能 | 描述 |
|------|------|
| 穩定性 | 改進嘅伺服器穩定性 |
| 連接管理 | 更好嘅連接處理 |
| 錯誤處理 | 改進嘅錯誤恢復 |
| 性能 | 更快嘅響應時間 |

### NES 改進

| 功能 | 描述 |
|------|------|
| 建議質量 | 更準確嘅建議 |
| 觸發速度 | 更快嘅觸發 |
| 語言支援 | 擴展嘅語言支援 |

### 編輯器體驗

| 功能 | 描述 | 設定 |
|------|------|------|
| 性能增強 | 持續嘅性能改進 | - |
| UI 精緻 | 視覺改進 | - |
| 穩定性 | 減少崩潰 | - |
| 記憶體 | 優化記憶體使用 | - |

### 源碼控制

| 功能 | 描述 |
|------|------|
| Git 增強 | 改進 Git 功能 |
| 協作功能 | 更好嘅團隊協作 |
| PR 體驗 | 改進 PR 流程 |

### Python

| 功能 | 描述 |
|------|------|
| Pylance 改進 | 更好嘅語言支援 |
| 除錯增強 | 改進除錯功能 |
| 測試改進 | 更好嘅測試支援 |

### 擴充功能開發

| 功能 | 描述 |
|------|------|
| API 穩定 | 更多穩定 API |
| 文檔更新 | 改進開發文檔 |
| 工具增強 | 更好嘅開發工具 |

---

## 🔧 重要設定

```json
{
  "terminal.integrated.suggest.enabled": true,
  "github.copilot.chat.agent.cloudAgents.enabled": true,
  "github.copilot.chat.agent.sessions.enabled": true
}
```

---

## 📚 參考連結

- [官方發佈說明](https://code.visualstudio.com/updates/v1_106)
- [Terminal IntelliSense 文檔](https://code.visualstudio.com/docs/terminal/shell-integration)
- [Agent 會話管理](https://code.visualstudio.com/docs/copilot/chat/chat-agent-mode)
