<div align="center">

<br/>

```
  ◈ EMPATHIZE → DEFINE → IDEATE → PROTOTYPE → TEST → IMPLEMENT ◈
```

# Design Thinking
### A Claude Code Skill

**Human-centered design methodology, from user research to shipped solution.**
Built for product designers, UX researchers, service designers, entrepreneurs, and business leaders.

<br/>

[![Version](https://img.shields.io/badge/version-1.0.0-0a0a0a?style=flat-square&labelColor=f5f0e8)](https://github.com/65ping/design-thinking)
[![Phases](https://img.shields.io/badge/phases-6-0a0a0a?style=flat-square&labelColor=f5f0e8)](https://github.com/65ping/design-thinking/blob/main/SKILL.md)
[![Audiences](https://img.shields.io/badge/audiences-3-0a0a0a?style=flat-square&labelColor=f5f0e8)](https://github.com/65ping/design-thinking/blob/main/SKILL.md#role-specific-application)
[![Claude Code](https://img.shields.io/badge/Claude_Code-skill-0a0a0a?style=flat-square&labelColor=f5f0e8)](https://claude.ai/claude-code)

<br/>

</div>
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


## What It Does

This skill turns Claude into a Design Thinking coach, facilitator and artifact generator. 
Tell Claude what phase you're in and what you need: it adapts to your role, context, and timeline.

```
"I need to plan empathy interviews for a mobile banking redesign"
"Help me synthesize these research notes into a problem statement"
"We're running a 90-minute remote ideation session, what method should we use?"
"I'm a founder, how do I validate my idea before I build anything?"
"We're redesigning a healthcare service, where do we start?"
```

Claude responds with structured guidance, ready-to-use artifacts, facilitation scripts, or design critique, all grounded in the methodology.

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

> The process is non-linear by design. Looping back is not failure: it is the methodology working as intended.


---

## Who It's For

### 🖥️ Product & Design Teams
Product designers, UX researchers, UI designers, service designers, and product managers applying Design Thinking inside sprint cycles, design critiques, and product strategy.

- Balances methodology depth with sprint velocity
- Frames design critiques around POV statements, not aesthetics
- Guides handoff documentation that preserves design intent through implementation

### 🚀 Entrepreneurs & Startups
Founders using Design Thinking for early-stage customer discovery, pre-launch validation, and lean iteration: before writing a line of code.

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
│   ├── Methodology foundation    ← 6-phase overview, three lenses, designer's mindset
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

## Prompt Examples

The most effective way to use this skill is to describe what phase you're in and what you need. Claude handles the rest.

---

### Simple: Single artifact or phase

**Generate an empathy map:**
```
Write an empathy map for a first-time homebuyer
going through the mortgage application process.
```
→ Claude returns a filled Do / Say / Think / Feel grid with observations, inferred beliefs, emotional texture, and workarounds.

**Write a POV statement:**
```
Write a POV statement for a nurse managing
medication handoffs between shifts at a busy hospital.
```
→ Claude returns a filled example, a blank template, and an annotation of what makes it strong or weak.

**Generate HMW questions:**
```
Here's my POV statement:
"A part-time caregiver needs to confirm her mother's medication
was taken remotely because the phone-call system creates daily
anxiety she cannot resolve."
Give me 10 How Might We questions for ideation.
```
→ Claude returns a prioritized list at the right scope: not too narrow (solution-prescribing), not too broad (useless).

**Choose prototype fidelity:**
```
We want to test whether users understand our new onboarding
flow before we build it. What kind of prototype should we make?
```
→ Claude recommends the lowest-cost prototype that tests the right assumption, with a brief explaining what to build and what to exclude.

**Prepare a test script:**
```
I'm running a usability test on a checkout redesign tomorrow
with 5 participants. Write me a test script with 3 tasks,
the right scenario framing, and the facilitator prompts to use
when someone gets stuck.
```
→ Claude returns a ready-to-run script with welcome, warm-up, tasks, probing questions, and a debrief structure.

**Evaluate a problem statement:**
```
Is this a good problem statement?
"Users need a better dashboard because the current one is confusing."
```
→ Claude diagnoses whether it's human-centered, solution-adjacent, or too vague: and rewrites it correctly.

---

### Intermediate: Multi-step or role-specific

**Synthesize research into a problem statement:**
```
I interviewed 6 remote caregivers about managing elderly
parents' medications. Here are my notes: [paste notes].
Help me run an affinity diagram and write a POV statement
from what I found.
```
→ Claude clusters observations into named themes, identifies tensions, and produces a POV statement grounded in the data.

**Plan an ideation session:**
```
We have 8 people, 90 minutes, and this HMW question:
"HMW help remote caregivers confirm medication was taken
without burdening the patient?"
Design the full session: methods, timing, warm-up,
and how we converge at the end.
```
→ Claude returns a complete agenda with facilitation instructions, materials list, a warm-up activity, brainstorm rounds, and a structured convergence method.

**Critique a brief before building:**
```
Here's our design brief: [paste].
We're about to start wireframing next week.
What assumptions are we making that we haven't tested yet?
```
→ Claude identifies phase-skipping risks, untested hypotheses, and the minimum research needed before wireframing is justified.

**Decide iterate vs. ship:**
```
We ran 5 usability tests on our prototype. Here's what we found:
[paste findings].
Should we iterate or move to implementation?
```
→ Claude applies the severity framework (critical / moderate / minor) and returns a clear decision with rationale.

**Adapt for a tight deadline:**
```
We have one week before presenting a direction to leadership.
We haven't spoken to any users yet. What's the minimum viable
Design Thinking process we should run in 5 days?
```
→ Claude returns a compressed day-by-day plan: which phases to abbreviate, which to protect, and what to skip at your own risk.

---

### Complex: Full project or workshop

**Startup: validate before building anything**
```
I'm a founder. My hypothesis: busy parents of school-age kids
forget to give their children daily medication, and it causes
anxiety and real health risk. I want to build a mobile app.

Before I write a single line of code or design a single screen,
walk me through how to validate this properly: who to talk to,
what to ask, what I'm trying to prove or disprove, and what I
need to know before I'm justified in building anything.
```
→ Claude returns a complete pre-build validation plan: problem interview guide, recruiting criteria, what "validated" looks like, and what disconfirms the hypothesis.

**Service designer: redesign from zero research**
```
I'm a service designer at a regional hospital. We've been asked
to reduce patient no-shows for outpatient appointments,
currently running at 22%. We have no prior research on why
patients don't show up.

I have 3 weeks and access to patients, frontline staff,
and scheduling data. Walk me through the full process:
who to talk to, what to observe, how to synthesize findings,
and how to frame a problem statement that leads to a real
solution: not just a reminder notification.
```
→ Claude maps the full 3-week process across all actors (not just patients), flags the most common assumption traps in no-show research, and produces a research plan with a synthesis workshop structure.

**Design sprint: one day, cross-functional team**
```
I'm running a design sprint with 7 people:
2 engineers, 2 designers, 1 PM, 1 customer success, 1 exec sponsor.
We have one full day.

Our HMW question:
"HMW make it easier for freelancers to follow up on overdue
invoices without damaging the client relationship?"

Give me the full day agenda: what we do each hour, what methods
we use, what materials we need, how we handle the exec in the room,
and what we should have produced by end of day.
```
→ Claude returns an hour-by-hour agenda with facilitation notes, a strategy for preventing the exec from collapsing ideation early, and a clear end-of-day output definition.

**Executive workshop: reframe before committing**
```
I'm facilitating a half-day innovation session for 12 executives
at a retail bank. The brief is to "improve the mortgage experience."
The problem: leadership already thinks the answer is a better app.

My job is to help them see the full picture before they commit.
Design the session: how I open it, how I build empathy without
them dismissing it, how I get them to a human-centered problem
statement, and how I protect the ideation phase from their
authority narrowing the options too early.
```
→ Claude designs the full workshop with an empathy-building opener that works with executives, a reframing exercise that surfaces the human problem behind the business brief, and facilitation moves for managing authority in ideation.

---

## The Three Lenses

Every design decision balances three questions:

- **Desirability**  Do people want this? Does it fit their lives and actual needs?
- **Feasibility**  Can it be built? What does technology currently allow?
- **Viability**  Is it sustainable? Does it make economic and organizational sense?

Strong design lives at the intersection of all three.

---

<div align="center">

Built as a [Claude Code](https://claude.ai/claude-code) skill · v1.0.0

</div>
