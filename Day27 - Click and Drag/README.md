<h1><b>筆記</b></h1>

<h4><b>1. 設定點擊物件起始點為0方法</b></h4>
<p>startX = e.pageX - item.offsetLeft;</p>

<h4><b>2. 設定物件隨滑鼠移動方式</b></h4>
<p>Step1: 使用mousemove</p>
<p>Step2: 計算移動距離</p>

`const walk = (x - startX) * 3;`

<p>Step3: 計算滑動後物件位置</p>

`slider.scrollLeft = scrollLeft - walk;`
