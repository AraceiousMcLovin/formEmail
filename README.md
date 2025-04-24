# FormEmail
1. Criação de formulário:
  Através do VScode foi feita a seguinte codificação:
<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    <!--  action - rece o endereço do arquivo/ página para onde os dados serão enviados.
    method - determina como os dados seerão enviados. -->
    <form action="https://formsubmit.co/alexandre.b.santana@aluno.senai.br" method="post">
        

        <!--  1 Formulário -->
        <!--  Nome  -->
        <div>
        <label for="name">Nome </label>
        </div>
        <input type="text" name="name" id="name" placeholder="Nome e sobrenome" maxlength="30" requerid autofocus>
        <!--  Maxlength: VARCHAR (30) - Limita o tanto de caracteres -->
        <br><br>
        <!-- E-mail -->

        <div>
        <label for="email">E-mail</label>
        </div>
        <input type="email" name="email" id="email" maxlength="50" placeholder="Email@gmail.com" requerid autocomplete>
        <!-- autocomplete: Quando o usuário preenche o campo e envia o formulário, os dados ficam salvos; 
         assim, caso ele queira enviar o formulário novamente, não é necessário redigitar todos os dados. -->
         <br><br>
         <!-- Telefone  -->
         <div>
         <label for="tel">Telefone</label>
        </div>
         <input type="tel" name="tel" id="tel" maxlength="11" placeholder="(XX) XXXXX-XXXX "  required autocomplete>
         <br><br>

         <!--  Curriculo  -->
         <div>
         <label for="Curriculum">Currículo</label>
        </div>
         <input type="file" name="curriculum" id="curriculum">
         <br><br>

         <!-- Mensagem -->
         <div>
         <label for="message">Mensagem</label>
         </div>
         <textarea name="message" id="message" rows="5" cols="20" maxlength="200" placeholder="Digite aqui a sua mensagem "></textarea>
         <br><br>

        <!-- Submit  -->
        <label for="submit"></label>
       
        <button type="submit" name="_next" value="http://127.0.0.1:5500/congratulations.html" style="border-radius: 5px;">
            Enviar
        </button>
    </form>
</body>
</html>

2. Como o formulário ficou funcional:
  Através dos comando usando "action" e "value" com as url devidas:
  <!--<form action="https://formsubmit.co/alexandre.b.santana@aluno.senai.br" method="post">
  <button type="submit" name="_next" value="http://127.0.0.1:5500/congratulations.html" style="border-radius: 5px;">                 Enviar
 </button>-->

3.Comandos Git usados na criação e publicação do repositório:
   * git init
   * git branch -M main
   * git add .
   * git commit -m "Comentário"
   * git remote add origin "Url-do-repositório"
   * git push -u origin main
