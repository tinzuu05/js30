

<h1><b>筆記</b></h1>

<h4><b>1. 如何使用querySelector選到不同的daya-key值?</b></h4>
<p>data-key="變數(使用$記號)"</p>

`例如- audio[data-key="${e.keyCode}"]` 

<h4><b>2. DOM currentTime可設定音訊時間</b></h4>

`例如- audio.currentTime = 0;` 

<h4><b>3. propertyName可設定屬性 </b></h4>

`例如- if (e.propertyName !== 'transform') return`

<h4><b>4. 事件監聽addEventListener </b></h4>
<p>要填入三個參數<br>
  a. 事件名稱並用引號包圍<br>
  b. 寫一個函式（匿名或命名皆可)<br>
  c. 最後一個參數大部分情況都寫 false (false事件氣泡，Event Bubbling-從指定元素往外層找。中止冒泡-在監聽器的函式內多寫一行：e.stopPropagation;)<br></p>
  
<h4><b>5. keyCode的概念 </b></h4>
<p>每一鍵盤按鈕對應一個數值</p>
<p>keyCode查詢: https://keycode.info/ </p>

<h4><b>6. js中使用classList.add/remove/toggle控制class</b></h4>

<h4><b>7. forEach迴圈的應用</b></h4>
<p>透過迴圈去把每個索引（index）的元素（item）取出來做運算</p>

<h4><b>8. Array.from迴圈的應用</b></h4>
<p>將偽陣列物件或可遍歷物件轉換為真陣列</p>
<p>接受三個引數：<br>
a. input(必須的): 你想要轉換的類似陣列物件和可遍歷物件<br>
b. map: 類似於陣列的map方法，用來對每個元素進行處理，將處理後的值放入返回的陣列<br>
c. context: 繫結map中用到的this</p>
