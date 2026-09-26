# Full-Stack Developer

PHP · JavaScript/TypeScript · C#/.NET · MySQL/MariaDB · Tooling and systems

I'm a full-stack developer based in Norway with around seven years of professional experience, mostly building client solutions, integrations, dashboards, and custom plugins in agency settings. Outside of client work, I build complete systems from the ground up — a disk space visualizer, a database administration tool, a CMS — to understand fundamentals, performance tradeoffs, and architectural decisions firsthand.

I favor clean architecture, minimal dependencies where they improve the code, and shipping things that work.

---

## Projects

### SpaceSharp
A disk space visualizer for Windows in the style of SpaceMonger, written in C# with WPF on .NET 10. Scans a drive or folder and renders usage as an interactive treemap so large files and directories stand out at a glance.

- Interactive nested treemap of disk usage
- Multiple color palettes with light and dark mode
- Distributed as a portable single executable, plus Setup.exe and MSI installers with auto-update via Velopack
- MIT licensed

Repository: https://github.com/ClearanceClarence/SpaceSharp

### Ledger
A phpMyAdmin alternative written in plain PHP and vanilla JavaScript, with no external dependencies apart from an MIT-licensed QR generator used for 2FA. Drop the folder into a web root, run the three-step installer, and start managing databases.

- SQL editor with a hand-built tokenizer and context-aware autocomplete (understands `FROM`, `JOIN`, and table aliases)
- Inline cell editing over AJAX, no page reloads
- Cross-table search across an entire database
- Interactive SVG ER diagrams with crow's foot notation, drag positioning, auto-layout, and per-database persistence
- Full CRUD for views, triggers, stored routines, and scheduled events
- Live process list with auto-refresh, query-time coloring, and one-click kill
- Query history with error capture and full PDO error details
- Index management with composite key support
- phpMyAdmin-compatible SQL exports (tables → data → indexes → constraints)
- 20 built-in themes plus a custom theme API
- Layered security: bcrypt, TOTP 2FA, CSRF protection, IP whitelisting, brute-force lockout, read-only mode, and query audit logging
- Docker support

Repository: https://github.com/ClearanceClarence/Ledger

### VoidForge CMS
A lightweight, WordPress-style CMS in plain PHP — no framework, no Composer, no dependencies.

- Roughly 350 KB footprint; sub-50 ms page loads without caching
- Plugin architecture with WordPress-style hooks
- 14+ custom field types, including repeaters and groups
- Drag-and-drop menu builder and post revisions with diff comparison
- Dark and light admin themes
- Bulk actions, quick edit, and a REST API for headless use
- Role-based access control

Repository: https://github.com/ClearanceClarence/VoidForge-CMS

---

## Tech Stack

**Backend:** PHP, MySQL, MariaDB, PDO, C#/.NET, REST APIs, authentication (bcrypt, TOTP 2FA, CSRF, OAuth/SSO)

**Frontend:** JavaScript (vanilla, ES modules), TypeScript, React, SVG, Canvas 2D

**Platforms and tooling:** WordPress (custom plugins, SSO, custom post types), WooCommerce, Docker, Git, Linux, WPF

---

## How I Work

- Clear structure over clever abstractions
- Dependencies only where they make the code better
- Performance grounded in an understanding of the fundamentals
- Reproducibility and determinism where they add value
- Code that stays maintainable as the team grows, not just as traffic does

---

I'm currently open to full-stack and developer roles, including remote work. If you're building real systems and want to talk, feel free to reach out.
