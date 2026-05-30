Tema escolhido: Fan Page do Grêmio
Link do Projeto: https://kaueschwanck7.github.io/Front-End/
O projeto tem 4 paginas HTML e 1 CSS e os componentes usados foram navbar,dropdown,carousel,cards,modal collapse e offcanvas
O projeto usa Flexbox tanto via utilitários Bootstrap quanto em CSS personalizados
Responsividade sem JavaScript
Todo o comportamento responsivo (menu hamburguer, carousel, collapse, offcanvas) é gerenciado pelos atributos data-bs-* do Bootstrap, sem nenhuma linha de JavaScript próprio.
CSS custom properties (variáveis)
As cores do clube foram centralizadas em variáveis CSS no :root, o que permite alterar toda a paleta editando apenas 4 linhas no topo do style.css.
Especificidade e !important
Alguns elementos do Bootstrap (como .navbar) têm estilos inline ou de alta especificidade. Onde necessário, foi usado !important para garantir que o tema tricolor prevaleça sobre os defaults do framework.
Acessibilidade básica
Foram adicionados atributos aria-label nas sections, aria-current="page" no link ativo da navbar, e aria-hidden="true" nos ícones decorativos do carousel — práticas recomendadas de acessibilidade web.
Imagens externas
As imagens dos jogadores são carregadas de URLs externas. Em produção, o ideal seria baixar as imagens e servi-las localmente para maior performance e controle.
Fonte carregada via Google Fonts
As fontes Bebas Neue e Barlow dependem de conexão com internet. Offline, o navegador usará sans-serif como fallback definido no CSS.

🛠️ Tecnologias

HTML5 semântico
CSS3 (Flexbox, variáveis, animações, media queries)
Bootstrap 5.3.8
Google Fonts (Bebas Neue + Barlow)
