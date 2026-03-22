# 2026-04-09（週四）｜第 3 週

**預估時間：1 小時**

## 今日學習重點

- `$.ajax` 或 `$.post` / `$.get`（擇一）
- 公開測試 API：例如 [JSONPlaceholder](https://jsonplaceholder.typicode.com/) `POST /posts`

## 建議學習方式

1. jQuery：[jQuery.post](https://api.jquery.com/jQuery.post/) 範例讀一遍。
2. 在 `success` / `done` 裡 `console.log` 回傳資料。

## 作業

1. 用 `$.post`（或 `$.ajax`）送一筆 JSON 到 JSONPlaceholder 的 `posts`（照文件範例欄位）。
2. 成功時把回傳的 `id` 顯示在頁面上。
3. 失敗時在畫面上顯示「請稍後再試」（可先故意改錯 URL 測失敗）。

## 完成標準（自檢）

- [ ] Network 面板能看到請求發出
- [ ] 能分別說出 `success` 與 `error` 何時會跑到
