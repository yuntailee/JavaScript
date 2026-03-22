# 2026-04-01（週三）｜第 2 週

**預估時間：1 小時**

## 今日學習重點

- **Regex（正規表達式）** 入門：`/pattern/`、`test()` 或 `match()`
- 二選一練熟：**只允許數字** **或** **簡單 Email 格式**

## 建議學習方式

1. MDN：[Regular Expressions](https://developer.mozilla.org/zh-TW/docs/Web/JavaScript/Guide/Regular_Expressions) 讀「建立」與「測試」小節。
2. 在 Console 試：`/^\d+$/.test("123")`、自訂 Email 簡易版（不必完美）。

## 作業（擇一主題做深）

**A. 只允許數字**（例如手機欄位）  
- 驗證失敗顯示「請只輸入數字」。

**B. Email 簡易格式**  
- 至少要有 `@`、前後非空；可用簡單 regex。

寫一個函式 `validateXxx(value)` 回傳 `{ ok: boolean, message: string }`。

## 完成標準（自檢）

- [ ] 至少 3 組測試字串（通過、失敗、邊界）
- [ ] Regex 能用自己的話解釋「大概在做什麼」（不用每個符號都背）
