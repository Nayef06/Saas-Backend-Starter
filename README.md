# **SaaS Backend Starter**

A minimal, practical backend template for building SaaS apps.
Built with TypeScript, Node.js, Express, PostgreSQL, Prisma, Redis, JWT auth, and Stripe.
Designed to be a clean starting point without extra noise.

---

## **Tech Stack**

* **TypeScript**, **Node.js**, **Express**
* **PostgreSQL** + **Prisma**
* **PostgreSQL RLS** for tenant isolation
* **JWT** + **bcryptjs** for auth
* **Redis** for caching and rate limits
* **Stripe** for billing
* **Winston** for logging

---

## **Features**

* User authentication (login, signup)
* Basic multi-tenancy structure
* Prisma schema + migrations
* Simple RLS policies for data isolation
* Stripe billing setup (customer + subscription)
* Redis caching and rate limiting
* Organized Express app structure

---

## **Project Structure**

```
src/
  config/
  middleware/
  modules/
    auth/
    users/
    tenants/
    billing/
  utils/
prisma/
```

---

## **Setup**

1. Install dependencies:

   ```bash
   pnpm install
   ```

2. Copy `.env.example` → `.env` and fill in:

   * PostgreSQL URL
   * Redis URL
   * Stripe keys
   * JWT secret

3. Run database migrations:

   ```bash
   pnpm prisma migrate dev
   ```

4. Start the dev server:

   ```bash
   pnpm dev
   ```

---

## **Scripts**

* `pnpm dev` — Start development server
* `pnpm build` — Build TypeScript
* `pnpm start` — Run production build
* `pnpm test` — Run tests (if added later)

---

## **Notes**

This is a personal template meant to stay simple.
Add, remove, and tweak whatever fits your project.

---

## **License**

MIT
