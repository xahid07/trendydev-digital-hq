# TrendyDev Digital HQ

Enterprise-grade multi-tenant SaaS ecosystem built with Next.js 15, Turborepo, Supabase (PostgreSQL + RLS), Drizzle ORM, and Stripe.

## Architecture Overview

Monorepo structure:

apps/
portfolio/ → Marketing site (trendydev.com)
admin/ → Internal dashboard (admin.trendydev.com)
client/ → Client portal (client.trendydev.com)

packages/
ui/ → Shared design system
db/ → Drizzle schema & database layer
auth/ → Authentication & RBAC logic

## Core Stack

- Next.js 15 (App Router + RSC)
- Turborepo + pnpm workspaces
- PostgreSQL (Supabase) with RLS
- Drizzle ORM
- Auth.js v5
- Stripe Billing
- Vercel Deployment

## Development

```bash
pnpm install
pnpm dev
```
