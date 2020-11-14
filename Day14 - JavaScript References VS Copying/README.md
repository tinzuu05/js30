<h1><b>筆記</b></h1>

<h4><b>1. Array陣列[]</b></h4>

`const players = ['Wes', 'Sarah', 'Ryan', 'Poppy'];`

<h4><b>2. Object物件{}</b></h4>

`const tin = {name: 'tin', age: 99,}`

<h4><b>3. Array.prototype.concat()</b></h4>
<p>用來合併兩個或多個陣列。此方法不會改變現有的陣列，回傳一個包含呼叫者陣列本身的值，作為代替的是回傳一個新陣列</p>

`const array3 = array1.concat(array2);`

<h4><b>4. 展開運算符(Spread Operator)</b></h4>
<p>符號是三個點(...)，與陣列有關</p>

`const arr = [1,2,3]`<br>
`const arr2 = [...arr]`

<h4><b>5. Array.from()</b></h4>
<p>會從類陣列（array-like）或是可迭代（iterable）物件建立一個新的 Array 實體</p>

`const array = Array.from([1, 2, 3], x => x + x);`<br>
`console.log(array); //Array [2, 4, 6]`

<h4><b>6. Object.assign()</b></h4>
<p>被用來複製一個或多個物件自身所有可數的屬性到另一個目標物件。回傳的值為該目標物件</p>

`var obj = { a: 1 };`<br>
`var copy = Object.assign({}, obj);`<br>
`console.log(copy); // { a: 1 }`

<h4><b>7. JSON.stringify() 和 JSON.parse()</b></h4>
<p>JSON.parse()：JSON 變物件</p>

` var shop = JSON.parse('{"food":"apple"}')`<br>
` console.log(shop); // {food: "apple"}`

<p>JSON.stringify()：物件變 JSON</p>

`var shop = JSON.stringify({food: 'apple'})`<br>
`console.log(shop); //{"food":"apple"}`
    
