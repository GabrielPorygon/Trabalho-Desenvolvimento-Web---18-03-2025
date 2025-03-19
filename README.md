<!DOCTYPE html>
<html lang="pt-BR">
  <head>
    <title>Trabalho Formulários em HTML</title>
    <meta Charset="UTF-8"
  </head>
  <body>
    <h3>Formulário de Cadastro da banda "Graveyard Dogs"</h3>
    <form action="/enviar" method="post"
      <label for="nome"> Nome: </label> <br>
      <input type="text" id="nome" name="nome" placeholder="Insira seu nome" > <br> <br>
      
      <label for="idade"> Data de nascimento: </label> <br>
      <input type="date" id="idade" name="idade" > <br><br>
      
      <label for="Telefone"> Telefone: </label> <br>
      <input type="tel" id="telefone" name="telefone" placeholder="insira seu telefone" > <br><br>
      
      <label for="Email"> Email: </label> <br>
      <input type="email" id="email" name="email" placeholder="insira seu E-mail" > <br><br>
      
      <label> Já participou de outras bandas? </label> <br>
      <input type="radio" id="banda" name="Banda" value="Sim"
      <label for="confirmação">Sim</label><br>
      <input type="radio" id="banda" name="Banda" value="Não"
      <label for="Negação">Não</label><br>
      <br>
      <label>Qual/Quais Instrumentos você toca? </label><br>
      <input type="checkbox" name="instrumentos">Guitarra </a><br>
      <input type="checkbox" name="instrumentos">Bateria </a><br>
      <input type="checkbox" name="instrumentos">Baixo </a><br>
      <input type="checkbox" name="instrumentos">Violão </a><br>
      <input type="checkbox" name="instrumentos">Cello </a><br>
      <br>
      Desde já agradecemos:D
      <br><br>
      <input type="submit" value="Enviar">
      <input type="reset" value="Limpar">
      
      
      </form>
  </body>
</html>
