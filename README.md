# Tulas International School — Frontend Assignment

A responsive, motion-rich school homepage concept built with React, Vite, Tailwind CSS and Framer Motion.

## Requirements
- Node.js 20.19+ (or a compatible current LTS)
- npm

## Run locally
```bash
npm install
npm run dev
```
Open the local URL printed by Vite.

## Production build
```bash
npm run build
npm run preview
```

## Deploy to Vercel
1. Push this repository to a public GitHub repository.
2. Import the repository at https://vercel.com/new.
3. Framework preset: **Vite**. Build command: `npm run build`; output directory: `dist`.
4. Deploy. No environment variables are required.

## Deploy to Netlify
Import the GitHub repository. Build command: `npm run build`; publish directory: `dist`.

## Design notes
- Responsive navigation, scroll progress bar, reveal-on-scroll sections, animated hero and interactive cards.
- Images use remote Unsplash source URLs for the visual prototype. Replace them with approved TIS assets before final submission.
- School-specific facts, admissions details and copy should be checked against https://tis.edu.in/ before publishing. This is a frontend concept, not an official TIS website.

## Suggested review checklist
- Test at 360px, 768px, 1024px and desktop widths.
- Check keyboard focus and reduced-motion preferences.
- Confirm all school copy, logos, links, phone numbers and images are authorized and accurate.
