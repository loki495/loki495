# Andres Crucitti

**Senior PHP / Laravel Developer** — Los Angeles metro (PT), open to remote roles.

15+ years building, integrating, deploying, and supporting production e-commerce and business applications in PHP — from initial schema design through deployment, on-call troubleshooting, and years of ongoing ownership. Strongest in Laravel, Livewire, REST integrations, MySQL, automated testing, and the Linux and Docker infrastructure underneath.

The three projects below are mine end to end: **750+ automated tests** between them, CI running PHPStan, Rector, Pint, Pest and real-browser tests on every push, and an open-source licence on each.

## Current focus

- PHP 8.x, Laravel, Livewire/Volt, Alpine.js, and Tailwind CSS
- REST APIs, third-party integrations, queues, and automation
- MySQL schema design, query optimization, SQLite, and Redis
- Automated testing with Pest, PHPUnit, and Playwright
- PHPStan, Rector, CI/CD, and GitHub Actions
- Linux, Docker Compose, AWS, Nginx, Apache, and Cloudflare

## Selected projects

### [Insights](https://github.com/loki495/insights) — Laravel · Livewire Volt · Plaid · AGPL-3.0

A personal-finance application that syncs bank and credit transactions through **Plaid**, with hierarchical user categories, rule-based auto-categorization, transfer matching, and Chart.js reporting. **600 tests** (Pest + Playwright) on a CI pipeline that runs the suite against **both SQLite and a live MySQL 8 service**, then builds the production Docker image, boots it, and smoke-tests it. PHPStan, Rector, Pint and Peck gate every push.

### [Sessioneer](https://github.com/loki495/sessioneer) — PHP · tmux · UNIX sockets · MIT

~24k lines of PHP behind a **deliberate two-runtime architecture**: the Dockerized web UI holds no tmux or `/proc` access at all and speaks a one-request/one-response JSON protocol over a UNIX socket to a host-native, systemd-socket-activated agent — because a tmux server spawned from inside a container is born in the wrong filesystem namespace. Drives Claude Code, Codex, OpenCode and Antigravity sessions from a phone: live transcripts, blocked-prompt answering, history search, session lifecycle. Backed by a dependency-free, self-isolating test suite (35 files, ~12k lines) that never touches the real tmux server.

### [Homie](https://github.com/loki495/homie) — Laravel 13 · Livewire 4 · Flux · MIT

A home-lab dashboard that auto-discovers Docker services over the API or SSH — including host-network containers, which report no ports and need an `inspect` fallback to find at all — and pulls live stats from self-hosted service APIs. Built to be genuinely distributable: no hostname, service, or credential exists anywhere in the code. Three-job CI on the declared PHP floor rather than the dev container's newer version, plus a containerized real-browser suite.

All three were built with AI-assisted workflows and full review — the test suites and CI above are why I trust the output.

## Open-source contributions

- **Merged into [SerenityOS](https://github.com/SerenityOS/serenity/pull/6720)** — added a "Game of Life" app to the system's bundled games.
- **Merged into [PeckPHP](https://github.com/peckphp/peck/pull/28)** — added full line and column reporting for misspellings, after a maintainer review cycle with Nuno Maduro.

## What I am looking for

Permanent full-time or part-time PHP/Laravel roles, especially remote positions where I can build and support real products as part of an engineering team. Also open to backend, platform, and Linux-oriented roles that benefit from a developer with production infrastructure experience.

## Contact

- [LinkedIn](https://www.linkedin.com/in/andres-crucitti-32ab2313)
- andres@ac495.net
