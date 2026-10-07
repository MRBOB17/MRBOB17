<h1 align="center">Hi, I'm Vitaliy 👋</h1>
<h3 align="center">Full-stack Laravel developer · PHP · Laravel · Vue 3 · Filament</h3>

<p align="center">
  I build commercial web products in a team: SaaS platforms, booking services and AI-powered apps.<br>
  Backend-first, but I'm just as comfortable shipping the UI on top of it.
</p>

---

### 🧰 Tech stack

**Backend**
<p>
  <img src="https://img.shields.io/badge/PHP_8.4-777BB4?style=flat-square&logo=php&logoColor=white" alt="PHP">
  <img src="https://img.shields.io/badge/Laravel_11--13-FF2D20?style=flat-square&logo=laravel&logoColor=white" alt="Laravel">
  <img src="https://img.shields.io/badge/Filament-FDAE4B?style=flat-square&logo=laravel&logoColor=white" alt="Filament">
  <img src="https://img.shields.io/badge/Livewire-4E56A6?style=flat-square&logo=livewire&logoColor=white" alt="Livewire">
  <img src="https://img.shields.io/badge/Sanctum-FF2D20?style=flat-square&logo=laravel&logoColor=white" alt="Sanctum">
  <img src="https://img.shields.io/badge/Horizon-405263?style=flat-square&logo=laravel&logoColor=white" alt="Horizon">
  <img src="https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white" alt="MySQL">
  <img src="https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white" alt="Redis">
  <img src="https://img.shields.io/badge/PHPUnit-3C9CD7?style=flat-square&logo=php&logoColor=white" alt="PHPUnit">
</p>

**Frontend**
<p>
  <img src="https://img.shields.io/badge/Vue_3-4FC08D?style=flat-square&logo=vuedotjs&logoColor=white" alt="Vue 3">
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black" alt="JavaScript">
  <img src="https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white" alt="Tailwind CSS">
  <img src="https://img.shields.io/badge/Alpine.js-8BC0D0?style=flat-square&logo=alpinedotjs&logoColor=black" alt="Alpine.js">
  <img src="https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white" alt="Vite">
</p>

**Integrations & tooling**
<p>
  <img src="https://img.shields.io/badge/Laravel_Echo-WebSockets-FF2D20?style=flat-square&logo=laravel&logoColor=white" alt="Laravel Echo">
  <img src="https://img.shields.io/badge/Firebase_FCM-FFCA28?style=flat-square&logo=firebase&logoColor=black" alt="Firebase">
  <img src="https://img.shields.io/badge/Telegram_Bot_API-26A5E4?style=flat-square&logo=telegram&logoColor=white" alt="Telegram">
  <img src="https://img.shields.io/badge/PayPal-003087?style=flat-square&logo=paypal&logoColor=white" alt="PayPal">
  <img src="https://img.shields.io/badge/LLM_APIs-Gemini_·_OpenAI_·_Claude-412991?style=flat-square&logo=openai&logoColor=white" alt="LLM APIs">
  <img src="https://img.shields.io/badge/MCP-AI_agents-000000?style=flat-square&logo=anthropic&logoColor=white" alt="MCP">
  <img src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white" alt="GitHub Actions">
  <img src="https://img.shields.io/badge/PhpStorm-000000?style=flat-square&logo=phpstorm&logoColor=white" alt="PhpStorm">
</p>

---

### 🚀 What I've been building

> The repositories are private (commercial products), so here is what I worked on.

#### 🗂 Logicore — project management platform
Internal SaaS for running a web studio: tasks & Kanban, sprints, meetings, time tracking, client requests, QA reports and contracts.
`Laravel 12` `Vue 3` `Tailwind 4` `Laravel Echo` `Horizon` `Laravel MCP`

- **Telegram integration**: personal notifications via a bot, webhook handling, localized messages
- **MCP server tools** that let AI agents manage meetings and users through the tracker
- **Client requests module**: client portal, filters, notifications for the team
- **Personal analytics dashboard**: task/project widgets, activity heatmap, responsive layout
- **Real-time updates** for comments and Kanban via broadcasting
- **QA flow**: test reports with one-click task creation
- **Sprints**: carrying unfinished tasks over to the next sprint
- **Company contracts**: one-off and subscription-based
- **GitHub integration**: pull request webhooks, connection ping, repository linking
- DOCX preview and media streaming, full Ukrainian localization

#### 🎁 GiftyAI — AI gift recommendation service
LLM-powered gift finder for the Italian market with a hybrid SaaS + affiliate model.
`Laravel 13` `PHP 8.4` `Filament 5` `Livewire 4` `Alpine.js` `Gemini / OpenAI / Claude`

- **AI chat** with voice input (speech-to-text transcription)
- **Cart API, checkout and payments**: payment session reuse, order cancellation, paid-order protection
- **Partner dashboard**: revenue analytics, top-products widget, unified order statuses
- **Partner auth hardening**: rate limiting and status gate for web and API
- **Multi-currency and language switcher**, 5 locales (EN / IT / FR / UK / RU)
- Account deletion, transactional email templates (order status, shipping with tracking)

#### 💇 vTime — salon booking aggregator
Backend and REST API for mobile apps that connect clients with beauty salons.
`Laravel 11` `Sanctum` `Horizon` `Redis` `Firebase FCM`

- **Push notifications**: role-based FCM token management, no duplicate alerts when the app is closed
- **Telegram bot** connection and localized notifications
- **Timezone-safe scheduling**: parsing in the user's timezone, storing in UTC, booking conflict fixes
- **Account deletion** for users and companies with full cleanup of related data
- **Multilingual categories**: refactored categories/subcategories to JSON translations
- Quarterly statistics for salon owners

---

### 🛠 How I work

- Thin controllers, business logic in **Action classes**, access control with **Policies**, **Enums** instead of magic strings
- Feature tests with **PHPUnit** for new logic, both happy path and rejections
- Conventional commits, code review through pull requests, CI checks on GitHub Actions
- i18n from day one: every project I touch ships in several languages
- AI-assisted development: building MCP tools and using AI agents in the daily workflow

---

### 📊 GitHub stats

<p align="center">
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=MRBOB17&show_icons=true&count_private=true&include_all_commits=true&hide_border=true&theme=transparent" alt="GitHub stats">
  <img height="165" src="https://streak-stats.demolab.com?user=MRBOB17&hide_border=true&theme=transparent" alt="GitHub streak">
</p>

---

### 📫 Contact

<!-- Fill in your links and uncomment the lines you need:
<p>
  <a href="https://t.me/YOUR_TELEGRAM"><img src="https://img.shields.io/badge/Telegram-26A5E4?style=flat-square&logo=telegram&logoColor=white" alt="Telegram"></a>
  <a href="https://www.linkedin.com/in/YOUR_LINKEDIN"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <a href="mailto:YOUR_EMAIL"><img src="https://img.shields.io/badge/Email-EA4335?style=flat-square&logo=gmail&logoColor=white" alt="Email"></a>
</p>
-->

Open to interesting Laravel / Vue projects. Feel free to reach out!
