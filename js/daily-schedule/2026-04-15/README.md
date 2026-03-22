# 2026-04-16（週四）｜第 4 週

**預估時間：1 小時**

## 今日學習重點

- 原生 **`fetch`** 發 **GET** 請求
- `response.json()`、用資料更新 DOM

## 建議學習方式

1. MDN：[使用 fetch](https://developer.mozilla.org/zh-TW/docs/Web/API/Fetch_API/Using_Fetch)。
2. 選一個不需 API key 的公開 API（例如 JSONPlaceholder `GET /users/1`）。

## 作業

1. `fetch('https://jsonplaceholder.typicode.com/users/1')`（網址可依官方文件調整）。
2. 成功後把 `name` 和 `email` 顯示在頁面上。
3. 用 `.catch` 或 `response.ok` 檢查，失敗時顯示錯誤字樣。

## 完成標準（自檢）

- [ ] Network 能看到 GET 與狀態 200
- [ ] 能說出 `fetch` 回傳的是什麼、為什麼還要 `.json()`
