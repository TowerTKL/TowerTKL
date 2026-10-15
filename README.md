<img src="banner.svg" alt="skuthyn · Full-Stack Developer · building PizzaFlow" width="100%">

## Hey, I'm Kevyn (skuthyn)

I'm a full-stack developer from São Paulo. I got into tech through IT support: help desk, servers, backups, the company ERP. I kept writing scripts to get rid of the repetitive work, and at some point I was building the systems instead of just keeping them running.

Today I work as an IT analyst at a produce distributor, I'm in my last semester of Computer Science, and on the side I'm building PizzaFlow, a system for pizzerias.

[PizzaFlow](https://pizza-saas-delta.vercel.app) · [LinkedIn](https://www.linkedin.com/in/kevyntintino) · [Email](mailto:skuthyn.github@gmail.com) · open to freelance and full-time work

---

### What I'm working on

**[PizzaFlow](https://pizza-saas-delta.vercel.app)** ([overview and architecture](https://github.com/TowerTKL/pizzaflow))<br>
My own product. Customers order from a menu link, no app to install, pay with Pix straight to the store, and can collect stamps on a loyalty card that is just their phone number. Behind the counter, the team runs the cash register, a kitchen screen you drive with the number pad, table orders by QR code and delivery routes that go to the driver's WhatsApp. There are also reports and a customer list that fills itself in. Each store pays a monthly fee, there's no cut per order, and every pizzeria only sees its own data. I do all of it, from the database to the screens.<br>
<sub>Next.js · TypeScript · PostgreSQL · Drizzle · better-auth · Stripe · Vercel</sub><br>
<sub>3,500+ automated tests · 50+ tables · 45+ migrations · 240+ commits since July 2026</sub>

**At work**<br>
I built the sales app the company uses today, and now I'm on the crate tracker: drivers log every drop-off and pickup with a photo, and we follow the route while they're out.

I also work on a WhatsApp sales platform for produce sellers. Customers order by chatting with a bot that has AI help, and the team handles picking and delivery from an admin panel.<br>
<sub>TypeScript · Node.js · LLMs</sub>

Most of this code is private, since it's either my product or the company's. One thing I did open up is [multi-tenant-rls](https://github.com/TowerTKL/multi-tenant-rls), a small example of keeping tenants apart with Postgres row-level security, with tests that try to break it. If you want to see more, send me a message and I'll walk you through it.

---

### Tools I use

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

### How I work

- Working in support taught me to think about the person using the screen, and about what happens when something breaks in the middle of a busy shift. Most of what I build is used by drivers, warehouse staff and store owners.
- I care a lot about each customer's data staying in its own place. Every query is filtered by account and store, and there are tests that fail if one of them loses that filter.
- I like billing to just work: subscriptions, webhooks that can arrive twice without breaking anything, plan changes nobody has to think about.
- I use Claude every day. I know my stack well and I review what it writes, it just gets me from the first version to production faster.
