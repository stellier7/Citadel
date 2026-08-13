# Citadel

Decentralized fractional real estate platform — tokenized property ownership with rental yield through Citadel.rent.

## Overview

Citadel is a single-page web app for exploring, funding, and managing fractional real estate holdings. The prototype covers four main areas:

- **Overview** — Hero, funding stats, process steps, featured development, and rent teaser
- **Citadel.build** — Property detail with tabs (overview, financials, ownership, documents) and a token purchase widget
- **Dashboard** — Portfolio KPIs, property holdings, and recent activity
- **Citadel.rent** — Browse and filter bookable Citadel properties

Wallet connection uses MetaMask (or any injected EIP-1193 provider) via [ethers.js v5](https://docs.ethers.org/v5/).

## Quick start

```bash
npm start
```

Open [http://localhost:3000](http://localhost:3000).

Alternatively, open `index.html` directly in a browser — no build step required.

## Project structure

```
├── index.html    # Full SPA (HTML, CSS, JS)
├── package.json  # Dev server script
└── README.md
```

## Features

- Client-side routing across four pages
- Animated token pyramid visualization on the landing page
- Isometric SVG property illustrations
- Scroll-reveal animations and parallax effects
- MetaMask wallet connect with live ETH balance display
- Mock token purchase flow (requires connected wallet)
- Responsive layout for mobile and desktop

## Tech stack

- Vanilla HTML / CSS / JavaScript
- [ethers.js 5.7](https://cdnjs.cloudflare.com/ajax/libs/ethers/5.7.2/ethers.umd.min.js) (CDN)
- Google Fonts: Space Grotesk, Manrope, JetBrains Mono

## Pilot property

The featured development is **Roatán Duplex — Unit A/B** in Prospera ZEDE, Roatán, Honduras:

- $200,000 total development cost ($100K token raise + $100K BTC-collateralized loan)
- $200 per token, 500 tokens total
- 18–22% projected rental yield via Citadel.rent
