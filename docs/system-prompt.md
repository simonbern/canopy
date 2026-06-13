# Canopy Development Context

## Project
Solo-founder P2P marketplace for Canada. Next.js 15 (App Router), tRPC v11, Supabase (DB + auth), Stripe Connect (escrow), EasyPost (multi-carrier shipping), Resend (email), shadcn/ui, Tailwind CSS, Vercel.

## Principles
- Step-by-step explanations, no shortcuts
- Prefer maintainability over cleverness
- Test critical paths: payments, escrow, shipping

## Current milestone
M1: Foundation — project setup, CI/CD pipeline, Supabase auth, base UI components

## Key decisions
- App Router only, no Pages Router
- tRPC for all API calls (type-safe end-to-end)
- Supabase for DB + auth (RLS enabled)
- Stripe Connect with manual capture for escrow
- EasyPost for Canada Post + Purolator label generation
- Canada-only for MVP

## Repo
github.com/simonbern/canopy
Local: C:\Users\Simon\Desktop\Projects\canopy