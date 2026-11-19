# Antigravity Skills & Plugins Library

A curated collection of 160+ modular skills and plugins for Google Antigravity, Claude Code, Cursor, and AI coding agents.

---

## ⚡ Instant Install via `npx skills`

You can install any skill directly from this repository into any project or globally across your PC using the **`skills` CLI**:

### 1. Interactive Selection (Choose what you need)
```bash
npx skills add ikonicity-airban/antigravity-skills
```
*Scans the repository, opens an interactive selector for all 160+ skills, and lets you choose which AI agent(s) (Claude Code, Cursor, Gemini, Copilot) to target.*

### 2. Global Installation (Available across all projects on your machine)
```bash
npx skills add ikonicity-airban/antigravity-skills -g
```

### 3. Install a Specific Skill Directly
```bash
npx skills add ikonicity-airban/antigravity-skills --skill threejs-3d-webgl
npx skills add ikonicity-airban/antigravity-skills --skill faceless-youtube-creator
npx skills add ikonicity-airban/antigravity-skills --skill agentic-workflows
npx skills add ikonicity-airban/antigravity-skills --skill scroll-craft
```

---

## 📦 What's Included

### 1. Standalone Skills (`/skills`)

| Skill | Category | Description |
| :--- | :--- | :--- |
| **`threejs-3d-webgl`** | 3D & Graphics | Three.js, React Three Fiber (R3F), Drei, GLSL shaders, Rapier physics, and asset optimization. |
| **`webgl-threejs-canvas`** | 3D & Games | Canvas games, GLTF model viewers, interactive 3D scenes. |
| **`faceless-youtube-creator`** | Content Creation | Script retention loops, AI voice pacing (ElevenLabs), Remotion rendering, high-CTR packaging. |
| **`ebook-creator`** | Publishing | Markdown book scaffolding, Pandoc EPUB 3.0 compilation, Typst typesetting for PDF. |
| **`solana-anchor-rust`** | Web3 & Blockchain | Solana on-chain programs with Rust & Anchor framework. |
| **`solidity-hardhat`** | Web3 & Blockchain | Ethereum smart contracts with Solidity, Hardhat, OpenZeppelin. |
| **`web3-dapp-architecture`** | Web3 & Blockchain | Wagmi, Viem, multi-wallet connectors, transaction tracking. |
| **`expo-mobile`** | Mobile Apps | Cross-platform mobile development with Expo, React Native, NativeWind. |
| **`flutter-apps`** | Mobile Apps | Flutter widget trees, Riverpod state management, cross-platform layouts. |
| **`tauri-desktop`** | Desktop Apps | Lightweight desktop apps with Tauri, Rust, and modern web frontends. |
| **`electron-desktop`** | Desktop Apps | Cross-platform desktop apps with Electron, secure IPC, native menus. |
| **`godot-engine`** | Game Dev | 2D/3D games in Godot Engine using GDScript and physics systems. |
| **`agentic-workflows`** | AI & Automations | Multi-agent pipelines, structured outputs (Zod), prompt chaining, eval loops. |
| **`rag-vector-search`** | AI & Automations | Chunking, dense embeddings, hybrid search (BM25 + vector), reranking. |
| **`automation-scripting`** | Tooling | Headless web scrapers, Playwright automations, webhook responders. |
| **`cli-tool-builder`** | Tooling | Interactive CLI tools in Node.js (Commander, Clack) or Python (Click, Typer). |
| **`bash-powershell-scripting`** | Tooling | Defensive shell scripts in Bash and PowerShell with robust error trapping. |
| **`photo-editing-automation`** | Media | Image optimization, background removal, smart cropping via Sharp/rembg. |
| **`svg-animation-craft`** | Media | Kinetic SVG path-drawing, SMIL, CSS keyframe morphs, GSAP vector sequences. |
| **`icon-design-systems`** | Media | Pixel-perfect SVG icon grids (16/24/32px) and accessible React wrappers. |
| **`scroll-craft`** | UI Design | High-performance momentum scrolling, parallax depth, and scroll-linked timelines. |

---

### 2. Plugins (`/plugins`)

Full plugin bundles equipped with custom agents, rules, instructions, and grouped skills:
- **`3d-development`**: Dedicated 3D graphics, shaders, and WebGL tooling.
- **`content-creation`**: Automated workflows for YouTube channels and eBook authoring.
- **`ui-design`**: 22 UI skills (coss-ui, aceternity-ui, shadcn-ui, magic-ui, baseline-ui, typography, transitions).
- **`jsmastery-pro`**: 9 lifecycle skills (architect, audit, check, debug, develop, document, scope, sync, test).
- **`matt-pocock-skills`**: 35+ architectural and design skills including interactive grill-me.
- **`tailwindcss`**: Tailwind CSS v4 & v3 design systems and core utility guides.
- **`blockchain-dapps`**: End-to-end Web3, Solana, and Ethereum tooling.
- **`mobile-apps`**: Native and cross-platform mobile app development.
- **`desktop-apps`**: Tauri and Electron engineering.
- **`game-development`**: Godot and WebGL game development suites.
- **`developer-tools`**: Shell scripting and CLI tool builders.
- **`graphics-media`**: Vector, icon, and automated image processing.
- **`ai-automations`**: Agentic workflows, RAG, and automation pipelines.
- **`elephant-goldfish`**: EGM multi-persona architectural review framework.

---

## 🚀 How to Use These Skills in Any Project

### Option A: Install Globally on Any Machine
Copy the folders into your global Antigravity config directory:
```bash
# Windows
xcopy /E /I /Y skills "%USERPROFILE%\.gemini\config\skills"
xcopy /E /I /Y plugins "%USERPROFILE%\.gemini\config\plugins"

# macOS / Linux
cp -R skills/* ~/.gemini/config/skills/
cp -R plugins/* ~/.gemini/config/plugins/
```

### Option B: Use Project-Locally (Workspace-Specific)
Place specific skills directly into your repository:
```
my-project/
├── .gemini/
│   └── skills/
│       ├── threejs-3d-webgl/
│       │   └── SKILL.md
│       └── ...
```
Antigravity automatically discovers and activates skills found in your workspace's `.gemini/skills/` directory!
