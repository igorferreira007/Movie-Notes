# RocketMovies 🎥

![Screenshot_45](https://github.com/user-attachments/assets/dbe8b166-f711-4132-b974-f3644155bf66)

RocketMovies é uma aplicação web para os amantes de cinema. Com ela, é possível criar, editar, remover e pesquisar notas sobre filmes, além de gerenciar seus dados pessoais.

## 🌟 Funcionalidades

- **Autenticação de usuários**: Login e cadastro para acesso à aplicação.
- **Gerenciamento de notas**:
  - Criar, editar, e excluir notas de filmes.
  - Adicionar marcadores às notas (Exemplo: aventura, ação, Marvel).
  - Pesquisar notas por título ou marcador.
- **Perfil do usuário**:
  - Atualizar nome, e-mail, senha e foto de perfil.

## 🛠️ Tecnologias Utilizadas

### **Frontend**
- **React**: Biblioteca para construção de interfaces.
- **Styled-components**: Para estilização baseada em componentes.
- **Axios**: Para requisições HTTP.
- **Vite**: Usado para criar o projeto React.

### **Backend**
- **Node.js**: Plataforma para construção do servidor.
- **Express**: Framework para desenvolvimento backend.
- **CORS**: Middleware para lidar com políticas de origem cruzada.
- **Knex**: Query builder para interações com o banco de dados.
- **SQLite**: Banco de dados leve e eficiente.

### **Ferramentas**
- **Insomnia**: Testes de API.
- **Netlify**: Hospedagem do frontend.
- **Render**: Hospedagem do backend.

## 🚀 Resultado final

- **Publicado em**: [RocketMovies na Netlify](https://rocketmovies-by-igor.netlify.app/)

## 🎯 Como Rodar o Projeto Localmente

### Pré-requisitos
- Node.js instalado.
- Gerenciador de pacotes (npm ou yarn).
- SQLite3.

### 1. Clone o repositório:
    ```bash
    git clone https://github.com/seu-usuario/rocketmovies.git
    cd rocketmovies




2. Configuração do Backend:

Instale as dependências:

    ```
    npm install

Configure o banco de dados SQLite com Knex:

    ```
    npx knex migrate:latest

Inicie o servidor:

    ```
    npm run dev

3. Configuração do Frontend:

Instale as dependências:

    ```
    npm install

Inicie o servidor de desenvolvimento:

    ```
    npm run dev
