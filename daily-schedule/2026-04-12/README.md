# 2026-04-13（週一）｜第 4 週

**預估時間：1 小時**

## 今日學習重點

- 事件冒泡（bubbling）：子元素事件會往上傳
- `stopPropagation()` 何時使用（與 `preventDefault` 不同）

## 建議學習方式

1. MDN：[事件流程](https://developer.mozilla.org/zh-TW/docs/Learn/JavaScript/Building_blocks/Events#event_bubbling_and_capture) 讀冒泡段。
2. 做一個外層 div 與內層 button，各別 `click`，觀察觸發順序。

## 作業

1. 外層 `click` `console.log('outer')`，內層 `click` `console.log('inner')`，點內層看順序。
2. 內層加上 `e.stopPropagation()` 後再觀察差異。
3. 用一句話寫註解：`preventDefault` 和 `stopPropagation` 分別挡什麼。

## 完成標準（自檢）

- [ ] 能示範「冒泡」給自己看（Console 順序）
- [ ] 能說出一個適合用 `stopPropagation` 的情境（例如外層可點擊關閉、內層不要關）
