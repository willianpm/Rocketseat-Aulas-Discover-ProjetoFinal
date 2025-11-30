# Landing Page de Links (Linktree-style)

Este projeto é uma landing page simples, no estilo “Linktree”, criada para o Projeto Final (desafio prático) do curso **Discover** da **Rocketseat** com **Mayk Brito**.

Ela reúne links importantes em um só lugar, com visual agradável e opção de alternar entre tema claro e escuro.

---

## Principais Funcionalidades

- **Alternância de Temas (Dark/Light Mode):** Permite ao usuário trocar entre o tema escuro padrão e o tema claro, alterando cores, imagens de fundo e a imagem de perfil usando variáveis CSS e JavaScript.
- **Design Responsivo:** O layout é otimizado para mobile (Mobile-First) e adaptado para telas maiores através de Media Queries.
- **Lista de Links:** Centraliza chamadas para ações importantes (Ex: Orçamento, Catálogo, WhatsApp) em um formato de lista.
- **Ícones Sociais:** Integração com as redes sociais (Facebook e Instagram) utilizando a biblioteca **Ionicons**.
- **Animações CSS:** O botão de alternância de tema possui uma animação de slide (`slide-in` e `slide-back`) para uma transição suave entre os modos.

---

## Tecnologias Utilizadas

- **HTML5:** Estrutura semântica da página.
- **CSS3:** Estilização, incluindo:
  - **Variáveis CSS (`:root`):** Usadas para gerenciar e alternar facilmente as cores e imagens de fundo entre os temas.
  - **Media Queries:** Para garantir a responsividade em telas maiores.
  - **Propriedade `backdrop-filter`:** Efeito de desfoque nos elementos de fundo.
  - **Animações (`@keyframes`):** Para o botão de alternância.
- **JavaScript:** Lógica para a função `toggleMode()` que:
  - Adiciona/remove a classe `.light` no elemento `<html>`.
  - Altera o atributo `src` e `alt` da imagem de perfil para refletir o tema atual.

---

## Layout

O design do projeto segue o padrão proposto pela Rocketseat, com cores e estilos que se ajustam ao tema claro e escuro.

---

## Desenvolvedor

- Feito por Willian Martins
- Baseado no curso **Discover** da **Rocketseat**
- Professor: **Mayk Brito**
