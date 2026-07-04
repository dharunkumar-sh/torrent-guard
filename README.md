<div align="center">
  <h1 style="background:linear-gradient(45deg,#4b6cb7,#182848);-webkit-background-clip:text;-webkit-text-fill-color:transparent;">Torrent Guard</h1>
  <h3 style="color:#a0aec0;">开户注册 Flood Analyzer & Risk Detection</h3>
  <p>
    <a href="https://github.com/dharunkumar-sh/torrent-guard"><img src="https://img.shields.io/github/stars/dharunkumar-sh/torrent-guard?style=flat-square" alt="GitHub Stars"></a>
    <a href="https://github.com/dharunkumar-sh/torrent-guard"><img src="https://img.shields.io/github/forks/dharunkumar-sh/torrent-guard?style=flat-square" alt="GitHub Forks"></a>
    <a href="https://www.npmjs.com/package/flood-analyser-app"><img src="https://img.shields.io/npm/v/flood-analyser-app?style=flat-square" alt="NPM Version"></a>
    <a href="https://github.com/dharunkumar-sh/torrent-guard/blob/main/package.json"><img src="https://img.shields.io/github/package-json/dependency-version/dharunkumar-sh/torrent-guard/next?label=next&style=flat-square" alt="Next.js Version"></a>
    <a href="https-large"><img src="https://img.shields.io/badge/TypeScript-4.7.4-blue?style=flat-square" alt="TypeScript"></a>
  </p>
</div>

---

## 📖 Description

Torrent Guard is a lightweight **Next.js** web application that visualizes torrent traffic, analyzes flood patterns, and flags potential risks in real time. Built with TypeScript, Radix UI, and Tailwind CSS, it offers a clean, responsive interface for monitoring torrent activity and protecting users from malicious or excessive traffic.

---

## 📄 Table of Contents

- [Features](#-features)
- [Tech Stack](#-tech-stack)
- [Getting Started](#-getting-started)
- [Usage](#-usage)
- [Folder Structure](#-folder-structure)
- [Contributing](#-contributing)
- [License](#-license)
- [Acknowledgements](#-acknowledgements)

---

## 🚀 Features

| Feature | Description |
|---------|-------------|
| **Flood Analysis** | Real‑time dashboard displaying torrent uploads, downloads, and peer counts. |
| **Risk Detection** | Automatic alerts when traffic exceeds configurable thresholds. |
| **Responsive UI** | Mobile‑first design using Tailwind CSS. |
| **Component Library** | Reusable Radix‑based UI components (buttons, alerts, tabs, etc.). |
| **TypeScript** | Strict typing for safer code and developer ergonomics. |
| **Server‑Side Rendering** | Next.js for SEO & fast initial load. |
| **Hot‑Reloading** | Instant feedback during development. |

---

## 🛠️ Tech Stack

- **Framework**: [Next.js](https://nextjs.org)  
- **Language**: [TypeScript](https://www.typescriptlang.org)  
- **UI Components**: [Radix UI](https://www.radix-ui.com)  
- **Styling**: [Tailwind CSS](https://tailwindcss.com) + [clsx](https://github.com/lukeed/clsx) + [class-variance-authority](https://github.com/joe-bell/class-variance-authority)  
- **Icons**: [Lucide](https://lucide.dev)  
- **Build Tool**: `next build` / `469`  
- **Linting**: ESLint + Next.js config  
- **Environment**: Node.js (recommended ≥ 16.x)

---

## 📦 Getting Started

```bash
# Clone the repository
git clone https://github.com/dharunkumar-sh/torrent-guard.git
cd torrent-guard

# Install dependencies
npm install

# Start the development server
npm run dev
# or run the provided script
./start-dev.sh
```

Open your browser at <http://localhost:3000> to view the app. The development server supports hot‑module replacement, so changes are reflected instantly.

---

## ⚙️ Usage

```bash
# Build for production
npm run build

# Start the production server
npm start
```

> **Tip**: The app can also be deployed to Vercel or any platform that supports Next.js. Just push the repository and let Vercel handle the build.

---

## 📁 Folder Structure

```text
torrent-guard/
├─ app/
│  ├─ favicon.ico
│  ├─ globals.css
│  ├─ layout.tsx
│  └─ page.tsx
├─ components/
│  └─ ui/
│     ├─ alert-dialog.tsx
│     ├─ badge.tsx
│     ├─ button.tsx
│     ├─ card.tsx
│     ├─ input.tsx
│     ├─ label.tsx
│     ├─ select.tsx
│     ├─ separator.tsx
│     ├─ tabs.tsx
│     └─ textarea.tsx
├─ lib/
│  └─ utils.ts
├─ public/
│  └─ logo.svg
├─ .gitignore
├─ eslint.config.mjs
├─ next.config.ts
├─ package-lock.json
├─ package.json
├─ postcss.config.mjs
├─ start-dev.sh
├─ tsconfig.json
└─ README.md
```

---

## 🤝 Contributing

We welcome contributions! Please read the following guidelines:

1. Fork the repository and create a branch for your feature/bugfix.
2. Ensure TypeScript compiles (`npm run lint`).
3. Add tests if applicable.
4. Submit a pull request and describe your changes.

All contributions must adhere to the **[Contributor Covenant](https://www.contributor-covenant.org/)** code of conduct.

---

## 📜 License

This project is currently **unlicensed**. If you wish to use the code, please contact the author for clarification on usage rights.

---

## 🙏 Acknowledgements

- **Radix UI** – Accessible component primitives.  
- **Tailwind CSS** – Utility-first styling.  
- **Lucide** – Modern icon set.  
- **Next.js** – React framework for production.  
- **TypeScript** – Static typing.  

---
