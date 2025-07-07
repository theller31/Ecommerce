# ShopSpark – React E-Commerce App

Live site: https://shop-spark.vercel.app  
GitHub repo: https://github.com/theller31/shop-spark

## Overview
ShopSpark is a beginner-friendly e-commerce platform built with React + Vite. It supports a shopping cart, routing, context-based state management, and responsive UI via Tailwind CSS.

## Features
- Browse products
- Add items to cart
- View and manage cart
- Responsive design

## Testing
Tests written using Jest + React Testing Library:
- Unit tests for `ProductCard` and `Cart`
- Integration test: cart updates after adding a product

## CI/CD
CI/CD pipeline via GitHub Actions:
- Runs on push to `main`
- Installs dependencies, runs tests
- Deploys to Vercel if tests pass

## Setup Instructions
```bash
git clone https://github.com/theller31/shop-spark
cd shop-spark
npm install
npm run dev
```

## Running Tests
```bash
npm run test
```

## GitHub Actions Workflow
- File: `.github/workflows/main.yml`
- Auto triggers on `main` push
- Runs build and tests
- Deploys to Vercel only if tests pass
