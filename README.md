<div align="center">

<br/>

```
  ◈ EMPATHIZE → DEFINE → IDEATE → PROTOTYPE → TEST → IMPLEMENT ◈
```

# Design Thinking
### A Claude Code Skill

**Human-centered design methodology — from user research to shipped solution.**
Built for product designers, UX researchers, service designers, entrepreneurs, and business leaders.

<br/>

[![Version](https://img.shields.io/badge/version-1.0.0-0a0a0a?style=flat-square&labelColor=f5f0e8)](https://github.com/65ping/design-thinking)
[![Phases](https://img.shields.io/badge/phases-6-0a0a0a?style=flat-square&labelColor=f5f0e8)](https://github.com/65ping/design-thinking/blob/main/SKILL.md)
[![Audiences](https://img.shields.io/badge/audiences-3-0a0a0a?style=flat-square&labelColor=f5f0e8)](https://github.com/65ping/design-thinking/blob/main/SKILL.md#role-specific-application)
[![Claude Code](https://img.shields.io/badge/Claude_Code-skill-0a0a0a?style=flat-square&labelColor=f5f0e8)](https://claude.ai/claude-code)

<br/>

</div>

---

## What It Does

This skill turns Claude into a Design Thinking coach, facilitator, and artifact generator. Tell Claude what phase you're in and what you need — it adapts to your role, context, and timeline.

```
"I need to plan empathy interviews for a mobile banking redesign"
"Help me synthesize these research notes into a problem statement"
"We're running a 90-minute remote ideation session — what method should we use?"
"I'm a founder — how do I validate my idea before I build anything?"
"We're redesigning a healthcare service — where do we start?"
```

Claude responds with structured guidance, ready-to-use artifacts, facilitation scripts, or design critique — all grounded in the methodology.

---

## The Six Phases

| # | Phase | Core Question | Output |
|---|---|---|---|
| 1 | 🔍 **Empathize** | Who are these people and what do they actually experience? | Empathy maps, research insights |
| 2 | 🎯 **Define** | What is the real problem worth solving? | POV statement, HMW questions |
| 3 | 💡 **Ideate** | What are all possible ways to solve this? | Solution concepts, decision rationale |
| 4 | 🔧 **Prototype** | What is the cheapest version we can learn from? | Prototype artifact (any fidelity) |
| 5 | 🧪 **Test** | Does this work for real people? | Validated insights, iteration priorities |
| 6 | 🚀 **Implement** | How do we get this to users? | Shipped solution, adoption plan |

> The process is non-linear by design. Looping back is not failure — it is the methodology working as intended.

---

## Install

**Add to an existing Claude Code project:**

```bash
# Clone into your project's .claude/skills directory
git clone https://github.com/65ping/design-thinking.git .claude/skills/design-thinking
```

**Or install globally** (available across all your projects):

```bash
git clone https://github.com/65ping/design-thinking.git ~/.claude/skills/design-thinking
```

Claude Code will detect the skill automatically. No configuration needed.

---

## Who It's For

### 🖥️ Product & Design Teams
Product designers, UX researchers, UI designers, service designers, and product managers applying Design Thinking inside sprint cycles, design critiques, and product strategy.

- Balances methodology depth with sprint velocity
- Frames design critiques around POV statements, not aesthetics
- Guides handoff documentation that preserves design intent through implementation

### 🚀 Entrepreneurs & Startups
Founders using Design Thinking for early-stage customer discovery, pre-launch validation, and lean iteration — before writing a line of code.

- Maps directly to Lean Startup: Build-Measure-Learn ↔ Prototype-Test-Iterate
- Addresses founder bias: the failure mode of building what you want, not what users need
- Stage-specific guidance from idea validation through scale

### 🏢 Business & Strategy Leaders
Executives running innovation workshops, redesigning services, and reframing business problems as human-centered problems.

- Reframes "increase retention by 12%" into actionable user insights
- Guides facilitation of strategy workshops and innovation sprints
- Addresses the idea-to-reality gap where most innovation dies

---

## What's Inside

```
design-thinking/
│
├── SKILL.md                      ← Main skill file (auto-loaded by Claude Code)
│   ├── Methodology foundation    ← 6-phase overview, IDEO 3 lenses, designer's mindset
│   ├── Stage 1: Empathize        ← Interviews, observation, empathy maps
│   ├── Stage 2: Define           ← Affinity diagramming, POV statements, HMW questions
│   ├── Stage 3: Ideate           ← Brainstorming, SCAMPER, Brainwrite, convergence
│   ├── Stage 4: Prototype        ← Fidelity table, prototype principles, artifact types
│   ├── Stage 5: Test             ← Usability testing, think-aloud, synthesis, severity
│   ├── Stage 6: Implement        ← Handoff, implementation review, post-launch learning
│   ├── Role-specific guidance    ← Product & design / Entrepreneurs / Business leaders
│   ├── Project context guide     ← New product / Existing product / Service / Workshop
│   └── Anti-patterns             ← 20+ common mistakes organized by phase
│
└── reference/
    ├── templates.md              ← 7 ready-to-fill artifacts
    ├── facilitation-methods.md   ← 4 complete workshop facilitation scripts
    └── service-design.md         ← Service blueprint, journey map, ecosystem map
```

---

## Templates Included

| Template | Use When |
|---|---|
| **Empathy Map** | After user interviews, before synthesis |
| **POV Statement** | After affinity diagramming, before ideation |
| **HMW Question List** | After POV statement, to open up solution space |
| **Prototype Brief** | Before building any prototype |
| **Usability Test Script** | Before any user testing session |
| **Test Findings Synthesis Table** | After all test sessions, before deciding next step |
| **Brainstorming Session Brief** | Before any ideation workshop |

---

## Facilitation Scripts Included

| Script | Format | Duration |
|---|---|---|
| **90-min Remote Ideation Session** | Remote / in-person | 90 min |
| **Research Synthesis Workshop** | Affinity diagramming | 2–3 hours |
| **Prototype Critique Session** | Rose, Bud, Thorn structure | 45–60 min |
| **3-Day Innovation Workshop** | Full sprint structure | 3 days |

---

## Example Outputs

**Phase planning:**
> "We're starting a new mobile app project with no prior research. What should we do in the first two weeks?"

Claude returns a structured Empathize + Define plan — methods, timing, participant recruitment criteria, outputs, and warning signs that you're shortcutting.

**Artifact generation:**
> "Write a POV statement for a nurse managing medication handoffs between shifts."

Claude returns a filled example, a blank template, and an annotation of what makes the statement strong or weak.

**Design critique:**
> "Here's our design brief [paste]. We're about to start building."

Claude identifies which phase the team is in, flags assumptions that should be tested first, checks for phase-skipping, and gives specific recommendations.

**Facilitation planning:**
> "We have 6 stakeholders and 3 hours. We need to align on the problem before ideating."

Claude returns a complete session agenda with timing, materials list, facilitation instructions per activity, and a plan for when it stalls.

---

## The Three Lenses

Every design decision balances three questions (IDEO):

- **Desirability** — Do people want this? Does it fit their lives and actual needs?
- **Feasibility** — Can it be built? What does technology currently allow?
- **Viability** — Is it sustainable? Does it make economic and organizational sense?

Strong design lives at the intersection of all three.

---

## Sources

This skill was built from five authoritative sources on Design Thinking methodology:

- [IDEO Design Thinking](https://designthinking.ideo.com/)
- [Nielsen Norman Group — Design Thinking 101](https://www.nngroup.com/articles/design-thinking/)
- [Interaction Design Foundation — 5 Stages](https://ixdf.org/literature/article/5-stages-in-the-design-thinking-process)
- [Voltage Control — Step-by-Step Guide](https://voltagecontrol.com/blog/5-steps-of-the-design-thinking-process-a-step-by-step-guide/)
- [Asana — Design Thinking Process](https://asana.com/resources/design-thinking-process)

---

<div align="center">

Built as a [Claude Code](https://claude.ai/claude-code) skill · v1.0.0

</div>
