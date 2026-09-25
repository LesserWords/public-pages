# public-pages

Páginas públicas, ferramentas e recursos interativos servidos via **GitHub Pages**. Um projeto por pasta; a raiz é um hub dinâmico que organiza os projetos com fallback estático instantâneo.

**Ao vivo:** [https://lesserwords.github.io/public-pages/](https://lesserwords.github.io/public-pages/)

---

## Estrutura do Repositório

- **Raiz (`index.html`)** — Hub central com barra de navegação global, cartões estáticos de acesso rápido e auto-listagem dinâmica via GitHub API.
- **`keroshop/`** — Documentos e status comercial da plataforma Keroshop.
- **`venture-capital/`** — Inteligência de mercado de venture capital, diretório de 184 investidores, 70 gestoras/incubadoras e templates de modelagem financeira (DRE).
- **`.nojekyll`** — Desativa o processamento Jekyll, garantindo que os arquivos HTML/CSS/JS sejam servidos exatamente como versionados.

---

## Projetos Publicados

### 1. Keroshop — `keroshop/`
Plataforma que transforma URLs e redes sociais em marcas e lojas completas com inteligência artificial.
- **Aplicação ao vivo:** [keroshop.com.br](https://keroshop.com.br)
- **Painel / App:** [app.keroshop.com.br](https://app.keroshop.com.br)

| Página | Descrição | URL |
|---|---|---|
| **Índice do Projeto** | Visão geral dos documentos Keroshop | [Ver Página](https://lesserwords.github.io/public-pages/keroshop/) |
| **Briefing Comercial** | One-pager de vendas, proposta de valor e modelo de negócio | [Ver Página](https://lesserwords.github.io/public-pages/keroshop/briefing.html) |
| **Progresso & Roadmap** | Auditoria e estado de implementação técnica das capacidades | [Ver Página](https://lesserwords.github.io/public-pages/keroshop/progress.html) |

---

### 2. Venture Capital & Modelagem Financeira — `venture-capital/`
Diretório interativo de investidores no Brasil e acervo de planilhas de DRE para startups em fase de captação.
- **Dados Brutos:** Planilhas originais disponíveis para download direto em CSV e XLSX na pasta `venture-capital/dados/`.

| Página | Conteúdo | URL |
|---|---|---|
| **Mapa de VCs (184)** | Diretório com busca em tempo real, filtros por modalidade (Early Stage, Aceleradoras, Anjos, CVC, etc.), teses, faixas de cheque e requisitos | [Acessar Diretório](https://lesserwords.github.io/public-pages/venture-capital/) |
| **Fundos & Incubação (70)** | Lista consolidada de 70 gestoras, programas de aceleração e hubs de inovação com links diretos | [Acessar Lista](https://lesserwords.github.io/public-pages/venture-capital/incubadoras-fundos.html) |
| **Modelos de DRE & Métricas** | Análise e prévia interativa do modelo padrão Bossa Nova (SaaS), DRE de Produtos (CMV/ICMS) e Serviços, além de glossário de métricas (CAC, LTV, Burn Multiple, Runway) | [Ver Modelos](https://lesserwords.github.io/public-pages/venture-capital/modelos-dre.html) |

---

## Como Adicionar um Novo Projeto

1. Crie uma nova pasta na raiz do repositório (ex: `meu-projeto/`).
2. Adicione um `index.html` com o conteúdo ou utilize o layout padrão com a barra de navegação compartilhada (`top-nav`).
3. Faça commit e push para a branch `main`:
   ```bash
   git add .
   git commit -m "Add meu-projeto"
   git push origin main
   ```
4. O GitHub Pages atualiza o hub e publica a nova pasta em cerca de 1 a 2 minutos.

---

## Políticas e Privacidade

- Todo o conteúdo deste repositório é **público**. Nunca faça commit de segredos, tokens de API ou informações confidenciais.
- Codificação padrão: **UTF-8**.
