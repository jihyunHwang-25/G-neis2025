<!DOCTYPE html>
<html lang="ko">
<head>
  <meta charset="UTF-8">
  <title>책자 홍보 페이지</title>
  <style>
    body { font-family: sans-serif; text-align: center; background: #f9f9f9; padding: 40px; }
    h1 { margin-bottom: 40px; }
    .container { display: flex; justify-content: center; gap: 30px; flex-wrap: wrap; }
    .book img { width: 200px; border-radius: 10px; box-shadow: 0 4px 10px rgba(0,0,0,0.2); }
    .book img:hover { transform: scale(1.05); transition: 0.2s; }
  </style>
</head>
<body>
  <h1>책자 홍보 페이지</h1>
  <div class="container">
    <a class="book" href="https://example.com/book1" target="_blank">
      <img src="book1-cover.jpg" alt="책자 1">
    </a>
    <a class="book" href="https://example.com/book2" target="_blank">
      <img src="book2-cover.jpg" alt="책자 2">
    </a>
    <a class="book" href="https://example.com/book3" target="_blank">
      <img src="book3-cover.jpg" alt="책자 3">
    </a>
  </div>
</body>
</html>
