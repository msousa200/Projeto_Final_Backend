# Objetivo da aplicação:

O objetivo desta aplicação é fornecer uma plataforma simples que possiblite a criação e visualização de posts.

## 2. Justificação Técnica da Escolha da Framework:

A escolha do Django como framework para desenvolvimento desta aplicação foi baseada em várias considerações técnicas:

- **Facilidade de Desenvolvimento:** Django é conhecido por sua facilidade de uso e sua rica coleção de bibliotecas e funcionalidades integradas. Isso acelera o processo de desenvolvimento, permitindo que nos concentremos na lógica de negócios da aplicação.
   
- **Administração Integrada:** Django fornece uma interface de administração integrada que facilita a administração dos dados do aplicativo diretamente no navegador, o que é útil durante o desenvolvimento e para gerenciamento de conteúdo posteriormente.

## 3. Processo de Instalação:

Para instalar e executar a aplicação, siga estas etapas:

1. Clone o repositório do projeto para o seu ambiente local.
2. Navegue até o diretório do projeto.
3. Instale as dependências do projeto usando o comando: docker-compose build 
4. De seguida execute o comando : docker-compose up 


## 4. Como utilizar a aplicação:

Após configurar e executar o projeto, você pode acessá-lo no seu navegador da web. A aplicação estará disponível em `http://localhost:8000/`.

A aplicação permite realizar as seguintes operações:

-Criação de uma conta de usuário
-Esta aplicação tem 4 secções, sendo estas o "home", o "about", o "Post" e o "new Post";
-Visualização de Posts existentes presentes na secção "Posts";
-Criação de novos Posts: para criar um novo post, clique no botão "New Post", preencha o formulário com o "title" , "body", "slug" e "banner" e depois clicar no botão "Add Post"





