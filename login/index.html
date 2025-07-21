<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <title>Login - Fuvestão</title>
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <link href="https://fonts.googleapis.com/icon?family=Material+Icons" rel="stylesheet">
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/materialize/1.0.0/css/materialize.min.css">
  <script src="https://ajax.googleapis.com/ajax/libs/jquery/1.11.1/jquery.min.js"></script>
  <script src="https://cdnjs.cloudflare.com/ajax/libs/jquery.maskedinput/1.4.1/jquery.maskedinput.min.js"></script>

  <style>
    #resultTable thead {
      position: sticky;
      top: 0;
      background-color: #f2f2f2;
      z-index: 100;
    }

    #resultTable tbody {
      max-height: 300px;
      overflow-y: auto;
    }

    .centered-form {
      display: flex;
      flex-direction: column;
      align-items: center;
    }

    .input-field {
      width: 50%;
    }

    @media (max-width: 600px) {
      .input-field {
        width: 80%;
      }
    }
  </style>
</head>

<body>
  <div style="text-align: center; padding: 10px;">
    <img src="https://lh3.googleusercontent.com/d/1BMxFhXTHy2zbw1n41e5m7Jf6GOQu8pM2=w1000">
  </div>

  <div class="row centered-form">
    <div class="input-field">
      <input id="matricula" type="text" maxlength="4" required>
      <label for="matricula">Login</label>
    </div>

    <div class="input-field">
      <input id="senha" type="password" maxlength="6" required>
      <label for="senha">Senha</label>
    </div>

    <div class="input-field center-align">
      <button class="btn waves-effect waves-light blue darken-4" onclick="fazerLogin()">
        Entrar <i class="material-icons right">send</i>
      </button>
      <button class="btn waves-effect waves-light blue darken-4" disabled>
        Adesão <i class="material-icons right">send</i>
      </button>
    </div>
  </div>

  <script src="https://cdnjs.cloudflare.com/ajax/libs/materialize/1.0.0/js/materialize.min.js"></script>
  <script>
    function fazerLogin() {
      const login = document.getElementById('matricula').value.trim();
      const senha = document.getElementById('senha').value.trim();

      if (!login || !senha) {
        M.toast({ html: 'Preencha login e senha', classes: 'red' });
        return;
      }

      fetch('https://script.google.com/macros/s/AKfycbyyhxtyettZATeyTfAC4w9ZtKUsrhgSY5PXq6g2l60crp0C3gW4wjbB-unnJYOg9OhP/exec?login=' + login + '&senha=' + senha)
        .then(response => response.json())
        .then(data => {
          if (data && data.login) {
            // Redireciona com os dados na URL
            window.location.href = `principal.html?login=${encodeURIComponent(data.login)}&unidade=${encodeURIComponent(data.nomeUnidade)}`;
          } else {
            M.toast({ html: 'Login ou senha inválidos', classes: 'red' });
          }
        })
        .catch(error => {
          console.error('Erro ao conectar:', error);
          M.toast({ html: 'Erro ao conectar ao servidor', classes: 'red' });
        });
    }
  </script>
</body>
</html>
