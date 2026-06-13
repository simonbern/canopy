# Development Setup

## Prerequisites

- Node 20+
- Supabase account
- GitHub account

## Local setup

```bash
git clone https://github.com/simonbern/canopy.git
cd canopy
npm install
cp .env.local.example .env.local
npm run dev
```

## Branch strategy

- `main` → production
- `develop` → staging
- `feature/*` → daily work, PR into develop
