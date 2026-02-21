# Orleans Cleaning — Business Website & CMS

![Next.js](https://img.shields.io/badge/Next.js-15-black?style=flat-square&logo=next.js)
![TypeScript](https://img.shields.io/badge/TypeScript-5-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Payload CMS](https://img.shields.io/badge/Payload-CMS_3-000000?style=flat-square)
![Tailwind](https://img.shields.io/badge/Tailwind_CSS-4-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)
![Repo](https://img.shields.io/badge/Source-Private-orange?style=flat-square)

**A professional cleaning service website with an integrated headless CMS for content management.** Built for a real client with a focus on SEO, lead generation, and easy content updates through an admin dashboard.

---

## Features

- **Modern Landing Page** — Clean, responsive design optimized for local service businesses
- **Payload CMS Integration** — Headless CMS with admin dashboard for managing blog posts, media, and site content
- **Blog System** — SEO-optimized blog with content collections for driving organic traffic
- **Media Management** — Upload and manage images through the CMS admin panel
- **Lead Generation** — Contact forms and CTAs designed for conversion

## Architecture

```
┌───────────────────────────────────────┐
│           Public Frontend              │
│    Next.js 15 App Router + Tailwind    │
│    (SSR / ISR for SEO)                 │
└──────────────────┬────────────────────┘
                   │
                   ▼
┌───────────────────────────────────────┐
│           Payload CMS Admin            │
│    Content Collections:                │
│    • Blog Posts                         │
│    • Media Library                      │
└──────────────────┬────────────────────┘
                   │
                   ▼
┌───────────────────────────────────────┐
│             Database                   │
│    (Payload managed, auto-migrated)    │
└───────────────────────────────────────┘
```

## Tech Stack

- **Framework:** Next.js 15 (App Router), TypeScript
- **CMS:** Payload CMS 3 (headless, self-hosted)
- **Styling:** Tailwind CSS
- **Content:** Blog posts and media collections
- **Rendering:** Server-side rendering for SEO performance

## Skills Demonstrated

- Client-facing web development for a real business
- Headless CMS integration and content modeling
- SEO optimization for local service businesses
- Full-stack architecture (frontend + CMS + database)
- Responsive, conversion-focused UI design

---

> *This is a showcase page for a private repository. Built for a client — source code available upon request.*
