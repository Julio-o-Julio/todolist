# todolist

Sistema de Gerenciamento de Tarefas Pessoais

### Como rodar o projeto na sua máquina

1. Abra o terminal em uma pasta de sua escolha e faça o clone do repositório rodando este código:

> git clone https://github.com/Julio-o-Julio/todolist

2. Após clonar o repositório, entre na pasta do repositório rodando o comando ainda no seu terminal:

> cd ./todolist

3. Agora abra mais um terminal, um para o Backend e outro para o Frontend.

4. Após abir mais um terminal rode o seguinte comando em um dos terminais:

> cd ./api

5. Agora altere o nome do arquivo ".env.exemple" para ".env" e rode os seguintes comandos no terminal:

> npm install

> npx prisma migrate dev --name init

> npx prisma generate

> npm run dev

6. No outro terminal rode os seguintes comandos:

> cd ./front

> npm install

> npm run dev

7. Para abrir o projeto no seu navegador, basta entrar nesta url: [http://localhost:5173/](http://localhost:5173/)
