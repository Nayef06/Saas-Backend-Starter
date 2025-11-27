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

WIP
---

## **Scripts**

WIP
---

## **Notes**

This is a personal template meant to stay simple.
Add, remove, and tweak whatever fits your project.

---

## **License**

MIT
