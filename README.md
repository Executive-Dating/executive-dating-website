# Executive Dating — Website

A premium, private introduction service website built with Astro.

## Local Development

```bash
npm install
npm run dev
```

The site runs at `http://localhost:4321`

## Build for Production

```bash
npm run build
npm run preview
```

## GitHub Setup

```bash
git init
git add .
git commit -m "Initial build"
git branch -M main
git remote add origin https://github.com/YOUR_USERNAME/executive-dating.git
git push -u origin main
```

## Netlify Deployment

1. Push repo to GitHub
2. Log in to [netlify.com](https://netlify.com)
3. Click **Add new site → Import an existing project**
4. Choose GitHub and select this repository
5. Build command: `npm run build`
6. Publish directory: `dist`
7. Click **Deploy site**

Netlify Forms are preconfigured — no additional setup needed.

## Before Launch

- [ ] Add advisor real name and bio to `src/pages/meet-your-advisor.astro`
- [ ] Upload logo file to `public/images/logo.svg` (or update Header.astro)
- [ ] Replace all image placeholders in `public/images/`
- [ ] Add Google Analytics tracking ID in `src/layouts/BaseLayout.astro`
- [ ] Review all legal pages with a South African attorney
- [ ] Register Information Officer with South Africa Information Regulator (POPIA)
- [ ] Update domain in `astro.config.mjs`
- [ ] Update `public/sitemap.xml` with final domain
