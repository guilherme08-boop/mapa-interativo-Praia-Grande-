
# Mapa Cultural de Praia Grande – Polos & PICs

Como abrir no computador (Windows/macOS):
1) **Baixe e extraia** este ZIP para uma pasta. 
2) Instale o **Python 3** (se ainda não tiver).
3) Abra o **Prompt de Comando (Windows)** ou **Terminal (macOS)**, entre na pasta extraída.
4) Rode: `python -m http.server 8000`
5) Abra o navegador e vá em: `http://localhost:8000/` (o arquivo `index.html` abrirá o mapa).

Como editar os pontos:
- Edite `data/polos.json` para corrigir/alterar **polos culturais** (lat/lon já prontos).
- Edite `data/pics.json` para alterar **PICs** (endereço → o mapa geocodifica sozinho).

Como compartilhar com o celular na mesma rede:
1) Descubra o **IP** do seu PC (Windows: `ipconfig`, olhe IPv4; macOS: `ifconfig | grep inet`). 
2) No celular conectado ao mesmo Wi‑Fi, entre em: `http://SEU_IP:8000/`.

Como publicar na internet (grátis):
- Envie os arquivos para um repositório e use **GitHub Pages**, **Netlify** ou **Vercel** (projeto é estático).

Importante:
- O mapa usa seu token do Mapbox embutido no `index.html`. Substitua por outro se preferir.
