# Ocean0510
<!DOCTYPE html>
<html>
<head>
  <title>樂透遊戲</title>
  <link rel="stylesheet" type="text/css" href="mystyle.css">
  <script src="script.js"></script>
</head>
<body>
  <h1>樂透遊戲</h1>
  <p>請輸入 3 個號碼 (範圍是數字 1~10)：</p>
  <input type="number" id="number1" min="1" max="10">
  <input type="number" id="number2" min="1" max="10">
  <input type="number" id="number3" min="1" max="10">
  <br><br>
  <button onclick="startGame()">開獎</button>
  <button onclick="resetGame()">重新開始</button>
  <br><br>
  <div id="result"></div>
  <script>
    
    var link = document.createElement('link');
    link.rel = 'stylesheet';
    link.type = 'text/css';
    link.href = 'mystyle.css';
    document.head.appendChild(link);
  </script>
</body>
</html>
