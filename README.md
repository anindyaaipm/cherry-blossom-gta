# Cherry Blossom in the GTA

Polished, mobile-first interactive city guide for cherry blossom viewing across Toronto, Mississauga, Brampton, Burlington, and Niagara.

## Tech Stack

- Next.js (App Router)
- React
- Tailwind CSS
- Leaflet + OpenStreetMap
- Local JSON data source

## Folder Structure

```text
cherry-blossom-gta/
├─ src/
│  ├─ app/
│  │  ├─ globals.css
│  │  ├─ layout.tsx
│  │  └─ page.tsx
│  ├─ components/
│  │  ├─ BestTimeSection.tsx
│  │  ├─ EtiquetteSection.tsx
│  │  ├─ FilterBar.tsx
│  │  ├─ Footer.tsx
│  │  ├─ HeroSection.tsx
│  │  ├─ HighlightsSection.tsx
│  │  ├─ ItinerarySection.tsx
│  │  ├─ SakuraMap.tsx
│  │  ├─ SpotCard.tsx
│  │  └─ SpotGrid.tsx
│  ├─ data/
│  │  └─ spots.json
│  └─ types/
│     └─ spot.ts
├─ next.config.ts
├─ tailwind.config.ts
├─ postcss.config.js
├─ tsconfig.json
└─ package.json
```

## Run Locally

1. Install dependencies:

```bash
npm install
```

2. Start development server:

```bash
npm run dev
```

3. Open [http://localhost:3000](http://localhost:3000)

## Build and Production Run

```bash
npm run build
npm run start
```

## Deploy on Vercel

1. Push this project to GitHub.
2. Import the repository in Vercel.
3. Framework preset: `Next.js` (auto-detected).
4. Build command: `npm run build` (default).
5. Output: `.next` (default).
6. Deploy.

No backend setup is required for this version.
