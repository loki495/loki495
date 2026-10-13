# Andres Crucitti

**Senior PHP / Laravel Developer** — Los Angeles metro (PT).

15+ years building, integrating, deploying, and supporting production e-commerce and business applications in PHP — from initial schema design through deployment, on-call troubleshooting, and years of ongoing ownership. Strongest in Laravel, Livewire, REST integrations, MySQL, automated testing, and the Linux and Docker infrastructure underneath.

I’m looking for a permanent PHP/Laravel backend or full-stack role building and supporting products on an engineering team. Remote preferred; equally open to hybrid or on-site work in the Los Angeles area.

[Resume (PDF)](./Andres-Crucitti-PHP-Laravel-Developer.pdf)

## Technical skills

- **PHP/Laravel**: PHP 8.x, Laravel, Livewire/Volt, Composer, REST APIs, object-oriented design, SOLID principles
- **Testing & quality**: Automated testing with Pest, PHPUnit, and Playwright; PHPStan, Rector; CI/CD with GitHub Actions
- **Data & performance**: MySQL, SQLite, Redis, schema design, query optimization
- **Frontend & platforms**: JavaScript, Alpine.js, Tailwind CSS, Bootstrap, HTML/CSS, OpenCart, WordPress
- **Infrastructure & delivery**: Linux, Docker/Compose, AWS EC2/SES/SNS, Nginx, Apache, Cloudflare, Git
 
## Selected projects

These four open-source projects grew out of tools I wanted for my own use. I build and maintain them end to end, with automated tests and static analysis in CI. Contributions and feedback are welcome.

### [Insights](https://github.com/loki495/insights)

[![CI](https://github.com/loki495/insights/actions/workflows/ci.yml/badge.svg)](https://github.com/loki495/insights/actions/workflows/ci.yml) [![codecov](https://codecov.io/gh/loki495/insights/graph/badge.svg)](https://codecov.io/gh/loki495/insights) [![License: AGPL v3 (or later)](https://img.shields.io/badge/license-AGPL--3.0--or--later-blue.svg)](https://github.com/loki495/insights/blob/main/LICENSE)

— Laravel · Livewire Volt · Plaid · v0.2.0 · [Demo](https://insights-demo.ac495.net)

A self-hosted Laravel/Livewire personal-finance app that syncs bank and credit-card transactions through Plaid. Organize transactions with hierarchical categories and automatic categorization rules, match transfers between accounts, and explore finances through Chart.js reports.

CI runs application tests against SQLite and MySQL, exercises browser workflows, and builds and smoke-tests the production Docker image. PHPStan, Rector, Pint, and Peck provide additional quality checks.

Demo login: `test@example.com` / `password`

### [Dibs](https://github.com/loki495/dibs)

[![CI](https://github.com/loki495/dibs/actions/workflows/ci.yml/badge.svg)](https://github.com/loki495/dibs/actions/workflows/ci.yml) [![codecov](https://codecov.io/gh/loki495/dibs/graph/badge.svg)](https://codecov.io/gh/loki495/dibs) [![License: MIT](https://img.shields.io/badge/license-MIT-blue.svg)](https://github.com/loki495/dibs/blob/main/LICENSE)

— Laravel · Livewire 4 · MCP · alpha · [Demo](https://dibs-demo.ac495.net)

An alpha-stage, self-hosted Laravel/Livewire task tracker for people and coding agents. Organize projects and plans, create and label tasks, search with filters, and track work through completion. Agents connect through a host-local stdio MCP server to read, claim, and complete tasks using the same business actions as the web UI. Included skill instructions help a fresh agent session discover open work across projects and pick up the context it needs.

Local SQLite is the source of truth, with optional asynchronous mirroring to GitHub Issues and Projects. Task claims coordinate work between agents, while shared actions keep behavior consistent across the web and MCP interfaces. An automated test suite, PHPStan, Rector, and Pint run in CI.

Demo login: `demo@example.com` / `demo-password-please-change`

### [Sessioneer](https://github.com/loki495/sessioneer)

[![CI](https://github.com/loki495/sessioneer/actions/workflows/ci.yml/badge.svg)](https://github.com/loki495/sessioneer/actions/workflows/ci.yml) [![License: MIT](https://img.shields.io/badge/license-MIT-blue.svg)](https://github.com/loki495/sessioneer/blob/main/LICENSE)

— PHP · tmux · UNIX sockets · prerelease v0.2

A self-hosted, LAN-only PHP web UI for easily managing multiple coding-agent sessions from a phone or browser. Launch sessions, respond to blocked prompts, browse live transcripts, and stop sessions across Claude Code, Codex, and OpenCode, plus experimental Antigravity support.

The Dockerized web UI communicates over a UNIX socket with a host-native agent, which runs agents headless by default or in tmux, and connects to their headless servers. This keeps process management in the host’s environment. Isolated automated tests and browser checks run in CI.

### [Homie](https://github.com/loki495/homie)

[![CI](https://github.com/loki495/homie/actions/workflows/ci.yml/badge.svg)](https://github.com/loki495/homie/actions/workflows/ci.yml) [![codecov](https://codecov.io/gh/loki495/homie/graph/badge.svg)](https://codecov.io/gh/loki495/homie) [![License: MIT](https://img.shields.io/badge/license-MIT-blue.svg)](https://github.com/loki495/homie/blob/main/LICENSE)

— Laravel 13 · Livewire 4 · Flux · v0.2.0 · [Demo](https://homie-demo.ac495.net)

A self-hosted Laravel/Livewire dashboard for organizing home-lab services into configurable cards. Combine service links, shell-command output, and live API data from services such as Sonarr, Radarr, and NZBGet. Discover Docker services on configured LAN machines through the Docker API or SSH.

Configuration can contain API tokens and SSH keys, so every deployment—including the demo—requires a login. Automated PHP tests and a containerized browser suite run in CI.

Demo login: `demo@example.test` / `homie-demo`

**Also:** [dotfiles](https://github.com/loki495/dotfiles)

[![CI](https://github.com/loki495/dotfiles/actions/workflows/ci.yml/badge.svg)](https://github.com/loki495/dotfiles/actions/workflows/ci.yml) [![License: MIT](https://img.shields.io/badge/license-MIT-blue.svg)](https://github.com/loki495/dotfiles/blob/main/LICENSE)

My Arch Linux, Neovim and PHP dev-tooling config plus AI skills and commands, installed as symlinks. CI runs the real installer in a container, asserts every symlink, and checks Neovim treesitter highlighting in a live tmux session.

I use coding agents as implementation and review tools. I remain responsible for architecture, validation, tests, security decisions, and maintenance.

## Open-source contributions

- **Merged into [PeckPHP](https://github.com/peckphp/peck/pull/28)** — added full line and column reporting for misspellings, after a maintainer review cycle with Nuno Maduro.
- **Merged into SerenityOS** — added a [Game of Life app](https://github.com/SerenityOS/serenity/pull/6720) to the bundled games and [always-on-top window support](https://github.com/SerenityOS/serenity/pull/8519).

## Experience snapshot

15+ years of continuous hands-on PHP development and systems administration, primarily as the principal developer for one small-business owner across several business ventures:

- **2020-present:** Laravel/Livewire applications, e-commerce automation, reservations, CRM, integrations, and production infrastructure
- **2014-2020:** Custom PHP, WordPress, hosting, migrations, and systems administration for 20-30 local-business websites
- **2010-2014:** E-commerce and dropshipping systems, distributor imports, payment gateways, and 20,000+ product catalogs

## Contact

- [GitHub profile](https://github.com/loki495)
- [LinkedIn](https://www.linkedin.com/in/andres-crucitti)
- andres@ac495.net
