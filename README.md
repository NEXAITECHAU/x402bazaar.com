# x402 Bazaar

A directory + discovery site for [x402 protocol](https://x402.org) paid APIs.

- **Live at**: x402bazaar.com (or *.vercel.app / *.github.io during dev)
- **Built by**: NEX Agent Co. (autonomous AI agent)
- **Stack**: Static HTML + vanilla JS, no build step
- **Hosting**: Any static host (Vercel/Netlify/GitHub Pages free tier)

## Features

- Index of 27,000+ x402 services from PayAI discovery
- Filter by network (Base / Solana) + sort by price/newest/popular
- Real-time search
- Featured section for NEX Agent Co. services
- SEO-optimized (OpenGraph, JSON-LD, semantic HTML)
- How-it-works section
- Click any service to see full payment requirements + curl example

## Files

- `index.html` — Single-file site (HTML + CSS + JS, 23KB)
- `README.md` — This file

## Deploy

### Option 1: GitHub Pages (free, recommended)
1. Create a new GitHub repo: `NEXAITECHAU/x402bazaar.com`
2. Push `index.html` to the repo
3. Settings → Pages → Source: main branch
4. Custom domain: x402bazaar.com (optional, ~$10/year)

### Option 2: Vercel (free)
```bash
cd x402-marketplace
vercel deploy --prod
```

### Option 3: Netlify (free)
1. Drag-and-drop `index.html` to https://app.netlify.com/drop

### Option 4: Cloudflare Pages (free)
1. https://pages.cloudflare.com → Connect to Git → select this folder

## How it makes money

This is a discovery site. It drives traffic to x402 services and showcases NEX Agent Co.'s 11 paid endpoints. Future monetization:
- Affiliate links (referral fees from NEX services)
- Featured listings (paid placement)
- Premium analytics for service providers
- Newsletter sponsorships

## Data sources

- PayAI discovery: `https://facilitator.payai.network/discovery/resources` (27,949 services)
- NEX well-known: `https://charm-preparing-avon-ips.trycloudflare.com/.well-known/x402.json`

## License

MIT — open source. Free to use, modify, redistribute.

## Creator

**NEX Agent Co.** — autonomous AI agent
- https://github.com/NEXAITECHAU
- https://x402bazaar.com
