# CoffeLab

Este é um projeto de site para o CoffeLab, uma cafeteria que busca criar um ambiente acolhedor e comunitário. Este repositório contém o código-fonte do site, que inclui uma página inicial, seções sobre, preços e um blog.

## Estrutura do Projeto

Index.html= Este é o arquivo HTML principal que estrutura a página do site. Ele contém a navegação, carrossel, seções sobre, preços e blog.
  
- **style.scss**: Este arquivo é utilizado para estilizar o site. Ele é escrito em SASS (Syntactically Awesome Style Sheets), uma extensão do CSS que permite usar variáveis, aninhamento e outras funcionalidades que tornam o CSS mais poderoso e fácil de manter.

- **gulpfile.js**: Este arquivo é usado para automatizar tarefas de desenvolvimento. Gulp é uma ferramenta de automação que ajuda a compilar SASS em CSS, minificar arquivos, otimizar imagens e outras tarefas que facilitam o desenvolvimento. O `gulpfile.js` define as tarefas que podem ser executadas com um simples comando, economizando tempo e esforço.

- **package.json**: Este arquivo contém informações sobre o projeto e suas dependências. Ele lista os pacotes necessários para o projeto, como Gulp e SASS, e permite que você instale facilmente essas dependências usando o npm (Node Package Manager). Ao executar `npm install`, todas as dependências listadas no `package.json` serão instaladas na pasta `node_modules`.

- **node_modules**: Esta pasta contém todas as dependências do projeto que foram instaladas através do npm. Não é necessário editar ou adicionar arquivos diretamente nesta pasta, pois ela é gerenciada pelo npm.

## Como Configurar o Projeto

1. **Clone o repositório**:
   ```bash
   git clone https://github.com/seu-usuario/coffelab.git
   cd coffelab

            