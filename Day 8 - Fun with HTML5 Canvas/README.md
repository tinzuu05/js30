<h1><b>筆記</b></h1>

<h4><b>1. 渲染環境(rendering context)</b></h4>
<p>getContext()，透過此方法可以取得渲染環境及其繪圖函數(function)</p>

`const ctx = canvas.getContext('2d')`

<h4><b>2. innerWidth與innerHeight</b></h4>
<p>window物件的只讀屬性,宣告視窗的文件顯示區的高度和寬度，以畫素(px)為計量單位</p>

`canvas.width = window.innerWidth` <br>
`canvas.height = window.innerHeight`

<h4><b>3. CanvasRenderingContext2D.strokeStyle</b></h4>
<p>window物件的只讀屬性,宣告視窗的文件顯示區的高度和寬度，以畫素(px)為計量單位</p>

`ctx.strokeStyle = '#bada55'`

<h4><b>4. line caps 是指線段的頂點樣式</b></h4>
<p>line Cap 有三個值可以設定<br>
a. 預設屬性 butt<br>
b. round<br>
c. square</p>

<h4><b>5. line join 是指線段的折角樣式</b></h4>
<p>line join 有三個值可以設定<br>
a. 預設屬性 miter<br>
b. bevel<br>
c. round</p>

<h4><b>6. CanvasRenderingContext2D.beginPath()</b></h4>
<p>是Canvas 2D API通過清空子路徑列表開始一個新路徑的方法。當你想創建一個新的路徑時，調用此方法。</p>

<h4><b>7. moveTo()</b></h4>
<p>移動畫筆到指定的(x, y)座標點</p>

<h4><b>8. offsetX和offsetY</b></h4>
<p>offset意為偏移量，是被點擊的元素距左上角為參考原點的長度</p>

<h4><b>9. offsetX和offsetY</b></h4>
<p>offset意為偏移量，是被點擊的元素距左上角為參考原點的長度</p>

<h4><b>10. Mother-effing hsla應用</b></h4>
<p>參考網站- https://mothereffinghsl.com/</p>

<h4><b>11. globalCompositeOperation 合成效果</b></h4>
<p>參考效果- https://developer.mozilla.org/en-US/docs/Web/API/CanvasRenderingContext2D/globalCompositeOperation</p>
