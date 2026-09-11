# public-pages

Páginas HTML avulsas da Keroshop, servidas via **GitHub Pages**.

**Ao vivo:** https://lesserwords.github.io/public-pages/

## Aplicação

| Ambiente | URL |
|----------|-----|
| Landing (site) | https://keroshop.com.br |
| App | https://app.keroshop.com.br |

## Páginas

| Página | URL |
|--------|-----|
| Índice (hub) | https://lesserwords.github.io/public-pages/ |
| Briefing (one-pager de vendas) | https://lesserwords.github.io/public-pages/briefing.html |
| Progresso (estado de implementação) | https://lesserwords.github.io/public-pages/progress.html |

## Adicionar uma página nova

1. Coloque um arquivo `.html` completo e independente na raiz do repo (com `<!doctype html>`, `<head>`, `<body>`).
2. Faça commit e push na `main`.
3. Ela aparece no índice automaticamente — o `index.html` lista todo `.html` do repo (menos ele mesmo)
   pela API pública do GitHub, então não há lista pra manter. O título do card vem do nome do arquivo
   (`minha-pagina.html` → "Minha Pagina").

O GitHub Pages reconstrói em ~1–2 min após o push; recarregue forçado se aparecer a versão antiga.

## Notas

- `.nojekyll` desliga o processamento Jekyll — os arquivos são servidos como estão.
- Fonte do Pages: `main` / raiz, HTTPS forçado.
- Tudo aqui é **público**. Não faça commit de nada privado.
