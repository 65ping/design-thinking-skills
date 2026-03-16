# Design Thinking

A Claude Code skill that guides any team through the Design Thinking methodology — from the first user conversation to a shipped solution. Built for product designers, UX researchers, service designers, product managers, entrepreneurs, and business leaders.

## Install

```bash
# Global install — available across all your projects
git clone https://github.com/65ping/design-thinking.git ~/.claude/skills/design-thinking

# Or per-project
git clone https://github.com/65ping/design-thinking.git .claude/skills/design-thinking
```

Claude Code detects the skill automatically. No configuration needed.

---

## Core Framework

The skill guides teams through six phases — used in sequence, in parallel, or looped back as new insight demands:

1. **Empathize** — User interviews, field observation, and empathy maps to understand what people actually do, not what they say they do
2. **Define** — Affinity diagramming, Point of View statements, and How Might We questions to frame the right problem before generating any solutions
3. **Ideate** — Structured brainstorming, SCAMPER, Brainwrite, and convergence methods to generate and select concepts worth testing
4. **Prototype** — Lowest-cost artifact that answers one specific question — paper sketch to service blueprint, matched to what you need to learn
5. **Test** — Moderated usability testing, think-aloud protocol, and behavioral synthesis to validate or invalidate your assumptions with real people
6. **Implement** — Handoff documentation, implementation review, and post-launch learning so the solution actually reaches users

The process is non-linear by design. Looping back is not failure — it is the methodology working as intended.

## The Three Lenses

Every design decision should balance three questions:

- **Desirability** — Do people want this? Does it fit their actual lives and needs?
- **Feasibility** — Can it be built? What does technology currently allow?
- **Viability** — Is it sustainable? Does it make economic and organizational sense?

Strong design lives at the intersection of all three. Designing for only one produces work that looks good but fails in the real world.

## Key Features

The skill detects what phase you are in and what you need — planning, artifact generation, facilitation, or critique — and responds accordingly. It produces structured phase plans, ready-to-fill artifacts (empathy maps, POV statements, HMW questions, prototype briefs, test scripts), complete workshop facilitation scripts, and grounded design critiques. Every output is adapted to your role, project context, and timeline.

Role-specific guidance covers product and design teams, entrepreneurs and early-stage startups, and business and strategy leaders. The reference files include seven artifact templates, four workshop facilitation scripts, and detailed service design tools including service blueprints, journey maps, and ecosystem maps.

---

## Prompt Examples

The most effective way to use this skill is to tell Claude what phase you are in and what you need. The skill handles the rest.

### Simple — Single Phase

**Start a research plan:**
```
I need to run empathy interviews for a fintech app redesign.
Who should I talk to and what should I ask?
```

**Generate an artifact:**
```
Write a POV statement for a nurse managing medication
handoffs between shifts at a busy hospital.
```

**Generate HMW questions:**
```
Here's my POV statement: [paste].
Give me 10 How Might We questions I can use for ideation.
```

**Choose a prototype type:**
```
We want to test whether users understand our new onboarding flow
before we build it. What kind of prototype should we make?
```

**Prepare a test script:**
```
I'm running a usability test on a checkout redesign tomorrow.
Write me a test script with 3 tasks and the right facilitator prompts.
```

**Evaluate a problem statement:**
```
Is this a good problem statement? "Users need a better dashboard."
```

---

### Intermediate — Multi-Step

**Synthesize research into a problem statement:**
```
I interviewed 6 caregivers of elderly parents about managing medications remotely.
Here are my notes: [paste]. Help me run an affinity diagram and write a POV statement.
```

**Plan an ideation session:**
```
We have 8 people, 90 minutes, and this HMW question:
"HMW help remote caregivers confirm medication was taken without burdening the patient?"
Design the session for us — methods, timing, warm-up, and how we'll converge at the end.
```

**Critique a design brief before building:**
```
Here's our design brief: [paste].
We're about to start wireframing. What are we assuming that we haven't tested yet?
```

**Decide whether to iterate or ship:**
```
We ran 5 usability tests on our prototype. Here's what we found: [paste].
Should we iterate or move to implementation?
```

**Adapt for a tight timeline:**
```
We have one week before we have to present a direction to leadership.
We haven't spoken to any users yet. What's the minimum viable process we should run?
```

---

### Complex — Full Project or Workshop

**Full early-stage startup validation:**
```
I'm a founder. My hypothesis: busy parents of school-age kids forget to give
their children daily medication, and it causes anxiety and health risk.
I want to build a mobile app. Before I write a single line of code or design
a single screen, walk me through how to validate this properly —
who to talk to, what to ask, what I'm trying to prove or disprove,
and what I need to know before I'm justified in building anything.
```

**Service redesign from scratch:**
```
I'm a service designer at a regional hospital. We've been asked to reduce
patient no-shows for outpatient appointments — currently running at 22%.
We have no prior research on why patients don't show up.
I have 3 weeks and access to patients, frontline staff, and scheduling data.
Walk me through the full process: who I should talk to, what I should observe,
how to synthesize what I find, and how to frame a problem statement that
will actually lead to a solution — not just a reminder system.
```

**Design sprint facilitation plan:**
```
I'm running a design sprint with a cross-functional team of 7 people
(2 engineers, 2 designers, 1 PM, 1 customer success, 1 exec sponsor).
We have one full day. Our HMW question is:
"HMW make it easier for freelancers to follow up on overdue invoices
without damaging the client relationship?"
Give me the full day agenda — what we do each hour, what methods we use,
what materials we need, how we handle the exec in the room,
and what we should have produced by end of day.
```

**Innovation workshop for a leadership team:**
```
I'm facilitating a half-day innovation session for 12 executives at a retail bank.
The brief is: improve the mortgage application experience.
The problem: leadership thinks the answer is a better mobile app.
My job is to help them see the full picture before they commit to a solution.
Design the session — how I open it, how I build empathy without them dismissing it,
how I get them to a human-centered problem statement, and how I protect the ideation phase
from their authority collapsing the options too early.
```

**Existing product — diagnosis and next steps:**
```
Our user activation rate dropped from 61% to 44% over the last quarter.
We have session recordings, 3 months of support ticket data,
and NPS verbatims from 200 users. We also have one engineer available for 2 weeks.
Help me use the Design Thinking process to diagnose what's wrong,
decide what to test, build the right prototype, and measure whether
our fix actually worked — all within that constraint.
```

---

## Who It's For

**Product & design teams** — Product designers, UX researchers, UI designers, service designers, and product managers applying the methodology inside sprint cycles, design critiques, and product strategy. Balances depth with velocity, frames decisions around user evidence rather than preference.

**Entrepreneurs and startups** — Founders using Design Thinking for customer discovery and pre-launch validation before committing to build. Maps directly to Lean Startup thinking and addresses the core failure mode: building what you want, not what users need.

**Business and strategy leaders** — Executives running innovation workshops, redesigning services, or reframing strategy questions as human-centered problems. Turns "increase retention by 15%" into an insight worth acting on.

---

## What's Inside

```
design-thinking/
├── SKILL.md                      ← Main skill (auto-loaded by Claude Code)
│   ├── 6-phase methodology
│   ├── Role-specific guidance
│   ├── Project context guide
│   └── 20+ anti-patterns
│
└── reference/
    ├── templates.md              ← 7 ready-to-fill artifacts
    ├── facilitation-methods.md   ← 4 workshop facilitation scripts
    └── service-design.md         ← Service blueprint, journey map, ecosystem map
```
