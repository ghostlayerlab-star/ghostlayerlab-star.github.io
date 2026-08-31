# Ghost Layer Lab

Site da Ghost Layer Lab, publicado com GitHub Pages a partir deste repositório.

| Endereço | Página |
| --- | --- |
| https://ghostlayerlab-star.github.io/ | Loja — link da bio, com os anúncios ativos no Mercado Livre |
| https://ghostlayerlab-star.github.io/identidade/ | Brand book — sistema de identidade visual |

## Estrutura

- `index.html` — loja. As fotos das peças e o selo estão embutidos no próprio
  arquivo como data URI, então a página não depende de nenhum host externo de
  imagem. Os preços são fixos no HTML e precisam ser atualizados à mão quando
  mudarem no Mercado Livre.
- `preview.webp` — imagem exibida quando o link é compartilhado (WhatsApp, Telegram).
- `identidade/` — brand book: fundamento de marca, selo, paleta, tipografia,
  sistema gráfico e aplicações.
- `identidade/assets/` — logotipos (`ghostlayer-white.png`, `ghostlayer-dark.png`).

## Desenvolvimento local

Abra o arquivo direto no navegador, ou sirva a pasta:

```bash
npx serve .
```
