# Pixel Lagancy 🕹️

Uma loja de jogos retrô desenvolvida em HTML5, CSS3 e JavaScript puro. O sistema permite cadastrar novos títulos com informações personalizadas e mantém os dados salvos mesmo após atualizar a página (F5).

## ✨ Funcionalidades

*   **Cadastro Dinâmico:** Adicione jogos informando nome, empresa desenvolvedora, data de lançamento, imagem (URL) e preço.
*   **Persistência Local:** Utiliza `localStorage` para armazenar a lista de jogos diretamente no navegador do usuário.
*   **Design Responsivo:** Layout adaptável em formato de grid utilizando CSS Grid e Flexbox.
*   **Interface Retrô Moderno:** Paleta de cores selecionada com cinza escuro, cinza claro, branco e azul frio.
*   **Capa Padrão:** Proporção vertical (9:13) ideal para emular caixas e cartuchos clássicos.

## 🛠️ Tecnologias Utilizadas

*   HTML (estruturação e tags semânticas como `dialog`)
*   CSS (estilização, grid responsivo e transições)
*   JavaScript (manipulação de DOM e persistência com Web Storage)

## 📁 Estrutura do Projeto

*   `index.html` - Estrutura principal da aplicação e modal de cadastro.
*   `style.css` - Estilos visuais, cores e formatação das capas dos jogos.
*   `script.js` - Lógica de renderização de cards e salvamento local.
