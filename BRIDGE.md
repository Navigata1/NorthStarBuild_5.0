# BRIDGE.MD — Framework Navigation & Integration Guide

## The Navigation Layer for NS + MBF

---

```
╔══════════════════════════════════════════════════════════════════════════════╗
║                                                                              ║
║                              BRIDGE.MD                                       ║
║                                                                              ║
║              Navigation Layer for the Unified Framework Ecosystem            ║
║                                                                              ║
║                          ────────────────                                    ║
║                                                                              ║
║         "Know where to look. Reference what you need. Build quality."        ║
║                                                                              ║
╚══════════════════════════════════════════════════════════════════════════════╝
```

---

## 1. DOCUMENT HIERARCHY & READING ORDER

### 1.1 The Documentation Ecosystem

```
┌─────────────────────────────────────────────────────────────────────────────┐
│                     DOCUMENTATION HIERARCHY                                  │
├─────────────────────────────────────────────────────────────────────────────┤
│                                                                              │
│  LAYER 1: ENTRY POINTS                                                       │
│  ═══════════════════════════════════════════════════════════════════════    │
│                                                                              │
│      ┌─────────────┐         ┌─────────────┐                                │
│      │  README.md  │────────►│  BRIDGE.md  │                                │
│      │  "What is   │         │  "How do    │                                │
│      │   this?"    │         │  pieces     │                                │
│      └─────────────┘         │  connect?"  │                                │
│                              └──────┬──────┘                                │
│                                     │                                        │
│  LAYER 2: CORE FRAMEWORKS           │                                        │
│  ═══════════════════════════════════│════════════════════════════════════   │
│                                     │                                        │
│            ┌────────────────────────┴────────────────────────┐              │
│            │                                                  │              │
│            ▼                                                  ▼              │
│  ┌─────────────────────┐                        ┌─────────────────────┐     │
│  │  NORTH STAR v5.0    │                        │  MASTER BUILD v1.1  │     │
│  │                     │                        │                     │     │
│  │  HOW to build       │                        │  WHAT to build      │     │
│  │  • Methodology      │                        │  • 60 categories    │     │
│  │  • Orchestration    │                        │  • Technology stacks│     │
│  │  • Quality gates    │                        │  • Tool matrices    │     │
│  │  • Context mgmt     │                        │  • Build patterns   │     │
│  │  • Handoffs         │                        │                     │     │
│  └─────────────────────┘                        └─────────────────────┘     │
│            │                                                  │              │
│            └────────────────────────┬────────────────────────┘              │
│                                     │                                        │
│  LAYER 3: PROJECT-SPECIFIC          │                                        │
│  ═══════════════════════════════════│════════════════════════════════════   │
│                                     │                                        │
│                                     ▼                                        │
│                        ┌─────────────────────┐                              │
│                        │     claude.md       │                              │
│                        │                     │                              │
│                        │  YOUR project's     │                              │
│                        │  persistent guide   │                              │
│                        │                     │                              │
│                        │  Points back to:    │                              │
│                        │  • BRIDGE.md        │                              │
│                        │  • NS sections      │                              │
│                        │  • MBF categories   │                              │
│                        └─────────────────────┘                              │
│                                                                              │
└─────────────────────────────────────────────────────────────────────────────┘
```

### 1.2 Reading Order by Scenario

```
SCENARIO A: NEW USER / FIRST TIME
─────────────────────────────────────────────────────────────────────────────
1. README.md           → Understand what this framework ecosystem is
2. BRIDGE.md           → Learn how pieces connect (you are here)
3. NS Section 0        → Agentic Bootstrap Protocol (how to start)
4. Generate claude.md  → Your project's persistent guide
5. Reference NS/MBF    → On demand via BRIDGE.md routing

SCENARIO B: STARTING A NEW PROJECT
─────────────────────────────────────────────────────────────────────────────
1. BRIDGE.md           → Navigate to what you need
2. NS Section 0.2      → Generate claude.md from template
3. NS Section 2        → Determine project tier (Space/Sky/Foundation)
4. MBF Build Patterns  → Identify category combinations for your project
5. NS Section 11       → Begin first vertical slice

SCENARIO C: RETURNING TO EXISTING PROJECT
─────────────────────────────────────────────────────────────────────────────
1. claude.md           → Check current state, recent work, next actions
2. HANDOFF.md          → If exists, review session handoff notes
3. Continue work       → Reference NS/MBF via BRIDGE.md as needed

SCENARIO D: PICKING UP PAUSED SESSION
─────────────────────────────────────────────────────────────────────────────
1. claude.md           → "Current State" section
2. HANDOFF.md          → Detailed context from pause point
3. NS Section 0.5      → Deviation & Pause Protocol if issues remain
4. Resume execution    → From documented checkpoint

SCENARIO E: AI AGENT RECEIVING THESE DOCS
─────────────────────────────────────────────────────────────────────────────
1. BRIDGE.md           → Understand document relationships
2. NS Section 0.1      → Quick-Start Directive (CRITICAL)
3. NS Section 0.4      → Load Balancing (DON'T consume everything)
4. Generate claude.md  → Project-specific lightweight guide
5. Reference on demand → Use BRIDGE.md to find what you need
```

---

## 2. PURPOSE & RELATIONSHIP

### 2.1 What is BRIDGE.md?

BRIDGE.md is the **navigation layer** that connects two comprehensive frameworks into a unified ecosystem. It doesn't duplicate content — it routes you to the right place. Think of it as the index, the map, and the traffic controller.

**BRIDGE.md answers:** "Where do I look for X?" 
**NS answers:** "How do I do X?"
**MBF answers:** "What tools/options exist for X?"

### 2.2 The Two Frameworks: HOW vs WHAT

```
┌─────────────────────────────────────────────────────────────────────────────┐
│                    THE FUNDAMENTAL DISTINCTION                               │
├─────────────────────────────────────────────────────────────────────────────┤
│                                                                              │
│  NORTH STAR BLUEPRINT v5.0                MASTER BUILD FRAMEWORK v1.1       │
│  ══════════════════════════               ═══════════════════════════       │
│                                                                              │
│  Answers: HOW to build                    Answers: WHAT to build with       │
│                                                                              │
│  Contains:                                Contains:                          │
│  • Methodology & philosophy              • 60 technology categories          │
│  • Quality gates & standards             • Exhaustive tool matrices          │
│  • AI orchestration patterns             • Stack selection guides            │
│  • Context engineering                   • Build pattern combinations        │
│  • Confidence calibration                • Reasoning loop definitions        │
│  • Handoff protocols                     • Skill manifest templates          │
│  • Load balancing strategies             • Cross-category dependencies       │
│                                                                              │
│  Size: 883 KB, 59 sections               Size: ~180 KB, 60 categories       │
│                                                                              │
│  Use when you need:                      Use when you need:                  │
│  • Process guidance                      • Technology options                │
│  • Quality assurance                     • Tool comparisons                  │
│  • Orchestration patterns                • Stack decisions                   │
│  • Session management                    • Category combinations             │
│                                                                              │
└─────────────────────────────────────────────────────────────────────────────┘
```

### 2.3 Why Both?

Neither framework is complete alone:

- **NS without MBF:** Knows HOW to build but must guess WHAT tools exist
- **MBF without NS:** Knows WHAT tools exist but lacks orchestration, handoffs, load balancing
- **NS + MBF via BRIDGE:** Complete ecosystem — methodology meets technology

---

## 3. QUICK DECISION TREE

### "I need to..." → Go here:

```
QUICK ROUTING — COMMON SCENARIOS
─────────────────────────────────────────────────────────────────────────────

STARTING & PLANNING
─────────────────────────────────────────────────────────────────────────────
"Start a new project"
→ NS Section 0 (Agentic Bootstrap) + NS Section 2 (Tier System)

"Figure out what technologies to use"
→ MBF relevant tier (1-8) + NS Section 38 (Selection Principles)

"Determine project complexity tier"
→ NS Section 2 (Space/Sky/Foundation)

"Create project documentation structure"
→ NS Section 0.3 (Documentation Orchestration)

"Generate a claude.md file"
→ NS Section 0.2 (Template)


BUILDING & IMPLEMENTING
─────────────────────────────────────────────────────────────────────────────
"Build my first feature"
→ NS Section 11 (Vertical Slice Methodology)

"Choose a frontend framework"
→ MBF Category 1 (Web Applications)

"Choose a database"
→ MBF Categories 15-21 (Data Tier) + NS Section 40 (Database Patterns)

"Implement authentication"
→ NS Section 47 (Auth Patterns) + MBF Category 50 (Identity)

"Set up CI/CD"
→ NS Section 50 (Pipeline Architecture) + MBF Category 43 (CI/CD)


AI & AGENT DEVELOPMENT
─────────────────────────────────────────────────────────────────────────────
"Work with AI models"
→ NS Part IV (Sections 13-19) + MBF Categories 29-35

"Choose a reasoning loop (RALPH, ReAct, etc.)"
→ MBF Category 31C (Agentic Reasoning Loops)

"Build an autonomous agent"
→ MBF Category 30 (Autonomous Agents) + NS Part V (Agent Composition)

"Implement RAG"
→ MBF Category 29 (Agentic RAG) + MBF Category 16 (Vector DBs)

"Define agent skills/capabilities"
→ MBF Category 31B (Skills & Capability Packaging)


QUALITY & PROCESS
─────────────────────────────────────────────────────────────────────────────
"Write tests"
→ NS Part IX (Sections 42-45) + MBF Category 46

"Implement security"
→ NS Part X (Sections 46-49) + MBF Categories 50-53

"Design UI/UX"
→ NS Part VII (Sections 28-36) + MBF Categories 1-7

"Handle deployment"
→ NS Part XI (Sections 50-53) + MBF Categories 43-44


ORCHESTRATION & MANAGEMENT
─────────────────────────────────────────────────────────────────────────────
"Manage context window"
→ NS Section 16 (Context Engineering Protocol)

"Calibrate confidence levels"
→ NS Section 17 (Confidence Calibration Engine)

"Set autonomy level"
→ NS Section 18 (Autonomy Dial System)

"Hand off a session"
→ NS Section 23 + NS Section 0.6 (Handoff Protocols)


WHEN STUCK
─────────────────────────────────────────────────────────────────────────────
"Uncertain how to proceed"
→ NS Section 0.5 (Deviation & Pause Protocol)

"Need to pause/break"
→ NS Section 0.5 (Scenario 3) + NS Section 0.6 (Handoff Format)

"Want to deviate from recommendations"
→ NS Section 0.5 (Scenario 2)

"Something feels wrong"
→ NS Section 0.5 (Scenario 4)
```

---

## 4. THE TWO FRAMEWORKS AT A GLANCE

### 4.1 Comparison Table

| Dimension | North Star v5.0 | Master Build v1.1 |
|-----------|-----------------|-------------------|
| **Core Question** | "How do I build this well?" | "What can I build this with?" |
| **Structure** | 13 Parts, 59 Sections | 8 Tiers, 60 Categories |
| **Size** | 883 KB | ~180 KB |
| **Primary Content** | Methodology, orchestration, patterns | Technology matrices, tool options |
| **Agent Readiness** | High (self-bootstrapping Section 0) | Medium (prompt hooks per category) |
| **Load Balancing** | Built-in (Section 0.4) | Not addressed |
| **Handoffs** | Comprehensive (Section 0.6, 23) | Not addressed |
| **Confidence Calibration** | Yes (Section 17) | Not addressed |
| **Technology Depth** | Principles, not exhaustive lists | Exhaustive tool matrices |
| **Build Patterns** | Quality-focused | Category combinations |

### 4.2 Strengths of Each

**North Star v5.0 Excels At:**
- Bootstrapping agents effectively
- Managing cognitive/context load
- Quality gates and standards
- Session continuity and handoffs
- Confidence and autonomy calibration
- Design specifications (animation, UX)

**Master Build v1.1 Excels At:**
- Exhaustive technology coverage
- Tool selection and comparison
- Build target variety (mobile, desktop, embedded)
- Content generation pipelines
- Reasoning loop definitions
- Skill manifest structures

---

## 5. CROSS-REFERENCE MATRIX

### 5.1 Complete NS ↔ MBF Mapping

```
CROSS-REFERENCE MATRIX — ORGANIZED BY DOMAIN
─────────────────────────────────────────────────────────────────────────────

AI & AGENTS
─────────────────────────────────────────────────────────────────────────────
NS Part IV: AI Orchestration          ←→  MBF Categories 29-35 (AI Systems)
├─ NS Section 13: Model Intelligence  ←→  MBF 33: Model Serving
├─ NS Section 14: Core 4 Primitives   ←→  MBF 31: MCPs & Tool Registries
├─ NS Section 15: Tool Hierarchy      ←→  MBF 31: MCPs & Tool Registries
├─ NS Section 16: Context Engineering ←→  MBF 31E: Memory Architecture
├─ NS Section 17: Confidence          ←→  MBF 35: AI Safety & Guardrails
├─ NS Section 18: Autonomy Dial       ←→  MBF 30: Autonomous Agents
└─ NS Section 19: Multi-Model         ←→  MBF 34: LLM Routing & Orchestration

NS Part V: Agent Composition          ←→  MBF Categories 31B-31E (v1.1)
├─ NS Section 20: Memory Architecture ←→  MBF 31E: Memory Architecture
├─ NS Section 21: Skills & Sub-Agents ←→  MBF 31B: Skills & Capability
├─ NS Section 22: Verification        ←→  MBF 31C: Agentic Reasoning Loops
└─ NS Section 23: Handoffs            ←→  (No MBF equivalent)

NS Part VI: MCP & Tools               ←→  MBF Category 31 (MCPs)
├─ NS Section 24: MCP Power Tools     ←→  MBF 31: MCPs & Tool Registries
├─ NS Section 25: MCP-First           ←→  MBF 31: MCPs & Tool Registries
├─ NS Section 26: Voice Workflows     ←→  MBF 47: Conversational & Voice
└─ NS Section 27: IDE Routing         ←→  MBF 14: Platform Engineering


DEVELOPMENT & CODE
─────────────────────────────────────────────────────────────────────────────
NS Part VIII: Code Architecture       ←→  MBF Tier 1-2 (Build Targets, Compute)
├─ NS Section 37: Architecture        ←→  MBF 1-7: Build Target Selection
├─ NS Section 38: Tech Stack          ←→  MBF 1-14: All technology matrices
├─ NS Section 39: Code Organization   ←→  MBF 1: Web Applications (structure)
├─ NS Section 40: Database Patterns   ←→  MBF 15-21: Data & Persistence Tier
└─ NS Section 41: API Design          ←→  MBF 8: APIs & Backend Services


DATA & PERSISTENCE
─────────────────────────────────────────────────────────────────────────────
NS Section 40: Database Patterns      ←→  MBF Tier 3: Data & Persistence
                                      ├─  MBF 15: Relational Databases
                                      ├─  MBF 16: Vector Databases
                                      ├─  MBF 17: Document & NoSQL
                                      ├─  MBF 18: Local-First & Offline
                                      ├─  MBF 19: Object Storage
                                      ├─  MBF 20: Data Warehousing
                                      └─  MBF 21: Search Engines


DESIGN & UX
─────────────────────────────────────────────────────────────────────────────
NS Part VII: Design Mastery           ←→  MBF Tier 1 (Build Targets)
├─ NS Section 28: Design Philosophy   ←→  MBF 1-5: UI considerations
├─ NS Section 29: Animation Pyramid   ←→  (No MBF equivalent - NS deeper)
├─ NS Section 30: Animation Specs     ←→  (No MBF equivalent - NS deeper)
├─ NS Section 31: Easings & Durations ←→  (No MBF equivalent - NS deeper)
├─ NS Section 32: Micro-Interactions  ←→  (No MBF equivalent - NS deeper)
├─ NS Section 33: Loading States      ←→  (No MBF equivalent - NS deeper)
├─ NS Section 34: Space Tier UX       ←→  (No MBF equivalent - NS deeper)
├─ NS Section 35: Accessibility       ←→  MBF 56: Compliance (a11y)
└─ NS Section 36: Design Terminology  ←→  (No MBF equivalent)


TESTING & QUALITY
─────────────────────────────────────────────────────────────────────────────
NS Part IX: Testing Framework         ←→  MBF Category 46 (Testing & QA)
├─ NS Section 42: Testing Philosophy  ←→  MBF 46: Testing strategies
├─ NS Section 43: Coverage Strategies ←→  MBF 46: Testing tools
├─ NS Section 44: Testing Patterns    ←→  MBF 46: Testing patterns
└─ NS Section 45: Test Infrastructure ←→  MBF 46: Testing infrastructure


SECURITY & COMPLIANCE
─────────────────────────────────────────────────────────────────────────────
NS Part X: Security                   ←→  MBF Tier 8 (Foundation)
├─ NS Section 46: Security-First      ←→  MBF 52: Security & Encryption
├─ NS Section 47: Authentication      ←→  MBF 50: Authentication & Identity
├─ NS Section 48: Authorization       ←→  MBF 50: Authentication & Identity
└─ NS Section 49: Data Protection     ←→  MBF 53: Secrets Management


DEVOPS & DEPLOYMENT
─────────────────────────────────────────────────────────────────────────────
NS Part XI: DevOps & Deployment       ←→  MBF Tier 7 (Automation)
├─ NS Section 50: CI/CD Pipelines     ←→  MBF 43: CI/CD Pipelines
├─ NS Section 51: Environment Mgmt    ←→  MBF 13: Infrastructure as Code
├─ NS Section 52: Monitoring          ←→  MBF 55: Monitoring & Observability
└─ NS Section 53: Deployment Strategy ←→  MBF 44: Workflow Orchestration


CONTENT GENERATION (MBF Only)
─────────────────────────────────────────────────────────────────────────────
(No NS equivalent)                    ←→  MBF Tier 6: Content Generation
                                      ├─  MBF 36: Image Generation
                                      ├─  MBF 37: Audio Generation
                                      ├─  MBF 38: Video Generation
                                      ├─  MBF 39: Document Generation
                                      ├─  MBF 40: Code Generation
                                      ├─  MBF 41: Data & Content Generation
                                      └─  MBF 42: Translation & Localization


DOCUMENTATION
─────────────────────────────────────────────────────────────────────────────
NS Part III: Documentation            ←→  MBF Category 48 (Documentation)
├─ NS Section 9: Doc Hierarchy        ←→  MBF 48: Documentation Systems
├─ NS Section 10: Superprompt         ←→  (No MBF equivalent - NS deeper)
├─ NS Section 11: Vertical Slice      ←→  (No MBF equivalent - NS deeper)
└─ NS Section 12: Fix Ledger          ←→  (No MBF equivalent - NS deeper)
```

---

## 6. USE CASE ROUTING

### 6.1 Building a SaaS Application

```
USE CASE: SaaS Web Application
─────────────────────────────────────────────────────────────────────────────

STEP 1: Bootstrap
├─ Read: NS Section 0.1 (Quick-Start Directive)
├─ Do: Generate claude.md using NS Section 0.2 template
└─ Set: Project tier (likely Sky or Space) using NS Section 2

STEP 2: Architecture
├─ Read: MBF Build Pattern → Categories 1 + 8 + 15 + 22 + 43 + 50 + 51 + 54 + 55
├─ Decide: Frontend framework using MBF Category 1
├─ Decide: Backend approach using MBF Category 8
├─ Decide: Database using MBF Category 15 + NS Section 40
└─ Document: Architecture decision in ADR

STEP 3: First Vertical Slice
├─ Read: NS Section 11 (Vertical Slice Methodology)
├─ Build: One complete feature end-to-end
├─ Test: Using NS Part IX principles
└─ Deploy: To staging using NS Section 50

STEP 4: Expand
├─ Reference: MBF categories as needed for each feature
├─ Follow: NS quality gates (Section 3)
└─ Maintain: claude.md current state

STEP 5: Production
├─ Security: NS Part X + MBF Categories 50-53
├─ Monitoring: NS Section 52 + MBF Category 55
├─ Payments: MBF Category 51
└─ Compliance: MBF Category 56 + NS Section 35 (accessibility)
```

### 6.2 Building an Autonomous Agent System

```
USE CASE: Autonomous Agent / AI System
─────────────────────────────────────────────────────────────────────────────

STEP 1: Bootstrap
├─ Read: NS Section 0.1 (Quick-Start Directive)
├─ Do: Generate claude.md using NS Section 0.2 template
└─ Set: Project tier (likely Space) using NS Section 2

STEP 2: Agent Architecture
├─ Read: NS Part IV (AI Orchestration) - ALL of it for this use case
├─ Read: NS Part V (Agent Composition) - ALL of it
├─ Reference: MBF Build Pattern → Categories 29 + 30 + 31 + 32 + 33 + 34 + 35
└─ Choose: Reasoning loop using MBF 31C (RALPH, ReAct, ReWOO, etc.)

STEP 3: Memory & Context
├─ Design: Using NS Section 20 (Memory Architecture) + MBF 31E
├─ Implement: Context engineering using NS Section 16
├─ Choose: Vector DB using MBF Category 16
└─ Build: Knowledge graph if needed using MBF Category 26

STEP 4: Skills & Tools
├─ Define: Skills using MBF 31B (Skill Manifests)
├─ Integrate: MCP tools using NS Section 24 + MBF Category 31
└─ Test: Using NS Part IX + MBF Category 46

STEP 5: Safety & Deployment
├─ Implement: Guardrails using MBF Category 35
├─ Set: Autonomy level using NS Section 18
├─ Calibrate: Confidence thresholds using NS Section 17
└─ Monitor: Using NS Section 52 + MBF Category 55
```

### 6.3 Building a Content Generation Pipeline

```
USE CASE: Content Generation Pipeline (Images, Video, Docs)
─────────────────────────────────────────────────────────────────────────────

STEP 1: Bootstrap
├─ Read: NS Section 0.1 (Quick-Start Directive)
├─ Do: Generate claude.md
└─ Set: Project tier using NS Section 2

STEP 2: Pipeline Architecture
├─ Reference: MBF Build Pattern → Categories 36 + 37 + 38 + 39 + 11 + 19 + 44
├─ Choose: Generation tools from MBF Tier 6 (Categories 36-42)
├─ Design: Workflow using MBF Category 44 (Workflow Orchestration)
└─ Plan: Storage using MBF Category 19 (Object Storage)

STEP 3: Infrastructure
├─ Compute: MBF Category 11 (GPU & ML Compute)
├─ Queues: MBF Category 23 (Message Queues)
├─ Caching: MBF Category 22 (Caching & Performance)
└─ Deploy: NS Part XI + MBF Category 43

STEP 4: Quality & Monitoring
├─ Testing: NS Part IX principles
├─ Monitoring: NS Section 52 + MBF Category 55
└─ Safety: MBF Category 35 (AI Safety)
```

### 6.4 Adding AI Features to Existing Application

```
USE CASE: Adding AI to Existing App
─────────────────────────────────────────────────────────────────────────────

STEP 1: Assessment
├─ Review: Existing claude.md (or create one)
├─ Identify: Integration points
└─ Determine: AI capability needed (chat, RAG, agents, generation)

STEP 2: AI Architecture
├─ Read: NS Part IV Section 13 (Model Intelligence Matrix)
├─ Choose: Model(s) using NS Section 13 + MBF Category 33
├─ Decide: RAG if needed using MBF Category 29
└─ Plan: Memory using NS Section 20 + MBF 31E

STEP 3: Integration
├─ API Design: NS Section 41 + MBF Category 8
├─ Tool Integration: NS Section 24 (MCP) + MBF Category 31
└─ Testing: NS Part IX with AI-specific considerations

STEP 4: Production
├─ Safety: MBF Category 35
├─ Monitoring: AI-specific metrics (NS Section 52)
├─ Cost: Model routing considerations (NS Section 13)
└─ Iterate: Based on user feedback
```

---

## 7. COMBINED WORKFLOW EXAMPLES

### 7.1 Example: "Build a SaaS with AI-Powered Features"

```
CONCRETE EXAMPLE: AI-Powered Project Management SaaS
─────────────────────────────────────────────────────────────────────────────

PHASE 1: BOOTSTRAP (Day 1)
─────────────────────────────────────────────────────────────────────────────

Action: Read NS Section 0.1-0.3
Result: Understand bootstrap protocol

Action: Determine tier
Reference: NS Section 2
Decision: "Sky" tier (standard SaaS, not ultra-premium)

Action: Generate claude.md
Reference: NS Section 0.2 template
Content:
  - Project: "TaskAI" - AI-powered project management
  - Tier: Sky
  - Stack decisions pending
  - Quality gates from NS Section 3 for Sky tier

Action: Set up docs scaffold
Reference: NS Section 0.3 Phase 0
Created: README.md, CHANGELOG.md, .gitignore


PHASE 2: ARCHITECTURE DECISIONS (Day 1-2)
─────────────────────────────────────────────────────────────────────────────

Question: "Which frontend framework?"
Reference: MBF Category 1 → Next.js 15 (Server components, App Router)
Document: ADR-001-frontend.md

Question: "Which database?"
Reference: MBF Category 15 + NS Section 40
Decision: PostgreSQL (NS default recommendation confirmed by MBF)
Document: ADR-002-database.md

Question: "How to add AI?"
Reference: NS Part IV + MBF Categories 29-35
Decision: 
  - OpenAI for task suggestions (MBF Category 33)
  - RAG for project context (MBF Category 29)
  - pgvector for embeddings (MBF Category 16)
Document: ADR-003-ai-architecture.md


PHASE 3: FIRST VERTICAL SLICE (Day 2-5)
─────────────────────────────────────────────────────────────────────────────

Reference: NS Section 11 (Vertical Slice Methodology)

Slice: "User can create a task and get AI suggestions"
├─ UI: Task creation form with AI suggestion panel
├─ API: POST /tasks, GET /tasks/:id/suggestions
├─ DB: tasks table, embeddings table
├─ AI: OpenAI integration for suggestions
└─ Test: E2E test of complete flow

Quality Check: NS Section 3 (Sky tier gates)
├─ ✓ TypeScript strict
├─ ✓ Unit tests for business logic
├─ ✓ Integration test for API
├─ ✓ No security warnings

Update: claude.md "Current State" section


PHASE 4: EXPAND FEATURES (Day 5-20)
─────────────────────────────────────────────────────────────────────────────

Feature 2: Authentication
├─ Reference: NS Section 47 + MBF Category 50
├─ Decision: NextAuth.js with magic links
└─ Document: ADR-004-auth.md

Feature 3: Team collaboration
├─ Reference: MBF Category 24 (Real-Time & WebSockets)
├─ Decision: Liveblocks for presence
└─ Implement per NS Section 11 methodology

Feature 4: AI chat assistant
├─ Reference: NS Section 20 (Memory) + MBF 31E
├─ Decision: Conversation memory with vector storage
├─ Implement: RAG using MBF Category 29 guidance
└─ Safety: MBF Category 35 guardrails


PHASE 5: PRODUCTION (Day 20-30)
─────────────────────────────────────────────────────────────────────────────

CI/CD: NS Section 50 + MBF Category 43
├─ GitHub Actions workflow
├─ Staging → Production pipeline
└─ Quality gates enforced

Security: NS Part X + MBF Categories 50-53
├─ Auth hardening (NS Section 47)
├─ Secrets management (MBF Category 53)
└─ Security headers (NS Section 46)

Payments: MBF Category 51
├─ Stripe integration
└─ Subscription tiers

Monitoring: NS Section 52 + MBF Category 55
├─ Error tracking (Sentry)
├─ Analytics (PostHog)
└─ AI cost tracking


RESULT: Production SaaS with AI features
─────────────────────────────────────────────────────────────────────────────
Built using NS methodology, MBF technology selection.
claude.md maintained throughout.
All decisions documented in ADRs.
Quality gates met for Sky tier.
```

### 7.2 Example: "Build an Autonomous Coding Agent"

```
CONCRETE EXAMPLE: Code Review Agent
─────────────────────────────────────────────────────────────────────────────

PHASE 1: BOOTSTRAP
─────────────────────────────────────────────────────────────────────────────

Tier: Space (premium quality for autonomous system)
Reference: NS Section 2 (Space tier criteria)

claude.md created with:
- Project: "ReviewBot" - Autonomous code review agent
- Tier: Space
- Special considerations: Autonomy level, confidence thresholds


PHASE 2: AGENT ARCHITECTURE
─────────────────────────────────────────────────────────────────────────────

Reasoning Loop Selection:
Reference: MBF Category 31C
Decision: RALPH loop (Reason→Act→Learn→Plan→Hypothesize)
Rationale: Complex analysis needs hypothesis testing

Memory Architecture:
Reference: NS Section 20 + MBF 31E
Design:
├─ Working: Current PR context in window
├─ Episodic: Past reviews in vector DB
├─ Semantic: Codebase knowledge graph
└─ Procedural: Review skills and patterns

Confidence Calibration:
Reference: NS Section 17
Thresholds:
├─ >80%: Auto-approve/comment
├─ 50-80%: Flag for human review
└─ <50%: Do not act, escalate

Autonomy Level:
Reference: NS Section 18
Setting: Level 4 "Supervised Auto" (can act, human validates)


PHASE 3: SKILL DEFINITION
─────────────────────────────────────────────────────────────────────────────

Reference: MBF Category 31B (Skill Manifests)

skill-code-review.json:
{
  "name": "code-review",
  "version": "1.0.0",
  "description": "Analyzes code changes for quality, security, performance",
  "category": "reasoning",
  "tools_required": ["read_file", "search_codebase", "git_diff"],
  "quality_gates": ["no_false_positives_in_tests"],
  "agentic_hooks": {
    "invoke": "Analyze this PR for issues..."
  }
}


PHASE 4: SAFETY & GUARDRAILS
─────────────────────────────────────────────────────────────────────────────

Reference: MBF Category 35 + NS Section 17

Implemented:
├─ Cannot approve own PRs
├─ Cannot merge without human
├─ Rate limiting on comments
├─ Confidence threshold enforcement
└─ Escalation to human on uncertainty


RESULT: Autonomous code review agent
─────────────────────────────────────────────────────────────────────────────
RALPH reasoning loop for thorough analysis.
Memory architecture for learning from past reviews.
Confidence-gated execution prevents bad actions.
Space tier quality throughout.
```

---

## 8. LOAD BALANCING REMINDER

### 8.1 The Core Principle

```
┌─────────────────────────────────────────────────────────────────────────────┐
│                         LOAD BALANCING PRINCIPLE                             │
├─────────────────────────────────────────────────────────────────────────────┤
│                                                                              │
│  ╔═══════════════════════════════════════════════════════════════════════╗  │
│  ║                                                                       ║  │
│  ║   DO NOT CONSUME BOTH FRAMEWORKS FULLY BEFORE STARTING               ║  │
│  ║                                                                       ║  │
│  ║   NS v5.0 = 883 KB                                                   ║  │
│  ║   MBF v1.1 = ~180 KB                                                 ║  │
│  ║   Combined = 1+ MB of content                                        ║  │
│  ║                                                                       ║  │
│  ║   This will overload any context window and any human brain.         ║  │
│  ║                                                                       ║  │
│  ╚═══════════════════════════════════════════════════════════════════════╝  │
│                                                                              │
│  INSTEAD:                                                                    │
│                                                                              │
│  1. Read BRIDGE.md (this document) to understand structure                  │
│  2. Skim NS Section 0 to understand bootstrap protocol                      │
│  3. Generate claude.md for your project                                     │
│  4. Reference specific sections ON DEMAND using this BRIDGE                 │
│                                                                              │
│  The frameworks are REFERENCE DOCUMENTS, not READING ASSIGNMENTS.           │
│                                                                              │
└─────────────────────────────────────────────────────────────────────────────┘
```

### 8.2 Load Balancing Tiers (from NS Section 0.4)

```
TIER 1: ALWAYS LOADED (Light)
─────────────────────────────────────────────────────────────────────────────
Keep in active memory:
• BRIDGE.md structure (this document)
• NS Section 0.4 Load Balancing concept
• Your project's claude.md

TIER 2: LOAD ON DEMAND (Medium)
─────────────────────────────────────────────────────────────────────────────
Reference when you hit the task:
• NS specific sections for methodology
• MBF specific categories for technology options
• Use BRIDGE.md Section 3 to route

TIER 3: DEEP REFERENCE (Heavy)
─────────────────────────────────────────────────────────────────────────────
Occasional deep dives:
• NS Part VII (Design) - detailed specs
• MBF technology matrices - exhaustive options
• Only when making major decisions
```

---

## 9. TEMPLATE REFERENCE

### 9.1 Available Templates

| Template | Source | Purpose | When to Use |
|----------|--------|---------|-------------|
| **claude.md** | NS Section 0.2 | Project intelligence file | Start of every project |
| **handoff.md** | NS Section 0.6 | Session continuity | End of session, pausing work |
| **adr.md** | NS Section 9 | Architecture decisions | Major technical choices |
| **skill-manifest.json** | MBF 31B | Capability packaging | Defining agent skills |
| **fix-ledger.md** | NS Section 12 | Bug pattern tracking | After fixing recurring issues |

### 9.2 Template Locations

```
templates/
├── claude.md.template        # From NS Section 0.2
├── handoff.md.template       # From NS Section 0.6
├── adr.md.template           # From NS Section 9
├── skill-manifest.json       # From MBF Category 31B
└── fix-ledger.md.template    # From NS Section 12
```

### 9.3 Quick Template: claude.md Header

Every project's claude.md should start with:

```markdown
# CLAUDE.MD — Project Intelligence File

> **READING ORDER:**
> 1. You're reading this file (project-specific state)
> 2. For navigation between frameworks → see BRIDGE.md
> 3. For methodology (HOW) → see North Star Blueprint v5.0
> 4. For technology options (WHAT) → see Master Build Framework v1.1

---
[Continue with NS Section 0.2 template...]
```

---

## 10. VERSION INFORMATION

```
┌─────────────────────────────────────────────────────────────────────────────┐
│                         VERSION INFORMATION                                  │
├─────────────────────────────────────────────────────────────────────────────┤
│                                                                              │
│  BRIDGE.md                                                                   │
│  Version: 1.0                                                                │
│  Created: January 2025                                                       │
│                                                                              │
│  COMPATIBLE WITH:                                                            │
│  • North Star Blueprint v5.0                                                │
│  • Master Build Framework v1.1                                              │
│                                                                              │
│  CHANGELOG:                                                                  │
│  v1.0 (January 2025) — Initial release                                      │
│    • Document hierarchy and reading order                                   │
│    • Complete cross-reference matrix                                        │
│    • Use case routing                                                        │
│    • Combined workflow examples                                              │
│                                                                              │
└─────────────────────────────────────────────────────────────────────────────┘
```

---

## QUICK REFERENCE CARD

```
┌─────────────────────────────────────────────────────────────────────────────┐
│                     BRIDGE.MD QUICK REFERENCE                                │
├─────────────────────────────────────────────────────────────────────────────┤
│                                                                              │
│  START HERE:           NS Section 0 (Bootstrap)                             │
│  NAVIGATE WITH:        BRIDGE.md (this document)                            │
│  HOW TO BUILD:         North Star Blueprint v5.0                            │
│  WHAT TO BUILD WITH:   Master Build Framework v1.1                          │
│  PROJECT STATE:        claude.md (your project's file)                      │
│                                                                              │
│  ─────────────────────────────────────────────────────────────────────────  │
│                                                                              │
│  COMMON ROUTES:                                                              │
│  • Starting project     → NS 0 + NS 2 + MBF Build Patterns                  │
│  • Choosing tech        → MBF Categories + NS 38                            │
│  • Building features    → NS 11 + MBF relevant category                     │
│  • AI/Agents            → NS IV-V + MBF 29-35                               │
│  • Testing              → NS IX + MBF 46                                    │
│  • Security             → NS X + MBF 50-53                                  │
│  • Stuck                → NS 0.5                                            │
│                                                                              │
│  ─────────────────────────────────────────────────────────────────────────  │
│                                                                              │
│  REMEMBER: Reference on demand. Don't consume everything upfront.           │
│                                                                              │
└─────────────────────────────────────────────────────────────────────────────┘
```

---

*End of BRIDGE.md v1.0*
