
# Site — Ferramentas Jurídicas (Gustavo Sella)

Multi-página estático, pronto para GitHub Pages.

## Estrutura
```
site_gustavo_sella/
  index.html
  busca-jurisprudencia.html
  xo-juridiquez.html
  assistente-peticao.html
  analise-processo.html
  assessoria-imprensa.html
  filtra-trt.html
  hub-gpt.html
  404.html
  assets/logo.svg
  README.md
```

## Publicar no GitHub Pages
1) Crie um repositório no GitHub, por exemplo: `ferramentas-gustavo-sella`.
2) Faça upload de **todos os arquivos** desta pasta (ou use Git):
   ```bash
   git init
   git add .
   git commit -m "Site: Ferramentas Jurídicas"
   git branch -M main
   git remote add origin https://github.com/SEU_USUARIO/ferramentas-gustavo-sella.git
   git push -u origin main
   ```
3) No GitHub: *Settings* → *Pages* → **Source**: `Deploy from a branch` → Branch: `main` → Folder: `/ (root)` → **Save**.
4) Aguarde a build. O site ficará disponível em: `https://SEU_USUARIO.github.io/ferramentas-gustavo-sella/`

## Editar cores/tema
- O botão no cabeçalho alterna entre **escuro** e **claro** (persistência com `localStorage`).
- Para substituir o logo, troque `assets/logo.svg`.

## Ajustes
- Para alterar os links do ChatGPT, edite o botão “Abrir no ChatGPT” em cada página.
- Para adicionar novas páginas, duplique um arquivo `.html` e inclua o item no menu.
