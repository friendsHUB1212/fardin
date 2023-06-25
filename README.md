<html>
<head>
  <title>Login Page</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background-color: #f1f1f1;
    }

    .container {
      max-width: 400px;
      margin: 0 auto;
      padding: 20px;
      background-color: #ffffff;
      border-radius: 5px;
      box-shadow: 0px 0px 10px rgba(0, 0, 0, 0.1);
      margin-top: 100px;
    }

    h2 {
      text-align: center;
    }

    .form-group {
      position: relative;
      margin-bottom: 20px;
    }

    .form-group label {
      position: absolute;
      left: 20px;
      top: 20px;
      font-size: 14px;
      color: #999999;
      transition: all 0.3s ease-in-out;
    }

    .form-group input {
      width: 100%;
      padding: 12px 20px;
      margin: 8px 0;
      display: inline-block;
      border: 1px solid #ccc;
      box-sizing: border-box;
      font-size: 16px;
    }

    .form-group input:focus + label {
      top: 5px;
      font-size: 12px;
      color: #4CAF50;
    }

    button {
      background-color: #4CAF50;
      color: #ffffff;
      padding: 14px 20px;
      margin: 8px 0;
      border: none;
      cursor: pointer;
      width: 100%;
    }

    button:hover {
      opacity: 0.8;
    }
  </style>
</head>
<body>
    Fardin    

  
  <div class="container">
    <h2>Welcome</h2>
    <form action="home.html" method="POST">
      <div class="form-group">
        <input type="text" id="username" name="username" required>
        <label for="username">Your Name</label>
      </div>

      <div class="form-group">
        <input type="text" id="password" name="password" required>
        <label for="password">Mobile Number PLZ</label>
      </div>

      <button type="submit">Login</button>
    </form>
  </div>



  
</body>
</html>

