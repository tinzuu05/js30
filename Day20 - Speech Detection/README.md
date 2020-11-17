<h1><b>筆記</b></h1>

<h4><b>1. 語音辨別</b></h4>
<p>window.SpeechRecognition = window.SpeechRecognition || window.webkitSpeechRecognition</p>
<p>初始化與使用var myRecognition = new SpeechRecognition();</p>

<h4><b>2. recognition.interimResults = true; // 是否要輸出中間結果</b></h4>

<h4><b>3. recognition.continuous = true; // 連續辨識</b></h4>

<h4><b>4. recognition.continuous = true; // 連續辨識</b></h4>

<h4><b>5. 設定輸出語言方式</b></h4>
<p>recognition.lang = '語言';</p>

`recognition.lang = 'en-UK';`

<h4><b>6. Node.appendChild</b></h4>
<p>將一個附加到指定父節點的子節點列表的末尾處，對於現存的 Node 它會採用搬移的方式，如果 appendChild 使用時要複製而非搬移，記得先使用 Node.cloneNode() 這個方法複製 Node Element</p>

<h4><b>7. Node.textContent</b></h4>
<p>表示節點或其後代的文字內容</p>

<h4><b>8. SpeechRecognitionResult.isFinal</b></h4>
<p>屬性是一個布林值，如果值是true，則表示這是最後一次返回的結果（語音識別結束）。如果為false，表示識別尚未結束，這只是一個臨時的數據，有可能會在稍後更新</p>
