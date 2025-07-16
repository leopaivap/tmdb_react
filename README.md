# TMDB React

Projeto de uma biblioteca de filmes desenvolvido durante o curso "React do zero a maestria" da Udemy. A aplicação utiliza a API do The Movie Database (TMDB) para exibir os filmes mais bem avaliados, permitir a busca por filmes e visualizar detalhes de cada um.

## Funcionalidades

* **Listagem de Filmes:** Exibe uma lista dos filmes mais bem avaliados da atualidade.
* **Busca de Filmes:** Permite que o usuário busque por filmes através de um campo de busca.
* **Detalhes do Filme:** Mostra informações detalhadas sobre cada filme, como orçamento, receita, duração e descrição.

## Tecnologias Utilizadas

* **React:** Biblioteca JavaScript para a construção da interface de usuário.
* **React Router Dom:** Para o gerenciamento das rotas da aplicação.
* **React Icons:** Para a utilização de ícones na interface.
* **Vite:** Ferramenta de build para o desenvolvimento frontend.
* **CSS:** Para a estilização das páginas.

## Estrutura do Projeto

O projeto está estruturado da seguinte forma:

```
tmdb_react/
├── public/
│   └── vite.svg
├── src/
│   ├── assets/
│   │   └── react.svg
│   ├── Components/
│   │   ├── MovieCard.jsx
│   │   ├── Navbar.jsx
│   │   └── Navbar.css
│   ├── pages/
│   │   ├── Home.jsx
│   │   ├── Movie.jsx
│   │   ├── Search.jsx
│   │   ├── Movie.css
│   │   └── MovieGrid.css
│   ├── App.jsx
│   ├── App.css
│   ├── index.css
│   └── main.jsx
├── .env
├── .gitignore
├── index.html
├── package.json
└── vite.config.js
```