# Aproxima NFC — V3 (corrigida e melhorada)

Landing page estática (HTML/CSS/JS puro). Funciona em GitHub + Vercel, Netlify ou Cloudflare Pages.

## Pastas e arquivos
- `index.html` — o site inteiro (leve, ~41 KB)
- (as fotos dos modelos já estão dentro do index.html)
- `og.png` — imagem de pré-visualização ao compartilhar o link
- `vercel.json` (Vercel) e `_headers` (Netlify / Cloudflare Pages) — segurança e cache
- `404.html` — página de erro amigável
- `robots.txt`, `sitemap.xml`, `favicon.svg`

## Antes de publicar
O endereço `https://aproxima-nfc-v2.vercel.app/` aparece em: `index.html` (canonical, og:url, og:image e dados estruturados), `robots.txt` e `sitemap.xml`. O botão "Visite nosso Site" da demonstração agora abre esta própria versão do site, em qualquer endereço. Troque pelo endereço real do site, se for outro.

## Onde editar
No `index.html`, procure por `var CFG=` (preços, desconto por quantidade, cupons e frete por região) e por `var IG=` (Instagram).

## Hospedagem
O plano gratuito da Vercel (Hobby) é só para uso pessoal e não comercial. Para um site de empresa, prefira Cloudflare Pages ou Netlify (planos gratuitos que permitem uso comercial) ou o plano pago da Vercel.
