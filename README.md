# Andres Crucitti

**Senior PHP / Laravel Developer** — Los Angeles metro (PT). Remote preferred, open to hybrid or on-site in the LA area.

15+ years building, integrating, deploying, and supporting production e-commerce and business applications in PHP — from initial schema design through deployment, on-call troubleshooting, and years of ongoing ownership. Strongest in Laravel, Livewire, REST integrations, MySQL, automated testing, and the Linux and Docker infrastructure underneath.

The four projects below are mine end to end, each with a real automated test suite, CI gating every push on static analysis and tests, and an open-source licence — Insights, Sessioneer, and Homie also include browser coverage. They're active, ongoing work — I rotate focus among them rather than developing all four in parallel, so scope and feature set will continue to evolve.

[Resume (PDF)](./Andres-Crucitti-PHP-Laravel-Developer.pdf)

## Technical skills

- **PHP/Laravel**: PHP 8.x, Laravel, Livewire/Volt, Composer, REST APIs, object-oriented design, SOLID principles
- **Testing & quality**: Automated testing with Pest, PHPUnit, and Playwright; PHPStan, Rector; CI/CD with GitHub Actions
- **Data & performance**: MySQL, SQLite, Redis, schema design, query optimization
- **Frontend & platforms**: JavaScript, Alpine.js, Tailwind CSS, Bootstrap, HTML/CSS, OpenCart, WordPress
- **Infrastructure & delivery**: Linux, Docker/Compose, AWS EC2/SES/SNS, Nginx, Apache, Cloudflare, Git
 
## Experience snapshot

15+ years of continuous hands-on PHP development and systems administration, primarily as the principal developer for one small-business owner across several business ventures:

- **2020-present:** Laravel/Livewire applications, e-commerce automation, reservations, CRM, integrations, and production infrastructure
- **2014-2020:** Custom PHP, WordPress, hosting, migrations, and systems administration for 20-30 local-business websites
- **2010-2014:** E-commerce and dropshipping systems, distributor imports, payment gateways, and 20,000+ product catalogs

## Selected projects

### [Insights](https://github.com/loki495/insights) [![CI](https://github.com/loki495/insights/actions/workflows/ci.yml/badge.svg)](https://github.com/loki495/insights/actions/workflows/ci.yml) — Laravel · Livewire Volt · Plaid · AGPL-3.0 · [Demo](https://insights-demo.ac495.net)

A personal-finance application that syncs bank and credit transactions through **Plaid**, with hierarchical user categories, rule-based auto-categorization, transfer matching, and Chart.js reporting. A large Pest + Playwright suite runs in CI against **both SQLite and a live MySQL 8 service**, then builds the production Docker image, boots it, and smoke-tests it. PHPStan, Rector, Pint and Peck gate every push.

Demo login: `test@example.com` / `password`

### [Sessioneer](https://github.com/loki495/sessioneer) [![CI](https://github.com/loki495/sessioneer/actions/workflows/ci.yml/badge.svg)](https://github.com/loki495/sessioneer/actions/workflows/ci.yml) — PHP · tmux · UNIX sockets · MIT

A self-hosted, LAN-only web UI for managing coding-agent sessions (Claude Code, Antigravity, OpenCode, Codex) from a phone or any browser — see blocked prompts, answer them, view live transcripts, and kill sessions without touching the machine directly. Dozens of hermetic test files with 2,000+ assertions, none of which touch a real tmux server.

### [Homie](https://github.com/loki495/homie) [![CI](https://github.com/loki495/homie/actions/workflows/ci.yml/badge.svg)](https://github.com/loki495/homie/actions/workflows/ci.yml) — Laravel 13 · Livewire 4 · Flux · MIT · [Demo](https://homie-demo.ac495.net)

A home-lab dashboard for organizing services into configurable cards, including links, plain Bash command output, and live API data from services such as Sonarr, Radarr, and NZBGet. It can also discover Docker services on LAN machines over the Docker API or SSH after configuring the target machine and starting a scan. Built to be genuinely distributable: no hostname, service, or credential exists anywhere in the code. Real application login gates every deployment, including this demo. **200+ tests** in CI (as of Sept. 2026), plus a containerized real-browser suite.

Demo login: `demo@homie.ac495.net` / `homie-demo-2026`

### [Dibs](https://github.com/loki495/dibs) [![CI](https://github.com/loki495/dibs/actions/workflows/ci.yml/badge.svg)](https://github.com/loki495/dibs/actions/workflows/ci.yml) — Laravel · Livewire 4 · MCP · MIT · [Demo](https://dibs-demo.ac495.net)

A self-hosted todo list app that's MCP-native: AI agents (Claude, Codex) read, claim, and complete tasks through the same Actions the web UI uses, over a host-local stdio MCP server, with local SQLite authoritative and GitHub Issues/Projects as an asynchronous mirror. A large automated test suite, plus PHPStan, Rector, and Pint gate every push.

Demo login: `demo@example.com` / `demo-password-please-change`

**Also:** [dotfiles](https://github.com/loki495/dotfiles) [![CI](https://github.com/loki495/dotfiles/actions/workflows/ci.yml/badge.svg)](https://github.com/loki495/dotfiles/actions/workflows/ci.yml) — my Arch Linux and PHP dev-tooling setup. CI runs the real installer in a container on every push, asserts on every symlink it creates, then opens each supported language in a live tmux + Neovim session to confirm treesitter highlighting actually loads.

I use coding agents as implementation and review tools. I remain responsible for architecture, validation, tests, security decisions, and maintenance.

## Open-source contributions

- **Merged into [SerenityOS](https://github.com/SerenityOS/serenity/pull/6720)** — added a "Game of Life" app to the system's bundled games.
- **Merged into [PeckPHP](https://github.com/peckphp/peck/pull/28)** — added full line and column reporting for misspellings, after a maintainer review cycle with Nuno Maduro.

## What I am looking for

Permanent PHP/Laravel roles building and supporting real products on an engineering team — also open to backend, platform, or Linux-infrastructure-adjacent roles. Remote preferred; equally open to hybrid or on-site in the LA metro area.

## Contact

- [GitHub profile](https://github.com/loki495)
- [LinkedIn](https://www.linkedin.com/in/andres-crucitti-32ab2313)
- andres@ac495.net
