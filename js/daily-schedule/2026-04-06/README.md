# 2026-04-07（週二）｜第 3 週

**預估時間：1 小時**

## 今日學習重點

- `.on('click', handler)`、`.on('submit', handler)`
- 與原生 `addEventListener` 對照寫同一個行為

## 建議學習方式

1. jQuery 文件：[`.on()`](https://api.jquery.com/on/)。
2. 同一個按鈕：先寫原生，再寫 jQuery，比較程式長度。

## 作業

1. 表單 `submit`：用 `$('#myForm').on('submit', function (e) { e.preventDefault(); ... })`。
2. 讀取兩個欄位，用 jQuery 顯示在頁面上。
3. 另建一個小按鈕用 `.on('click')` 清空兩個欄位。

## 完成標準（自檢）

- [ ] `submit` 有 `preventDefault`
- [ ] 能指出 `e` 是什麼、為什麼要傳進去
