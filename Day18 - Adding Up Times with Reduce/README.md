<h1><b>筆記</b></h1>

<h4><b>1.取所有值並轉成陣列</b></h4>
<p使用Array.from可轉成陣列，或[...]</p>

`const timeNodes = Array.from(document.querySelectorAll('[data-time]'));)`
`const timeNodes = […document.querySelectorAll('[data-time]')];`

<h4><b>2. 字串轉成數組方法</b></h4>
<p使用parseFloat函數</p>

`const [mins, secs] = timeCode.split(':').map(parseFloat)`

<h4><b>3. Math.floor()</b></h4>
<p會回傳小於等於所給數字的最大整數</p>
