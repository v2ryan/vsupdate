# VS Code 2025年1月更新 (版本 1.97)

## 📅 發佈日期
2025年1月

---

## 🌟 主要功能摘要

| 類別 | 功能名稱 | 說明 |
|------|----------|------|
| **GitHub Copilot** | Copilot 下一步編輯建議 (NES) | Copilot 預測你下一步可能會做嘅編輯，用 Tab 鍵快速導航同接受建議 |
| **GitHub Copilot** | Copilot Edits 正式版 | 多檔案代碼編輯功能正式推出 |
| **GitHub Copilot** | o3-mini 同 Gemini 2.0 Flash 模型 | 新增 OpenAI o3-mini 同 Google Gemini 2.0 Flash 模型選擇 |
| **工作區** | 移動命令面板 | 可以將命令面板拖放到新位置 |
| **工作區** | 信任擴充功能發佈者 | 首次安裝擴充功能時會顯示信任對話框 |
| **輸出面板** | 複合日誌 | 將多個日誌合併成單一視圖 |
| **輸出面板** | 過濾日誌 | 按日誌級別、類別或文字過濾輸出內容 |
| **源碼控制** | Git blame 資訊 | 編輯器同狀態欄顯示詳細嘅 Git blame 資訊 |
| **終端機** | Ligature 支援 | 終端機字體連字功能正式穩定 |
| **筆記本** | 行內數值顯示 | 執行儲存格後顯示行內變數值 |

---

## 📝 詳細功能列表

### GitHub Copilot

| 功能 | 描述 | 設定 |
|------|------|------|
| 下一步編輯建議 (NES) | Copilot 預測你下一步嘅編輯位置同內容 | `github.copilot.nextEditSuggestions.enabled` |
| Copilot Edits 正式版 | 支援跨多個檔案進行代碼編輯 | 預設啟用 |
| 改進編輯器控制 | 可以個別接受或放棄編輯 | - |
| 自動接受編輯 | 設定超時後自動接受編輯建議 | `chat.editing.autoAcceptDelay` |
| 時間上下文 | 使用最近互動嘅檔案作為上下文 | `github.copilot.chat.editor.temporalContext.enabled` |
| 工作區索引狀態 | 狀態欄顯示 Copilot 使用嘅索引類型 | - |
| 建立遠端工作區索引 | 為 GitHub 專案建立遠端索引 | - |
| Git 變更上下文 | 使用 `#changes` 參考 Git 中修改嘅檔案 | - |
| o3-mini 模型 | 新增 OpenAI o3-mini 推理模型 | 模型選擇器 |
| Gemini 2.0 Flash | 新增 Google Gemini 2.0 Flash 模型 | 模型選擇器 |

### 無障礙功能

| 功能 | 描述 |
|------|------|
| 增強無障礙音效 | 更新保存、摺疊區域、終端快速修復等音效 |
| Copilot Edits 無障礙幫助 | 螢幕閱讀器用戶可透過 Alt+F1 存取指引 |
| 源碼控制無障礙幫助 | 源碼控制視圖嘅無障礙幫助對話框 |
| 忽略代碼塊語音轉文字 | 可以喺文字轉語音時忽略代碼塊 |

### 工作區

| 功能 | 描述 | 設定 |
|------|------|------|
| 移動命令面板 | 拖放命令面板到新位置，位置會跨重載保存 | - |
| 信任擴充功能發佈者 | 首次安裝時顯示發佈者信任對話框 | - |
| 輸出面板過濾 | 按日誌級別、類別或文字過濾 | - |
| 複合日誌 | 將多個日誌合併成單一視圖 | - |
| 匯出/匯入日誌 | 支援日誌匯出同匯入 | - |
| SVG 圖片預覽 | 內建圖片預覽支援 SVG 檔案 | - |
| CLI 移除根資料夾 | 使用 `--remove` 選項從多根工作區移除資料夾 | - |

### 編輯器

| 功能 | 描述 | 設定 |
|------|------|------|
| 持久化尋找/取代歷史 | 尋找同取代歷史跨會話保存 | `editor.find.replaceHistory` |
| 未提交評論確認 | 關閉含未提交評論嘅控制項時顯示確認 | `comments.thread.confirmOnCollapse` |
| 評論編輯器快速操作 | 可以喺評論編輯器中使用快速操作 | - |

### 源碼控制

| 功能 | 描述 | 設定 |
|------|------|------|
| Git blame 資訊 | 編輯器裝飾同狀態欄顯示 Git blame | `git.blame.statusBarItem.enabled` |
| GitHub 整合 | 時間軸、源碼控制圖同 blame 懸停中嘅「喺 GitHub 開啟」連結 | - |
| 源碼控制圖操作 | 新增 Checkout、Delete Branch、Delete Tag 操作 | - |

### 終端機

| 功能 | 描述 | 設定 |
|------|------|------|
| Ligature 支援 | 終端機字體連字功能正式穩定 | `terminal.integrated.fontLigatures.enabled` |
| ConEmu 進度序列 | 支援 ConEmu 進度回報序列 | - |
| Sticky Scroll 截斷命令 | 命令被截斷時顯示省略號 | - |
| 最後終端關閉行為 | 設定最後終端關閉時是否隱藏面板 | `terminal.integrated.hideOnLastClosed` |

### 筆記本

| 功能 | 描述 | 設定 |
|------|------|------|
| 行內數值 | 儲存格執行後顯示行內變數值 | `notebook.inlineValues` |
| 自訂 Markdown 字體 | 為 Markdown 儲存格設定自訂字體 | `notebook.markup.fontFamily` |

### 預覽功能

| 功能 | 描述 | 設定 |
|------|------|------|
| Agent 模式 | Copilot 自動搜索工作區、編輯檔案、執行終端命令 | `chat.agent.enabled` |
| Copilot Vision | 喺 Chat 中附加同互動圖片 | VS Code Insiders |
| 可重用提示檔案 | 建立同分享可重用嘅 `.prompt.md` 檔案 | `chat.promptFiles` |
| Linux 自訂標題欄 | 喺 Linux 上啟用自訂標題欄 | `window.titleBarStyle` |
| Tree-Sitter 語法高亮 | 實驗性 TypeScript Tree-Sitter 語法高亮 | `editor.experimental.preferTreeSitter` |

---

## 🔧 重要設定

```json
{
  "github.copilot.nextEditSuggestions.enabled": true,
  "chat.agent.enabled": true,
  "git.blame.statusBarItem.enabled": true,
  "terminal.integrated.fontLigatures.enabled": true,
  "notebook.inlineValues": true
}
```

---

## 📚 參考連結

- [官方發佈說明](https://code.visualstudio.com/updates/v1_97)
- [VS Code 文檔](https://code.visualstudio.com/docs)
