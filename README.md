# TechBlog
Blog Tarefa StackX

🚀 Tech Blog 2025

Um blog estático moderno focado em tecnologias de desenvolvimento web, construído com HTML, CSS e JavaScript. Ideal para compartilhar artigos sobre Frontend, Backend, DevOps e outras tendências tech!

## estrutura

tech-blog-2025/
├── index.html          # Página inicial com lista de posts
├── post.html           # Página de post completo
├── js/
│   ├── main.js         # Lógica da página inicial (filtros, temas)
│   ├── post.js         # Carrega conteúdo do post
│   └── posts.js        # Banco de dados de posts (títulos, conteúdo, imagens)
├── css/
│   └── style.css       # Estilos globais e temas
└── img/                # Pasta para imagens dos posts

## Funcionalidades

- **Filtro de categorias:** Exiba posts específicos (Frontend, Backend, DevOps) ou todos de uma vez.
- **Tema claro/escuro:** Alternância suave entre modos de cor, com persistência via `localStorage`.
- **Contador de visualizações:** Acompanhe quantas vezes cada post foi acessado.
- **Design responsivo:** Adapta-se a qualquer dispositivo (desktop, tablet, mobile).
- **Posts dinâmicos:** Conteúdos carregados via JavaScript a partir de um arquivo central (`posts.js`).
- **Navegação intuitiva:** Botão de retorno estilizado e navbar fixa.
- **Acessibilidade melhorada:** Cores com alto contraste e texto justificado.

## Tecnologias

- **HTML5** (Estrutura semântica)
- **CSS3** (Grid, Flexbox, Variáveis, Media Queries)
- **JavaScript Vanilla** (Manipulação do DOM, `localStorage`)
- **Font Awesome** (Ícones sociais)
- **Google Fonts** (Fonte Inter)
