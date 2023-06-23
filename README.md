# genius-snippets README

Biblioteca de snippets para automatizar comandos mais utilizados no dia a dia de trabalho do time de Genius

## Features

Snippets de código
```javascript
// digite iife
(() => {
  
})()


// digite delay
document.addEventListener('DOMContentLoaded', () => {
  //trecho de código aqui
});

// digite major-delay
document.addEventListener('readystatechange', event => { 
  if (event.target.readyState === "complete") {
    //trecho de código aqui
  }
});

// digite addstyle
const addStyle = (styles) => {
  const css = styles,
    head = document.head || document.getElementsByTagName('head')[0],
    style = document.createElement('style');
  head.appendChild(style);
  style.setAttribute('type', 'text/css');
  if (style.styleSheet) {
    // This is required for IE8 and below.
    style.styleSheet.cssText = css;
  } else {
    style.appendChild(document.createTextNode(css));
  }
};
```
---
Snnipets com padrões para subir script no admin
```htm
// digite script-ftp
<!-- descreva a tarefa - GENIUSATD-1234 -->
<!-- 22/06/2023 | Autor -->
<script src="https://legado.autoforce.com.br/plugins/teste.js"></script>

// digite script-inline
<!-- descreva a tarefa - GENIUSATD-1234 -->
<!-- 22/06/2023 | Autor -->
<script>
  
</script>

// digite style-ftp
<!-- descreva a tarefa - GENIUSATD-1234 -->
<!-- 22/06/2023 | Autor -->
<link rel="stylesheet" href="https://legado.autoforce.com.br/plugins/teste.js">

// digite style-inline
<!-- descreva a tarefa - GENIUSATD-1234 -->
<!-- 22/06/2023 | Autor -->
<style>
  
</style>
```

## Contribute

Fiquem a vontade para contribuir para o projeto

[Documentação do Visual Studio Code para criação de snippets](https://code.visualstudio.com/api/language-extensions/snippet-guide)