# 🛒 Lojinha TechStar — Projeto Universitário

Este projeto foi desenvolvido para fins **acadêmicos**, como parte das atividades da universidade, com o objetivo de praticar **HTML, CSS e JavaScript** aplicados à criação de uma página de loja virtual.

---

## 🎯 Objetivo do Projeto

Criar uma página funcional de catálogo de produtos com:

- Exibição dinâmica dos itens da loja  
- Sistema de busca  
- Layout responsivo e estilizado  
- Organização em **HTML + CSS + JS**  
- Manipulação de arrays e funções JavaScript  

---

## 🛠️ Tecnologias Utilizadas

- **HTML5** – Estrutura da página  
- **CSS3** – Estilização, grid e responsividade  
- **JavaScript** – Lógica, filtro de busca e renderização dos produtos  
- **Font Awesome** – Ícones  
- **Unsplash** – Imagens temporárias dos produtos  

---

## 🛒 Funcionalidades Implementadas

### ✔️ Catálogo Dinâmico

Os produtos são armazenados em um array de objetos no arquivo `scripts.js`.  
Cada item contém:

- `id`
- `title`
- `price`
- `discount`
- `image`

A função `createProductCard()` transforma cada produto em HTML, enquanto `renderProduct()` insere os cards dinamicamente na página.

---

### ✔️ Sistema de Busca

O usuário pode pesquisar produtos pelo nome.  
A busca é feita com filtragem em tempo real via a função `searchProducts()`.

---

### ✔️ Layout Responsivo e Moderno

- Grid de produtos (CSS Grid)  
- Cards com animação de hover  
- Header com logo e barra de busca  
- Hero (banner principal) configurável  

---

## 📂 Estrutura de Pastas

```bash
/Lojinha_fecaf
│
├── index.html        # Página principal
├── styles.css        # Estilos visuais
├── scripts.js        # Lógica e manipulação dos produtos
└── README.md         # Documentação do projeto
