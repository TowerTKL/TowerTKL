<img src="banner.svg" alt="skuthyn · Full-Stack Developer · building PizzaFlow" width="100%">

## Hey, I'm skuthyn

I build software that people actually run their business on. Right now that means a SaaS for pizzerias, the systems behind a produce distributor, and the small tools that keep everything moving in between.

I like owning the whole thing: the database design, the auth, the billing, the screen the cashier taps at 9pm on a Friday.

Based in Brazil · [PizzaFlow](https://pizza-saas-delta.vercel.app) · [LinkedIn](https://www.linkedin.com/in/kevyntintino) · [Email](mailto:skuthyn.github@gmail.com) · open to freelance and full-time work

---

### Things I'm working on

**[PizzaFlow](https://pizza-saas-delta.vercel.app)** · [overview and architecture](https://github.com/TowerTKL/pizzaflow)<br>
A complete system for pizzerias that runs in the browser. Customers order from an online menu with no app to install, pay by Pix straight to the store's key, and can collect stamps on a loyalty card that is just their phone number. Behind the counter, the team runs the cash register, a kitchen screen driven from the number pad, table orders by QR code, delivery routes sent to the driver's WhatsApp, and reports with a customer list that builds itself. Pricing is a flat monthly subscription per store, with no commission per order, and every pizzeria only sees its own data.<br>
<sub>Next.js · TypeScript · PostgreSQL · Drizzle · better-auth · Stripe · Vercel</sub><br>
<sub>3,500+ automated tests · 50+ tables · 45+ migrations · 240+ commits since July 2026</sub>

**Systems for a produce distributor**<br>
At the company I work for, I built the sales app that's already live in production, and I'm building a returnable-crate tracker: drivers log every drop-off and pickup with a photo while their route is tracked.

**Selling over WhatsApp**<br>
A white-label platform for produce sellers, where customers place orders by chatting with an AI-assisted bot, and the team handles picking and delivery from an admin panel.<br>
<sub>TypeScript · Node.js · LLMs</sub>

Most of this lives in private repos, since it's either my own product or systems I build at work. My reference implementation of tenant isolation in Postgres is open source in [multi-tenant-rls](https://github.com/TowerTKL/multi-tenant-rls), with tests that try to break it. I'm always happy to walk someone through the rest.

---

### Tools I reach for

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Drizzle](https://img.shields.io/badge/Drizzle-C5F74F?style=flat-square&logo=drizzle&logoColor=black)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![Stripe](https://img.shields.io/badge/Stripe-635BFF?style=flat-square&logo=stripe&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=flat-square&logo=vercel&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Claude](https://img.shields.io/badge/Claude-D97757?style=flat-square&logo=claude&logoColor=white)

### What I care about

- Data that stays where it belongs. Queries are scoped to a tenant explicitly, and tests fail the moment a covered query loses its filter.
- Billing that just works. Subscriptions, idempotent webhooks and plan changes nobody has to think about.
- Software for the floor, not the boardroom. Built for drivers, warehouse staff and store owners.
- AI as a multiplier, not a crutch. I know my stack in depth and use Claude every day to apply it faster, from first prototype to production.
