# Orleans Quality Cleaning — Client Website & CMS

![Next.js](https://img.shields.io/badge/Next.js-15-black?style=flat-square&logo=next.js)
![TypeScript](https://img.shields.io/badge/TypeScript-5-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Payload CMS](https://img.shields.io/badge/Payload-CMS_3-000000?style=flat-square)
![Tailwind](https://img.shields.io/badge/Tailwind_CSS-4-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)
![Live](https://img.shields.io/badge/Live-orleansqualitycleaning.ca-brightgreen?style=flat-square)
![Repo](https://img.shields.io/badge/Source-Private-orange?style=flat-square)

**I designed and built a full website for a real cleaning business client in the Ottawa-Gatineau region.** Not a template — a custom Next.js site with a headless CMS so the client can manage their own content.

🌐 **[orleansqualitycleaning.ca](https://www.orleansqualitycleaning.ca)**

---

## The Client

A professional cleaning service covering Ottawa, Gatineau, Orléans, and the broader Eastern Ontario region. They needed a modern website to replace their outdated Weebly site, with the ability to update content themselves.

## What I Built

### Custom Website with Lead Generation Focus
- Modern, responsive landing page designed to convert visitors into booked cleanings
- **Contact form** collecting name, address, email, and service details
- Clear service area coverage and pricing information
- Mobile-first design — most of their customers find them on their phones

### Payload CMS Integration
- Set up **Payload CMS 3** as a headless CMS — the client manages their own content through an admin dashboard
- **Blog system** with SEO-optimized posts for driving organic traffic
- **Media library** for managing images through the admin panel
- Content collections are fully typed with TypeScript — no runtime surprises

### SEO for Local Services
- Optimized for local search terms (cleaning services Ottawa, house cleaning Orléans, etc.)
- Server-side rendering for fast loads and full crawlability
- Structured data markup for local business schema

## Architecture

```
┌───────────────────────────────────┐
│          Public Website            │
│   Next.js 15 + Tailwind (SSR)     │
│   Contact form │ Blog │ Services  │
└──────────────────┬────────────────┘
                   │
                   ▼
┌───────────────────────────────────┐
│        Payload CMS Admin           │
│   Blog Posts │ Media │ Content     │
│   (Client manages this)            │
└──────────────────┬────────────────┘
                   │
                   ▼
┌───────────────────────────────────┐
│            Database                │
│   Auto-migrated by Payload        │
└───────────────────────────────────┘
```

## Tech Stack

`Next.js 15` · `TypeScript` · `Payload CMS 3` · `Tailwind CSS` · `SSR/ISR`

---

> *Built for a client. Visit [orleansqualitycleaning.ca](https://www.orleansqualitycleaning.ca) to see it live.*
