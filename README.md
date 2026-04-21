# awesome-copilot

> A curated list of awesome GitHub Copilot instructions, agents, and plugins.

[![All Contributors](https://img.shields.io/github/all-contributors/awesome-copilot/awesome-copilot?color=ee8449&style=flat-square)](CONTRIBUTORS.md)

Fork of [github/awesome-copilot](https://github.com/github/awesome-copilot) with additional community contributions.

> **Personal fork notes:** I'm using this to experiment with custom Copilot instructions for TypeScript/React projects. PRs here may not be kept in sync with upstream.

## Contents

- [Copilot Instructions](#copilot-instructions)
- [Agentic Workflows](#agentic-workflows)
- [Plugins & Extensions](#plugins--extensions)
- [Contributing](#contributing)

---

## Copilot Instructions

Custom instruction files (`.github/copilot-instructions.md`) that tailor GitHub Copilot behavior for specific project types, languages, or workflows.

| Name | Description | Language/Framework |
|------|-------------|------------------|
| [General Instructions](.github/copilot-instructions.md) | Default instructions for this repository | General |
| [TypeScript/React Instructions](instructions/typescript-react.md) | Instructions tuned for React + TypeScript projects (my primary use case) | TypeScript, React |
| [Node.js/Express Instructions](instructions/nodejs-express.md) | Instructions for backend Node.js + Express APIs | Node.js, Express |
| [Python/FastAPI Instructions](instructions/python-fastapi.md) | Instructions for Python + FastAPI projects (experimenting with this stack) | Python, FastAPI |
| [Go Instructions](instructions/golang.md) | Instructions for Go projects — added this since I've been picking up Go lately | Go |
| [Rust Instructions](instructions/rust.md) | Instructions for Rust projects — starting to learn Rust, very WIP | Rust |
| [SQL/PostgreSQL Instructions](instructions/sql-postgres.md) | Instructions for PostgreSQL queries and schema design — added for a side project | SQL, PostgreSQL |
| [Docker Instructions](instructions/docker.md) | Instructions for Dockerfile and docker-compose files — added while containerizing side projects | Docker |
| [Vitest Instructions](instructions/vitest.md) | Instructions for writing tests with Vitest — added since I switched from Jest | TypeScript, Vitest |
| [Tailwind CSS Instructions](instructions/tailwind.md) | Instructions for Tailwind CSS styling — added since most of my React projects use Tailwind now | TypeScript, Tailwind CSS |
| [Next.js Instructions](instructions/nextjs.md) | Instructions for Next.js (App Router) projects — added as I migrate my React apps to Next.js | TypeScript, Next.js |
| [Prisma Instructions](instructions/prisma.md) | Instructions for Prisma ORM — added for my Next.js + PostgreSQL projects | TypeScript, Prisma |
| [Astro Instructions](instructions/astro.md) | Instructions for Astro projects — experimenting with this for static/content sites | TypeScript, Astro |
| [GitHub Actions Instructions](instructions/github-actions.md) | Instructions for writing GitHub Actions workflows — added to help with CI/CD setup | YAML, GitHub Actions |

---

## Agentic Workflows

Agent definition files (`.github/age
