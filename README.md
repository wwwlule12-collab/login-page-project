# login-page-project
this is an advance login page good for website authentication, logging in, registration.
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Login Page</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background: linear-gradient(135deg, #4facfe, #00f2fe);
      height: 100vh;
      display: flex;
      justify-content: center;
      align-items: center;
      margin: 0;
    }
    .login-container {
      background: rgba(255, 255, 255, 0.9);
      padding: 40px;
      border-radius: 12px;
      box-shadow: 0 8px 20px rgba(0,0,0,0.2);
      width: 350px;
    }
    .login-container h2 {
      margin-bottom: 20px;
      text-align: center;
      color: #333;
    }
    .input-group {
      margin-bottom: 15px;
    }
    .input-group label {
      display: block;
      margin-bottom: 5px;
      color: #555;
    }
    .input-group input {
      width: 100%;
      padding: 10px;
      border: 1px solid #ddd;
      border-radius: 8px;
      transition: border-color 0.3s;
    }
    .input-group input:focus {
      border-color: #4facfe;
      outline: none;
    }
    .options {
      display: flex;
      justify-content: space-between;
      align-items: center;
      margin-bottom: 15px;
    }
    .options a {
      color: #4facfe;
      text-decoration: none;
      font-size: 14px;
    }
    .options a:hover {
      text-decoration: underline;
    }
    button {
      width: 100%;
      padding: 12px;
      background: #4facfe;
      border: none;
      border-radius: 8px;
      color: #fff;
      font-size: 16px;
      cursor: pointer;
      transition: background 0.3s;
    }
    button:hover {
      background: #00c6fb;
    }
  </style>
</head>
<body>
  <div class="login-container">
    <h2>Login</h2>
    <form>
      <div class="input-group">
        <label for="username">Username</label>
        <input type="text" id="username" placeholder="Enter username" required>
      </div>
      <div class="input-group">
        <label for="password">Password</label>
        <input type="password" id="password" placeholder="Enter password" required>
      </div>
      <div class="options">
        <label><input type="checkbox"> Remember me</label>
        <a href="#">Forgot Password?</a>
      </div>
      <button type="submit">Login</button>
    </form>
  </div>
</body>
</html>
