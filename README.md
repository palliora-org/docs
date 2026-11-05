# Palliora documentation

Source for the Palliora docs, built with [Mintlify](https://mintlify.com).
Migrated from the public GitBook site at docs.palliora.org (Core, DeFi and AI sections).

## Layout

- `docs.json` — site config and navigation (tabs: Core, DeFi, AI)
- `*.mdx` — pages; paths match the old GitBook URLs (`/learn/concepts/guardian`, `/defi/...`, `/ai/...`)
- `images/` — diagrams (light and dark variants)
- `files/` — downloadable attachments
- `style.css` — GitBook-style buttons and column layout

## Local preview

```bash
npm i -g mint
mint dev
```

Pushes to `main` deploy automatically through the Mintlify GitHub app.
