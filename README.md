# hapulse.dev

Website of HA Pulse, the home of [HAGHS](https://github.com/HA-Pulse/home-assistant-global-health-score).
Static HTML and CSS, no build step, no JavaScript, no third-party requests. Served by GitHub Pages from `main`, custom domain in `CNAME`.

## Keep in sync with a HAGHS release

- Version in `index.html` (hero eyebrow, trust strip and JSON-LD `softwareVersion`).
- Install count in the trust strip (lower bound from Home Assistant's opt-in analytics, rounded down).
- `lastmod` in `sitemap.xml` for changed pages.

## Licences

Fonts: Inter and JetBrains Mono, SIL Open Font License 1.1 (`assets/fonts`).
