<h1><b>筆記</b></h1>

<h4><b>1. 語音合成創建方式</b></h4>
<p>使用SpeechSynthesisUtterance()函式</p>

`const msg = new SpeechSynthesisUtterance();`

<h4><b>2. 設定與取得發音各屬性方式</b></h4>
<p>a. .lang：語言<br>
b. .pitch：音調<br>
c. .rate：速度<br>
d. .text：文字內容<br>
e. .voice：聲音<br>
f. .volume：音量</p>

<h4><b>3. SpeechSynthesis.getVoices()</b></h4>
<p>取得並返回語言列表</p>

<h4><b>4. SpeechSynthesis的voiceschanged事件(event)</b></h4>
<p>SpeechSynthesis.getVoices()被觸發與改變</p>

<h4><b>5. Function.prototype.bind()</b></h4>
<p>bind() 方法，會建立一個新函式。該函式被呼叫時，會將 this 關鍵字設為給定的參數，並在呼叫時，帶有提供之前，給定順序的參數</p>

`.bind(thisArg[, arg1[, arg2[, ...]]])`
