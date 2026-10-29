# Алекс Ади ЕООД – сайт за тапицерски услуги

Статичен HTML сайт (без build стъпка).

## Структура
- `index.html` – страницата (SEO мета тагове, Open Graph, JSON-LD LocalBusiness + FAQPage)
- `assets/` – оптимизирани снимки и лого
- `og-image.jpg`, `favicon.png`, `apple-touch-icon.png`, `icon-512.png`
- `robots.txt`, `sitemap.xml`, `404.html`
- `wrangler.toml`, `.assetsignore` – деплой в Cloudflare Workers

## Преди публикуване
Сменете домейна `https://aleksadi.bg` с реалния във: `index.html` (canonical, og:url, og:image, JSON-LD), `robots.txt`, `sitemap.xml`.

## Публикуване
**GitHub Pages:** качете всичко в репото → Settings → Pages → Deploy from branch → `main` / root.
**Cloudflare Workers:** `npx wrangler deploy`
