<!DOCTYPE html>
<html>
<head>
  <title>Formulário de Login</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background-color: #020f23;
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100vh;
      margin: 0;
    }

    .login-container {
      background-color: rgb(129, 33, 208);
      border-radius: 8px;
      padding: 20px;
      box-shadow: 0 2px 4px rgba(0, 0, 0, 0.2);
      width: 300px;
    }

    .login-container h1 {
      text-align: center;
    }

    .form-group {
      margin-bottom: 10px;
    }

    .form-group label {
      display: block;
      font-weight: bold;
      margin-bottom: 5px;
    }

    .form-group input[type="text"],
    .form-group input[type="password"] {
      width: 100%;
      padding: 8px;
      border-radius: 4px;
      border: 1px solid #bb1414;
    }

    .form-group button {
      width: 100%;
      padding: 10px;
      background-color: #1877f2;
      color: rgb(0, 0, 0);
      border: none;
      border-radius: 4px;
      cursor: pointer;
    }

    .form-group button:hover {
      background-color: #b87697;
    }
  </style>
</head>
<body>
  <div class="login-container">
    <h1>Login</h1>
    <form>
      <div class="form-group">
        <label for="username">Usuário:</label>
        <input type="text" id="username" placeholder="Digite seu usuário" required>
      </div>
      <div class="form-group">
        <label for="password">Senha:</label>
        <input type="password" id="password" placeholder="Digite sua senha" required>
      </div>
      <button type="submit">Cadastrar</button>
      <div class="form-group">
        <button type="submit">Entrar</button>
      </div>
    </form>
  </div>
</body>
</html>
