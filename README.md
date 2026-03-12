# Maase — One Extra Meal From Maa

> **Launching soon at [maaseindia.com](https://maaseindia.com)**

Maase is a hyperlocal platform that connects home cooks with people who want fresh, home cooked meals nearby. Home cooks prepare one extra portion of the same meal they cook for their family — and earn from it.

---

## What is Maase?

Every day, millions of Indian mothers cook incredible food for their families.

- The stove is already on.
- The spices are already measured.
- The cooking is already happening.

Maase is built on a simple idea: **what if cooking just one extra portion could create income?**

No restaurant. No commercial kitchen. Just real food from real homes.

---

## This Repository

This repo contains the **Maase marketing website and landing page** — a static HTML/CSS/JS site deployed on Vercel.

**Live preview:** [web-preview-virid.vercel.app](https://web-preview-virid.vercel.app)
**Production domain (coming soon):** [maaseindia.com](https://maaseindia.com)

---

## Pages

| File | Description |
|------|-------------|
| `index.html` | Main landing page |
| `footer.js` | Shared footer (injected on all pages) |
| `chef-profile.html` | Home cook public profile |
| `mother-survey.html` | Home cook research survey |
| `privacy-policy.html` | Privacy Policy |
| `terms.html` | Terms & Conditions |
| `refund-cancellation.html` | Refund & Cancellation Policy |
| `supabase-schema.sql` | Database schema for Supabase |

---

## Tech Stack

- **Frontend:** Pure HTML, CSS, Vanilla JS — no build step
- **Database:** Supabase (PostgreSQL) — stores chef applications, nominations, waitlist, surveys
- **Hosting:** Vercel (static deployment)
- **Fonts:** Google Fonts — Playfair Display + Poppins
- **Design:** Custom design system using CSS variables

### Design Tokens

```css
--turmeric: #F4A300    /* Primary brand colour */
--mocha:    #5C3A21    /* Text / dark backgrounds */
--ivory:    #F8F3E8    /* Background / light surfaces */
```

---

## Supabase Tables

Run `supabase-schema.sql` in your Supabase SQL editor to set up:

- `chef_applications` — home cook sign-ups
- `chef_nominations` — nominations from customers
- `waitlist` — customer waitlist
- `mother_surveys` — home cook research survey responses

Supabase project: `aaixsytygsjilgvebnfv`

---

## Deploying

This site deploys automatically via Vercel on every push to `main`.

To deploy manually:

```bash
npx vercel --prod
```

---

## Other Repositories

| Repo | Description |
|------|-------------|
| [Maase-Food-Delivery-App](https://github.com/gpradeep7898/Maase-Food-Delivery-App) | Customer mobile app (React Native + Expo) |
| Maase-Chef-App *(coming soon)* | Chef / cook dashboard (Next.js) |
| Maase-Delivery-App *(coming soon)* | Delivery partner app (React Native) |
| Maase-API *(coming soon)* | Backend API (Node.js + Prisma + Railway) |

---

## Contact

**Email:** support@maaseindia.com
**Website:** [maaseindia.com](https://maaseindia.com) *(launching soon)*

---

*Maase India · Bangalore · 2026*
