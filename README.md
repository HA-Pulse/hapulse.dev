# hapulse.dev

[![Website - hapulse.dev](https://img.shields.io/badge/Website-hapulse.dev-10B981?style=for-the-badge&logo=data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCI+PHBhdGggZD0iTTIgMTJoNC41bDIuNS03IDQuNSAxNCAyLjUtN2g2IiBmaWxsPSJub25lIiBzdHJva2U9IndoaXRlIiBzdHJva2Utd2lkdGg9IjIuNiIgc3Ryb2tlLWxpbmVjYXA9InJvdW5kIiBzdHJva2UtbGluZWpvaW49InJvdW5kIi8+PC9zdmc+)](https://hapulse.dev)

Website of HA Pulse, the home of [HAGHS](https://github.com/HA-Pulse/home-assistant-global-health-score).
Static HTML and CSS, no build step, no JavaScript, no third-party requests. Served by GitHub Pages from `main`, custom domain in `CNAME`.

## Keep in sync with a HAGHS release

- Version in `index.html` (hero eyebrow, trust strip and JSON-LD `softwareVersion`).
- Install count in the trust strip (lower bound from Home Assistant's opt-in analytics, rounded down).
- `lastmod` in `sitemap.xml` for changed pages.

## Licences

Fonts: Inter and JetBrains Mono, SIL Open Font License 1.1 (`assets/fonts`).
