<h1><b>筆記</b></h1>

<h4><b>1. 設定flex數值可以規劃畫面比例</b></h4>

`flex: 1;`<br>
` flex: 1 0 auto;`

<h4><b>2. 選擇子層，使用 > 符號 </b></h4>

` .panel > * {}`

<h4><b>3. e.propertyName可以抓到觸發transitionend的屬性名稱 </b></h4>

`e.propertyName.includes('flex')`

<h4><b>4. 設定監聽事件中的transitionend，會在 CSS transition 結束後觸發 </b></h4>
