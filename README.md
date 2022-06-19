# Pre
## STEP0 install Node.js
- 安裝 nodejs, 版本請不要低於 14。

----
## STEP1 VSCode extensions
- required
  - https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint
  - https://marketplace.visualstudio.com/items?itemName=dsznajder.es7-react-js-snippets
  - https://marketplace.visualstudio.com/items?itemName=xabikos.JavaScriptSnippets
  - https://marketplace.visualstudio.com/items?itemName=Gruntfuggly.todo-tree
- optionals
  - https://marketplace.visualstudio.com/items?itemName=vincaslt.highlight-matching-tag
  - https://marketplace.visualstudio.com/items?itemName=formulahendry.auto-rename-tag
---
## STEP2 JavaScript ES6
- 不熟的話，可以先讀一下這一編：https://milkmidi.medium.com/react-%E8%B5%B7%E6%89%8B%E5%BC%8F-js-es6%E7%AF%87-4b8f1a9e07e0
---
## STEP3 手感練習題
### TodoList
- 請用 VanillaJS 開發。
- 請參考 todoList.html
- 視覺參考 https://www.figma.com/file/WjH0KtgMDe4iEbIQAmNUS5/To-Do-List-(Community)-(Copy)?node-id=0%3A1
- 功能需求 1
  1. input 可以輸入文字，是按下左邊的 button 可以新增一筆 Todo。
  2. 顯示所有的 Todos 列表。
  3. 每筆 Todo Item，要有文字、是否完成狀態、刪除功能。
  4. UI，style 不重要。
- 功能需求 2
  - 要有 All 和 Active 和 Completed 的按鈕，用來 filter Todos 顯示用。
- Nice to Have：
  - input 文字框按下 enter 要能自動送出。

### Countdown
- 請用 VanillaJS 開發。
- 請參考 countdown.html
- 功能需求 1
  1. 用 API 載入 countdown.json
  2. 針對載入的資料，過濾有效的時間(有效的時間指的是，`使用者系統時間要在 startDate 和 endDate 區間`)。
  3. 以過濾後第一筆資料的 endDate 當倒數計時數啟動的值。
- 功能需求 2
  > 如果功能需求 1 卡住，可以直接實作功能需求 2 的部份，並以 2022-12-31 為倒數計時的值。
  1. 實作倒數計時功能
  2. Start button 按下可重新啟動計時器
  3. Stop button 暫停計時器
  4. 顯示格式為：DD:hh:mm:ss
- Nice to have
  - 啟動中 Start Button 為 disabled
  - 停止中 Stop Button 為 disabled
---
