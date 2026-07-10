# Farmacia Naturală Creștină — Landing Page

Página de vendas (em **romeno**) do ebook **"Farmacia Naturală Creștină — 30 de leacuri din vremea Bibliei"**, voltada ao público da página de Facebook *Descoperă Biblia* (Romênia, 35–65+).

## Deploy
- Site estático de um arquivo: **`index.html`** (na raiz) é a página que a Vercel serve.
- Sem build. Basta importar o repositório na Vercel → deploy automático.
- Preço do produto: **24,99 lei** (≈ 5 €). Checkout via Hotmart (trocar o link do botão de compra).

## Estrutura
- `index.html` — página final (documento completo, com charset; abre direto no navegador).
- `ESTUDO EBOOK PÁGINA/` — materiais internos de estratégia (não publicados no site):
  - `01-ESTUDO-ESTRATEGICO.md` — análise de público, funil, projeções.
  - `02-EBOOK-ESBOCO.md` — índice das 30 receitas bíblicas.
  - `03-PAGINA-DE-VENDAS.md` — especificação da página.
  - `04-DEPOIMENTOS.md` — modelos + como coletar depoimentos reais.
  - `pagina-vendas.html` — versão da página usada no preview.
- `estrutura-pagina-vendas.md` — template genérico de página de vendas.

## Pendências antes de publicar
- [ ] Trocar o link do botão de compra pelo checkout real da Hotmart.
- [ ] Substituir os depoimentos de exemplo por **depoimentos reais** (ver `04-DEPOIMENTOS.md`).
- [ ] Revisão final do romeno por falante nativo.
- [ ] Adicionar Política de Privacidade, Termos e Contato.
