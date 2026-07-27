<div align="center">

# Utilização do Sistema // System Usage
  
</div>

# EN 🇺🇸

## About

Automatically adds a role from your Discord server to all its members.

## installation of the premises

First of all, make sure that Node.js and npm are correctly installed on your machine. If they are not, go to the Node.js website and install them:
[https://nodejs.org/pt-br](https://nodejs.org/pt-br)

Then, download the files from the repository to your machine and open the folder where all the files are located in the terminal or command prompt and install the project dependencies using one of the following commands:

```npm i --save``` or ```npm install --save```

## Bot Settings:

Go to the Discord developer website, create a new application, and retrieve the following information:
`Client_ID` && `Token`

[https://discord.dev](https://discord.dev)

After that, obtain the ID corresponding to the role you want to add and the server that will be affected by the application.

With all the collected information, open the `index.js` file in your VS Code or Notepad and replace the following lines with the previously obtained information:

TOKEN: `client.login('Your Token Here');`, on the last line of code `52`

Server ID: `const GUILD_ID = 'Server ID';` on line `9`

Role ID: `const ROLE_ID = 'ID of the role to be added';` on line `10`

## Application Execution:

After everything is correctly configured, simply run the following command in the same terminal/cmd where you installed the project dependencies:

```node .``` or ```node index.js```

The code will start executing and the members of your server will receive the role one by one. On servers with many members, it may take a while, as it adds the role to one member every second to prevent the code from breaking mid-process due to too many simultaneous requests.

Simply monitor the logs in the terminal itself to see which members have received the role, how many are left, and when the application finishes executing.

## Illustrative image:

<img width="1113" height="618" alt="image" src="https://github.com/user-attachments/assets/5162131a-2b2a-4c5f-96f2-0a9c428169ac" />

# PT-BR 🇧🇷

## Instalação das dependências

Antes de tudo, certifique-se de que o node.js e o npm estão instalados de forma correta em sua máquina, caso não esteja, acesse o site do node.js e faça a instalação:
[https://nodejs.org/pt-br](https://nodejs.org/pt-br)

depois, baixe os arquivos do respositório em sua máquina e abra a pasta onde todos os arquivos se encontram no terminal ou no prompt de comandos e realize a instalação das depêndencias do projeto utilizando um dos seguintes comandos:

```npm i --save``` ou ```npm install --save```

## Configurações do bot:

Acesse o site de desenvolvedores do Discord, crie uma nova aplicação e resgate as seguintes informações:
`Client_ID` && `Token`

[https://discord.dev](https://discord.dev)

Após isso, obtenha o ID referente ao cargo que deseja adicionar e o servidor que vai ser afetado pela aplicação.
Com todas as informações coletadas, abra o código do arquivo `index.js` no seu VS Code ou no bloco de notas e substitua as seguintes linhas com as informações obtidas anteriormente:

TOKEN : `client.login('Seu Token Aqui');`, na ultima linha do código `52`

ID do Servidor : `const GUILD_ID = 'Id do servidor';` na linha `9`

ID do Cargo : `const ROLE_ID = 'Id do cargo que será adicionado';` na linha `10`

## Execução da aplicação:

Depois de tudo configurado corretamente basta, no mesmo terminal/cmd onde instalou as depêndencias do projeto, execute o seguinte comando:

```node .``` ou ```node index.js```

O código irá começar a ser executado e os membros do seu servidor vão receber o cargo um por um. Em servidores com muitos membros, pode demorar um pouco, já que ele adiciona o cargo em um membro a cada 1 segundo, para evitar que o código quebre no meio do processo por muitas requisições simultâneas.

Basta acompanhar os logs no proprio terminal para saber quais membros receberam o cargo, quantos faltam e quando a aplicação terminar sua execução.

## Imagem demonstrativa:

<img width="1113" height="618" alt="image" src="https://github.com/user-attachments/assets/5162131a-2b2a-4c5f-96f2-0a9c428169ac" />
