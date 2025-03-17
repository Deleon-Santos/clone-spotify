


# Clone Spotify

Este projeto é uma réplica da interface web do Spotify e foi desenvolvido na imersão front-end da ALURA. Esta focado em recriar a experiência do usuário na navegação e visualização de playlists e artistas. O objetivo principal é demonstrar habilidades em desenvolvimento front-end e manipulação de DOM, utilizando as principais tecnologias e práticas do desenvolvimento web.

## Tecnologias Utilizadas

* **HTML:** Estrutura da página e conteúdo.
* **CSS:** Estilização e layout da interface.
* **JavaScript:** Interatividade, manipulação de dados e lógica da aplicação.
* **JSON:** Formato de dados para playlists e artistas.
* **Manipulação de DOM:** Interação dinâmica com os elementos da página.
* **Node.js:** Simulação de um backend simples para fornecer dados.

## Estrutura do Projeto

```clone-spotify/
├── src/
│   ├── assets/
│   │   ├── favicon.png
│   │   ├── logo-spotify.png
│   │   ├── playlist/
│   │   │   ├── 1.jpeg
│   │   │   ├── 2.png
│   │   │   ├── ...
│   │   ├── search.png
│   │   ├── small-left.png
│   │   ├── small-right.png
│   ├── estilos/
│   │   ├── main.css
│   │   ├── paginas.css
│   │   ├── reset.css
│   │   ├── root.css
│   │   ├── midaquerre.css
│   ├── data/
│   │   ├── playlists.json
│   │   ├── artists.json
├── script.js
├── index.html
├── package.json 
```

## Detalhamento das Tecnologias

### HTML

* Estrutura semântica: Uso de tags como `<header>`, `<nav>`, `<main>`, `<footer>`, `<section>`, `<div>`, `<span>`, `<img>`, `<a>`, `<input>` e `<button>` para organizar o conteúdo de forma lógica e acessível.
* Links e imagens: Utilização de `<a>` para navegação e `<img>` para exibição de imagens de playlists e artistas.
* Formulário de busca: Implementação de um `<input type="text">` para permitir a busca de conteúdo.

### CSS

* Reset CSS: Normalização de estilos com `reset.css` para garantir consistência entre navegadores.
* Variáveis CSS: Definição de cores, fontes e outros valores reutilizáveis em `root.css`.
* Layout flexbox e grid: Uso de `display: flex` e `display: grid` para criar layouts responsivos e flexíveis.
* Estilização de componentes: Criação de estilos para a barra lateral, cabeçalho, playlists, cards e outros elementos da interface.
* Media Queries: Criação de estilos responsivos para diferentes tamanhos de tela em `midaquerre.css`.

### JavaScript

* Manipulação de DOM: Uso de `document.querySelector`, `document.querySelectorAll`, `createElement`, `appendChild`, `innerHTML`, `classList` e outros métodos para interagir com os elementos da página de forma dinâmica.
* Eventos: Captura de eventos como `click`, `input` e `keydown` para adicionar interatividade à aplicação.
* Busca de conteúdo: Implementação da lógica de busca para filtrar playlists e artistas com base no texto digitado no campo de busca.
* Exibição de resultados: Atualização dinâmica da interface com os resultados da busca.
* Funções de pesquisa: criação de funções que pegam o que é digitado no input de pesquisa, e que manipulam o DOM, para que seja exibido o resultado da pesquisa para o usuário.

### JSON

* Dados de playlists: Armazenamento de informações sobre playlists em um arquivo `playlists.json`, incluindo nome, imagem e descrição.
* Dados de artistas: Armazenamento de informações sobre artistas em um arquivo `artists.json`, incluindo nome, imagem e gênero.
* Carregamento de dados: Utilização de `fetch` ou `XMLHttpRequest` para carregar os dados JSON e exibi-los na interface.

### Manipulação de DOM

* Criação de elementos: Geração dinâmica de elementos HTML com base nos dados JSON.
* Atualização de conteúdo: Modificação do conteúdo de elementos existentes para exibir informações de playlists e artistas.
* Adição e remoção de classes: Utilização de `classList.add` e `classList.remove` para controlar a exibição de elementos e aplicar estilos dinamicamente.

### Node.js 

* Servidor web: Criação de um servidor web simples com Node.js e Express para fornecer os arquivos JSON.
* Rotas: Definição de rotas para servir os dados de playlists e artistas.
* Facilitação do desenvolvimento: Permite simular um backend e facilita o carregamento de dados durante o desenvolvimento.

## Considerações Finais

Este projeto Clone Spotify é um excelente exercício para aprimorar suas habilidades em desenvolvimento front-end e manipulação de dados. Ao seguir esta documentação, você poderá entender melhor como as tecnologias se integram e como criar uma aplicação web interativa e responsiva.

## Subir a API para um server local 

```json-server ./api-artists/artists.json```

https://deleon-santos.github.io/clone-spotify/
