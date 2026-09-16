# public-pages

Páginas HTML avulsas, servidas via **GitHub Pages**. Um projeto por pasta; a raiz é um hub que lista os projetos.

**Ao vivo:** https://lesserwords.github.io/public-pages/

## Estrutura

- **Raiz** (`index.html`) — hub que lista automaticamente as pastas de projeto do repo.
- **`<projeto>/index.html`** — índice do projeto, lista automaticamente os `.html` daquela pasta.

## Projetos

### Keroshop — `keroshop/`

Aplicação: https://keroshop.com.br · App: https://app.keroshop.com.br

| Página | URL |
|--------|-----|
| Índice do projeto | https://lesserwords.github.io/public-pages/keroshop/ |
| Briefing (one-pager de vendas) | https://lesserwords.github.io/public-pages/keroshop/briefing.html |
| Progresso (estado de implementação) | https://lesserwords.github.io/public-pages/keroshop/progress.html |

## Adicionar um projeto novo

1. Crie uma pasta na raiz do repo com um `index.html`. Copie o `keroshop/index.html` como base e ajuste `DIR` para o nome da pasta.
2. Faça commit e push na `main`. A pasta aparece no hub da raiz automaticamente.

## Adicionar uma página a um projeto

1. Coloque um arquivo `.html` completo e independente dentro da pasta do projeto (com `<!doctype html>`, `<head>`, `<body>`).
2. Commit e push na `main`. Aparece no índice do projeto automaticamente — o `index.html` lista todo `.html` daquela pasta (menos ele mesmo) pela API pública do GitHub, sem lista pra manter. O título do card vem do nome do arquivo (`minha-pagina.html` → "Minha Pagina").

O GitHub Pages reconstrói em ~1–2 min após o push; recarregue forçado se aparecer a versão antiga.

## Notas

- `.nojekyll` desliga o processamento Jekyll — os arquivos são servidos como estão.
- Fonte do Pages: `main` / raiz, HTTPS forçado.
- Tudo aqui é **público**. Não faça commit de nada privado.
