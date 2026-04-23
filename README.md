# Shiplog — Stop forgetting ideas. Start shipping them.

> You forget 70% of your ideas in 24 hours. Shiplog captures them 
> and reveals which ones actually matter — so you can stop thinking 
> and start shipping.

🔗 **Live at:** [shiplog.webarc.one](https://shiplog.webarc.one)

---

## The Problem

Builders don't lack ideas — they have too many. Brilliant ideas 
strike at 3 AM and disappear by breakfast. The rest get buried in 
generic note apps between grocery lists and meeting minutes, never 
to be seen again.

## The Solution

Shiplog is a **pattern detection system** for your brain — not a 
note app, not a task manager.

- Log an idea in **5 seconds**
- Log the same idea **5 times** → Shiplog marks it as a signal
- Your repeating idea = what your brain actually wants to build
- **Stop bouncing. Start shipping.**

---

## Features

- ⚡ **5-second capture** — frictionless idea logging, no friction
- 🎯 **Pattern detection** — automatically tracks recurring ideas
- 📊 **Signal scoring** — surfaces which ideas have the most momentum
- 💳 **Subscription billing** — monthly, yearly, and lifetime plans
- 🔐 **Authentication** — secure user accounts and protected routes
- 📝 **Blog** — built-in content for SEO and community building

---

## Tech Stack

| Layer | Technology |
|---|---|
| Framework | Next.js 16 (App Router) |
| Language | TypeScript |
| Database | PostgreSQL |
| ORM | Prisma |
| Styling | Tailwind CSS |
| Payments | DODO payments (subscriptions + webhooks) |
| Deployment | AWS / Vercel |
| Auth | BetterAuth implementation |

---

## Pricing

| Plan | Price |
|---|---|
| Free | $0 — limited captures |
| Pro Monthly | Recurring |
| Pro Yearly | Recurring (discounted) |
| Lifetime | $39 one-time (limited spots) |

---

## Architecture Overview
shiplog/
├── app/                  # Next.js App Router
│   ├── (auth)/           # Auth routes — login, signup
│   ├── app/              # Protected dashboard
│   └── api/              # API routes
├── components/           # Reusable UI components
├── lib/                  # Prisma client, utilities
├── prisma/
│   └── schema.prisma     # Database schema
└── public/               # Static assets

---

## What I Learned Building This

- DODO payments webhook handling and subscription lifecycle management
- Next.js App Router patterns for auth-protected routes
- Prisma schema design for multi-tenant SaaS data
- Product positioning and conversion copywriting
- End-to-end SaaS deployment on AWS

---

## Built By

**Parth Singh** — Full-stack developer & indie maker  
🌐 [webarc.one](https://webarc.one) · 
𝕏 [@parthfullstack](https://x.com/parthfullstack) · 
💼 [LinkedIn](https://linkedin.com/in/parthfullstack)

---

## Landing Page ScreenShot

<img width="1918" height="971" alt="image" src="https://github.com/user-attachments/assets/d556bb8f-8d96-48ff-899a-d0ebf5d2f1f5" />


## Repo Topics

`nextjs` `typescript` `saas` `postgresql` `prisma` `stripe` 
`tailwindcss` `developer-tools` `idea-tracker` `indie-hacker`
