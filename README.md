# Deltablock Liquidity Portal

A polished, static front-end portal for a market intelligence and liquidity operations workflow. This project presents a modern dashboard experience for monitoring trading activity, comparing companies, managing user access, reviewing analytics, and navigating day-to-day portfolio operations.

It is designed as a UI prototype and demo application rather than a full backend-powered product, with a clean dashboard aesthetic, responsive layout, and reusable component styling.

## Overview

The application simulates a digital workspace for a financial operations or market liquidity platform. It includes:

- login and signup flows
- an overview dashboard with market KPIs
- analytics and access logs
- company and portfolio views
- peer comparison pages
- trade, contract, and accounting sections
- admin subscription and support ticket interfaces
- report generation and data health views

This makes the project suitable for showcasing a premium SaaS-style portal for institutional trading or securities operations.

## What the project includes

The repository contains a collection of HTML pages that represent different parts of the application:

- `login.html` — sign-in screen
- `signup.html` — account creation flow
- `dashboard.html` — main operational overview
- `analytics.html` — user behavior and access analysis
- `companies.html` — company list and portfolio navigation
- `company.html` — detailed company profile view
- `comparison.html` — peer benchmarking interface
- `trades.html` — trade history / activity
- `contract.html` — contracts and legal documents
- `accounting.html` — accounting details
- `reports.html` and `reports/` — reporting modules
- `tickets.html` — support and issue tracking
- `users.html` — team and user management
- `wireframes.html` — visual planning and mock screen references
- `guest-invite.html` and `password-reset.html` — onboarding and auth helpers

## Design and tech stack

This project is built primarily with:

- HTML for page structure
- CSS for styling and layout
- JavaScript for interactions and dynamic UI elements
- Tailwind CSS for component utilities and design consistency

The styling system is driven by `src/input.css`, and the project includes a Tailwind build process defined in `package.json`.

## Project structure

```text
.
├── README.md
├── index.html
├── login.html
├── signup.html
├── dashboard.html
├── analytics.html
├── companies.html
├── company.html
├── comparison.html
├── contract.html
├── accounting.html
├── trades.html
├── tickets.html
├── users.html
├── reports.html
├── reports/
├── guest-invite.html
├── password-reset.html
├── wireframes.html
├── css/
├── js/
├── src/
├── package.json
├── package-lock.json
├── tailwind.config.js
└── .gitignore
```

## How to run the project

Because this is a static front-end project, you can run it in a few easy ways:

### Option 1: Open directly in the browser

Open `index.html` in a browser to start from the app entry point. The page redirects to the login screen.

### Option 2: Run a local static server

From the project root:

```bash
npm install
npm run build
```

Then serve the folder using any local static server, for example:

```bash
npx serve .
```

Then open the local URL provided in the terminal.

## Tailwind setup

This repo includes a simple Tailwind workflow:

```bash
npm install
npm run build
```

The build command compiles the source CSS into the final stylesheet used by the application.

## Important note

This repository contains a front-end prototype and UI mockup experience. It does not include a real backend, database, authentication service, or production data layer. The purpose is to demonstrate a high-fidelity product UI for a liquidity and market portal.

## Summary

`second_update_liquidity` is a premium-looking dashboard prototype for a market-facing liquidity platform. It blends trading intelligence, operational monitoring, and customer-facing portal workflows into a single cohesive interface. The result is a clean, investor-ready front-end experience that feels like a real enterprise product.

If you want, I can also turn this into a more marketing-style README, a developer-focused README, or a GitHub-ready polished version with badges and screenshots sections.
