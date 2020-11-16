<h1><b>筆記</b></h1>

<h4><b>1.連結與串聯用戶端麥克風、攝影鏡頭方式</b></h4>
<p>function getVideo() { <br>
  &nbspnavigator.mediaDevices<br>
    &nbsp&nbsp&nbsp&nbsp.getUserMedia({ video: true, audio: false })<br>
   &nbsp &nbsp&nbsp.then((localMediaStream) => {<br>
     &nbsp &nbsp&nbsp&nbsp&nbsp&nbspconsole.log(localMediaStream);<br>
      &nbsp &nbsp&nbsp&nbsp&nbsp&nbspvideo.srcObject = localMediaStream;<br>
      &nbsp&nbsp&nbsp&nbsp &nbsp&nbsp//older version does not work anymore<br>
      &nbsp&nbsp &nbsp&nbsp // video.src = window.URL.createObjectURL(localMediaStream);<br>
      &nbsp &nbsp&nbsp&nbsp&nbsp&nbspvideo.play();<br>
     &nbsp &nbsp&nbsp})<br>
    &nbsp &nbsp&nbsp.catch((err) => {<br>
      &nbsp &nbsp&nbspconsole.error(`no!!`, err);<br>
    &nbsp &nbsp&nbsp});<br>
}</p>

<p>因getUserMedia()會返回一個Promise物件，所以我們需要利用.then來取得其返回的MediaStream物件</p>

<h4><b>2. HTMLCanvasElement.getContext()</b></h4>
<p>返回canvas的某些，如果某些沒有定義則返回null</p>

<h4><b>3. setTimeout() 與 setInterval()</b></h4>
<p>setTimeout() 的作用 是在延遲了某段時間 (單位為毫秒) 之後，才去執行「一次」指定的程式碼，並且會回傳一個獨立的 timer ID</p>
<p>setInterval() 則是固定延遲了某段時間之後，才去執行對應的程式碼，然後「不斷循環」。 也會回傳一個獨立的 timer ID</p>

<h4><b>4. drawImage(image, x, y, width, height)</b></h4>
<p>當放置影像於畫布上時，會按照參數width(寬)、height(高)來縮放影像</p>

<h4><b>5. HTML5 canvas getImageData()</b></h4>
<p>返回ImageData對象，該對象拷貝了畫布指定矩形的預定數據</p>

<h4><b>6. CanvasRenderingContext2D.globalAlpha</b></h4>
<p>設置圖形和圖片透明度的屬性，數值的範圍從 0.0 （完全透明）到1.0 （完全不透明）</p>

<h4><b>6. CanvasRenderingContext2D.putImageData()</b></h4>
<p>是Canvas 2D API將數據從現有的ImageData對象重定向到位圖的方法</p>

<h4><b>7. 下載圖片並儲存至本地端方法</b></h4>
<p>Step1: HTMLCanvasElement.toDataURL()回傳含有圖像和參數設置特定格式的 data URIs (預設 PNG). 回傳的圖像解析度為 96 dpi.</p>
 `canvas.toDataURL(type, encoderOptions);`<br>
 `const data = canvas.toDataURL("image/jpeg");`

<p>Step2: Document.createElement() 方法可以依指定的標籤名稱（tagName）建立 HTML 元素，或是在未定義標籤名稱下建立一個 HTMLUnknownElement</p>
 `var element = document.createElement(tagName[, options]);`<br>
 `const link = document.createElement("a");`

<p>Step3: link.href = data</p>
<p>Step4: link.setAttribute("download", "name");</p>
<p>Step5: link.innerHTML = `<img src="${data}" alt="name" />`;</p>
<p>Step6: Node.insertBefore()在父元素下，將每次新產的link插入至第一個子元素的最前面</p>
`strip.insertBefore(link, strip.firstChild)`

<h4><b>9. 效果設定，以四個色板rgba對應0,1,2,3下去做調整，i+=4是因為rgba四個為一組，所以每次跳四個才會到下一個rgba</b></h4>
<p>紅色效果-將r部分的顏色提高，其餘減少</p>
<p>色彩分離-將rgb不同的顏色移動到不同的位置即可</p>
<p>綠幕(去背)-只要顏色落在指定區間，就讓他變透明(a變為0)</p>
