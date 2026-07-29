<div align="center">

# Hi, I'm Chan Nyein Tun 👋

**I build for the web, the terminal, and the chain — mostly in TypeScript and Go.**

<p>
  <a href="https://www.linkedin.com/in/channyeintun/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge" alt="LinkedIn" /></a>
  <a href="https://channyeintun.gitbook.io/"><img src="https://img.shields.io/badge/GitBook-3884FF?style=for-the-badge&logo=gitbook&logoColor=white" alt="GitBook" /></a>
</p>

</div>

- 🧑‍💻 Six years of shipping product frontends (React / Next.js) and backends (Node, Go, Java)
- ⛓️ Built Web3 features with Fireblocks WaaS, Ethers.js, and smart-contract integrations
- 🤖 All-in on LLM-assisted engineering — building my own coding agent to understand the loop end to end

---

## 🛠️ What I'm building

### <img src="https://raw.githubusercontent.com/channyeintun/next-editor/main/public/logo.svg" width="26" align="top" alt="" /> Next Editor

**[nexteditor.dev](https://nexteditor.dev)** · **[source](https://github.com/channyeintun/next-editor)** · TypeScript

<a href="https://nexteditor.dev/learn/how-next-editor-works-state-not-pixels"><img src="assets/nexteditor.webp" width="240" alt="How Next Editor Works: State, Not Pixels — watch the lesson" /></a>

A browser-based recorder and replay engine for real, multi-file coding lessons. It captures the whole workspace — editor changes, live preview, terminal, HTTP calls, slides, captions, audio, even the instructor camera — and replays everything from a single timeline. Recordings stream as `.ne` files that start playing before they finish downloading, and Yjs-powered live rooms with voice chat make lessons collaborative. Built with Monaco, WebContainers, rrweb, and Cloudflare Workers.

🎬 Its **Studio** is something that doesn't exist anywhere else yet: an AI lesson-production pipeline inside the editor. A director compiles authored scripts into deterministic performances — typing the code in the real editor, drag-highlighting exactly what the narration explains, running it live — with in-browser TTS narration linted by an editorial critic. Every render must pass mechanical QA and a two-render repeatability check before a human reviews and publishes it.

### 🌊 Nami

**[github.com/channyeintun/nami](https://github.com/channyeintun/nami)** · Go

An agentic coding CLI powered by LLMs — think, plan, and execute code changes without leaving the terminal. A Go engine drives the agent loop, tool execution, and permission gating; a custom TUI (**Silvery**) streams the session; and plans, task lists, and walkthroughs persist as first-class, reviewable artifacts. Works with Anthropic, OpenAI, Google, DeepSeek, Groq, Mistral, Ollama, and GitHub Copilot.

---

## 🤖 Agentic coding

Most of my work now starts as a prompt, a plan, and a review. The agents I actually keep open:

<p>
  <img src="https://img.shields.io/badge/Claude%20Code-D97757?style=flat-square&logo=claude&logoColor=white" alt="Claude Code" />
  <img src="https://img.shields.io/badge/Codex-000000?style=flat-square&logo=data:image/svg%2Bxml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCI%2BPHBhdGggZmlsbD0iI2ZmZiIgZD0iTTIyLjI4IDkuODJhNS45OCA1Ljk4IDAgMCAwLS41MTU3LTQuOTEgNi4wNSA2LjA1IDAgMCAwLTYuNTEtMi45QTYuMDcgNi4wNyAwIDAgMCA0Ljk4IDQuMThhNS45OCA1Ljk4IDAgMCAwLTQgMi45IDYuMDUgNi4wNSAwIDAgMCAuNzQyNyA3LjEgNS45OCA1Ljk4IDAgMCAwIC41MTEgNC45MSA2LjA1IDYuMDUgMCAwIDAgNi41MSAyLjlBNS45OCA1Ljk4IDAgMCAwIDEzLjI2IDI0YTYuMDYgNi4wNiAwIDAgMCA1Ljc3LTQuMjEgNS45OSA1Ljk5IDAgMCAwIDQtMi45IDYuMDYgNi4wNiAwIDAgMC0uNzQ3NS03LjA3em0tOS4wMiAxMi42MWE0LjQ4IDQuNDggMCAwIDEtMi44OC0xLjA0bC4xNDE5LS4wODA0IDQuNzgtMi43NmEuNzk0OC43OSAwIDAgMCAuMzkyNy0uNjgxM3YtNi43NGwyLjAyIDEuMTdhLjcxLjA3IDAgMCAxIC4zOC4wNXY1LjU4YTQuNSA0LjUgMCAwIDEtNC40OSA0LjQ5em0tOS42Ni00LjEzYTQuNDcgNC40NyAwIDAgMS0uNTM0Ni0zLjAxbC4xNDIuMDkgNC43OCAyLjc2YS43NzEyLjc3IDAgMCAwIC43ODA2IDBsNS44NC0zLjM3djIuMzNhLjgwNC4wOCAwIDAgMS0uMzMyLjA2TDkuNzQgMTkuOTVhNC41IDQuNSAwIDAgMS02LjE0LTEuNjV6TTIuMzQgNy45YTQuNDkgNC40OSAwIDAgMSAyLjM3LTEuOTdWMTEuNmEuNzY2NC43NyAwIDAgMCAuMzg3OS42OGw1LjgxIDMuMzUtMi4wMiAxLjE3YS43NTcuMDggMCAwIDEtLjA3MSAwbC00LjgzLTIuNzlBNC41IDQuNSAwIDAgMSAyLjM0IDcuODd6bTE2LjYgMy44NkwxMy4xIDguMzYgMTUuMTIgNy4yYS43NTcuMDggMCAwIDEgLjA3MSAwbDQuODMgMi43OWE0LjQ5IDQuNDkgMCAwIDEtLjY3NjUgOC4xdi01LjY4YS43OS43OSAwIDAgMC0uNDA3LS42Njd6bTIuMDEtMy4wMmwtLjE0Mi0uMDg1Mi00Ljc3LTIuNzhhLjc3NTkuNzggMCAwIDAtLjc4NTQgMEw5LjQxIDkuMjNWNi45YS42NjIuMDcgMCAwIDEgLjAyODQtLjA2MTVsNC44My0yLjc5YTQuNSA0LjUgMCAwIDEgNi42OCA0LjY2ek04LjMxIDEyLjg2bC0yLjAyLTEuMTZhLjgwNC4wOCAwIDAgMS0uMDM4LS4wNTY3VjYuMDdhNC41IDQuNSAwIDAgMSA3LjM4LTMuNDVsLS4xNDIuMDhMOC43IDUuNDZhLjc5NDguNzkgMCAwIDAtLjM5MjcuNjh6bTEuMS0yLjM3bDIuNi0xLjUgMi42MSAxLjV2M2wtMi42IDEuNS0yLjYxLTEuNVoiLz48L3N2Zz4%3D" alt="Codex" />
  <img src="https://img.shields.io/badge/GitHub%20Copilot-000000?style=flat-square&logo=githubcopilot&logoColor=white" alt="GitHub Copilot" />
  <img src="https://img.shields.io/badge/Antigravity-3186FF?style=flat-square&logo=data:image/svg%2Bxml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjEzIDE0LjUgODUgODUiPjxwYXRoIGZpbGw9IiNmZmYiIGQ9Ik04OS43IDkzLjY5Qzk0LjM3IDk3LjE5IDEwMS4zNyA5NC44NiA5NC45NSA4OC40NEM3NS43IDY5Ljc4IDc5Ljc4IDE4LjQ1IDU1Ljg3IDE4LjQ1QzMxLjk1IDE4LjQ1IDM2LjAzIDY5Ljc4IDE2Ljc4IDg4LjQ0QzkuNzggOTUuNDQgMTcuMzcgOTcuMTkgMjIuMDMgOTMuNjlDNDAuMTIgODEuNDQgMzguOTUgNTkuODYgNTUuODcgNTkuODZDNzIuNzggNTkuODYgNzEuNjIgODEuNDQgODkuNyA5My42OVoiLz48L3N2Zz4%3D" alt="Antigravity" />
  <img src="https://img.shields.io/badge/OpenCode-000000?style=flat-square&logo=opencode&logoColor=white" alt="OpenCode" />
</p>

---

## 🧰 Toolbox

**Frontend**

<p>
  <img src="https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB" alt="React" />
  <img src="https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white" alt="Next.js" />
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" alt="TypeScript" />
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=000000" alt="JavaScript" />
  <img src="https://img.shields.io/badge/React%20Native-20232A?style=flat-square&logo=react&logoColor=61DAFB" alt="React Native" />
  <img src="https://img.shields.io/badge/XState-2C3E50?style=flat-square&logo=xstate&logoColor=white" alt="XState" />
  <img src="https://img.shields.io/badge/Redux-764ABC?style=flat-square&logo=redux&logoColor=white" alt="Redux" />
  <img src="https://img.shields.io/badge/TanStack%20Query-FF4154?style=flat-square&logo=reactquery&logoColor=white" alt="TanStack Query" />
  <img src="https://img.shields.io/badge/Tailwind%20CSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white" alt="Tailwind CSS" />
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white" alt="HTML5" />
  <img src="https://img.shields.io/badge/CSS-663399?style=flat-square&logo=css&logoColor=white" alt="CSS" />
</p>

**Backend**

<p>
  <img src="https://img.shields.io/badge/NestJS-E0234E?style=flat-square&logo=nestjs&logoColor=white" alt="NestJS" />
  <img src="https://img.shields.io/badge/Express-000000?style=flat-square&logo=express&logoColor=white" alt="Express" />
  <img src="https://img.shields.io/badge/Strapi-4945FF?style=flat-square&logo=strapi&logoColor=white" alt="Strapi" />
  <img src="https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white" alt="Go" />
  <img src="https://img.shields.io/badge/Fiber-00ACD7?style=flat-square&logo=go&logoColor=white" alt="Fiber" />
  <img src="https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white" alt="Java" />
  <img src="https://img.shields.io/badge/Spring-6DB33F?style=flat-square&logo=spring&logoColor=white" alt="Spring" />
  <img src="https://img.shields.io/badge/REST%20APIs-6E7781?style=flat-square" alt="REST APIs" />
  <img src="https://img.shields.io/badge/GraphQL-E10098?style=flat-square&logo=graphql&logoColor=white" alt="GraphQL" />
</p>

**Delivery**

<p>
  <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" alt="Docker" />
  <img src="https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white" alt="GitHub Actions" />
  <img src="https://img.shields.io/badge/Jest-C21325?style=flat-square&logo=jest&logoColor=white" alt="Jest" />
  <img src="https://img.shields.io/badge/Vitest-6E9F18?style=flat-square&logo=vitest&logoColor=white" alt="Vitest" />
  <img src="https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white" alt="Git" />
  <img src="https://img.shields.io/badge/Figma-F24E1E?style=flat-square&logo=figma&logoColor=white" alt="Figma" />
  <img src="https://img.shields.io/badge/VS%20Code-007ACC?style=flat-square" alt="VS Code" />
</p>

**Web3 · AI**

<p>
  <img src="https://img.shields.io/badge/Fireblocks%20WaaS-001E3C?style=flat-square" alt="Fireblocks WaaS" />
  <img src="https://img.shields.io/badge/Ethers.js-2535A0?style=flat-square&logo=ethereum&logoColor=white" alt="Ethers.js" />
  <img src="https://img.shields.io/badge/Smart%20Contracts-363636?style=flat-square&logo=solidity&logoColor=white" alt="Smart Contracts" />
  <img src="https://img.shields.io/badge/LLM--assisted%20Engineering-D97757?style=flat-square&logo=anthropic&logoColor=white" alt="LLM-assisted Engineering" />
</p>

---

<div align="center">

If **Next Editor** or **Nami** looks useful to you, a ⭐ goes a long way.

</div>
