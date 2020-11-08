<h1><b>筆記</b></h1>

<h4><b>1. css variables</b></h4>
<p>以 -- 開頭來命名 / 定義變數</p>
<p>:root命名變數</p>
<p>var()呼叫該變數</p>

`:root {--base: lightgreen;}`<br>
` .hl {color: var(--base);}`

<h4><b>2. Document.documentElement</b></h4>
<p>會回傳目前文件（document）中的根元素（Element），如：HTML 文件中的 <html> 元素。</p>
