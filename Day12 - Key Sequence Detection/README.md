<h1><b>筆記</b></h1>

<h4><b>1. pressed.splice(-secretcode.length - 1, pressed.length - secretcode.length)</b></h4>
<p>inputs.splice(start, deleteCount)</p>
<p>限制資料陣列的長度，在splice中的start設定為負數且大於資料列的長度，這樣索引值就會從0開始</p>
<p>deleteCount的值小於目標值時(為0即不刪除)，而當資料陣列大於目標值才進行刪除資料列長度-目標列長度</p>
