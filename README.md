# Apostila Educador Infantil — Cianorte/PR

Site estático preparado para GitHub Pages.

## Estrutura

- `index.html` — painel de estudos
- `ranks/` — um arquivo por Rank
- `simulados/erros.html` — caderno de erros
- `simulados/geral.html` — acesso aos simulados
- `assets/style.css` — estilos compartilhados
- `assets/data.js` — questões e flashcards
- `assets/app.js` — progresso, busca, quizzes e navegação
- `assets/search-index.js` — índice de busca local

## Atualização no GitHub

Envie **todo o conteúdo deste diretório para a raiz do repositório**, substituindo o `index.html` antigo. O GitHub Pages continuará usando `index.html` como página inicial.

O progresso fica salvo no `localStorage` do navegador e usa o mesmo prefixo da versão anterior, preservando checklists e resultados já existentes quando possível.

## Ranks incluídos

1. BNCC + DCNEI
2. LDB
3. ECA
4. Vygotsky, Piaget e Wallon
5. Avaliação mediadora + Jussara Hoffmann

Rank 6 e posteriores podem ser adicionados em `ranks/` sem transformar novamente o site em uma página única.
