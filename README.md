**Full Stack Developer | PHP • JavaScript • Tools & Systems Engineering**

I build developer tools, custom CMS solutions, and libraries with a focus on clean architecture, zero-dependency engineering, and shipping things that actually work.

By trade I work with PHP, MySQL, and modern JavaScript. By curiosity I build full systems from scratch — CMS engines, database tools, PRNG libraries — to better understand fundamentals, performance tradeoffs, and architectural decisions.

---

## 🚀 Projects

### 🗄 DBForge
*The database tool phpMyAdmin should have been.*

A ground-up phpMyAdmin alternative built in pure PHP with vanilla JavaScript and zero external dependencies (one MIT-licensed QR generator for 2FA aside). Drop the folder into your web root, run the 3-step installer, and manage your databases.

**Highlights**
- Custom SQL editor with a hand-built tokenizer (612 tokens across keywords, functions, types, constants) and context-aware autocomplete that understands `FROM`, `JOIN`, and table aliases
- AJAX inline cell editing — click any cell, type, hit Enter. No page reloads, ever.
- Cross-table search across an entire database in a single query
- Interactive SVG ER diagram with crow's foot notation, drag-to-position, auto-layout physics simulation, and per-database persistence
- Full CRUD for views, triggers, stored routines, and scheduled events
- Live processlist with auto-refresh, color-scaled query times, and self-kill protection
- 20 built-in themes (10 light, 10 dark) plus a custom theme API and per-zone font control
- 12-layer security chain: bcrypt + TOTP 2FA, CSRF, IP whitelist, brute force lockout, read-only mode, query audit logging
- Docker support — `docker-compose up` and you're running

👉 Repo: https://github.com/ClearanceClarence/DBForge

### 🧩 VoidForge CMS
A lightweight WordPress-style CMS built entirely in pure PHP — no frameworks, no Composer, no dependencies.

**Highlights**
- ~350KB total footprint, sub-50ms page loads without caching
- Plugin architecture with WordPress-style hooks
- 14+ custom field types including repeaters and groups
- Drag-and-drop menu builder, post revisions with diff comparison
- Dual theme system (dark and light), customizable admin UI
- Bulk actions, quick edit, and a clean REST API for headless usage
- Role-based security model

👉 Repo: https://github.com/ClearanceClarence/VoidForge-CMS

### 🌱 SeedForge
Advanced seedable PRNG library for JavaScript — published on npm, zero dependencies, full TypeScript definitions.

**Highlights**
- 6 PRNG algorithms (Mulberry32, Xoshiro128**, Xorshift128, PCG32, SFC32, LCG) with characteristic-based recommendations
- 17 statistical distributions: normal, exponential, Poisson, binomial, gamma, beta, Pareto, Zipf, von Mises, hypergeometric, and more
- 6 noise generators (Value, Simplex, Perlin, Worley, Ridged, Billowed) with fBm, turbulence, and domain warping
- Full state management — save, restore, clone, and `fork()` for independent sub-system streams
- Geometric utilities for 2D/3D point distribution, weighted selection, deck shuffling
- 100% reproducible — same seed, same sequence, every time
- Universal: works in Node.js, browsers, and module bundlers

👉 Repo: https://github.com/ClearanceClarence/seedforge-prng · [npm](https://www.npmjs.com/package/seedforge-prng)

---

## 🛠 Tech Stack

**Backend**
- PHP, MySQL, MariaDB, PDO
- REST APIs, prepared statements
- Authentication, CSRF, TOTP 2FA, bcrypt
- Custom CMS and tooling architecture

**Frontend**
- JavaScript (vanilla, ES modules)
- TypeScript, React
- SVG, Canvas 2D
- Custom tokenizers and syntax highlighting

**Platforms & Tooling**
- WordPress (custom plugins, SSO, custom post types)
- Docker, Git, Linux
- npm publishing, semantic versioning
- XAMPP / WAMP / MAMP / Laragon

---

## 🧠 What I Care About

- Clean architecture over clever abstractions
- Zero dependencies when it makes the code better, not just smaller
- Performance built on understanding fundamentals
- Reproducibility and determinism in systems that benefit from it
- Maintainable systems that scale with people, not just traffic
- Shipping real value instead of unnecessary complexity

---

If you enjoy building real systems — database tools, CMS engines, generative libraries — and solving real problems, we'll probably get along.
