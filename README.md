# Frontend Mentor - Recipe page solution

This is a solution to the [Recipe page challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/recipe-page-KiTsR8QQKm). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)


## Overview
Omelette recipe page

### Links

- Solution URL: [](https://www.frontendmentor.io/solutions/omelette-recipe-site-using-html-e-css-alZ94PQCqb)
- Live Site URL: [](https://fabriciocraft.github.io/recipe-omelette/)

## My process

### Built with

- HTML
- CSS

### What I learned

Use this section to recap over some of your major learnings while working through this project. Writing these out and providing code samples of areas you want to highlight is a great way to reinforce your own knowledge.

To see how you can add code snippets, see below:

```css

/*Importa font externa*/
@font-face {
font-family: 'Young Serif';
src: url('"C:\Users\fabri\Documents\Cubos Academy\Frontend Mentor\Página de Receitas\recipe-page-main\assets\fonts\young-serif\YoungSerif-Regular.ttf"') format('truetype');
font-weight: normal;
font-style: normal;

/*Marcador de tópico*/
#instructions{
    ol li::before{ 
    content: counter(item) ".";
    counter-increment: item;
    color: hsl(14, 45%, 36%);
    margin-right: 10px;
    font-weight: bold;
    
    }

/*Constroi tabela*/
table{
    width: 100%;
    border-collapse: collapse;
    
}
td{
    padding: 10px;
    
}
tr{
    border-bottom: 0.5px  rgb(223, 214, 214) solid;
}
  
```

