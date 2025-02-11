# Google-clone# Clone da Página Inicial do Google

Este projeto consiste na recriação da página inicial do Google, incluindo responsividade e funcionalidade de busca.

## Tecnologias Utilizadas
- HTML5
- CSS3
- JavaScript

## Funcionalidades
- Layout responsivo para diferentes dispositivos
- Campo de pesquisa funcional
- Redirecionamento para o Google Search com os termos digitados pelo usuário

## Estrutura do Projeto
```
/
|-- index.html  # Estrutura da página
|-- style.css   # Estilos para a página
|-- script.js   # Funcionalidade da barra de pesquisa
```

## Como Executar
1. Baixe ou clone o repositório.
2. Abra o arquivo `index.html` em um navegador.
3. Digite um termo no campo de pesquisa e pressione "Enter" para ser redirecionado ao Google Search.

## Implementação da Pesquisa
A funcionalidade de busca é implementada em `script.js` usando JavaScript para capturar o texto inserido e redirecionar o usuário para o Google Search:
```javascript
document.getElementById("search-form").addEventListener("submit", function(event) {
    event.preventDefault();
    let query = document.getElementById("search-input").value;
    window.location.href = `https://www.google.com/search?q=${encodeURIComponent(query)}`;
});
```


---
Projeto criado para fins educativos e práticos.

