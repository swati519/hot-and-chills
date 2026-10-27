# Hot and Chills

Premium café website for Hot and Chills with menu, cart, and GitHub Pages deployment.

## Features
- Responsive landing page and dedicated menu page
- Product catalog with category filters and search
- Cart drawer with quantity management and checkout form
- WhatsApp order request flow with placeholder number
- Testimonials, gallery, promo sections, and privacy notice
- Vite + React + TypeScript + Tailwind CSS project structure
- GitHub Pages deployment workflow

## Local setup
```bash
npm install
npm run dev
```

## Production build
```bash
npm run build
```

## GitHub Pages deployment
1. Push this repository to GitHub.
2. In GitHub, open Settings → Pages.
3. Set source to GitHub Actions.
4. Commit the workflow in `.github/workflows/deploy.yml`.
5. After the workflow runs, the site will be available at `https://<username>.github.io/hot-and-chills/`.

## Notes
- Replace placeholder address, phone, WhatsApp number, and social links in `src/data/menu.ts` and the footer/header.
- The checkout flow creates a WhatsApp order request without confirming payment or order completion.
