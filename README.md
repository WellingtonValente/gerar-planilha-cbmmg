# Gerar Planilha – Modo Offline (XLSX local) + CSV fallback

Este pacote evita o erro **`XLSX is not defined`** carregando a biblioteca **localmente** (sem depender de CDN).
Se `xlsx.full.min.js` não estiver presente, o botão `.xlsx` fica desativado e o botão **Baixar .csv** continua funcionando.

## Como habilitar o .xlsx sem CDN
1. Baixe o arquivo da biblioteca SheetJS:
   - URL (qualquer uma):  
     - `https://cdn.jsdelivr.net/npm/xlsx@0.20.2/dist/xlsx.full.min.js`  
     - `https://unpkg.com/xlsx@0.20.2/dist/xlsx.full.min.js`
2. Salve o arquivo com o nome **`xlsx.full.min.js`** (exatamente assim).
3. Faça upload desse arquivo para o **mesmo diretório** do `index.html` no seu repositório GitHub Pages.
4. Aguarde 1–2 minutos e recarregue a página. O botão **Gerar .xlsx** ficará habilitado e funcional.

## Publicação (GitHub Pages)
- Branch: `main`
- Folder: `/ (root)`
- Link: `https://SEU_USUARIO.github.io/gerar-planilha-cbmmg/`

## Observações
- O botão **Baixar .csv** funciona sempre, mesmo sem a biblioteca XLSX.
- Excel abre CSV normalmente; use `.xlsx` quando quiser formatos avançados (fórmulas, estilos, múltiplas abas, etc.).
