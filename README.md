# Atividade-05052022

O documento apresentado é um formulário de cadastro de desenvolvedores.

Feito com HTML básico, com validação de preenchimento obrigatório.

#<!DOCTYPE html>
#<html lang="en">
#<head>
#    <meta charset="UTF-8">
#    <meta http-equiv="X-UA-Compatible" content="IE=edge">
#    <meta name="viewport" content="width=device-width, initial-scale=1.0">
#    <title>Cadastro de DEVs!</title>
#</head>
#<body>
#    <h1 id="titulo">Cadastro de DEVs!</h1>
#    <p id="subtitulo">Complete suas informações.</p>
#    <br>
#<div>
#    <form>
#        <fieldset classe="grupo">
#            <!-- <p> validação online do preenchimento obrigatório, nome, sobrenome e e-mail </p>-->
#            <div>
#                <label for="nome"><strong>Nome:</strong></label>
#                <input type= "text" name= "nome" id="nome" required> 
#            </div>
#            <div classe="campo">
#                <label for="sobrenome"><strong>sobrenome</strong></label>
#                <input type="text" nome= "sobrenome" id="sobrenome" required>
#            </div>
#        <div classe="campo">
#            <label for="email"><strong>E-mail</strong></label>
#            <input type="email" name= "email"  id="email" required> 
#        </div>
#    </fieldset>
#    <div classe="campo">
#        <label>De qual lado da aplicação você desenvolve ? </label>
#        <label>
#            <input type="radio" name= "devweb"  valve="frontend" checked>Front-end 
#        </label>
#        <label>
#            <input type="radio" name= "devweb" valve= "backend">Back-end
#        </label>
#        <label>
#            <input type="radio" name= "devweb" valve= "fullstack">Fullstack
#        </label>
#        </div>
#        <div classe="campo">
#            <label for="senioridade"><strong>Senioridade:</strong></label>
#            <select id="senioridade">
#                <option>Selecione :</option>
#                <option>Junior</option>
#                <option>Pleno</option>
#                <option>Senior</option>
#                <option>Especialista</option>
#            </select>   
#        </div>
#        <br>
#        <fieldset classe="grupo">
#            <div id="check">
#                <label><strong> Selecione as tecnologias que utiliza:</strong></label><br><br>
#                <input type="checkbox" id= "linghtml" name="linghtml" valve= "HTML">
#                  <label for= "linghtml">HTML</label>
#                <input type="checkbox" id="lingcss" name= "lingcss" valve="CSS">
#                  <label for="lingcss">CSS</label>
#                <input type="checkbox" id="lingjava" name="lingjava" valve="Javascript">
#                  <label for="lingjava">Javascript</label>
#                <input type="checkbox" id="lingphp" name="lingphp" valve="PHP">
#                  <label for="lingphp">PHP</label>
#                <input type="checkbox" id="lingcsharp" name="lingcsharp" valve="C#">
#                  <label for="lingcsharp">C#</label>
#                <input type="checkbox" id="lingpython" name="lingpython" valve="Python"> 
#                  <label for="lingpython">Python</label>
#                <input type="checkbox" id="lingcobol" name="lingcobol" valve="Cobol">
#                  <label for="lingcobol">Java</label>
#            </div>
#        </fieldset>
#<div>
#    <br>
#    <label>Conte um pouco da sua experiência:</label>
#    <textarea row="6" style="width: 26em" id="experiencia" name="experiencia"></textarea>
#     <br>
#</div>
#<button classe="botao"type="submit">Concluido</button>
#<button classe="botao"type="reset">Limpar</button>
#</body>
#</html>
