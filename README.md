# HTML5-CSS3

**Introdução a criação de websites com HTML5 e CSS3**

1. História e estrutura básica
2. Semântica
3. Principais elementos do HTML

Requisitos:
* Editor de texto
* Navegador de internet

**Criador: Tim Bernes-Lee**

* HTML 1 - 1991
* HTML 2 - 1995
* HTML 3 - 1997
* HTML 4 - 1997
* HTML 5 - 2014

## Elemento HTML:

* <h1 class="titulo">Título</h1> - Elemento HTML
* <h1 ...>  - Abrindo a TAG
* class="titulo" - Atributo
* Título -  Conteúdo
* </h1> - fechamento da TAG

## Estrutura básica

<!DOCTYPE html>                 #informo ao navegador oque estou escrevendo
<html>
    <head>                      
        <meta>                  #Meta informações para orientar buscador #Charset, define conjunto de caracteres, codificação
        <title></title>         #Título na aba do navegador
    </head>
    <body>
    </body>
</html>

# Semântica

## HTML 4
<div>
</div>

## HTML 5
Novos elementos:
* <section> # Representa uma seção genérica / lista de artigos
* <header>  # Cabeçalho de uma página ou section
* <article> # Conteúdo relevante, artigo de um blog  
* <aside>   # Conteúdo relacionado ao relevante
* <footer>  # Rodapé da página, article ou section
* <h1>-<h6> # Títulos dentro de uma página 
* <h1>      # Título da página (apenas um por página)
* <h2>      # Título da section
* <h3>      # Título do artigo
* <p>       # Conteúdo do artigo

# Textos e Links

**Compartilhar textos e documentos, objetivos HTML**

<p>Parágrafo</p> # Textos maiores e mais densos (imagens, códigos, vídeo)
<a>Link</a>
<a href="https://www.linkedin.com/in/davi-jose-araujo-b70aa021/?lipi=urn%3Ali%3Apage%3Ad_flagship3_feed%3BDg6PYyzfRqG1dXD8VaLNZw%3D%3D">Linkedin</a>
<a href="mailto:davijose@gmail.com">E-mail</a>
<a target="_blank">Link</a>

# Imagens
<img>
<img alt="Foto de Davi José">
<image src="img/avatar.jpg>

*Dica: remover meta informações de imagens no endereço TinyPNG.com*

# Lista

*Agrupar coleção de itens*

<ul> ## Ordem dos itens não é importante
<ol> ## Ordem dos itens é importante (número, letras, algarismos romanos)
<li> ## Item das lista

# CSS3

**Objetivos**

* 1. Oque são seletores
* 2. Conceitos Básico
* 3. Principais Seletores

Requisitos:
* Editor de texto
* Navegador de internet
* Aulas de HTML5

Liguagem de estilo com sintaxe bem simples, regras de estilo para elementos ou grupos de elementos

* Seletores a, p, h1, h3
* Declarações:
* Color: blue;
* font-size: 14px;

## ID X Classe

<header id="header" class="header"></header>
<header class="header"></header>

## Editar um elemento específico:
.header {
    padding: 10px;
}

## Editar um grupo de elementos:
#header {
    padding: 15px;
}

# Box Model
Alterar aparência da caixa 
* 1. Margin     # Espaçamento entre elementos;
* 2. Border     # Circundam o padding e conteudo, conseguimos alterar largura e cor;
* 3. Padding    # Espaçamento entre borda e conteúdo;
* 4. Content    # Conteúdo pode ser texto, imagem ou vídeo.

# Estilizando Elementos

## Padding e Margin

.post {
    padding: 10px 5px 5px 10px;
    }

Um valor para cada lado, na sequência: topo, direita, inferior e esquerda. Outra forma:


.post {
    padding-top: 10px;
    padding-right: 5px;
    padding-bottom: 5px; 
    padding-left: 10px;
    }

## Background

.post {
    background-color: #fff;
    background-image: url("bg.png");
    background-color: top;
}

https://developer.mozilla.org/pt-BR/

.post {
    background-color: green;
    background-color: #008000;
    background: #008000;
}

**Cor em inglês ou Hexadecimal**

## Border

Largura em pixels, centímetros ou milímetros
Cor:  blue, #0000ff...
Estilo: sólida, pontilhada ou tracejada.

.post {
    border: 3px solid blue;
    border-top: 2px dotted green;
    border-right: 4px dashed pink;
}

.post {
    border-top: 3px solid blue;
    border-right: 2px dotted green;
    border-bottom: 4px dashed pink;
    border-left: 4px dashed pink;
}

.post {
    border: 3px solid #505050;
}

.post {
    border-width: 3px;
    border-color: #505050;
    border-style: solid;
}

.post {
    border-top-width: 3px;
    border-top-color: #505050;
    border-top-style: solid;
}

## Border-radius

border-radius: 10px;
border-radius: 50%;
border-radius: 10% 20%;
border-radius: 10% 20% 15% 22%;

## Etilizando texto

.title {
    font-family: Verdana;
    font-size: 30px;
    font-style: normal;
    font-weight: normal;
    text-transform: uppercase;
    text-decoration: underline;
}

.subtitle {
    font-family: Verdana, Arial;
    font-size: 18px;
    font-style: italic;
    font-weight: bold;
    text-transform: lowercase;
    text-decoration: overline;
}

.post_title {
    text-transform: capitalize;
    text-decoration: line-through;
}

## Estilizando Listas

ol {
    list-style-type: square;
}

ul {
    list-style-type: upper-roman;
}

ul {
    list-style-type: "\1F44D";
}

ol {
    list-style-image: url("rockert.png");
}

a {
    text-decoration: line-through;
    color: #505050;
}

.contact_list {
    list-style-type: none;
    padding-left: 15px;
}

.contact_list li a  {
    color: blue;
}

# Dimensão e Alinhamento

Widht       - Altura
Height      - Largura

Max-width   - Altura máxima
Max-height  - Largura máxima

Margin      - Espaçamento entre elementos, alinhar elemento  automaticamente
 
Text align - Alinha textos
