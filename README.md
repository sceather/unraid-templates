# Unraid Templates

## Dockhand

A powerful, intuitive Docker platform. Free for homelabs, ready for enterprise. SQLite by default, runs on a Raspberry Pi, zero telemetry, free forever. Self-host everything without the complexity.

### Features
* Container Management: Start, stop, restart, and monitor containers in real-time
* Compose Stacks: Visual editor for Docker Compose deployments
* Git Integration: Deploy stacks from Git repositories with webhooks and auto-sync
* Multi-Environment: Manage local and remote Docker hosts
* Terminal & Logs: Interactive shell access and real-time log streaming
* File Browser: Browse, upload, and download files from containers
* Authentication: SSO via OIDC, local users, and optional RBAC (Enterprise)

### Tech Stack
- Base: own OS layer built from scratch using Wolfi packages via apko. Every package is explicitly declared in the Dockerfile.
- Frontend: SvelteKit 2, Svelte 5, shadcn-svelte, TailwindCSS
- Backend: Bun runtime with SvelteKit API routes
- Database: SQLite or PostgreSQL via Drizzle ORM
- Docker: direct docker API calls.


### Links  
- Website: https://dockhand.pro  
- Documentation: https://dockhand.pro/manual  
- Project: https://github.com/Finsys/dockhand

----
