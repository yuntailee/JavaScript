# 2026-04-08（週三）｜第 3 週

**預估時間：1 小時**

## 今日學習重點

- 表單序列化：`$('#form').serialize()`（或逐欄位 `.serializeArray()`）
- 在 Console 看送出字串長什麼樣子

## 建議學習方式

1. 表單內每個 `input` 都要有 `name`，否則序列化可能不完整。
2. 印出 `serialize()` 結果，對照 URL query 風格。

## 作業

1. 一個表單至少三個欄位，都有 `name`。
2. 送出時 `console.log($('#formId').serialize())`。
3. 試試 `.serializeArray()`，把結果變成 `{ key: value }` 物件（手寫迴圈或用 `reduce` 選做）。

## 完成標準（自檢）

- [ ] 能解釋 `name` 屬性在表單裡的用途
- [ ] `serialize` 與自己組物件各試一次
