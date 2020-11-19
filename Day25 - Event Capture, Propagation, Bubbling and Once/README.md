<h1><b>筆記</b></h1>

<h4><b>1. 事件冒泡(Event Bubbling)</b></h4>
<p>由子層傳到父層</p>

<h4><b>2. 事件捕捉(Event Bubbling)</b></h4>
<p>由子父層傳到子層</p>

<h4><b>3. 防止事件冒泡</b></h4>
<p>e.stopPropagation()</p>

<h4><b>4. 事件只執行一次</b></h4>
<p>設定once: true,</p>

`  button.addEventListener('click', () =>` {<br>
`    console.log('click!');`<br>
`  },` {<br>
`    once: true,`<br>
`  })`
