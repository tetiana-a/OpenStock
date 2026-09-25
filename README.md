<div align="center">

📈 OpenStock — tetiana kotolup Edition

🚀 A modern, open-source stock market terminal for everyday investors

<p>
  <a href="https://tetianakotolup.com/" target="_blank">
    <img src="https://img.shields.io/badge/🚀%20Live%20Demo-OpenStock-00C7B7?style=for-the-badge" alt="Live Demo">
  </a>
  <a href="https://github.com/tetiana-a/OpenStock" target="_blank">
    <img src="https://img.shields.io/badge/GitHub-Source%20Code-181717?style=for-the-badge&logo=github" alt="GitHub">
  </a>
  <a href="https://github.com/Open-Dev-Society/OpenStock" target="_blank">
    <img src="https://img.shields.io/badge/Based%20on-OpenStock-0A0A0A?style=for-the-badge" alt="Original OpenStock">
  </a>
</p>

<p>
  <img src="https://img.shields.io/badge/Next.js-15-black?style=flat-square&logo=next.js" alt="Next.js">
  <img src="https://img.shields.io/badge/React-19-61DAFB?style=flat-square&logo=react" alt="React">
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" alt="TypeScript">
  <img src="https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=flat-square&logo=tailwindcss&logoColor=white" alt="Tailwind CSS">
  <img src="https://img.shields.io/badge/MongoDB-00A35C?style=flat-square&logo=mongodb&logoColor=white" alt="MongoDB">
  <img src="https://img.shields.io/badge/Inngest-000000?style=flat-square" alt="Inngest">
  <img src="https://img.shields.io/badge/Finnhub-30B27A?style=flat-square" alt="Finnhub">
  <img src="https://img.shields.io/badge/TradingView-2962FF?style=flat-square&logo=tradingview&logoColor=white" alt="TradingView">
</p>

<p>
  <b>Personal deployment & customization by Eduard</b><br>
  Built on the open-source OpenStock project by Open Dev Society.<br>
  🌐 <a href="https://tetianakotolup.com/" target="_blank">tetianakotolup.com</a>
</p>

</div>

🌐 Live

OpenStock — your personal market terminal, available online from any device.

🌐 https://tetianakotolup.com/

📱 Desktop · Tablet · Mobile

🧭 What is OpenStock?

OpenStock is an open-source alternative to expensive market platforms.

It brings together:

📊 stock prices and market information

🔎 fast symbol search

⭐ personal watchlists

📈 TradingView charts and market views

🏢 company profiles and financial information

📰 market news

🔐 email/password authentication

🤖 automation and AI-powered workflows

🌍 support for international markets

OpenStock is a community-built market information application — not a brokerage and not financial advice. Market data availability and delay depend on the data provider and plan. fileciteturn1file0L47-L51

✨ Why this project?

🧠 Information without unnecessary complexity

The goal is simple:

Make useful market information easier to access, understand and explore.

The original Open Dev Society project is built around open technology, accessible learning and community-driven development. This fork keeps that spirit while adding a personal deployment and visual identity. fileciteturn1file0L75-L90

🚀 Main Features

🔐 Secure Authentication

Email/password registration and sign-in

Better Auth

MongoDB-backed sessions

Protected application routes

🔎 Smart Search

Fast stock search

Finnhub-powered symbols and company lookup

Command palette with Cmd/Ctrl + K

⭐ Personal Watchlist

Add and remove symbols

User-specific watchlists

Persistent storage in MongoDB

📈 Professional Market Views

TradingView charts

Candlestick and advanced chart views

Technical indicators

Company profile and financial widgets

Market heatmaps and top stories

📰 News & Insights

Market news through Finnhub

Optional cross-source sentiment integrations

Stock-specific information pages

🤖 Automation & AI

Inngest workflows

AI-powered welcome experience

Scheduled weekly news summaries

Gemini integration support

🌙 Clean Interface

Dark-first visual design

Tailwind CSS

shadcn/ui

Radix UI

Responsive interface for desktop and mobile

The original project documents these core capabilities, including authentication, search, watchlists, TradingView, onboarding, automation and the dark theme. fileciteturn1file0L115-L140

🧩 Technology Stack

🎨 Frontend

Technology

Purpose

Next.js 15

App framework

React 19

UI

TypeScript

Type-safe development

Tailwind CSS v4

Styling

shadcn/ui

UI components

Radix UI

Accessible primitives

Lucide

Icons

🗄️ Backend & Data

Technology

Purpose

MongoDB + Mongoose

Persistence

Better Auth

Authentication

Finnhub API

Market data and news

TradingView

Charts and market widgets

⚙️ Automation

Technology

Purpose

Inngest

Events, cron jobs and workflows

Nodemailer

Email delivery

Gemini

Optional AI-generated content

These technologies and integrations are documented in the original project README. fileciteturn1file0L92-L110

🏗️ Architecture

                        🌐 Browser
                            │
                            ▼
                    ┌────────────────┐
                    │    Next.js     │
                    │   App Router   │
                    └───────┬────────┘
                            │
            ┌───────────────┼────────────────┐
            ▼               ▼                ▼
      🔐 Better Auth     📊 Finnhub     📈 TradingView
            │               │                │
            └───────────────┼────────────────┘
                            ▼
                    🗄️ MongoDB
                            │
                            ▼
                       ⚙️ Inngest
                            │
                  ┌─────────┴─────────┐
                  ▼                   ▼
              🤖 AI Workflows      📧 Email

📱 Personalization

OpenStock includes an onboarding flow for:

🌍 Country

🎯 Investment goals

🛡️ Risk tolerance

🏭 Preferred industry

These preferences are used to personalize the application experience. fileciteturn1file0L131-L135

🛠️ Quick Start

1. Clone

git clone https://github.com/tetiana-a/OpenStock.git
cd OpenStock

2. Install dependencies

npm install

or:

pnpm install

3. Configure environment

Create a .env file in the project root.

NODE_ENV=development

MONGODB_URI=mongodb+srv://<user>:<pass>@<cluster>/<db>?retryWrites=true&w=majority

BETTER_AUTH_SECRET=your_better_auth_secret
BETTER_AUTH_URL=http://localhost:3000

NEXT_PUBLIC_FINNHUB_API_KEY=your_finnhub_key
FINNHUB_BASE_URL=https://finnhub.io/api/v1

INNGEST_SIGNING_KEY=your_inngest_signing_key

# Optional
GEMINI_API_KEY=your_gemini_api_key
NODEMAILER_EMAIL=youraddress@gmail.com
NODEMAILER_PASSWORD=your_gmail_app_password

The original project documents MongoDB, Better Auth, Finnhub, Inngest and optional AI/email variables in its environment configuration. fileciteturn1file0L247-L289

4. Check the database

npm run test:db

5. Start development

npm run dev

Open:

http://localhost:3000

The official project documents the same development flow and local URL. fileciteturn1file0L162-L191

🐳 Docker

OpenStock can also be run with Docker Compose.

docker compose up -d mongodb
docker compose up -d --build

Local application:

http://localhost:3000

MongoDB runs inside the Docker network and uses a persistent volume. fileciteturn1file0L193-L220

🔐 Production Deployment

☁️ Vercel

For a Vercel deployment, configure the required environment variables before deploying:

MONGODB_URI=...
BETTER_AUTH_SECRET=...
BETTER_AUTH_URL=...
NEXT_PUBLIC_FINNHUB_API_KEY=...
FINNHUB_BASE_URL=https://finnhub.io/api/v1
INNGEST_SIGNING_KEY=...

The project specifically marks NEXT_PUBLIC_FINNHUB_API_KEY as required for Vercel deployment and INNGEST_SIGNING_KEY as required for the Inngest integration. fileciteturn1file0L247-L285

🚀 Personal deployment

Live deployment:

👉 https://tetianakotolup.com/

📂 Project Structure

app/
├── (auth)/
│   ├── sign-in/
│   └── sign-up/
├── (root)/
│   ├── help/
│   ├── stocks/[symbol]/
│   └── watchlist/
├── api/inngest/
└── globals.css

components/
├── ui/
├── forms/
├── Header.tsx
├── Footer.tsx
├── SearchCommand.tsx
└── WatchlistButton.tsx

database/
├── models/
└── mongoose.ts

lib/
├── actions/
├── better-auth/
├── inngest/
└── nodemailer/

scripts/
types/
public/

This structure follows the project layout documented in the original repository. fileciteturn1file0L339-L374

🌍 Market Data

OpenStock uses multiple market-data and visualization sources:

🟢 Finnhub

Used for:

symbol search

company profiles

market news

🔵 TradingView

Used for:

charts

heatmaps

quotes

timelines

market views

🌎 International markets

The original project reports support for 30+ international exchanges, with availability and real-time/delayed behavior depending on provider limitations and plan. fileciteturn1file0L378-L425

⚠️ Important Security Rules

Never commit secrets to GitHub.

Keep these values private:

MONGODB_URI
BETTER_AUTH_SECRET
INNGEST_SIGNING_KEY
GEMINI_API_KEY
NODEMAILER_PASSWORD

Also remember:

Variables beginning with NEXT_PUBLIC_ are exposed to the browser.

The original project explicitly recommends keeping private keys server-side whenever possible and avoiding secrets in Dockerfiles or source code. fileciteturn1file0L334-L337

🧪 Useful Commands

# Development
npm run dev

# Production build
npm run build

# Production server
npm start

# Database connectivity test
npm run test:db

# Inngest local development
npx inngest-cli@latest dev

The project's documented scripts include development, build, start, lint and database testing. fileciteturn1file0L428-L440

🤝 Open Source & Contributions

OpenStock is built around an open-source community model.

Ideas, bug reports and focused pull requests are welcome. The original project encourages contributors to help beginners, avoid gatekeeping and keep pull requests focused. fileciteturn1file0L443-L450

🛡️ Security

If you discover a security vulnerability:

Do not open a public issue.

Use the responsible disclosure contact listed by the original project:

📧 opendevsociety@cc.cc fileciteturn1file0L452-L456

📜 License

OpenStock is licensed under AGPL-3.0.

The original project states that if you modify, redistribute or deploy the project as a web service, you must release the source under the same license and credit the original authors. fileciteturn1file0L459-L474

🏆 Credits & Acknowledgements

Original Project

Open Dev Society — OpenStock

🔗 https://github.com/Open-Dev-Society/OpenStock

Personal deployment & customization

Eduard

Special thanks to

Finnhub — market data

TradingView — market widgets

Next.js, React, Tailwind CSS

shadcn/ui and Radix UI

Inngest — workflows

Better Auth — authentication

MongoDB — persistence

All contributors who make open-source tools possible

The original project credits these technologies and contributors, including Adrian Hajdin / JavaScript Mastery, and thanks its broader open-source community. fileciteturn1file0L463-L498

<div align="center">

❤️ Built openly. Improved continuously.

OpenStock — tetiana kotolup Edition

🚀 Explore the market.
📊 Understand the data.
⭐ Build your watchlist.
🌍 Keep learning.

Open the live version →

</div>
