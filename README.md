I'm a senior full-stack engineer and hands-on technical lead with 11 years in software, building the software between a scientist's screen and the machine doing the work. Since 2021 I've worked on the laboratory platform of DNA Script, the biotech company behind the Syntax benchtop DNA synthesizer — the React/NestJS web applications scientists use, and the C++ and Electron software that drives the instrument hardware.

What I build:
- Instrument software: built the Electron and Next.js replacement for the Syntax Qt/QML operator interface — run scheduling, reagent and consumable workflows, run reports, maintenance and diagnostics — with the C++ synthesis and maintenance workflows underneath it connected over MQTT and Protocol Buffers.
- Web platform: gene-design, plate-layout and laboratory workflow interfaces in React, TypeScript and Tailwind CSS with NestJS and tRPC services behind them, tested with Vitest, and gene design moved off the request path onto an asynchronous pipeline.
- Authentication and security: built the platform's authentication — cookie-based sessions, multi-factor authentication, brute-force protection and Redis-backed session caching over PostgreSQL — and am now specifying its extension to the instruments.
- Laboratory automation: extracted the Hamilton liquid-handler controller into its own Rust and Tauri desktop application, replacing its Python backend, connected to the platform through an EMQX broker.

As technical lead I set the authentication and Hamilton controller architecture, review the team's pull requests, and translate 21 CFR Part 11 requirements into specifications for instrument authentication, access control and audit trails.

I work from written specifications with acceptance criteria that development and QA both build and verify against, and investigate failures across the software-hardware boundary with the instrument QA team.

Core technologies: TypeScript, Python, React, Node.js, NestJS, tRPC, PostgreSQL, Redis, Vitest, C++, Electron, MQTT, Protocol Buffers, Rust, and Tauri.

I like problems where software meets physical equipment — where a bug isn't just a wrong API response, but a machine doing the wrong thing.

Open to senior full-stack, backend and hands-on technical-lead roles, particularly in laboratory automation, regulated environments, and software connected to physical systems.

[LinkedIn](https://linkedin.com/in/alex-miagotin)

---

### Stack

**Core**

![C++](https://img.shields.io/badge/C%2B%2B-1a1b2e?style=flat-square&logo=cplusplus&logoColor=bb9af7)
![Rust](https://img.shields.io/badge/Rust-1a1b2e?style=flat-square&logo=rust&logoColor=e0af68)
![TypeScript](https://img.shields.io/badge/TypeScript-1a1b2e?style=flat-square&logo=typescript&logoColor=7aa2f7)
![Python](https://img.shields.io/badge/Python-1a1b2e?style=flat-square&logo=python&logoColor=e0af68)
![Node.js](https://img.shields.io/badge/Node.js-1a1b2e?style=flat-square&logo=nodedotjs&logoColor=9ece6a)
![NestJS](https://img.shields.io/badge/NestJS-1a1b2e?style=flat-square&logo=nestjs&logoColor=f7768e)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-1a1b2e?style=flat-square&logo=postgresql&logoColor=7dcfff)
![Drizzle](https://img.shields.io/badge/Drizzle%20ORM-1a1b2e?style=flat-square&logo=databricks&logoColor=c0caf5)

**Infra & Messaging**

![Redis](https://img.shields.io/badge/Redis-1a1b2e?style=flat-square&logo=redis&logoColor=f7768e)
![Docker](https://img.shields.io/badge/Docker-1a1b2e?style=flat-square&logo=docker&logoColor=7aa2f7)
![MQTT](https://img.shields.io/badge/MQTT-1a1b2e?style=flat-square&logo=eclipse&logoColor=bb9af7)
![Protobuf](https://img.shields.io/badge/Protobuf-1a1b2e?style=flat-square&logo=google&logoColor=7dcfff)
![Bull Queue](https://img.shields.io/badge/Bull%20Queue-1a1b2e?style=flat-square&logo=npm&logoColor=9ece6a)

**Desktop & Frontend**

![Tauri](https://img.shields.io/badge/Tauri-1a1b2e?style=flat-square&logo=tauri&logoColor=e0af68)
![Electron](https://img.shields.io/badge/Electron-1a1b2e?style=flat-square&logo=electron&logoColor=7dcfff)
![React](https://img.shields.io/badge/React-1a1b2e?style=flat-square&logo=react&logoColor=7dcfff)
![Tailwind CSS](https://img.shields.io/badge/Tailwind%20CSS-1a1b2e?style=flat-square&logo=tailwindcss&logoColor=7dcfff)
![Next.js](https://img.shields.io/badge/Next.js-1a1b2e?style=flat-square&logo=nextdotjs&logoColor=c0caf5)
![tRPC](https://img.shields.io/badge/tRPC-1a1b2e?style=flat-square&logo=trpc&logoColor=7aa2f7)
