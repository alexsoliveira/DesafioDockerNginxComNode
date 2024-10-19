# DesafioDockerNginxComNode
Desafio docker Nginx com Node.js

**Primeiro passo:** baixa o projeto na máquina e executa a linha de comando abaixo:<br>
**git clone https://github.com/alexsoliveira/DesafioDockerNginxComNode.git**

**Segundo Passo:** quando finalizar de baixar o projeto, executa a linha de comando abaixo:<br>
**cd .\DesafioDockerNginxComNode\node**

**Terceiro passo:**em seguida executar o comando abaixo:<br>
**npm install**

**Quarto passo:** quando finalizar de instalar, executa comando abaixo:<br>
**cd..** <br>

**Quinto passo:** e em seguida executa o comando abaixo::<br>
**docker-compose up -d**

**Sexto passo:** depois executa a url abaixo, no browser:<br>
**[http://localhost:3000/]** <br>
**Obs.: A primeira vez pode demorar um pouco para subir a aplicação**

**Sétimo passo:** Para inserir registro, execura a url abaixo, no postman, o programa similar:<br>
**[http://localhost:3000/pessoas]** e no body do postman, executa json abaixo:<br>
``{
    "name": "Wesley"
}``