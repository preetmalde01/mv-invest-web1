# MV Invest — Your Personal CIO (Swiss Minimalist Editorial Redesign)
**Parent Entity:** Malde Ventures  
**Design Reference:** Swiss Minimalist / Brutalist Studio (`image_5a89ca.png`)

---

## Architecture & Features

### 1. Hero Page Matching Reference Layout
- **Center Headline:** `YOUR PERSONAL CIO` in massive, tightly-tracked grotesque typography.
- **Background Ambient Glow:** Live, interactive fluid orange-coral glow (`#F36F43` / `#FF5722`) rendered via HTML5 canvas with inertia mouse/touch tracking, organic breathing pulsation, and dual-layer radial dispersion.
- **Top Navigation:**
  - `(●) MV INVEST` minimalist vector branding.
  - `● GET IN TOUCH` direct action link with status indicator.
  - Minimalist 2-line hamburger menu icon (`=`).
- **Bottom Navigation Row:**
  - `↓↓↓` downward scroll jump indicator.
  - 3-line uppercase mission statement:
    *WE GUIDE DISCERNING FAMILIES & ENTREPRENEURS ACROSS INDIA*  
    *INDEPENDENT MULTI-ASSET WEALTH ARCHITECTURE SOLELY ON MERIT*  
    *SEBI REGISTERED INVESTMENT ADVISOR · 100% FEE-ONLY*
  - **Live Mode Toggle:** Working `LIGHT MODE / DARK MODE` switch with smooth theme transition.

### 2. Comprehensive Wealth Advisory Sections Below The Fold
- `01 / MANDATE`: The Personal CIO Advantage (100% Direct Plans, 0.0% Commissions vs Distributor Model).
- `02 / TRANSPARENCY`: Whose Interests Does Your Wealth Manager Actually Serve? (Conflict audit: Distributor, Broker, Real estate).
- `03 / MATHEMATICAL REALITY`: A 1% Commission Trail Is Not A Fee. It's A Leak (Interactive compounding loss calculator).
- `04 / ARCHITECTURE`: Tailored Solutions Across Every Tier of Wealth (HNIs/UHNIs Private Office vs Emerging Wealth).
- `05 / PROCESS`: Disciplined 4-Step Advisory Protocol.
- `06 / ENGAGE`: Consultation Request Desk & Direct Advisory Contacts.
- **Footer:** Complete SEBI RIA regulatory disclosures and copyright.

---

## Formats Included

### `standalone/` (Zero-Dependency Static Build)
- Open `index.html` directly in any web browser or deploy instantly to Vercel, Netlify, Cloudflare Pages, GitHub Pages, or AWS S3.
- No Node.js, npm, or build step required.

### `react-app/` (React 18 + Vite + Tailwind CSS)
- Modular component-based Single Page Application.
- Run locally:
  ```bash
  cd react-app
  npm install
  npm run dev
  ```
