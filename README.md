<!DOCTYPE html>
<html lang="pt-br">
<head>
  <meta charset="UTF-8">
  <title>Minhas Fotos</title>
  <style>
    body {
      font-family: Arial;
      background: #111;
      color: white;
      text-align: center;
    }

    h1 {
      margin-top: 20px;
    }

    .galeria {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
      gap: 15px;
      padding: 20px;
    }

    .galeria img {
      width: 100%;
      border-radius: 10px;
      transition: 0.3s;
    }

    .galeria img:hover {
      transform: scale(1.05);
    }
  </style>
</head>

<body>

  <h1>📸 Minhas Fotos</h1>

  <div class="galeria">
    <img src="foto1.jpg">
    <img src="foto2.jpg">
    <img src="foto3.jpg">
    <img src="foto4.jpg">
  </div>

</body>
</html># Nota-de-anime-
Eu dou nota de anime 
