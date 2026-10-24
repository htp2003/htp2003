# Hi, I'm Phát 👋

**Junior Frontend Developer** building production admin platforms with **React + TypeScript**.
I care about clean feature architecture, strict typing, and following the backend contract closely, so features ship stable and stay easy to maintain.

📍 Ho Chi Minh City, Vietnam · 🌐 [htp-portfolio.vercel.app](https://htp-portfolio.vercel.app) · 💼 [LinkedIn](https://www.linkedin.com/in/hà-tấn-phát-41008727a)

---

### 💼 Experience

**Junior Frontend Developer — Estuary Solutions** *(Dec 2025 – Present)*
Joined as a Fresher, promoted to Junior after probation in Feb 2026.

- Built the full frontend of admin panels for **product authentication (UID/QR traceability)** and **e-commerce**, covering operational workflows, user management and role-based permissions
- Developed new modules and maintained features in a **membership administration platform**, including electronic member cards and tier management
- Delivered features such as QR/UID print and reprint approvals, batch generation, warehouse transfers, kitting/unkitting, farm and pond monitoring, and **Microsoft SSO** integration
- Managed server state with **TanStack Query** and UI state with **Zustand**, focusing on avoiding redundant requests and unnecessary re-renders (virtualized tables, `keepPreviousData` pagination, form `dependencies` over `useWatch`)
- Built reusable shared components and a consistent feature structure used across projects
- Worked with **GitLab CI, Docker, Nginx** for build and deploy pipelines; collaborated daily with Backend, BA, QA, CS and DevOps, and took part in code reviews

**Frontend Developer Intern — Amazing Tech** *(May 2024 – Aug 2024)*

- Built responsive React interfaces for customer dashboards
- Fixed and improved authentication, form validation and API-driven screens; joined code reviews
- Worked in sprints with daily standups and sprint planning

---

### 🌟 Personal Projects

#### 📚 [Ram Novel](https://github.com/htp2003/dark-novel)
Full-stack web novel platform in a **Yarn workspaces monorepo**: a fast public reading site and a separate admin panel for publishing.

- **Reader web** — **Astro** SSR on Vercel with almost zero client JS and CDN caching; likes, threaded comments and reply notifications updated in **real time** via Supabase Realtime; follow list, reading progress and chapter view tracking
- **Admin panel** — **React 19, Ant Design 6, TanStack Query 5, React Router 7, nuqs** (filters and pagination synced to the URL); permission-based feature modules, **Tiptap** rich-text chapter editor, and bulk import of a whole novel from `.docx` / `.txt` that auto-splits chapters with preview before saving
- **Backend** — **Supabase** (Postgres, Auth, Storage, Realtime) with **Row Level Security** so only admins can write; Postgres triggers keep like/comment counts and notifications consistent
- **Safety & quality** — every payload validated with **Zod**, chapter HTML sanitized with **DOMPurify**, strict TypeScript, **Vitest** tests, ESLint + Prettier + Husky pre-commit hooks

`Astro` `React` `TypeScript` `Ant Design` `TanStack Query` `Supabase` `PostgreSQL` `Tailwind CSS` `Vitest`

#### ✨ [Portfolio v3](https://github.com/htp2003/portfolio/tree/v3) · [Live](https://htp-portfolio.vercel.app)
My personal portfolio, rebuilt from scratch with a focus on motion and performance.

- **Next.js 16** App Router with **English / Vietnamese** localized routes, per-page SEO metadata, hreflang alternates and Open Graph images
- Interactive **WebGL fluid simulation** in the hero with bloom post-processing and theme-aware palettes; it only runs on desktop with a mouse, respects `prefers-reduced-motion`, pauses off-screen and lowers its own quality when frame time gets too high
- Page transitions and scroll effects with **GSAP** and **Framer Motion**, light/dark theme

`Next.js` `React 19` `TypeScript` `WebGL` `GSAP` `Framer Motion` `Tailwind CSS`

> Most of my professional work lives in private company repositories.

---

### 🛠 Tech Stack

**Frontend**
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white)
![Astro](https://img.shields.io/badge/Astro-BC52EE?style=for-the-badge&logo=astro&logoColor=white)
![Ant Design](https://img.shields.io/badge/Ant_Design-0170FE?style=for-the-badge&logo=antdesign&logoColor=white)
![TanStack Query](https://img.shields.io/badge/TanStack_Query-FF4154?style=for-the-badge&logo=reactquery&logoColor=white)
![Zustand](https://img.shields.io/badge/Zustand-443E38?style=for-the-badge&logo=react&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white)

**Backend & Data**
![Supabase](https://img.shields.io/badge/Supabase-3FCF8E?style=for-the-badge&logo=supabase&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-43853D?style=for-the-badge&logo=node.js&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-4ea94b?style=for-the-badge&logo=mongodb&logoColor=white)

**Tooling & DevOps**
![Vite](https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white)
![Vitest](https://img.shields.io/badge/Vitest-6E9F18?style=for-the-badge&logo=vitest&logoColor=white)
![GitLab CI](https://img.shields.io/badge/GitLab_CI-FC6D26?style=for-the-badge&logo=gitlab&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=for-the-badge&logo=nginx&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white)

---

### 📬 Get in touch
- **Email:** hatanphat1121@gmail.com
- **LinkedIn:** [Hà Tấn Phát](https://www.linkedin.com/in/hà-tấn-phát-41008727a)
- **Portfolio:** [htp-portfolio.vercel.app](https://htp-portfolio.vercel.app)
