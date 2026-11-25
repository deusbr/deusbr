<div align="center">

# Emerson Almeida (`@deusbr`)

### Full Stack & Local AI Engineer · Model Context Protocol (MCP) Tooling · Brazil

[![Open to Work & Consulting](https://img.shields.io/badge/Status-Available_for_Consulting_%26_Collaborations-10b981?style=flat-square)](https://github.com/deusbr)
[![GitHub](https://img.shields.io/badge/GitHub-@deusbr-181717?style=flat-square&logo=github)](https://github.com/deusbr)
[![Focus](https://img.shields.io/badge/Focus-Local_AI_%C2%B7_MCP_%C2%B7_Full_Stack-2563eb?style=flat-square)](#-focus-areas)
[![License](https://img.shields.io/badge/Open_Source-MIT_Licensed-6366f1?style=flat-square)](#-flagship-open-source-suite)

*Designing zero-dependency developer tooling, privacy-first desktop AI systems, and cross-client **Model Context Protocol (MCP)** infrastructure.*

[Focus Areas](#-focus-areas) · [Flagship Suite](#-flagship-open-source-suite) · [Ecosystem Architecture](#-ecosystem-architecture) · [Engineering Standards](#-engineering-standards) · [Tech Stack](#-tech-stack) · [GitHub Analytics](#-github-analytics)

</div>

---

## Focus Areas

<table>
  <tr>
    <td width="33%" valign="top">
      <h3>MCP Tooling &amp; Infrastructure</h3>
      <p>Zero-dependency generators, drift-safe SHA-256 config installers, handshake diagnostics, and <code>stdio</code> JSON-RPC 2.0 servers compatible with <strong>Claude Desktop</strong>, <strong>Claude Code</strong>, <strong>Codex</strong>, <strong>Gemini CLI</strong>, <strong>Cursor</strong>, and <strong>OpenBot</strong>.</p>
    </td>
    <td width="33%" valign="top">
      <h3>Local &amp; Privacy-First AI</h3>
      <p>Offline-capable desktop inference with <code>llama.cpp</code> (CPU/Vulkan GGUF), local <code>Whisper</code> transcription, JSON Schema repair proxies for small models, SQLite memory, and Ed25519-signed releases.</p>
    </td>
    <td width="33%" valign="top">
      <h3>Full Stack, Porting &amp; Agentic Studios</h3>
      <p>End-to-end developer workbenches combining portable <code>SKILL.md</code> workflows, native MCP servers, local web UIs, and PC/Xbox-to-Android porting automation (<code>NDK</code>, <code>SDL2</code>, <code>Winlator</code>) in Node.js, TypeScript, and Python.</p>
    </td>
  </tr>
</table>

---

## Flagship Open-Source Suite

### AI Studios & Desktop Assistants

| Project | Summary | Core Stack | CI & Release |
| :--- | :--- | :--- | :--- |
| [**`port-forge`**](https://github.com/deusbr/port-forge#readme) | Zero-dependency cross-platform porting studio (CLI + MCP Server + Web UI + `SKILL.md`) for PC apps, Windows `.exe` (`Winlator/Box64/DXVK`) & Xbox 360 `.xex` (`XenonRecomp`) to Android | `Node.js >=18` · `MCP stdio` · `NDK/SDL2` · `Winlator` · `MIT` | [![CI](https://github.com/deusbr/port-forge/actions/workflows/ci.yml/badge.svg)](https://github.com/deusbr/port-forge/actions/workflows/ci.yml) [![Release](https://img.shields.io/github/v/release/deusbr/port-forge?color=2563eb&label=release)](https://github.com/deusbr/port-forge/releases) |
| [**`mcp-studio`**](https://github.com/deusbr/mcp-studio#readme) | Zero-dependency workbench (CLI + MCP Server + Local Web UI + `SKILL.md`) turning OpenAPI specs, local CLIs, and Windows desktop apps without native MCP support into tested MCP servers | `Node.js >=18` · `MCP stdio` · `OpenAPI` · `COM` · `MIT` | [![CI](https://github.com/deusbr/mcp-studio/actions/workflows/ci.yml/badge.svg)](https://github.com/deusbr/mcp-studio/actions/workflows/ci.yml) [![Release](https://img.shields.io/github/v/release/deusbr/mcp-studio?color=2563eb&label=release)](https://github.com/deusbr/mcp-studio/releases) |
| [**`ui-craft-studio`**](https://github.com/deusbr/ui-craft-studio#readme) | Zero-dependency Anti-AI-Slop UI/UX & Interactive App Design Studio MCP (Mobile + Desktop/PC): scans your codebase first, researches GitHub design skills, compiles `DESIGN.md` + clickable 4-state prototypes & runs deterministic WCAG AA audits | `Node.js >=18` · `MCP stdio` · `DESIGN.md` · `WCAG AA` · `MIT` | [![CI](https://github.com/deusbr/ui-craft-studio/actions/workflows/ci.yml/badge.svg)](https://github.com/deusbr/ui-craft-studio/actions/workflows/ci.yml) [![Release](https://img.shields.io/github/v/release/deusbr/ui-craft-studio?color=2563eb&label=release)](https://github.com/deusbr/ui-craft-studio/releases) |
| [**`meshforge-mcp`**](https://github.com/deusbr/meshforge-mcp#readme) | Zero-dependency, zero-API-key Text/Image-to-3D CLI, pure-code SDF/Marching-Tetrahedra & 2D-EDT GLB generator, Three.js inspector, and 7-tool `stdio` MCP server | `Node.js >=18` · `GLB/glTF` · `SDF` · `MCP stdio` · `MIT` | [![CI](https://github.com/deusbr/meshforge-mcp/actions/workflows/ci.yml/badge.svg)](https://github.com/deusbr/meshforge-mcp/actions/workflows/ci.yml) [![Release](https://img.shields.io/github/v/release/deusbr/meshforge-mcp?color=2563eb&label=release)](https://github.com/deusbr/meshforge-mcp/releases) |
| [**`lumina-a55-studio`**](https://github.com/deusbr/lumina-a55-studio#readme) | Native Android computational-photography camera crafted for Galaxy A55 (`CameraX` + `Camera2` + Multi-Frame YUV HDR+ burst + offline ML Kit/TFLite + GPU `OKLab` Capture One `AGSL` shaders) | `Kotlin` · `Jetpack Compose` · `CameraX` · `AGSL` · `MIT` | [![CI](https://github.com/deusbr/lumina-a55-studio/actions/workflows/ci.yml/badge.svg)](https://github.com/deusbr/lumina-a55-studio/actions/workflows/ci.yml) [![Release](https://img.shields.io/github/v/release/deusbr/lumina-a55-studio?color=2563eb&label=release)](https://github.com/deusbr/lumina-a55-studio/releases) |
| [**`ai-photo-studio`**](https://github.com/deusbr/ai-photo-studio#readme) | 8-agent Essence-Driven AI photo studio (`v4`: hybrid craft research, posing geometry, cinema/trailer & beauty presets, optical filters, editorial makeup, 5 prompt engines & Anti-AI QA) | `Node.js >=18` · `MCP stdio` · `SKILL.md` · `HTTP` · `MIT` | [![CI](https://github.com/deusbr/ai-photo-studio/actions/workflows/ci.yml/badge.svg)](https://github.com/deusbr/ai-photo-studio/actions/workflows/ci.yml) [![Release](https://img.shields.io/github/v/release/deusbr/ai-photo-studio?color=2563eb&label=release)](https://github.com/deusbr/ai-photo-studio/releases) |
| [**`lume`**](https://github.com/deusbr/lume#readme) | Open-source Windows desktop AI assistant with bidirectional MCP (`@modelcontextprotocol/client`), local `Whisper` CPU transcription, `llama.cpp` GGUF inference, SQLite memory & Ed25519 updates | `Electron` · `Node.js 24` · `MCP` · `SQLite` · `MIT` | [![CI](https://github.com/deusbr/lume/actions/workflows/ci.yml/badge.svg)](https://github.com/deusbr/lume/actions/workflows/ci.yml) [![Release](https://img.shields.io/github/v/release/deusbr/lume?color=2563eb&label=release)](https://github.com/deusbr/lume/releases) |

### MCP Infrastructure, Diagnostics & Token Optimization

| Project | Summary | Core Stack | CI & Release |
| :--- | :--- | :--- | :--- |
| [**`context-slim`**](https://github.com/deusbr/context-slim#readme) | Zero-dependency universal token-saving compressor (CLI + ultra-lean 3-tool `stdio` MCP + `SKILL.md`) with hybrid `repomix`/`rtk` support for code, JSON, logs, CSV & directories | `Node.js >=18` · `MCP stdio` · `SKILL.md` · `MIT` | [![CI](https://github.com/deusbr/context-slim/actions/workflows/ci.yml/badge.svg)](https://github.com/deusbr/context-slim/actions/workflows/ci.yml) [![Release](https://img.shields.io/github/v/release/deusbr/context-slim?color=2563eb&label=release)](https://github.com/deusbr/context-slim/releases) |
| [**`mcp-doctor`**](https://github.com/deusbr/mcp-doctor#readme) | Zero-dependency CLI, library, and portable `SKILL.md` auditing MCP configs across 7 clients (Claude Desktop, Claude Code, Cursor, Codex, Gemini CLI, Antigravity & VS Code) for broken paths, Windows wrappers, secret leaks, live handshakes & token bloat | `Node.js >=18` · `MCP stdio` · `SKILL.md` · `MIT` | [![CI](https://github.com/deusbr/mcp-doctor/actions/workflows/ci.yml/badge.svg)](https://github.com/deusbr/mcp-doctor/actions/workflows/ci.yml) [![Release](https://img.shields.io/github/v/release/deusbr/mcp-doctor?color=2563eb&label=release)](https://github.com/deusbr/mcp-doctor/releases) |
| [**`mcp-client-installer`**](https://github.com/deusbr/mcp-client-installer#readme) | Zero-dependency, SHA-256 drift-safe atomic MCP config installer and rollback library for JSON and TOML MCP clients | `Node.js >=18` · `JSON/TOML` · `SHA-256` · `MIT` | [![CI](https://github.com/deusbr/mcp-client-installer/actions/workflows/ci.yml/badge.svg)](https://github.com/deusbr/mcp-client-installer/actions/workflows/ci.yml) [![Release](https://img.shields.io/github/v/release/deusbr/mcp-client-installer?color=2563eb&label=release)](https://github.com/deusbr/mcp-client-installer/releases) |
| [**`local-tool-bench`**](https://github.com/deusbr/local-tool-bench#readme) | Zero-dependency tool-calling benchmark suite and JSON Schema repair micro-proxy (`<think>`/`<tool_call>` recovery, recursive coercion & `/stats`) for local GGUF (`llama.cpp`) and Ollama models | `Node.js >=18` · `HTTP Proxy` · `llama.cpp` · `Ollama` · `MIT` | [![CI](https://github.com/deusbr/local-tool-bench/actions/workflows/ci.yml/badge.svg)](https://github.com/deusbr/local-tool-bench/actions/workflows/ci.yml) [![Release](https://img.shields.io/github/v/release/deusbr/local-tool-bench?color=2563eb&label=release)](https://github.com/deusbr/local-tool-bench/releases) |
| [**`repo-release-guard`**](https://github.com/deusbr/repo-release-guard#readme) | Portable AI Skill (`SKILL.md`) and zero-dependency `stdio` MCP server for `git worktree` inspection, pre-release hygiene audits, secret scanning & SemVer tag readiness | `Node.js >=18` · `Git` · `MCP stdio` · `SKILL.md` · `MIT` | [![CI](https://github.com/deusbr/repo-release-guard/actions/workflows/ci.yml/badge.svg)](https://github.com/deusbr/repo-release-guard/actions/workflows/ci.yml) [![Release](https://img.shields.io/github/v/release/deusbr/repo-release-guard?color=2563eb&label=release)](https://github.com/deusbr/repo-release-guard/releases) |

---

## Ecosystem Architecture

```mermaid
flowchart LR
  Clients["AI Clients: Claude Desktop · Claude Code · Codex · Gemini CLI · Cursor · OpenBot"]
  PortForge["port-forge (PC / Xbox 360 → Android NDK/SDL2/Winlator)"]
  McpStudio["mcp-studio (OpenAPI / CLI / Windows COM → MCP)"]
  UiCraft["ui-craft-studio (Codebase-First Anti-Slop UI/UX + DESIGN.md)"]
  MeshForge["meshforge-mcp (Zero-Key SDF / EDT 3D GLB + MCP)"]
  LuminaA55["lumina-a55-studio (Galaxy A55 YUV Burst + AGSL Camera)"]
  PhotoStudio["ai-photo-studio v4 (Craft Research + 8-Agent Anti-AI QA)"]
  ContextSlim["context-slim (Token Compressor + 3-Tool MCP)"]
  Installer["mcp-client-installer (Atomic JSON/TOML + SHA-256)"]
  Doctor["mcp-doctor (Config, Handshake & Token Audit)"]
  Guard["repo-release-guard (Worktree & Release Hygiene)"]
  Lume["lume (Electron Desktop AI + Local Whisper & llama.cpp)"]
  Bench["local-tool-bench (GGUF Tool-Call Benchmark & Repair Proxy)"]

  PortForge -->|"Skill + MCP + Scaffolds"| Clients
  McpStudio -->|"generates & probes"| Clients
  UiCraft -->|"DESIGN.md + Interactive UI"| Clients
  MeshForge -->|"GLB / 3D Scene + MCP"| Clients
  LuminaA55 -->|"CameraX + AGSL Editorial Engine"| Clients
  PhotoStudio -->|"Skill + MCP stdio"| Clients
  ContextSlim -->|"compresses context"| Clients
  Installer -->|"writes & rolls back"| Clients
  Doctor -->|"audits & probes"| Clients
  Guard -->|"verifies releases"| Clients
  Lume -->|"connects to"| Clients
  Bench -->|"repairs tool JSON"| Lume
```

---

## Engineering Standards

- **Zero-Dependency Core Philosophy:** Core MCP servers, installers, diagnostics, and studios run on pure Node.js standard libraries (`node:fs`, `node:http`, `node:crypto`, `node:child_process`, `node:test`) to eliminate supply-chain bloat and startup overhead.
- **Cross-Platform CI Matrix:** Every flagship repository runs automated GitHub Actions verification across `ubuntu-latest`, `windows-latest`, and `macos-latest` on Node.js `18`, `20`, `22`, and `24`.
- **Safe Automation by Default:** Atomic file swaps with SHA-256 drift detection, `execFile` without shell interpolation (`shell: false`), strict secret hygiene checks prior to release, and portable `SKILL.md` specifications.

---

## Tech Stack

| Layer | Technologies |
| :--- | :--- |
| **Languages & Runtimes** | JavaScript (`Node.js 18–24`), TypeScript, Kotlin, Python |
| **AI & Agent Protocols** | Model Context Protocol (`stdio` JSON-RPC 2.0, `@modelcontextprotocol/client`), Agent Skills (`SKILL.md`), `llama.cpp` (GGUF), Ollama, `Whisper` |
| **Applications & Mobile** | Electron, React, Jetpack Compose (`CameraX` / `Camera2` / `AGSL`), Vite, FastAPI, SQLite, Supabase / PostgreSQL |
| **Porting & Native Targets** | Android NDK, CMake, SDL2, Vulkan / DXVK, Winlator / Box64, Capacitor, Buildozer |
| **Quality & Delivery** | `node:test`, JUnit + Gradle CI, GitHub Actions CI/CD, Playwright, SemVer Releases, MIT Licensing |

---

## GitHub Analytics

<div align="center">
  <img height="175" src="https://github-readme-stats.vercel.app/api?username=deusbr&show_icons=true&show=reviews&theme=github_dark&hide_border=true" alt="GitHub Stats for @deusbr" />
  <img height="175" src="https://github-readme-stats.vercel.app/api/top-langs/?username=deusbr&layout=compact&langs_count=6&theme=github_dark&hide_border=true" alt="Top Languages for @deusbr" />
</div>

---

<div align="center">
  <strong>Open to AI/MCP engineering collaborations, developer tooling work, and open-source contributions.</strong><br />
  <sub>Based in Brazil (UTC-3) · Reach out via <a href="https://github.com/deusbr">GitHub (@deusbr)</a> or repository issues &amp; discussions.</sub>
</div>
