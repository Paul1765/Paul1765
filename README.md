# Hi, I'm Paul Greenwood

I research security infrastructure for AI agents. Based in the UK.

Currently working on **[MPP — Model Package Protocol](https://mpp-protocol.io)**, an open standard for packaging, signing, and sandboxing AI tools as portable `.mpp` artifacts. Think of it as a secure app store for AI agent tools, cryptographic signing, WASM isolation, and zero-trust permissions by default.

---

## What I'm building

**[Quantum2x / mpp](https://github.com/Quantum2x/mpp)** — The MPP runtime, CLI, registry, and SDK. Rust-based. Apache 2.0.

Core pieces:
- `mpp-runtime-core` — Gatekeeper verification, Ed25519 signing, privacy filters
- `mpp-wasm-sandbox` — Wasmtime execution with capability-based access control
- `mpp-permissions` — Manifest declarations to WASI resource tokens
- `mpp-kv-store` — Per-package persistent SQLite state
- `mpp-registry-api` — Axum + PostgreSQL package registry with federation

---

## Stack

Rust · WebAssembly · WASI · Wasmtime · Axum · SQLite · PostgreSQL · Ed25519

---

## Get in touch

- **Org:** [quantum2x.com](https://quantum2x.com)
- **Protocol:** [mpp-protocol.io](https://mpp-protocol.io)
- **Email:** hello@quantum2x.com

<!--
**Paul1765/Paul1765** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
