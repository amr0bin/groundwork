# Groundwork — Path Architecture
### One engine, escalating problems: how the full learning path could be structured
**From Accessible Learning Labs · Companion to the Planning Document, Module Design Standard, and MoodleCloud Setup Guide**

*Tagline: Learning design from the ground up — accessibility built in, not bolted on.*

> **What this document is for.** The planning document defines the *path*; the Module Design Standard locks the *module*; the setup guide handles the *platform*. This one sits between them and answers a structural question that surfaced once we asked whether early-career designers get to practice solving the problems organizations actually hire them for: **how should the path be layered so it covers enough without over-building?** It proposes an architecture and surfaces the decisions that architecture forces. Every decision is flagged inline as **◆ Decision** so you can find and resolve them in one pass.

---

## 1. The one idea that organizes everything

There are two different axes hiding inside the question "are we covering what early-career designers need?", and keeping them separate is most of the clarity.

- **The workflow axis** — the lifecycle of *one project*: Bearings → Survey → Footprint → Blueprint → Frame → Proof → Capstone. This is a *method*. It's the same regardless of what problem you point it at.
- **The problem-type axis** — the *kinds* of problems organizations hand a designer: the top 10 (convert expertise, compliance, consistency, admin burden, accessibility, behaviour change, fragmented systems, tool adoption, ROI, culture/change).

The spine is not a list of the top 10. The spine is **the engine that solves any of them.** This reframe changes the build strategy completely. "Cover all 10 as practice" means adding modules until the list is exhausted — which multiplies the build and shreds the portfolio. "Feed harder problems into the one engine" means building the engine once and escalating the difficulty of what you run through it.

**The whole architecture follows from that single move: build one engine, escalate the problems.**

---

## 2. The five structural layers

The path is best understood as five nested layers. Naming them prevents the drift that happens when "course," "module," and "outcome" get used interchangeably.

| Layer | What it is | The rule that governs it |
|---|---|---|
| **Engine** | The five-phase rhythm (Why → See → Try → Share → Reflect) | Fixed. Built once. Never changes. *(This is the Module Design Standard.)* |
| **Spine** | The seven building-stage courses, in lifecycle order | Fixed sequence. Each stage = one course. |
| **Course** | One stage of the spine (e.g. *Footprint*) | 1–3 verifiable learning outcomes. *Ceiling, not a target.* |
| **Outcome → Module** | Each verifiable outcome gets one full 5-phase module | Modules produce *components*, not standalone artifacts. |
| **Artifact** | What the learner walks away holding | **One portfolio-grade artifact per course.** Components roll up into it. |

And running *across* all of this, a sixth dimension — **Level** (beginner / intermediate / advanced) — which is **not new content** but the same engine run on harder cases. Section 6 covers it.

The discipline that keeps this sane is one sentence: **one engine, components roll up to one artifact per course, levels are case packs.** Without it, the structure quietly becomes levels × courses × modules × phases — sixty-plus five-phase passes — and collapses under its own weight.

---

## 3. Courses, outcomes, and the artifact-proliferation trap

Promoting each spine *stage* to a *course* with up to three outcomes is the right structure — but it carries one real risk, and the architecture has to defend against it deliberately.

**The risk.** If every outcome spawns its own standalone portfolio artifact, a seven-stage path with three outcomes each produces ~20 artifacts. The portfolio's entire power (planning document §8) is that it's **one coherent project told end to end** — six artifacts, not twenty. Proliferation destroys the through-line that makes the portfolio worth paying for.

**The fix.** A course can hold multiple outcomes and multiple modules, but they **assemble into a single portfolio-grade artifact.** Sub-modules produce *components*; the course produces the *deliverable*.

*Footprint* is the clean illustration. It legitimately carries three distinct outcomes:

1. Draw a defensible project boundary (scope).
2. Negotiate with an SME / requester under pressure.
3. Get accessibility into scope, budget, and timeline — and defend it against "later."

Each can be a genuine 5-phase module with its own self-coaching questions and its own productive struggle. But all three roll up into **one Scoped Design Brief** — the single artifact *Footprint* contributes to the portfolio. Three outcomes, three modules, one artifact.

Most stages won't need three. *Bearings* stays a single light orientation module (as already drafted). *Survey* is one weight-bearing module producing the Diagnosis Memo. "Up to 3" is a **ceiling driven by genuinely distinct outcomes, never a quota to fill.**

> **◆ Decision 1 — Outcome count per course.** Confirm the ceiling is three *verifiable* outcomes, and that the number is set by how many genuinely distinct, provable competencies a stage contains — not by a desire for symmetry across courses. Lopsided is correct here: *Bearings* has one, *Footprint* has three.

> **◆ Decision 2 — One artifact per course.** Confirm the rule that sub-modules produce components that assemble into a single portfolio-grade artifact per course. This is the rule that protects the portfolio's coherence. The alternative — one artifact per outcome — is on the table but trades the end-to-end story for granularity.

**What "verifiable" means here.** An outcome is verifiable when it is *provable in the artifact*. "Distinguishes a learning problem from a non-learning performance gap and defends the distinction in writing" is verified by the Diagnosis Memo itself. The artifact is the verification. No separate test is needed — which is exactly what Section 5 builds on.

---

## 4. Mapping the top 10 — what the spine covers, and what it doesn't

Holding the top 10 against the seven stages honestly shows a clear pattern in the gaps.

| Status | Top-10 problems | Where it lives (or doesn't) |
|---|---|---|
| **Covered deeply** | Convert expertise; Consistency across audiences; Accessibility; Behaviour change & performance; Demonstrating value / ROI | Blueprint; Blueprint + "all learners"; the accessibility thread throughout; Survey + Proof; Proof |
| **Partial — surfaced by scenario, not yet taught as its own competency** | Compliance & risk; Tool / practice adoption; Culture & change | A *domain* layered onto any stage; Frame covers tool *choice* but not change management; Footprint covers stakeholders but not deep change work |
| **Genuinely uncovered** | Reducing administrative burden; Navigating fragmented systems | No natural home in the project lifecycle |

The tell is in the right two columns: what's missing clusters around **organizational, systems, and change** problems. And that is **not beginner work** — it's mid-career work. An early-career designer doesn't need to *master* fragmented-systems integration or the ROI of a change-management programme. They need to master the engine that lets them eventually take those on, plus enough *exposure* to see the terrain and locate themselves on it.

This produces a firm recommendation:

> **◆ Decision 3 — Scope of the beginner path against the top 10.** Recommendation: **do not** treat "give beginners real practice on all 10" as a goal. Cover the *engine* deeply; *map* the 10 so learners see the landscape; *stage* the organizational/systems/change problems for the advanced level (Section 6) as exposure, not mastery. Chasing all 10 at beginner level is the over-complication to avoid.

---

## 5. Assessment — testing the content, not the learner

Your instinct — "summative and formative assessments, but only to test whether the content is fulfilling its destiny, not testing the learner" — is the correct inversion, and the existing design already half-implements it. Making it explicit requires recognizing that assessment here has **two audiences**.

**For the learner (formative, ungraded).** The self-coaching questions and the self-review rubric. Their job is diagnostic *for the learner*: they reveal whether the content equipped the learner to do the real thing. Any H5P knowledge-checks live here too — retrieval practice, never gatekeepers.

**For you, the builder (summative — on the content).** The real summative signal is the pattern *across* learners' artifacts: where many learners struggle, stall, or produce weak work tells you whether a module is doing its job. This is your pilot-and-iterate loop. The thing being graded is the *module*, not the person.

**The learner's only real assessment is the artifact** — and ultimately the Capstone portfolio. Nothing gates on a *score*. Progression gates on *artifact submission / activity completion*, which is exactly the MoodleCloud activity-completion + restrict-access model already specified in the setup guide. Success is defined as *"I made a real, defensible, born-accessible thing in my own context,"* not *"I passed."*

> **◆ Decision 4 — Assessment model.** Confirm: (a) no score-based gating anywhere; progression gates on completion/submission; (b) formative instruments (self-coaching questions, self-review rubric, knowledge-checks) are ungraded and learner-facing; (c) the artifact/portfolio is the only summative measure of the learner; (d) cross-learner artifact patterns are *your* summative measure of the content. The one judgment call: whether *any* automated check (e.g. an H5P "which gap type is this?" item) is worth building as retrieval practice, given it must never gate.

---

## 6. Levels — the spiral, not three curricula

The most important structural recommendation: **do not build beginner, intermediate, and advanced as three different bodies of content.** Build the engine once and run it on **escalating cases.** The spine and the five-phase rhythm never change; only the difficulty of the problem you feed them does.

| Level | The case the learner runs the spine on | What it gives | Build cost |
|---|---|---|---|
| **Beginner** | The provided **sandbox case** (the safety-protocol scenario) | Guaranteed quality, lowest barrier, fast early win | The core build — modules + one sandbox case |
| **Intermediate** | The learner's **own real project**, in their own context | Maximum context-fit and portfolio value | A *case pack* + harder self-coaching prompts — **no new modules** |
| **Advanced** | A **hard organizational problem** — compliance, change adoption, a fragmented-systems mess | Exposure to the top-10 gaps from §4, as stretch scenarios | Case pack + possibly a different modality (see below) |

This single move does four things at once:

1. **Houses the missing top-10 problems** (admin burden, fragmented systems, deep change/compliance) without inventing new architecture — they become *advanced scenarios* fed into the existing engine.
2. **Resolves the open "sandbox vs. own project vs. both" fork** from planning document §10 by turning an either/or into a *progression*. The answer to "which case?" becomes "all of them, in sequence."
3. **Keeps the portfolio coherent and makes it stronger.** A learner who climbs all three levels leaves with three complete projects of rising sophistication — a genuinely powerful portfolio narrative.
4. **Reuses the engine**, so the marginal cost of a level is *case packs and harder questions*, not a new curriculum.

A caution worth stating plainly: the **advanced** level may not want to be a full 5-phase pass at all. The organizational/systems/change problems fit the **resource-hub modality** from the second source PDF — short explainer + checklist/template + real example + reflection prompt + common-pitfalls — better than they fit a make-an-artifact module. Advanced might be a *different shape*, or even a separate later product.

> **◆ Decision 5 — The level model.** Recommendation: adopt the spiral (same engine, escalating cases) rather than three distinct curricula. Confirm this, and confirm the resulting build order: **build beginner only for MVP**; add the intermediate own-project case pack once beginner is validated; hold advanced as a deliberate later decision.

> **◆ Decision 6 — Advanced's modality.** If/when advanced is built, decide whether it runs the full five-phase rhythm on hard cases, or shifts to the resource-hub pattern (explainer + checklist + example + reflection + pitfalls) better suited to org-level problems — or folds into a separate offering aimed at a more experienced audience.

---

## 7. What this means for the MVP

Encouragingly, this architecture means the MVP is **almost exactly what was already planned** — the layering mostly formalizes existing instincts rather than adding scope.

The MVP is the **beginner level**, delivered as the two-course funnel the setup guide already specifies:

- **"Groundwork: Start Here" (free)** — *Bearings* + *Survey*, run on the sandbox case.
- **"Groundwork: The Full Path" (paid)** — *Footprint → Blueprint → Frame → Proof → Capstone*, run on the sandbox case.

Then, in order: validate the beginner level with the quiet pilot; add the **intermediate** own-project case pack; hold **advanced** for a deliberate later call. Nothing here changes the platform plan, the Share decision, or the credential decision already in flight — it slots cleanly on top of them.

> **◆ Decision 7 — MVP boundary.** Confirm the MVP is beginner-level only, sandbox case, two-course funnel. The one thing to decide *now* (because it shapes the case-writing you'd start immediately): how polished and how "real" the single sandbox case needs to be, given every beginner learner runs the entire seven-stage lifecycle on it.

---

## 8. The decisions, collected

For a single-pass review:

1. **Outcome count per course** — confirm a ceiling of three *verifiable* outcomes, set by genuine distinctness, not symmetry. *(§3)*
2. **One artifact per course** — confirm sub-modules produce components that assemble into one portfolio-grade artifact. *(§3)*
3. **Beginner scope vs. top 10** — confirm: cover the engine deeply, map the 10, stage org/systems/change problems for advanced. Don't chase all 10 at beginner level. *(§4)*
4. **Assessment model** — confirm completion-gating (no scores), ungraded formative tools, artifact-as-summative; decide whether to build any non-gating knowledge-checks. *(§5)*
5. **Level model** — confirm the spiral (one engine, escalating cases) over three curricula, and the build order it implies. *(§6)*
6. **Advanced's modality** — decide later whether advanced is full five-phase or resource-hub-shaped (or a separate product). *(§6)*
7. **MVP boundary** — confirm beginner-only, sandbox case, two-course funnel; decide how polished the single sandbox case must be. *(§7)*

---

## 9. Why this holds together

The architecture works because it refuses to let "more coverage" mean "more structure." The seven-stage engine already teaches the method that solves *any* of the problems organizations hire designers for. What early-career designers lack isn't exposure to all ten problems at once — it's the *judgment* the engine builds, plus a clear map of the terrain and a way to climb toward the harder problems as they grow. Levels-as-cases gives them that climb without forcing you to build three programs. One artifact per course keeps the portfolio telling one clean story. And assessment that grades the *content* rather than the *learner* keeps the whole thing honest to its own thesis: the proof was never a score — it was always the thing they built, in their own context, accessibly, start to finish.
