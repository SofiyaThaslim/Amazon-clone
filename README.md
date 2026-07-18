# Velvet Market — E-Commerce Clone

A curated marketplace UI built with **React + React Router**, pulling **live product data** from the [FakeStore API](https://fakestoreapi.com) (no hardcoded/dummy data). Built as a portfolio project to demonstrate real API integration, routing, and form validation.

**Live demo:** _add your Netlify/Vercel link here after deploying_

## Features

- Live product catalog fetched via `fetch()` from a real REST API
- Category filtering + live search
- Product detail page with dynamic routing (`/product/:id`)
- Login page with client-side form validation (email format, password length)
- Custom design system: pink/berry palette, Fraunces + Inter typography
- Fully responsive (mobile, tablet, desktop)
- Loading and error states handled for all API calls

## Tech Stack

- React 18
- React Router v6
- Vite
- Vanilla CSS (custom design tokens, no framework)
- [FakeStore API](https://fakestoreapi.com) — real REST API for product data

## Getting Started

```bash
npm install
npm run dev
```

Open `http://localhost:5173` in your browser.

### Build for production

```bash
npm run build
```

Output goes to the `dist/` folder — ready to deploy on Netlify, Vercel, or GitHub Pages.

## Project Structure

```
src/
  components/
    Navbar.jsx
    ProductCard.jsx
  pages/
    Home.jsx
    ProductDetail.jsx
    Login.jsx
  App.jsx
  main.jsx
  index.css
```

## What I Learned / Would Improve Next

- Integrating a third-party REST API with proper loading/error states
- Client-side routing with dynamic route params
- Next steps: persistent cart (localStorage), real auth (Firebase), checkout flow

---
Built by Sofiya Thaslim
