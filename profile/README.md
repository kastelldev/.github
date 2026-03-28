<p align="center">
  <img src="https://raw.githubusercontent.com/kastelldev/kastell/main/assets/logo.png" width="80" height="80" alt="Kastell Logo" />
</p>

<h1 align="center">Kastell</h1>

<p align="center">
  <strong>Your infrastructure, fortified.</strong>
</p>

<p align="center">
  Autonomous security and maintenance layer for self-hosted infrastructure.<br/>
  Deploy, secure, maintain, and monitor — one tool, every server task.
</p>

<p align="center">
  <a href="https://www.npmjs.com/package/kastell"><img src="https://img.shields.io/npm/v/kastell?color=00d4ff&labelColor=0d1117&label=version" alt="npm version" /></a>
  <a href="https://www.npmjs.com/package/kastell"><img src="https://img.shields.io/npm/dt/kastell?color=1e6fff&labelColor=0d1117&label=downloads" alt="npm downloads" /></a>
  <a href="https://github.com/kastelldev/kastell/blob/main/LICENSE"><img src="https://img.shields.io/badge/license-Apache%202.0-blue?color=1e6fff&labelColor=0d1117" alt="license" /></a>
  <a href="https://github.com/kastelldev/kastell"><img src="https://img.shields.io/github/stars/kastelldev/kastell?color=00d4ff&labelColor=0d1117&style=flat" alt="GitHub stars" /></a>
  <a href="https://socket.dev/npm/package/kastell"><img src="https://socket.dev/api/badge/npm/package/kastell" alt="Socket Security" /></a>
  <img src="https://img.shields.io/badge/node-%3E%3D20-00d4ff?labelColor=0d1117" alt="Node.js" />
  <a href="https://github.com/kastelldev/kastell/actions/workflows/ci.yml"><img src="https://github.com/kastelldev/kastell/actions/workflows/ci.yml/badge.svg" alt="Tests" /></a>
  <a href="https://app.codecov.io/gh/kastelldev/kastell"><img src="https://img.shields.io/codecov/c/github/kastelldev/kastell?color=00d4ff&labelColor=0d1117" alt="Coverage" /></a>
  <img src="https://komarev.com/ghpvc/?username=kastelldev&color=00d4ff&style=flat&label=profile+views" alt="Profile views" />
</p>

<br/>

<img src="https://raw.githubusercontent.com/kastelldev/kastell/main/assets/demo.gif" width="100%" alt="Kastell Demo" />

<br/>

## What is Kastell?

Kastell is an open-source CLI tool that autonomously manages self-hosted servers. Stop babysitting your infrastructure — Kastell handles security hardening, maintenance, backups, and monitoring so you don't have to.

```bash
npx kastell
```

<br/>

## Features

- 🔒 **Security Audit** — 448+ checks across 31 categories. CIS, PCI-DSS, HIPAA compliance mapping.
- 🚀 **Deploy** — Provision servers on Hetzner, DigitalOcean, Vultr, Linode. Coolify, Dokploy, or bare VPS.
- 🔧 **Maintain** — Full maintenance cycles with pre-update snapshots and health checks.
- 💾 **Backup** — One-command backup & restore with manifest tracking.
- 🛡️ **Lock** — One-command production hardening: SSH, fail2ban, UFW, sysctl.
- 🤖 **MCP Server** — 14 tools for AI-powered server management via Claude Code, Cursor, Windsurf.

<br/>

## Stats

<p align="center">
  <img src="https://img.shields.io/badge/tests-5506%20passing-00d4ff?labelColor=0d1117" alt="Tests" />
  <img src="https://img.shields.io/badge/checks-457%2B%20security-1e6fff?labelColor=0d1117" alt="Checks" />
  <img src="https://img.shields.io/badge/categories-30-00d4ff?labelColor=0d1117" alt="Categories" />
  <img src="https://img.shields.io/badge/MCP%20tools-14-1e6fff?labelColor=0d1117" alt="MCP Tools" />
</p>

<br/>

## Supported Providers & Platforms

<p align="center">
  <img src="https://img.shields.io/badge/Hetzner-stable-00d4ff?labelColor=0d1117" alt="Hetzner" />
  <img src="https://img.shields.io/badge/DigitalOcean-stable-00d4ff?labelColor=0d1117" alt="DigitalOcean" />
  <img src="https://img.shields.io/badge/Vultr-stable-00d4ff?labelColor=0d1117" alt="Vultr" />
  <img src="https://img.shields.io/badge/Linode-beta-1e6fff?labelColor=0d1117" alt="Linode" />
  <img src="https://img.shields.io/badge/Coolify-supported-1e6fff?labelColor=0d1117" alt="Coolify" />
  <img src="https://img.shields.io/badge/Dokploy-supported-1e6fff?labelColor=0d1117" alt="Dokploy" />
  <img src="https://img.shields.io/badge/Bare%20VPS-supported-1e6fff?labelColor=0d1117" alt="Bare VPS" />
</p>

<br/>

## Quick Start

```bash
# Run instantly
npx kastell

# Or install globally
npm install -g kastell
```

<br/>

## MCP Integration

```json
{
  "mcpServers": {
    "kastell": {
      "command": "npx",
      "args": ["-y", "-p", "kastell", "kastell-mcp"]
    }
  }
}
```

<br/>

<p align="center">
  <a href="https://kastell.dev">kastell.dev</a> · 
  <a href="https://www.npmjs.com/package/kastell">npm</a> · 
  <a href="https://github.com/kastelldev/kastell">GitHub</a>
</p>

<p align="center">
  <sub>Built by <a href="https://github.com/omrfc">@omrfc</a> · Apache 2.0</sub>
</p>
