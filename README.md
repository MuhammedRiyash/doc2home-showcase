# Doc2Home — 24/7 Home-Healthcare Marketplace

> **Thanks for visiting!** Doc2Home is a private project, so its source code lives in a private repository.
> If you're reviewing my application and would like to see the code, I'm happy to share it.
>
> **[Request access to the source →](mailto:thisismd.riyash@gmail.com?subject=Doc2Home%20source%20code%20access%20request&body=Hi%20Muhammed%2C%0A%0AI%27d%20like%20to%20review%20the%20Doc2Home%20source%20code.%20My%20GitHub%20username%20is%3A%20)**
> — or message me on [LinkedIn](https://www.linkedin.com/in/muhammedriyash). Send your GitHub username and I'll add you as a read-only collaborator.

---

## What it is

Doc2Home is a two-sided home-healthcare marketplace: patients book care at home, healthcare providers apply to join,
and an admin team verifies providers and manages bookings. I designed and built it on my own.

| | |
|---|---|
| **Framework** | Next.js (App Router), React, TypeScript |
| **Data** | Prisma, PostgreSQL |
| **Auth** | Auth.js v5 (staff sign-in), phone OTP for patients and providers |
| **UI** | Tailwind CSS v4, GSAP, Recharts |
| **Validation** | Zod |
| **Quality** | Vitest unit tests, Playwright end-to-end tests, GitHub Actions |

## Highlights

- **Patient booking** — a five-step OTP-verified wizard with explicit consent that opens a consultation ticket for a callback.
- **Provider onboarding** — a sectioned application form with phone OTP and KYC, held for admin verification before going live.
- **Privacy by design** — personal and health fields are AES-256-GCM encrypted at rest; phone and licence numbers are blind-indexed so they stay searchable and de-duplicated without being stored in plain text.
- **Encrypted document storage** — KYC uploads are written encrypted behind a storage abstraction that can swap a local adapter for cloud storage.
- **Admin console** — bookings, provider verification, lead-to-provider matching, calendar scheduling, patients, payments and reports, behind staff sign-in.

## Status

Built June – September 2026 (142 commits).

---

**Muhammed Riyash J** · Senior Full-Stack Developer · Bengaluru, India

[Portfolio](https://md-riyash-portfolio.vercel.app/) · [LinkedIn](https://www.linkedin.com/in/muhammedriyash) · [GitHub](https://github.com/MuhammedRiyash)
