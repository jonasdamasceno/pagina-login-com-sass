# Criando Landing Page com Sass

Este projeto consiste na criação de uma landing page utilizando Sass para a estilização.

## Autor

**Jonas Michael Oliveira Damasceno**

## Introdução

Neste artigo, vamos criar uma landing page usando Sass para a estilização. Caso não saiba usá-lo, tem um artigo meu que mostra como usar o sass.

A landing page será sobre uma empresa de marketing que deseja capturar mais clientes para sua empresa.

## Configurando o Ambiente

Nessa parte, vou mostrar as configurações básicas que serão feitas no editor Visual Studio Code, caso estiver usando outro editor, pule para a próxima parte.

Para esse projeto, precisará instalar duas extensões:

1. Live Server: usado para iniciar um servidor estilo nodemon.
2. Live Sass: converterá automaticamente os arquivos .scss para css.

## Estrutura de Pastas

Abaixo estará a estrutura de pastas do projeto:

| index.html
| sass
| header.scss
| contents.scss
| variables.scss
| index.scss

php
Copy code

## Iniciando o Projeto

### HTML

Primeiramente, iniciaremos o Live Server e o Live Sass. Assim, começaremos editando o `index.html`, que terá a estrutura inicial de HTML5:

```<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="index.scss">
    <title>Document</title>
</head>
<body>
    <header>
        <h1>Aprenda Markenting</h1>
    </header>
    <main>
        <div class="text">
            <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit.</p>
            <p>Lorem ipsum dolor sit amet, adipiscing.</p>
            <p>Lorem ipsum dolor sit amet elit.</p>
        </div>
        <div class="form">
            <h2>Preencha abaixo os campos para receber os videos</h2>
            <form>
                <label>Nome</label>
                <input type="text"/>
                <label>Email</label>
                <input type="email"/>
                <label>Setor</label>
                <input type="text"/>
                <button>Enviar</button>
            </form>
        </div>
    </main>
</body>
</html>
