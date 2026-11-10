# nameuser4123

👤 **GitHub**: [nameuser4123](https://github.com/nameuser4123)  
🔧 **Part-time Full-stack Software Engineer** at [LoBot LLC](https://github.com/LoBot-LLC)  
🌙 *Just wanna sleep all day :((*

---

## 🎨 About Me

I'm **nameuser4123** (m1zuk!), a part-time full-stack software engineer working with [LoBot LLC](https://github.com/LoBot-LLC). When I'm not coding, you can find me:

- 😴 **Resting** — I don't travel much and prefer staying at home
- 🎬 **Anime marathons** — Favorite includes *Attack on Titan*
- 📚 **Manga reading** — Following *Conan* and *One Piece*
- 🦖 **Kaiju movies** — Especially *Godzilla: Minus One* and the classic *Godzilla (1954)*

I'm a **liberal** who believes in making all software free and open source. My philosophy aligns with the free software movement — software should be free as in freedom, not just price.

---

## 📂 Repository Overview

I maintain 4 public repositories, all written in **TypeScript**:

| Repository | Description | Primary Language | License |
|------------|-------------|------------------|---------|
| [nameuser4123](https://github.com/nameuser4123/nameuser4123) | A brief introduction of m1zuk! | TypeScript | GNU GPL v3.0 |
| [.github](https://github.com/nameuser4123/.github) | Overall introduction to LoBot LLC startup | — | GNU AGPL v3.0 |
| [lobot-homepage](https://github.com/nameuser4123/lobot-homepage) | The OFFICIAL HOMEPAGE of LoBot LLC! | TypeScript | BSD-3-Clause |
| [tecno-indicator-personal-own](https://github.com/nameuser4123/tecno-indicator-personal-own) | The most reliable website to predict real-time oil and electricity prices for the next decade to come! | TypeScript | MIT License |

**Tech Stack across all repositories**: TypeScript (100%)

---

## 🏠 Main Project: LoBot Homepage

My flagship project is the **[LoBot Homepage](https://github.com/nameuser4123/lobot-homepage)**, forked from [LoBot-LLC/homepage](https://github.com/LoBot-LLC/homepage). It's the official landing website for [LoBot LLC](https://lobotllc.vercel.app/).

### 🚀 Quick Overview

The OFFICIAL HOMEPAGE of LoBot LLC — an AI-native startup building logistics and business solutions that help organizations of every size make future-ready strategic decisions.

**Live Demo**: [https://lobotllc.vercel.app/](https://lobotllc.vercel.app/)

### 🛠 Tech Stack (LoBot Homepage)

| Category | Technology |
|----------|------------|
| **Framework** | Next.js 16.4.5 (App Router, Turbopack) |
| **Language** | TypeScript 5.9 |
| **Styling** | Tailwind CSS 4.1 (PostCSS) |
| **Database** | PostgreSQL + Drizzle ORM 0.45 |
| **Runtime** | Node.js 22+ |
| **Package Manager** | npm (with `package-lock.json` for reproducibility) |
| **Linting** | ESLint 9 + eslint-config-next |
| **CI/CD** | GitHub Actions (Node.js `latest`) |
| **Internationalization** | 3 languages: English, Spanish, Vietnamese |

### 📁 Project Structure

```
src/
├── app/              # Next.js App Router pages and API routes
│   ├── api/          # API endpoints (health, blog)
│   ├── blog/         # Blog functionality
│   ├── products/     # Products index and TecnoIndicator
│   ├── about/        # About page
│   ├── careers/      # Careers page
│   ├── layout.tsx    # Root layout
│   └── page.tsx      # Homepage
├── components/       # Reusable UI components
│   ├── Navbar.tsx    # Sticky navbar with toggles
│   ├── Footer.tsx    # Footer with logo and links
│   ├── Icons.tsx     # SVG icons and brand marks
│   ├── Providers.tsx # React context providers
│   └── ui.tsx        # Reusable UI components
├── db/               # Drizzle ORM database layer
│   ├── schema.ts     # Blog schema/types
│   └── index.ts      # Lazy-initialized Drizzle client
├── lib/              # Utility libraries
│   ├── blog.ts       # Blog data layer with seed posts
│   ├── github.ts     # GitHub helpers for community stats
│   └── site.ts       # Site constants (email, URLs)
└── i18n/             # Internationalization files (en, es, vi)
```

### 🌍 Internationalization

The site supports **3 languages** out of the box:
- **English** (`en`) — default
- **Spanish** (`es`)
- **Vietnamese** (`vi`)

Language is detected from the browser and persisted via a cookie.

### 🧪 Quality Checks

Run the full CI pipeline:
```bash
npm run typecheck   # TypeScript type checking
npm run lint        # ESLint
npm run build       # Production build
```

CI runs on every push/PR to `main` with Node.js `latest`.

### 📄 License

**BSD 3-Clause License** — see [LICENSE](https://github.com/nameuser4123/lobot-homepage/blob/main/LICENSE) for details.

---

## 💡 Core Beliefs

- 🗽 **Liberal mindset** — I believe in making all software free and open source
- 💻 **Free software for all** — Software freedom is a fundamental right
- 🏠 **Homebody** — Prefers staying at home, doesn't travel much
- 🌙 **Work-life balance** — Part-time work allows me to enjoy personal interests

---

## 📜 License

This profile and repositories are licensed under various open source licenses. See individual repositories for specific licensing terms.

---

*✨ "Code is like humor. When you have to explain it, it's bad." — Cory House*

*Last updated: November 10, 2026*