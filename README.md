# Massive Hosting

**Modern Hosting, From Scratch**

A research hosting platform exploring how modern mass hosting should work. Multi-tenant isolation, automated provisioning, and a complete API — with a Terraform provider on top.

This repository contains the source code for [massive-hosting.com](https://massive-hosting.com), the landing page and documentation hub for the platform.

## Platform Features

- **Web Applications** — PHP, Node.js, Python, Ruby, and static sites
- **Databases** — MySQL and Valkey (Redis-compatible)
- **Object Storage** — S3-compatible
- **OCI Containers** — Run container images directly
- **Email** — JMAP and IMAP support
- **VPN** — WireGuard access to your infrastructure
- **Terraform Provider** — 21 resource types for infrastructure as code
- **CI/CD** — GitHub Actions and GitLab CI templates, push-to-deploy
- **Observability** — Centralized logging with Loki and Grafana dashboards
- **Tenant Isolation** — Chroot jails, per-tenant ULA IPv6, TOTP 2FA
- **MCP Server** — AI-assisted infrastructure management

## Tech Stack

- [Astro](https://astro.build) — Static site generator
- [Tailwind CSS](https://tailwindcss.com) — Styling
- [Cloudflare Pages](https://pages.cloudflare.com) — Hosting and deployment

## Development

```sh
npm install          # Install dependencies
npm run dev          # Start dev server at localhost:4321
npm run build        # Build for production to ./dist/
npm run preview      # Preview the production build locally
```

## Deployment

Pushes to `main` are automatically deployed to Cloudflare Pages via GitHub Actions.

## Links

- [Documentation](https://docs.massive-hosting.com)
- [Terraform Provider](https://registry.terraform.io/providers/massive-hosting/hosting)
- [GitHub Organization](https://github.com/Massive-Hosting)
