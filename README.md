# my-frist-project
<!DOCTYPE html>
<html lang="az">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Ana Səhifə</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      max-width: 500px;
      margin: 30px auto;
      padding: 20px;
    }
    nav {
      margin-bottom: 20px;
      padding-bottom: 10px;
      border-bottom: 1px solid #ccc;
    }
    nav a {
      margin-right: 15px;
      text-decoration: none;
      color: #007bff;
      font-weight: bold;
    }
    .form-group {
      margin-bottom: 15px;
    }
    label {
      display: block;
      margin-bottom: 5px;
      font-weight: bold;
    }
    input, textarea, button {
      width: 100%;
      padding: 10px;
      box-sizing: border-box;
      font-size: 16px;
    }
    button {
      background-color: #007bff;
      color: white;
      border: none;
      cursor: pointer;
      margin-top: 10px;
    }
  </style>
</head>
<body>

  <!-- Səhifələrarası Keçid Menyusu -->
  <nav>
    <a href="index.html">Ana Səhifə</a>
    <a href="haqqimda.html">Haqqımda</a>
    <a href="xidmetler.html">Xidmətlər</a>
  </nav>

  <h2>Bizimlə Əlaqə</h2>

  <form action="https://formspree.io/f/SİZİN_FORMSPREE_ID" method="POST">
    <div class="form-group">
      <label for="name">AD SOYAD:</label>
      <input type="text" id="name" name="name" required>
    </div>

    <div class="form-group">
      <label for="email">E-POÇT:</label>
      <input type="email" id="email" name="email" required>
    </div>

    <div class="form-group">
      <label for="message">MESAJINIZ:</label>
      <textarea id="message" name="message" rows="4" required></textarea>
    </div>

    <button type="submit">Göndər</button>
  </form>

</body>
</html>
