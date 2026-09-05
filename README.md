# SteelSim Documentation

Official developer, architecture, and engineering documentation website for **SteelSim** — an industrial digital-twin minimum viable product (MVP) engineered for secondary steel producers (induction-furnace and continuous-casting mini-mills producing TMT rebar).

Built with [VitePress](https://vitepress.dev/) adhering strictly to the pure OpenAI documentation design system (platform.openai.com/docs).

---

## Documentation Structure

The documentation site contains 40 comprehensive topic pages organized into 5 primary sections:

1. **Getting Started:** System overview, problems solved in MSME steelmaking, MVP scope boundaries, quick start, and investor walkthrough script.
2. **Task 1 — Visual Plant Builder:** React Flow engineering canvas, typed industrial ports, equipment catalog, topology validation, Auto Connect, Auto Layout, and live equipment telemetry.
3. **Task 2 — Simulation Engine:** FastAPI execution runtime, deterministic 1-second ticks, material-flow approximations, aggregate utility sizing (electrical and cooling water), cascade interlocks, and live Control Center WebSocket streams.
4. **Reference:** Standard 10-node TMT reference topology, complete equipment parameter catalogue, REST API endpoints, WebSocket event frames, data models, environment variables, security, and troubleshooting matrix.
5. **Project Context:** System architecture, Task 1 & 2 integration contract, verified MVP boundaries, and ACAMIS industrial roadmap.

---

## Local Development

### Prerequisites
- Node.js 18+ (tested on Node.js 20+ / 24+)
- npm 9+

### Installation
`ash
npm install
`

### Run Local Development Server
`ash
npm run docs:dev
`
The site will start at http://localhost:5174/.

### Build for Production
`ash
npm run docs:build
`
Builds the static HTML and assets into .vitepress/dist/.

### Preview Production Build
`ash
npm run docs:preview
`

---

## Repository Links

* **Main Application Repository:** [https://github.com/prabhasb06/steelsim](https://github.com/prabhasb06/steelsim)
* **Documentation Repository:** [https://github.com/prabhasb06/steelsimdocumentation](https://github.com/prabhasb06/steelsimdocumentation)
