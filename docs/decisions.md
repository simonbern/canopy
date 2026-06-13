# Architecture & Design Decisions

## Tech Stack

- **Next.js 16**: App Router, server components for content-heavy marketplace
- **tRPC v11**: End-to-end type safety, ideal for solo dev
- **Supabase**: Postgres + RLS + auth + storage in one product
- **Stripe Connect**: Only viable marketplace payout option in Canada
- **EasyPost**: Multi-carrier API supporting Canada Post + Purolator
- **Resend**: Transactional email
- **Vercel**: Hosting, best DX for Next.js
