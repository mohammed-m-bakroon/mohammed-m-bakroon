<div align="center">

# Mohammed Bakroon

### Backend Developer · Laravel · APIs · Business Automation

📍 Gaza, Palestine &nbsp;•&nbsp; 💼 4+ years of experience &nbsp;•&nbsp; 🌐 Arabic (native) · English (professional)

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/mohammed-mostafa33)
[![GitHub](https://img.shields.io/badge/GitHub-mohammed--m--bakroon-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/mohammed-m-bakroon)

</div>

---

## 👋 About me

I'm a backend developer who builds **business systems and APIs with PHP / Laravel**: admin panels, CRMs, invoicing, learning platforms, charity and donation portals, and a media platform for Palestinian content creators. I also automate business workflows with **n8n** and AI.

I care about structure that holds up as a project grows: **modular Laravel apps, real role-based access, and deployments that live in Git** instead of being patched by hand on the server.

---

## 🛠️ Tech stack

<p>
  <img src="https://img.shields.io/badge/PHP-777BB4?style=for-the-badge&logo=php&logoColor=white"/>
  <img src="https://img.shields.io/badge/Laravel-FF2D20?style=for-the-badge&logo=laravel&logoColor=white"/>
  <img src="https://img.shields.io/badge/Filament-FDAE4B?style=for-the-badge&logo=laravel&logoColor=black"/>
  <img src="https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white"/>
  <img src="https://img.shields.io/badge/Vue.js-4FC08D?style=for-the-badge&logo=vuedotjs&logoColor=white"/>
  <img src="https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white"/>
  <img src="https://img.shields.io/badge/n8n-EA4B71?style=for-the-badge&logo=n8n&logoColor=white"/>
  <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white"/>
  <img src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white"/>
  <img src="https://img.shields.io/badge/Power_BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black"/>
</p>

| Area | Skills |
|---|---|
| **Backend** | PHP, Laravel 8 → 11, REST APIs, Sanctum, Spatie Permissions, modular architecture (laravel-modules) |
| **Admin panels** | Filament 3, role-based access control |
| **Data** | MySQL, Supabase / pgvector |
| **Frontend** *(when needed)* | Blade, Vue.js, Tailwind CSS |
| **Payments** | Stripe |
| **Automation & AI** | n8n, RAG pipelines, Telegram bots, LLM APIs |
| **Tooling** | Git, GitHub Actions, Postman |

---

## 🧭 How I build

- **Modular by default.** Features live in their own modules (admin, courses, orders, users) so large Laravel apps stay navigable.
- **Access control that is real.** Roles and permissions drive both the API and the admin panel.
- **Secure content and accounts.** Signed URLs, HLS / AES-128 encrypted video, and verification codes scoped per user.
- **Repeatable deployments.** Fixes are committed to Git and shipped through CI/CD, never applied only on the server.
- **Bilingual and multilingual products.** Arabic (RTL), English and more, with translatable content.

---

## 🚀 Featured work (public code)

| Project | What it shows |
|---|---|
| [**Laravel-Filament**](https://github.com/mohammed-m-bakroon/Laravel-Filament) | Laravel 11 + Filament 3 business-management panel in one app: **HR** (departments, employees, attendance), **projects & tasks**, **CRM** (customers, leads, opportunities, interactions), **sales** (orders, payments), **purchasing** (vendors, purchases), **accounting** (accounts, transactions), and dashboard widgets. |
| [**e-commerce**](https://github.com/mohammed-m-bakroon/e-commerce) | Modular Laravel 8 online store built with a teammate: products with brands, categories, variants, galleries, ratings and wishlists; carts and orders with pluggable payment and shipment methods; Spatie roles and permissions. |
| **n8n RAG assistant** | Retrieval pipeline over Google Drive documents using Cohere embeddings and Supabase pgvector, answering through Telegram with Groq / Gemini. |
| **n8n Telegram bot** | Multi-modal bot: text chat, image generation, real image search, and photo understanding through the Anthropic API. |

---

## 💼 Client & company work

Most of my production work belongs to employers and clients, so the repositories are private. These are live products and systems I have worked on.

### 🎙️ [Sawt · صوت](https://sawtgaza.com)
**Media platform from Gaza for content creators**

`Laravel 11` `Filament 3` `Next.js 15` `MySQL` `GitHub Actions`

Backend developer. REST API, Filament admin panel with Spatie roles and permissions, video management with **HLS / AES-128 encryption and signed URLs**, campaigns, donations, creator onboarding, and server deployment with GitHub Actions.

### 🤲 [Fajr Relief & Development · جمعية فجر للإغاثة والتنمية](https://www.fajrrelief.com)
**Donation and campaign platform for a licensed Palestinian humanitarian NGO in Gaza**

`Laravel` `Filament` `MySQL` `Payment API integration` `Multilingual (AR / EN / TR)`

**Role: Website rewrite developer & payment integration engineer.** I rebuilt the charity's website from the ground up and connected it to a third-party donation / payment API, so supporters can give online directly to the campaigns they choose.

- **Full website rewrite:** a clean, maintainable codebase replacing the previous site, built for an organization that depends on donor trust.
- **Payment integration through a dedicated service layer:** the third-party donation / payment API is isolated behind its own service class, keeping controllers thin, making the integration easy to test, and allowing the provider to be swapped or extended without touching the rest of the app.
- **Campaign management:** projects grouped by category (psychosocial support, food security, water & sanitation, shelter & early recovery), each with a funding goal, amount raised and live progress percentage.
- **Trilingual interface:** Arabic (RTL), English and Turkish with a language switcher.
- **Trust & engagement:** blog / news, partners, FAQ, impact counters, contact form, supporter sign-up and newsletter, protected with reCAPTCHA v3.
- **Staff-managed content:** sliders, campaigns, categories and pages editable by the team without code changes.

### 🎓 [Rocket LMS · Online learning marketplace](https://lms.rocket-soft.org)
**Full-featured e-learning platform with courses, live classes and a tutor marketplace**

`Laravel` `MySQL` `REST API` `Localization (AR / EN / ES)` `Multi-currency`

**Role: Backend developer on a production Rocket LMS deployment.** I extended the platform with new and updated features, built a REST API on top of it, and delivered full translation support.

- **Feature development:** updated and extended existing platform features to fit the client's needs while keeping the core upgradable.
- **REST API:** designed and added API endpoints so the platform can be consumed by external clients such as mobile apps and third-party services.
- **Localization:** added translation support so the interface and content work across languages, including Arabic with RTL.
- **Platform scope:** courses and bundles, quizzes and assignments, verifiable certificates, live classes, instructor finder with meeting booking, subscriptions and installments, store, reward points, forums, blog and a job board.

### 🧩 Learning platform (LMS), custom build
**Online courses**

`Laravel 8` `laravel-modules` `Stripe`

Modular app with **Admin, Course and User modules**: courses, lectures, teachers, reviews, articles, cart and Stripe checkout, and translatable content.

### 🏢 CRM & invoicing systems · Atyaf Company *(2022 – 2023)*
**Customer management and finance**

`Laravel`

Backend developer. Built the **CRM**, the **invoicing system** and the **learning management system (LMS)**.

> 🔒 Code is private under client agreements. I'm happy to walk through the architecture, design decisions and trade-offs in an interview.

---

## 🎓 Education & certifications

- **B.Sc. Software Engineering**, Al-Azhar University
- **Certifications:** Laravel · AI Workflow Automation · Power BI (PL-300) · Data Entry & Office Administration

---

## 🌍 Languages

Arabic (native) · English (professional proficiency)

---

## 📫 Let's work together

I'm open to backend, Laravel and automation projects, whether you need a new system, an API, an admin panel, or a smarter workflow.

[![LinkedIn](https://img.shields.io/badge/Message_me_on_LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/mohammed-mostafa33)