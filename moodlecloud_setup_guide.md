# Groundwork — MoodleCloud Setup Guide
### How to stand up the path in the accessible environment, concretely
*From Accessible Learning Labs · Companion to the Planning Document and Module Design Standard*

---

## 0. The shape of the decision

Start on **MoodleCloud** (managed, no servers to run) to build and validate, and **graduate to partner-hosted Moodle later** only when a specific need appears. The trigger for graduating is almost always one of: the Brickfield accessibility toolkit, PDF certificates, a fully custom theme, or more than ~750 learners. Until then, MoodleCloud's core gives you an externally audited, accessible shell — which is the one thing you can't compromise — without the maintenance burden. Your courses export cleanly from MoodleCloud and import into a self-hosted/partner Moodle when you move, so this is a one-way door you can walk through later without losing work.

---

## 1. Which plan

MoodleCloud tiers scale by learner count. Two things determine your starting tier:

- **You can only sell via Stripe on the Small plan and up.** PayPal is available more broadly, but Stripe (the cleaner checkout) starts at Small. So your first *paid* tier is Small, not the entry Starter/Mini.
- **Capacity caps at ~750 users**, with annual fees roughly $170–$2,140 depending on size. Confirm current tier names and prices in the MoodleCloud portal — they shift.

Suggested path:
1. **Free 28-day trial** — build the skeleton and the reusable module template (section 4). No cost, no commitment.
2. **Small or Medium plan** once you're ready to enroll paying learners and need Stripe. Sized to your expected early numbers (well under 750).
3. **Partner-hosted Moodle** when a graduation trigger hits.

---

## 2. Site and course structure

Map *Groundwork* onto Moodle objects like this:

- **Your MoodleCloud site** = the *Groundwork* academy (branded with your colours, logo, name).
- **Two courses, not seven:**
  - **"Groundwork: Start Here" (free)** — contains *Bearings* + *Survey*. Open/self-enrolment. This is your on-ramp and lead magnet, the thing you funnel people into from your site or a Udemy intro.
  - **"Groundwork: The Full Path" (paid)** — contains *Footprint → Blueprint → Frame → Proof → Capstone*. Stripe enrolment. This is the schoolhouse.
- **Inside each course, use the Topics format with one Topic per module.** Each Topic holds that module's full five-phase rhythm as a set of activities.
- **Make it self-paced but sequential** using two core features together: **Activity completion** (mark each activity complete on submission/view) and **Restrict access** (the next module's Topic unlocks when the previous one's key activity is complete). That gives a guided linear path without you being present.

Why two courses rather than one: it cleanly separates the free funnel from the paid product, lets you price and enroll them differently, and keeps the storefront-vs-schoolhouse split you already decided on.

---

## 3. The five-phase rhythm, mapped to Moodle activities

This is the heart of the setup: each phase of your rhythm has a natural Moodle tool. Build this set **once**, then duplicate the Topic for every module so the structure stays identical (consistency engine, meet platform).

| Phase | What it does | Moodle tool(s) |
|---|---|---|
| **Why** — relevance & activation | Frame the scenario; surface prior knowledge; pose the self-coaching questions | A **Page** for the scenario + a **Choice** or **Feedback** activity for the prior-knowledge/self-coaching prompts (low-stakes, ungraded) |
| **See** — concept-building | Teach the concept multi-modally; show worked + anti-example | **Page** or **Book** for text; captioned **video**; **H5P** (built into Moodle) for an interactive worked/anti-example |
| **Try** — active & experiential | Learner produces the module's portfolio artifact | **Assignment** (file or online-text submission) — the artifact upload point |
| **Share** — social learning | Put the artifact in front of another person | **Workshop** for structured peer assessment *when learner volume supports pairing*; otherwise a **Forum** plus a "share-into-context" prompt (show a colleague/SME) — see note below |
| **Reflect** — integration & transfer | Self-review against the rubric; transferable question; bridge | A **Rubric** (Moodle advanced grading) attached to the Try assignment so learners can self-apply it; a short reflective **Assignment** or journal prompt; completion gate to the next module |

**The Share note.** Moodle's **Workshop** activity is purpose-built for your Share phase: learners submit work and assess each other against a rubric. The catch is that it needs enough learners active at the same time to pair them — which is in tension with self-paced enrolment, where people arrive at different times. So:

- **Baseline (always works):** a **Forum** for asynchronous peer exchange + the "share-into-context" prompt that sends the learner to show their artifact to a colleague, SME, or manager in their own setting. No timing dependency.
- **Upgrade (when volume allows):** turn on **Workshop** for true peer review, or run it in periodic batches.

This is the platform-level version of the open decision flagged in the planning document — Moodle gives you both options; you choose based on volume.

---

## 4. Accessibility configuration (the on-brand part)

On MoodleCloud core, without any plugins, you already get:

- **An externally audited, WCAG 2.2 AA shell** — the player, navigation, and quiz engine you can't otherwise control.
- **The built-in editor accessibility checker** — it flags issues as you author and requires you to add alt text to images or mark them decorative, so screen readers handle them correctly.
- **The accessible default theme (Boost)** — brand it with your colours and logo through theme settings; check your colour choices for contrast.

Your authoring discipline on top of that:
- Upload **corrected caption files (SRT)** for every video — auto-captions alone are not WCAG-conformant.
- Use **real heading styles** in the editor (not bold text) so structure is navigable.
- Keep **consistent navigation** and clear Topic/section names.
- Write **link text that describes its destination**, not "click here."

When you graduate to partner-hosted Moodle, add:
- **Brickfield Accessibility Toolkit** (a plugin) for automated *course-wide* accessibility reports and remediation — this is what Moodle Academy uses to check courses before release.
- **ReadSpeaker** (a certified integration) for "click and listen" text-to-speech with synchronised highlighting and high-contrast mode.

Skill-up resource: Moodle Academy's free **Accessible Teaching Basics** and **Introduction to Accessibility** courses — take them both as research and as a model of accessible course structure.

---

## 5. Commerce and enrolment (storefront → schoolhouse)

- **Free course:** set enrolment to **self-enrolment** (open) or guest access. This is the funnel entry.
- **Paid course:** enable the **Stripe enrolment** method (Small plan or above). Learner pays → auto-enrolled. Set the price here.
- **Funnel:** market on your own site or a Udemy intro → drive to the free *Start Here* course → upsell to the paid *Full Path* at the end of *Survey*.
- Keep the actual learning in Moodle regardless of where you market; the storefront can live anywhere, the schoolhouse stays in the accessible environment.

---

## 6. Credentials

- **Badges are core Moodle** — you can issue a badge per module and a path-completion badge on MoodleCloud today, no plugin needed. Good for motivation and a visible early win.
- **PDF certificates need a plugin** (e.g., Custom Certificate), so they belong to the partner-hosted stage. Moodle Academy's own model is a useful template: badges free, a formal certificate optionally purchasable.
- This maps to the "credential" open decision in the planning document: you can launch with badges now and add certificates later if learners want them.

---

## 7. Build and launch sequence

1. **Trial (free, 28 days):** create the site; build one module's five-phase activity set; duplicate the Topic to confirm the template replicates cleanly.
2. **Build the free on-ramp:** *Bearings* + *Survey*, fully accessible. Test it as a learner using a student test account and the Moodle mobile app.
3. **Upgrade to Small/Medium; turn on Stripe; build the paid path:** *Footprint → Blueprint → Frame → Proof → Capstone*.
4. **Add the social layer:** Forum + share-into-context everywhere; switch on Workshop where volume supports it.
5. **Pilot quietly** with one or two people who already ask you for mentorship.
6. **Graduate to partner-hosted Moodle** only when a real trigger arrives (Brickfield, certificates, custom theme, or >750 learners). Export from MoodleCloud, import to the new host.

**Reuse tip:** build the module Topic once and use **course Import / duplicate** to stamp the same five-phase structure into every module. The Module Design Standard's template becomes a literal, repeatable Moodle object — that's how you stay consistent without rebuilding from scratch each time.

---

## 8. Two examples to look up

1. **Mount Orange School** — `school.moodledemo.net`. Moodle's official demo, running the current version. Log in as `student` / `moodle` to feel the learner experience, or `teacher` / `moodle` to see the build side. It resets every hour, so explore freely. This answers: *what does Moodle feel like to use?*

2. **Moodle Academy** — `moodle.academy`. A real, public, polished Moodle site delivering free self-paced professional learning to educators and instructional designers, with badges and optional certificates — and free accessibility courses. Enroll and take one as a learner. This answers: *what does my own product look like when it's done well on this platform?* It is, in effect, a working reference implementation of *Groundwork*'s delivery model.

(If you want to see the Share phase in action specifically, the Moodle docs for the **Workshop** activity walk through the submission-and-peer-assessment cycle.)
