<h1><b>筆記</b></h1>

<h4><b>1. 如何使用fetch取資料?</b></h4>
<p>fetch('http://example.com/movies.json')<br>
  .then(function(response) {<br>
    return response.json();<br>
  })<br>
  .then(function(myJson) {<br>
    console.log(myJson);<br>
  });</p>
  
<h4><b>2. 正規表示法(Regular expressions)</b></h4>
<p>函數為 RegExp</p>
<p>宣告方式- re = new RegExp("pattern", "flag")</p>
<p>pattern代表正規表示法來顯示的字串，flag 則是比對的方式。flag 的值有三種：<br> 
g：全域比對（Global match)<br>
i：忽略大小寫（Ignore case）<br>
gi：全域比對並且忽略大小寫</p>
<p>表示法符號- http://syunguo.blogspot.com/2013/04/jsregular-expressions.html</p>

<h4><b>3. String.prototype.replace()</b></h4>
<p>replace()方法會傳回一個新字串，此新字串是透過將原字串與 pattern 比對，以 replacement 取代吻合處而生成</p>

<h4><b>4. Array.prototype.join()</b></h4>
<p>join()方法會將陣列（或一個類陣列（array-like）物件）中所有的元素連接、合併成一個字串，並回傳此字串</p>
