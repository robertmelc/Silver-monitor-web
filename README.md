# Silver Monitor – Web

Landing page pro [silver-monitor.com](https://silver-monitor.com)

## Stack
- Čistý HTML/CSS/JS, žádné závislosti
- Google Fonts (Playfair Display, DM Sans, DM Mono)
- GitHub Pages deployment

## Deployment
1. GitHub Pages → Settings → Pages → Source: `main`, `/ (root)`
2. Custom domain: `silver-monitor.com`
3. Enforce HTTPS: ✓

## GoDaddy DNS
| Typ   | Název | Hodnota               |
|-------|-------|-----------------------|
| A     | @     | 185.199.108.153       |
| A     | @     | 185.199.109.153       |
| A     | @     | 185.199.110.153       |
| A     | @     | 185.199.111.153       |
| CNAME | www   | robertmelc.github.io  |

## Struktura
```
silver-monitor-web/
├── index.html   ← landing page (CZ/EN, hero, pricing, education)
├── CNAME        ← custom domain
└── README.md
```
