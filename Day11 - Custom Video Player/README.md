<h1><b>筆記</b></h1>

<h4><b>1. 如何在原生js中選取data-* attribute?</b></h4>
<p>使用[data-*]</p>

`例如-  const skipButtons = document.querySelectorAll("[data-skip]")`

<h4><b>2. HTML Audio/Video DOM Reference</b></h4>
<p>method列表- https://www.w3schools.com/tags/ref_av_dom.asp</p>

`例如- const method = video.paused ? 'play' : 'pause';`<br>
     `video[method]();`
     
<h4><b>3. innerText 和 textContent</b></h4>
<p>innerText 取得的是被 CSS 調整過樣式後渲染的文字；textContent 則是實際取得節點中的文字內容</p>

<h4><b>4. parseInt()可以傳回由字串轉換而成的整數</b></h4>

<h4><b>5. parseFloat()可以傳回由字串轉換而成的浮點數</b></h4>

<h4><b>6. CSS5中的flex-basis</b></h4>
<p>決定 flexbox 排版的 item 的初始寬/高(取決於 flex-direction 的方向)</p>

<h4><b>7. e.offsetX:為當前水平位置</b></h4>

<h4><b>8. const scrubTime = (e.offsetX / progress.offsetWidth) * video.duration;</b></h4>
<p>a. 利用event中的offestX，紀錄當前點擊的位置<br>
b. 除以進度條本身的長度，最後乘上影片的總長度<br>
c. 即可算出影片現在的進度</p>

