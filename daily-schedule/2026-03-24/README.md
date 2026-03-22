# 2026-03-25（週三）｜第 1 週

**預估時間：1 小時**

## 今日學習重點

- 物件字面量 `{ }`
- 用 `.` 或 `[]` 讀寫屬性
- 和「表單」的連結：欄位名稱 → 值

## 建議學習方式

1. MDN：[物件基礎](https://developer.mozilla.org/zh-TW/docs/Learn/JavaScript/Objects/Basics) 前半段即可。
2. 在紙上或記事本畫一個表單有三個欄位，再對應成物件的 key。

## 作業

1. 建立一個物件 `formData`，包含：`name`、`phone`、`email`（字串皆可自訂假資料）。
2. 寫一個函式 `getField(formData, fieldName)`，用 `fieldName` 字串取出對應值（練習 `[]`）。
3. 新增一個欄位 `note`，並在 `formData` 上加上去（練習修改物件）。

## 完成標準（自檢）

- [ ] 能用 `formData.phone` 和 `formData['phone']` 兩種方式取值
- [ ] 能向物件加新屬性且不覆蓋錯欄位
