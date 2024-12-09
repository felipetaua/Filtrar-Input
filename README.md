# Filtrar Input

Este projeto é uma aplicação simples para filtrar produtos em uma lista dinâmica usando dados de uma API. Ele utiliza a [Fake Store API](https://fakestoreapi.com/) para simular produtos de uma loja e permite ao usuário buscar por itens em tempo real.

[![Live Server](https://img.shields.io/badge/Live_Server-Click_Here-brightgreen?style=for-the-badge)](https://felipetaua.github.io/Filtrar-Input/)


## Funcionalidades

- Consumo de dados da [Fake Store API](https://fakestoreapi.com/).
- Exibição de produtos com imagens, títulos e links.
- Filtro de busca em tempo real com destaque para os textos correspondentes.
- Feedback visual quando nenhum item corresponde à busca.

## Tecnologias Utilizadas

- **HTML:** Estrutura da página.
- **CSS:** Estilização básica da interface (utilizando fontes do Google Fonts).
- **JavaScript:** 
  - Consumo da API com `fetch`.
  - Manipulação dinâmica do DOM.
  - Implementação do sistema de busca e filtro.

## Como Funciona

1. **Carregamento de Produtos:**  
   Os primeiros 10 produtos são carregados da API com a seguinte chamada:  
   ```javascript
   fetch('https://fakestoreapi.com/products?limit=10')
