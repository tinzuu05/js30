<h1><b>筆記</b></h1>

<h4><b>1. 當前時間宣告方式</b></h4>
<p>new Date();</p>
<p>表達月份 (month) 是從 0 到 11，0 是一月；11 是十二月</p>

`例如- var now = newDate`

<h4><b>2. 取得當前時間方式</b></h4>
<p>getDate();</p>

`例如- const seconds = now.getSeconds();`

<h4><b>3. 設定當前時間方式</b></h4>
<p>setDate();</p>

<h4><b>4. object.style.transform能設定transform屬性</b></h4>

``例如- secondHand.style.transform = `rotate(${secondsDegrees}deg)` ``

<h4><b>5. 利用setInterval(setDate, 1000)每秒更新一次</b></h4>
<p>透過setInterval指定一段程式碼或函式定時在多少毫秒(ms)後執行，並回傳此定時器的編號。
<p>可以透過 clearInterval 取消程式碼的執行。</p>
<p>大致用法與 setTimeout 相同，只差在定時執行</p>
