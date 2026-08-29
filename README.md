# WarrantyCam.com site

Public static site for WarrantyCam (privacy policy and store/OAuth links).

**Live URL:** https://warrantycam.com/privacy/

Hosted on **Cloudflare Pages** with the custom domain `warrantycam.com` (not GitHub Pages).

## Content

- `docs/index.html` — redirects to `/privacy/`
- `docs/privacy/index.html` — privacy policy

## Deploy

Cloudflare Dashboard → Workers & Pages → project connected to this repo → build output directory `docs`.