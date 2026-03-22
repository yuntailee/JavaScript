# 2026-03-26（週四）｜第 1 週

**預估時間：1 小時**

## 今日學習重點

- `document.querySelector` / `querySelectorAll`
- 修改文字：`textContent`
- 修改樣式類別：`classList.add` / `remove` / `toggle`

## 建議學習方式

1. 建立 `index.html` + `main.js`，用 `<script defer src="main.js">` 引入。
2. MDN：[查詢 DOM](https://developer.mozilla.org/zh-TW/docs/Learn/JavaScript/Client-side_scripting/DOM_scripting) 依範例做一遍。

## 作業

1. HTML 裡放一個 `h1`（id 例如 `title`）和一個 `p`（id `msg`）。
2. 在 `main.js` 用 `querySelector` 把 `h1` 改成「DOM 練習」。
3. 按鈕點擊後（可先寫在 HTML `onclick` 或明天再改成 `addEventListener`）切換 `p` 的 class，讓字變色或顯示/隱藏（用 CSS 先寫好 `.hidden`）。

## 完成標準（自檢）

- [ ] 重新整理頁面後，JS 能正確找到節點
- [ ] `classList` 至少用過一次（add 或 toggle）
