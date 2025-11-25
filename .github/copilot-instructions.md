<!-- Arquivo gerado por assistente. Revise e ajuste conforme necessário. -->
# Instruções rápidas para agentes de código (Copilot / AI)

Este repositório atualmente contém um único arquivo: `index.html` (vazio). Use estas instruções para ser prático e seguro ao trabalhar aqui.

- **Contexto do repositório**: há apenas `index.html` no diretório raiz. Não há sistema de build, testes automatizados, nem pastas de código/estilos detectadas.

- **Objetivo de curto prazo**: antes de fazer grandes mudanças (criar estruturas, adicionar bundlers, mover arquivos), confirme com o mantenedor que é desejado — o repositório parece ser um site estático simples.

- **Quando editar `index.html`**:
  - Preserve a estrutura existente (se houver conteúdo). Se o arquivo estiver vazio, crie mudanças mínimas e explicáveis em um PR.
  - Se adicionar dependências (ex.: Bootstrap via CDN), documente a escolha no cabeçalho do `index.html` e no novo `README.md`.

- **Visualizar localmente**: não há comando de build; para visualização local use um servidor HTTP simples. Exemplos:

  - `python3 -m http.server 8000` — abre `http://localhost:8000` no navegador.
  - `npx http-server -p 8000` — alternativa com Node.js.

- **Fluxo de PR / commits**:
  - Pequenas mudanças únicas: commite em branch descritiva `feat/…` ou `fix/…` e abra PR.
  - Explique o porquê das mudanças no corpo do PR (ex.: adicionar header, configurar CDN, implementar layout responsivo).

- **Padrões detectáveis**: atualmente não há convenções de código a partir dos arquivos presentes. Se você introduzir convenções (p.ex. `styles/`, `scripts/`, `assets/`), documente-as num `README.md` na raíz.

- **O que NÃO fazer sem confirmação**:
  - Não adicionar ferramentas de build (Webpack, Vite, etc.) sem orientação do mantenedor.
  - Não remover ou renomear `index.html` sem avisar — pode ser a página principal esperada.

- **Sugestões ao criar novos arquivos**:
  - Se adicionar CSS/JS, prefira pastas `css/` e `js/` ou `assets/` e referencie com caminhos relativos no `index.html`.
  - Inclua um `README.md` breve explicando como visualizar e quais decisões foram tomadas.

- **Se precisar de mais contexto**: abra uma issue ou peça ao mantenedor informações sobre:
  1. propósito do projeto (site estático, exercício de curso, template, etc.);
 2. expectativas de deploy (p.ex. GitHub Pages);
 3. preferências por CDN vs dependências locais.

---

Se desejar, eu posso:
- gerar um `README.md` minimal descrevendo como rodar o servidor local;
- adicionar um `index.html` de exemplo com Bootstrap (após confirmar que é desejado);
- ou manter alterações pequenas e abrir um PR com descrição. Diga qual opção prefere.
