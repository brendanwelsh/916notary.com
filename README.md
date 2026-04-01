# 916notary.com

Sacramento mobile notary service — lead capture and info page.

**Live:** [916notary.com](https://916notary.com)

## Stack

- Single-page static HTML/CSS/JS
- Hosted on [Cloudflare Pages](https://pages.cloudflare.com)
- No build step

## Deploy

```bash
wrangler pages deploy . --project-name=916notary-com
```

## Notes

- DNS managed via Cloudflare (Zone ID: `76fbfcfed43496ce690cb70f6ce4f489`)
- Always sync local with live before editing — see root `CLAUDE.md`
