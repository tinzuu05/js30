<h1><b>筆記</b></h1>

<h4><b>1. console.log()一般測試用法</b></h4>
`console.log('hello world');`

<h4><b>2. console.log()混和用法</b></h4>
<p>符號列表<br>
%s --> 字串<br>
%d 或 %i --> 整數<br>
%f --> 小數點<br>
%o --> DOM 元素<br>
%O --> JavaScript 物件<br>
%c --> CSS</p>

`console.log('Hello I am a %s string!', '😃');`

<h4><b>3. console.warn()警告顯示</b></h4>

<h4><b>4. console.error()錯誤顯示</b></h4>

<h4><b>5. console.assert()設立條件，如不滿條件就會顯示錯誤訊息</b></h4>

`console.assert(p.classList.contains('ouch'), 'That is wrong!');`

<h4><b>6. console.clear()清除所有console.log</b></h4>

<h4><b>7. console.dir()可以顯示一個對象的所有屬性和方法（詳細顯示，利於分析對象）</b></h4>

<h4><b>8. console.groupCollapsed & console.groupEnd</b></h4>
<p>創建一個新的分組。隨後輸出到控制台上的內容都會被添加一個縮進，表示該內容屬於當前分組，直到調用console.groupEnd（）之後，當前分組結束。和console.group（）方法的不同用戶必須單擊一個按鈕才能將折疊的內容打開</p>

<h4><b>9. console.count() 計算顯示次數</b></h4>

<h4><b>10. console.time() 和 console.timeEnd()</b></h4>
<p>跟蹤代碼執行點之間經過的時間</p>
