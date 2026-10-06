# 💻 TechNews Today — Desafio CSS (Aula 10)

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)

Projeto desenvolvido como entrega da **Aula 10**, cujo desafio consiste em transformar uma estrutura HTML semântica em um portal de notícias de tecnologia moderno no estilo **Dark Mode**, utilizando apenas CSS puro em no máximo **50 linhas de código**.

---

## 📌 Sobre o Projeto

O **TechNews Today** é um portal de notícias responsivo que explora recursos nativos e modernos do CSS para criar uma interface atraente e leve, mantendo a estrutura original do arquivo `desafio10a.html` intacta (sem alterações no HTML e sem o uso de JavaScript ou frameworks).

---

## 🎯 Requisitos do Desafio

- [x] **Glassmorphism:** Efeito de vidro fosco no cabeçalho utilizando `backdrop-filter`.
- [x] **Gradiente no Texto:** Título principal estilizado com efeito degradê.
- [x] **CSS Grid:** Alinhamento lado a lado para o vídeo incorporado e o formulário de newsletter.
- [x] **Header Sticky:** Cabeçalho fixo no topo ao rolar a página (`position: sticky`).
- [x] **Responsividade:** Adaptação perfeita para telas menores/celulares através de *@media queries*.
- [x] **Limite de Linhas:** Estilização desenvolvida em **no máximo 50 linhas** de CSS.
- [x] **Regras Estritas:** Desenvolvido sem frameworks (Tailwind, Bootstrap, etc.), sem JavaScript e mantendo o HTML original.

---

## 🧱 Estrutura Semântica do HTML

O projeto se baseia na estrutura semântica aprendida durante a aula:

- **`<header>`:** Cabeçalho com o título principal e efeito glassmorphism.
- **`<main>`:** Conteúdo principal da aplicação.
- **`<article>`:** Artigo de notícia com título, parágrafos, ênfases (`<strong>`, `<em>`) e o recurso nativo de "Leia mais" (`<details>` e `<summary>`).
- **`<section>`:** Layout em grid organizando o vídeo do YouTube (`<iframe>`) e a área da newsletter.
- **`<form>`:** Formulário de inscrição com validação nativa do navegador (`<input>`, `<select>`, `<checkbox>`, `<button>`).
- **`<footer>`:** Rodapé com informações institucionais.

---

## 📂 Estrutura do Repositório

```text
technews-today/
├── desafio10a.html    # Estrutura HTML semântica da página
├── 10a_desafio.css