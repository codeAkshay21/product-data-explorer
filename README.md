# Product Data Explorer – World of Books

## Overview
A full-stack product exploration platform that scrapes live data from World of Books, allowing users to navigate from headings → categories → products → product detail pages.

## Tech Stack
### Frontend
- Next.js (App Router)
- TypeScript
- Tailwind CSS
- React Query

### Backend
- NestJS
- PostgreSQL
- Crawlee + Playwright
- BullMQ + Redis

## Architecture
- Frontend communicates with backend via REST APIs
- Backend triggers asynchronous scraping jobs
- Scraped data is cached and stored in PostgreSQL

## Features
- Navigation & category drilldown
- Live product scraping
- Product detail pages with reviews & metadata
- Caching & deduplication
- Accessible & responsive UI

## Running Locally
(Coming soon)

## API Documentation
(Coming soon)

## Deployment
(Coming soon)
