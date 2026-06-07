# workers-sites

Static sites deployed on Cloudflare Workers, maintained via Claude.

| Folder | Site | Live |
|---|---|---|
| `tracker/` | Habit tracker (multi-month, dark Notion theme) | tracker.loris-impinna.workers.dev |
| `mortgage/` | Swiss mortgage calculator (green theme) | green-queen-9198.loris-impinna.workers.dev |

Each folder is a self-contained `index.html` (no build step).

**Deploy setup (one-time per site):** Cloudflare dashboard -> Workers & Pages -> Create -> connect this repo -> root directory = the site folder -> no build command, assets = `.`
