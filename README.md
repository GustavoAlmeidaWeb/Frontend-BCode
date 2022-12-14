# Frontend BCode

É necessário ter o [Node/NPM](https://nodejs.org/en/download/) instalado para funcionar o projeto.

## 1º Passo - Instalação das dependências do projeto

Execute o comando abaixo na pasta raiz do projeto:

```
npm install
```

## 2º Passo - Instalação do SASS

Para instalação do SASS no computador execute o seguinte comando:
 
```
npm install -g sass
```

Obs.: Quaisquer dúvidas acesse a [documentação do SASS](https://sass-lang.com/install)

## 3º Passo - Execução do SASS dentro do projeto

Acesse a pasta "/assets" de dentro do projeto no terminal e rode o seguinte comando:

```
sass --watch scss/config.scss:css/style.css
```

O único arquivo de SCSS que deve ser alterado é o style.scss.

## 4º Passo - Plugin VS Code

Uma dica para melhor produtividade instalar o plugin [Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer) e rodar no arquivo index.html.
