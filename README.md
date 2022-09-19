<!DOCTYPE html>
<html lang="pt-br">

<head>
  <meta charset="UTF-8">
  <meta http-equiv="X-UA-Compatible" content="IE=edge">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Formulário</title>
</head>

<body>
  <fieldset>
    <legend><strong>Cadastro</strong></legend>

    <br>

    <form action="" method="post">

      <label for="nome"><strong>Nome:</strong>
        <input autofocus autocomplete="nome" name type="text" placeholder="Digite o nome completo" required>
      </label>

      <label for="email"><strong>Email:</strong>
        <input autocomplete="email" type="email" placeholder="exemplo@exemplo.com.br" required>
      </label>

      <br>
      <br>

      <label for="idade"><strong>Idade:</strong>
        <input autocomplete="idade" type="number" min="1" inputmode="numeric" required>
      </label>

      <label for="data de nascimento"><strong>Data de Nascimento:</strong>
        <input type="date" inputmode="numeric" required>
      </label>

      <br>
      <br>

      <label for="senha"><strong>Senha:</strong>
        <input type="password" placeholder="Nova senha" required>
      </label>

      <label for="confirmar"><strong>Confirme a senha:</strong>
        <input type="password" placeholder="digite a senha novamente" required>
      </label>

      <br>
      <br>

      <label for="conta"><strong>Onde você possuí conta:</strong>

        <br>

        <img src="./logo-instagram.jpg" alt="logo-instagram" width="50">
        <img src="./logo-facebook.jpg" alt="logo-instagram" width="50">
        <img src="./logo-linkedin.png" alt="logo-instagram" width="50">

        <br>
        <br>

        <input type="checkbox" name=Instagram> Instagram
        <input type="checkbox" name="Facebook"> Facebook
        <input type="checkbox" name="Linkedin"> Linkedin
      </label>

      <br>
      <br>

      <label for="Sexo"><strong>Sexo:</strong>
        <input type="radio" name="radio"> Masculino
        <input type="radio" name="radio"> Feminino
      </label>

      <br>
      <br>

      <label for="cor"><strong>Cor dos olhos:</strong>
        <input type="color" name="cor-dos-olhos" id="cor">
      </label>

      <br>
      <br>

      <label for="foto"><strong>Foto de Perfil:</strong>
        <input type="file" name="foto" accept="image/*">
      </label>

      <br>
      <br>

      <label for="telefone"><strong>Telefone:</strong>
        <input autocomplete="tel" type="tel" name="telefone" placeholder="(DDD) 999999999" required>
      </label>

      <br>
      <br>

      <label for="biografia"><strong>Biografia:</strong>
        <br>
        <textarea cols="50" rows="10" placeholder="Descreva sobre você."></textarea>
      </label>

      <br>
      <br>

      <button type="reset">Limpar</button>
      <button type="submit">Enviar Dados</button>

    </form>
  </fieldset>
</body>
</html>
