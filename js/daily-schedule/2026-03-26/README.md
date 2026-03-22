# 2026-03-27（週五）｜第 1 週

**預估時間：1 小時**

## 今日學習重點

- `addEventListener('click', ...)`
- 表單 `submit` 事件
- `event.preventDefault()` 阻止預設送出

## 建議學習方式

1. MDN：[事件入門](https://developer.mozilla.org/zh-TW/docs/Learn/JavaScript/Building_blocks/Events)。
2. 用 `<form>` 包住輸入框與送出鈕，在 `submit` 裡 `preventDefault()`，用 `console.log` 確認有攔截到。

## 作業

1. 一個表單：一個文字輸入 + `type="submit"` 按鈕。
2. 監聽 `submit`，阻止預設行為，讀取輸入值並 `console.log`。
3. 再加一個按鈕用 `click` 事件清空輸入框（用 `input.value = ''`）。

## 完成標準（自檢）

- [ ] 按下送出時頁面不會整頁重新載入（有 preventDefault）
- [ ] 能說出 `click` 和 `submit` 差在哪裡（一句話）
