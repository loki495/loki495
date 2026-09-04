# Andres Crucitti

**Senior PHP / Laravel Developer** — Los Angeles metro (PT). Remote preferred, open to hybrid or on-site in the LA area.

15+ years building, integrating, deploying, and supporting production e-commerce and business applications in PHP — from initial schema design through deployment, on-call troubleshooting, and years of ongoing ownership. Strongest in Laravel, Livewire, REST integrations, MySQL, automated testing, and the Linux and Docker infrastructure underneath.

The three projects below are mine end to end: **nearly 4,000 automated tests and checks** between them, CI gating every push on static analysis and the full suite, including browser smoke tests, and an open-source licence on each.

[Resume (PDF)](./Andres-Crucitti-PHP-Laravel-Developer.pdf)

## Current focus

- PHP 8.x, Laravel, Livewire/Volt, Alpine.js, and Tailwind CSS
- REST APIs, third-party integrations, queues, and automation
- MySQL schema design, query optimization, SQLite, and Redis
- Automated testing with Pest, PHPUnit, and Playwright
- PHPStan, Rector, CI/CD, and GitHub Actions
- Linux, Docker Compose, AWS, Nginx, Apache, and Cloudflare

## Experience snapshot

15+ years of continuous hands-on PHP development and systems administration, primarily as the principal developer for one small-business owner across several business ventures:

- **2020-present:** Laravel/Livewire applications, e-commerce automation, reservations, CRM, integrations, and production infrastructure
- **2014-2020:** Custom PHP, WordPress, hosting, migrations, and systems administration for 20-30 local-business websites
- **2010-2014:** E-commerce and dropshipping systems, distributor imports, payment gateways, and 20,000+ product catalogs

## Selected projects

### [Insights](https://github.com/loki495/insights) [![CI](https://github.com/loki495/insights/actions/workflows/ci.yml/badge.svg)](https://github.com/loki495/insights/actions/workflows/ci.yml) — Laravel · Livewire Volt · Plaid · AGPL-3.0

A personal-finance application that syncs bank and credit transactions through **Plaid**, with hierarchical user categories, rule-based auto-categorization, transfer matching, and Chart.js reporting. **1,100+ automated checks** (Pest + Playwright) on a CI pipeline that runs the suite against **both SQLite and a live MySQL 8 service**, then builds the production Docker image, boots it, and smoke-tests it. PHPStan, Rector, Pint and Peck gate every push.

### [Sessioneer](https://github.com/loki495/sessioneer) [![CI](https://github.com/loki495/sessioneer/actions/workflows/ci.yml/badge.svg)](https://github.com/loki495/sessioneer/actions/workflows/ci.yml) — PHP · tmux · UNIX sockets · MIT

~24k lines of PHP behind a two-runtime architecture: the Dockerized web UI communicates over a UNIX socket with a host-native agent, keeping tmux and host-process access out of the container. Supports both tmux-backed sessions (Claude Code, Antigravity, and OpenCode’s fallback mode) and headless agent servers (OpenCode’s default mode and Codex), all managed from any browser, including mobile, with live transcripts, blocked-prompt answering, history search, and session lifecycle controls. Backed by 35 dependency-free, self-isolating test files containing **2,400+ automated checks** that never touch the real tmux server.

### [Homie](https://github.com/loki495/homie) [![CI](https://github.com/loki495/homie/actions/workflows/ci.yml/badge.svg)](https://github.com/loki495/homie/actions/workflows/ci.yml) — Laravel 13 · Livewire 4 · Flux · MIT

A home-lab dashboard for organizing services into configurable cards, including links, plain Bash command output, and live API data from services such as Sonarr, Radarr, and NZBGet. It can also discover Docker services on LAN machines over the Docker API or SSH after configuring the target machine and starting a scan. Built to be genuinely distributable: no hostname, service, or credential exists anywhere in the code. **390+ automated checks** in CI, plus a containerized real-browser suite.

I use AI tools selectively to accelerate research and implementation; I review, test, and take responsibility for the architecture and final code. I bring 15+ years of PHP experience, including many years before I began using AI coding tools.

## Open-source contributions

- **Merged into [SerenityOS](https://github.com/SerenityOS/serenity/pull/6720)** — added a "Game of Life" app to the system's bundled games.
- **Merged into [PeckPHP](https://github.com/peckphp/peck/pull/28)** — added full line and column reporting for misspellings, after a maintainer review cycle with Nuno Maduro.

## What I am looking for

Permanent full-time or part-time PHP/Laravel roles where I can build and support real products as part of an engineering team. Also open to backend, platform, and Linux-oriented roles that benefit from a developer with production infrastructure experience.

Remote is my preference, but I am equally open to hybrid or on-site work anywhere in the Los Angeles metro area — I drive and am happy to be in an office when that is how the team works best.

## Contact

- [GitHub profile](https://github.com/loki495)
- [LinkedIn](https://www.linkedin.com/in/andres-crucitti-32ab2313)
- +1 (714) 936-1988
- andres@ac495.net
