# 🚀 Desafio 03 - Bootcamp Ignite (Rocketseat)
![node-js-badge](https://img.shields.io/badge/Node.js-43853D?style=for-the-badge&logo=node.js&logoColor=white) ![js-badge](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

## 📙 1. Sobre o desafio
Este desafio consiste na correção de diversos erros de escrita de código em um template já disponibilizado pela Rocketseat.

## 🏃 2. Como rodar o desafio
Basta dar um git clone neste repositório, carregar as dependências, executar o comando para iniciar o servidor Node e utilizar algum software como Insomnia ou Postman para as requisições
```
git clone https://github.com/Seiixas/desafio03-ignite-nodejs.git
cd desafio03-ignite-nodejs
yarn
yarn dev
```

## ⚙️ 3. Funcionalidades
### 😃 3.1. Criar um novo repositório.
Utilizando a rota `localhost:3333/repositories` no metodo POST é possível criar um novo repositórios com os seguintes parâmetros:
```json
{
    "title": "Desafio 03",
    "url": "https://github.com/Seiixas/desafio03-ignite-nodejs",
    "techs": ["JavaScript", "Node.JS"]
}
```

### 👍 3.2. Dar like em repositório.
Utilizando a rota `localhost:3333/repositories/:id/like` no metodo POST é possível adicionar um like no repositório.

### 📜 3.3. Listar todos os repositórios
Utilizando a rota `localhost:3333/repositories` no método GET, é possível listar todos os repositórios cadastrados.

### 📝 3.4. Editar um repositório existente
Utilizando a rota `localhost:3333/repositories/:id` no método PUT, é possível alterar um repositório já existente com os seguintes parâmetros: 
```json
{
    "title": "Desafio 03",
    "url": "https://github.com/Seiixas/desafio03-ignite-nodejs",
    "techs": ["JavaScript", "Node.JS"]
}
```

### ❌ 3.5. Deletar um repositório
Utilizando a rota `localhost:3333/repositories/:id` no método DELETE, é possível deletar um repositório específico.
