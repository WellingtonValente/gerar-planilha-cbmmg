# Gerar Planilha — CBMMG (Client-side, grátis)

Ferramenta estática para converter **CSV/JSON → Excel (.xlsx)** **no navegador do usuário**, sem servidor e sem custos.
Ideal para servir como *fallback* quando o GPT não puder enviar anexos a contas gratuitas.

## Publicação (GitHub Pages)
1. Crie um repositório público chamado `gerar-planilha-cbmmg`.
2. Faça upload do `index.html` (este repositório contém um exemplo pronto).
3. Ative **Settings → Pages → Build and deployment → Deploy from branch** (branch `main`, pasta `/root`).
4. Acesse: `https://SEU_USUARIO.github.io/gerar-planilha-cbmmg/`

## Uso no GPT
Instrua o GPT a sempre fornecer os dados também em **CSV** e **JSON**. Se anexos estiverem bloqueados, oriente o usuário a colar o conteúdo no link acima e clicar em **Gerar .xlsx**.

---
**Observação:** Esta solução é 100% client-side (SheetJS) e não envia dados a servidores.
