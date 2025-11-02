BusHub — Next.js Vercel-friendly Frontend
========================================

Files included:
- package.json
- next.config.js
- tailwind.config.js
- postcss.config.js
- app/ (Next 14 app-router)
  - layout.js
  - globals.css
  - page.js
  - login/page.js
  - signup/page.js
- components/
  - Hero.jsx
- public/
  - og-image.png

How to run locally (VS Code):
1. Install Node.js 18+.
2. In the project root run:
   npm install
   npm run dev
3. Open http://localhost:3000

Vercel deploy:
- Push this repo to Git and import into Vercel. Vercel will detect Next.js and set defaults.

Notes:
- This scaffold uses Next.js 14 app router. Tailwind is configured via postcss.
- Replace images in components/Hero.jsx (Image src) with your assets if desired.
