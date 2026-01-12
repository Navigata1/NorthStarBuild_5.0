# North Star Build

## The Framework Ecosystem for Production-Ready Development

```
╔══════════════════════════════════════════════════════════════════════════════╗
║                                                                              ║
║                           NORTH STAR BUILD                                   ║
║                              v5.0                                            ║
║                                                                              ║
║              Build with intention. Ship with confidence.                     ║
║                                                                              ║
╚══════════════════════════════════════════════════════════════════════════════╝
```

---

## What Is This?

North Star Build is a comprehensive framework ecosystem for building production-ready software with AI assistance. It provides methodology, technology guidance, and orchestration patterns for AI-powered development.

### The Three Components

| Component | Purpose | Size |
|-----------|---------|------|
| **North Star Blueprint v5.0** | HOW to build — methodology, orchestration, quality gates | ~890 KB |
| **Master Build Framework v1.1** | WHAT to build with — 60 technology categories, tool matrices | ~185 KB |
| **BRIDGE.md** | Navigation layer — routes you between NS and MBF | ~52 KB |

### The Ignition Key

**NORTH_STAR_BOOTSTRAP.md** (~75 KB) is the single file you share. It contains:
- Condensed essential methodology
- Scaffolding fetch protocol (pulls full docs from this repo)
- Self-cleaning build process
- IDE detection and instruction file generation
- Quality gates, confidence calibration, handoff protocols

---

## How To Use

### For Users (Building Projects)

1. **Get the Bootstrap file** — Download `NORTH_STAR_BOOTSTRAP.md`
2. **Drop into your AI environment** — Claude, Cursor, Claude Code, Windsurf, etc.
3. **Start your project** — "Build me [your idea]"
4. **Agent handles the rest:**
   - Fetches full framework into `./build` folder
   - Generates project instruction file
   - Builds your project
   - Removes scaffolding when complete

---

## Repository Structure

```
NorthStarBuild_5.0/
├── README.md                         ← You are here
├── LICENSE                           ← CC BY-NC-SA 4.0
├── NORTH_STAR_BOOTSTRAP.md           ← THE IGNITION KEY (share this)
├── BRIDGE.md                         ← Navigation layer
│
├── north-star-blueprint/
│   └── NORTH_STAR_BLUEPRINT_v5.0.md  ← Full methodology
│
├── master-build-framework/
│   └── MASTER_BUILD_FRAMEWORK_v1.1.md ← Full technology
│
├── templates/                        ← IDE instruction templates
│
└── projects/                         ← Archived project intelligence
```

---

## The Scaffolding Pattern

Framework files are fetched temporarily during development, then removed when complete:

```
DURING BUILD:                         AFTER COMPLETION:
─────────────────────                 ─────────────────────
project/                              project/
├── build/           ← TEMPORARY      ├── .north-star-provenance ← STAYS
│   ├── BRIDGE.md                     ├── claude.md              ← STAYS
│   ├── NS_v5.0.md                    ├── README.md
│   └── MBF_v1.1.md                   ├── src/
├── claude.md                         └── ...
├── src/
└── ...                               build/ folder: DELETED ✓
```

---

## Supported IDEs & Tools

| Tool | Instruction File | Status |
|------|------------------|--------|
| Claude Code | CLAUDE.md | ✅ Full Support |
| Cursor | .cursorrules | ✅ Full Support |
| Windsurf | .windsurfrules | ✅ Full Support |
| Cline | .clinerules | ✅ Full Support |
| GitHub Copilot | .github/copilot-instructions.md | ✅ Full Support |
| Aider | CONVENTIONS.md | ✅ Full Support |
| Claude.ai | Paste Bootstrap | ✅ Full Support |

---

## License

**Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International (CC BY-NC-SA 4.0)**

- ✅ Use for personal projects
- ✅ Share and redistribute with attribution
- ❌ Commercial use requires separate license

**"North Star Build"** and **"North Star Framework"** are trademarks.

---

## Links

- **Repository:** https://github.com/Navigata1/NorthStarBuild_5.0
- **Bootstrap (Raw):** https://raw.githubusercontent.com/Navigata1/NorthStarBuild_5.0/main/NORTH_STAR_BOOTSTRAP.md

---

*Build with intention. Ship with confidence.*
