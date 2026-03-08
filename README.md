# 🎬 Catálogo de Filmes Inteligente

Aplicação interativa de página única (SPA) projetada para o gerenciamento pessoal de acervos cinematográficos. O projeto foca em **persistência de dados client-side** e **experiência do usuário reativa**.

## 🚀 Funcionalidades Principais

* **Gerenciamento Dinâmico (CRUD):** Interface intuitiva para adição e remoção de títulos por categoria em tempo real.
* **Sorteador Inteligente:** Algoritmo que utiliza filtragem de status para ignorar filmes marcados como "vistos" e histórico de sessão para evitar repetições consecutivas.
* **Persistência Local:** Implementação da *Web Storage API* (LocalStorage), garantindo que os dados e marcações permaneçam salvos no navegador sem a necessidade de um banco de dados externo.
* **UI/UX Refinada:**
* **Modo Escuro/Claro:** Alternância dinâmica de temas com salvamento automático da preferência do usuário.
* **Scroll Inteligente:** Navegação por âncoras que centraliza a categoria selecionada no meio da tela para melhor visualização.
* **Identidade Visual:** Aura de brilho estática e minimalista nos botões, respeitando a paleta de cores de cada gênero.

## 🛠️ Tecnologias Utilizadas

* **Python:** Utilizado para a estruturação lógica do dicionário de dados (`filmes_storage`) e geração automatizada do arquivo HTML final.
* **JavaScript (ES6+):** Motor de interatividade, responsável pela lógica do sorteador, manipulação do DOM e gerenciamento do LocalStorage.
* **CSS3:** Estilização avançada com variáveis dinâmicas (`:root`), Flexbox, Grid e animações de transição.
* **HTML5:** Estruturação semântica e interface responsiva.

## 📦 Como Utilizar

1. Acesse o repositório e faça o download do arquivo `catalogo_filmes.html`.
2. Abra o arquivo em qualquer navegador moderno (Chrome, Firefox, Edge).
3. Utilize o painel superior para personalizar sua lista. Todas as alterações serão mantidas automaticamente.
