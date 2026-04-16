# Feature Page Skill for Claude Cowork

A 3-phase workflow that turns raw research into elite feature page briefs — ready for SEO specialists, copywriters, and CRO experts to execute. Covers research intake, page strategy, and heuristic QA critique. Each phase saves a standalone document.

---

## What It Does

Most feature pages fail because they're built on assumptions — internal product language, guessed buyer problems, and copy that any competitor could paste on their own site. This skill fixes the inputs before anyone writes a word.

It runs a structured research and analysis workflow across three phases. Each phase produces a document a specialist can pick up and work from independently. The skill does not write your page. It builds the brief that makes your experts faster and more precise.

---

## Phases and Outputs

### Phase 1 — Research Intake
Pulls product truth, voice-of-customer data, competitor intelligence, behavior analytics, and SEO demand data from connected tools. Audits any existing research files you provide before starting.

Produces two documents:
- **`[feature]-research-intake.md`** — Buyer problem summary, product truth, capabilities vs. differentiators, behavior insights, FAQ candidates, and a full page inputs brief.
- **`[feature]-seo-analysis.md`** — Keyword landscape, GSC data, intent mapping, competitor ranking analysis, demand vs. internal language gaps, and prioritized SEO recommendations. Structured for direct handoff to an SEO specialist.

### Phase 2 — Strategy and Structure
Turns the research into a page strategy, narrative arc, section outline, and messaging system.

Produces:
- **`[feature]-strategy-and-structure.md`** — Page classification, narrative tension, section outline with each section annotated by job and key message, hero options, claims to prove, claims to remove, and prototype notes.

### Phase 3 — QA and Critique
Stress-tests a draft page through two heuristic lenses plus a full messaging and copy critique.

- **Nielsen's 10 UX Heuristics** adapted for landing pages — covers visibility, consistency, cognitive load, and scannability.
- **CXL/Wynter CRO Heuristics** — covers clarity, value proposition, friction, anxiety reduction, social proof relevance, and mobile conversion path.

Produces:
- **`[feature]-qa-critique.md`** — Heuristic findings from both lenses, a combined severity table (Critical / Major / Minor) sorted for handoff to a developer or designer, messaging critique, prioritized changes, and a final readiness assessment.

---

## How It Works

At the start of each session the skill asks:
- Which phase(s) to run and how much to complete in one session
- Where to save output documents
- Whether you have an existing research folder to review

If you point it at an existing folder, it narrates every file it finds — filename, what it contains, and whether it's Usable, Partial, or Not usable as a research input — before doing anything else.

It checks which MCPs are connected at the start of each phase, lists what's missing and why it matters, and asks whether to wait for connections or proceed and flag the gaps. Every claim in every output is labeled: **Verified** (directly retrieved), **Likely** (strong indirect evidence), or **Unconfirmed** (needs validation).

---

## Compatible Data Sources

The skill works with any of the following if connected via MCP:

| Tool | Used For |
|---|---|
| Notion / Google Drive | Internal docs, briefs, existing drafts |
| Intercom or equivalent | Support voice-of-customer |
| Ahrefs / Semrush / GSC | Keyword demand and SEO data |
| Canny or equivalent | Feature request voice-of-customer |
| Mouseflow / FullStory / Clarity | Behavior analytics for existing pages |
| Web fetch | Competitor pages, public docs, help center |

If a tool isn't connected, the skill asks you to paste in exported data or flags the gap in the output with its implications. It never silently skips a data source.

---

## Installation

1. Download `feature-page.skill`
2. Open Claude Cowork
3. Go to Skills → Install from file
4. Select the downloaded `.skill` file

Once installed, trigger it by asking Claude to build, improve, or critique a feature page.

---

## Requirements

- Claude Cowork
- At least one connected MCP for data retrieval (the skill will work with fewer connections but will flag what's missing)

---

## About

Built by [Eddie](https://www.linkedin.com/in/yourhandle) as a personal contribution to the B2B marketing community. If you use it, improve it, or have feedback, open an issue or reach out on LinkedIn.
