# 2026-04-06（週一）｜第 3 週

**預估時間：1 小時**

## 今日學習重點

- 用 CDN 引入 jQuery
- `$()` 選取、`val()` 讀表單值、`text()` / `html()` 差異（先粗懂）

## 建議學習方式

1. 在 HTML 底部加：`<script src="https://code.jquery.com/jquery-3.7.1.min.js"></script>`（版本可照官方最新）。
2. 確認 Console 輸入 `jQuery` 或 `$` 不是 `undefined`。

## 作業

1. 建立 `index.html`，引入 jQuery 與你的 `main.js`。
2. 一個 `#name` 輸入框、一個 `#output` 的 div。
3. 按鈕點擊時，用 `$('#name').val()` 取出，用 `$('#output').text(...)` 顯示「你好，___」。

## 完成標準（自檢）

- [ ] 頁面載入後 jQuery 可用
- [ ] 能說出 `text()` 和 `html()` 為什麼表單顯示優先用 `text` 較安全（一句話即可）
