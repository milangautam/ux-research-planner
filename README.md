# UX Research Planner

A [Claude Code](https://claude.ai/code) skill for building complete, executable UX research plans. Works module by module, with a validation checkpoint at every stage.

## What it does

The skill acts as a senior UX research strategist. Give it a product and a problem statement, and it walks you through the full planning process. Every output can be handed directly to a team and executed without ambiguity.

**Primary framework:** OMSEP (Objectives, Methodology, Scope, Essentials, Protocol)

It also supports alternative frameworks and handles partial requests like "I just need screener questions" or "write me a discussion guide" without forcing you through the full flow.

## Modules

| # | Module | What it produces |
|---|--------|-----------------|
| 1 | **Intake** | Understands your context, constraints, user groups, and output preference |
| 2 | **Objectives** | Research goals and questions, tagged by type and mapped to methods |
| 3 | **Methodology** | Finalized methods with rationale, pros, cons, and which questions they answer |
| 4 | **Scope** | What is and isn't being tested: flows, screens, features, and user groups |
| 5 | **Essentials** | Roles, product, deliverables, tools, timeline, and cost structure |
| 6 | **Protocol** | Full moderator discussion guide with bias-checked questions |
| 7 | **Recruitment Plan** | User group profiles, participant counts, recruitment methods, and edge cases |
| 8 | **Screeners** | Screener questions per group with accept/reject tags and a rejection message |
| 9 | **Package** | Compiles everything into in-conversation text or downloadable Word document(s) |

## How to use it

Load the skill in Claude Code and try any of these:

- `Plan a UX study for [product/problem]`
- `Create a research plan`
- `Write a discussion guide for [context]`
- `Write screener questions for [user group]`
- `Help me define research objectives`
- `I need a recruitment plan for [study]`

Or just describe your product and what you're trying to learn. The skill will pick it up.

## Features

**Validation at every stage.** The skill pauses after each module and asks for confirmation before moving forward. Misalignments are caught early, not at the end.

**Bias checking.** Every question in the discussion guide is checked against bias rules before it's presented. No leading questions, no assumed feelings, no UI element naming.

**Multiple user groups.** Fully supported. The skill generates separate outputs per group where the tasks or criteria differ.

**Partial requests.** You don't have to start from scratch. Ask for just the screeners, just the discussion guide, or just the recruitment plan. The skill asks only the minimum context needed and offers to continue with the full plan afterward.

**Output flexibility.** Receive outputs as in-conversation text, downloadable Word document(s), or both. Word documents can be a single master file or separate files per module for distribution to different team members.

**Constraint-aware.** All recommendations adapt to your budget, timeline, team size, geography, and available tools.

## Reference files

The skill reads from five reference documents at runtime:

| File | Purpose |
|------|---------|
| `references/frameworks.md` | Alternative research frameworks beyond OMSEP |
| `references/methodologies.md` | Full landscape of UX research methods with trade-offs |
| `references/discussion-guide.md` | Discussion guide structure, bias rules, and moderator guidance |
| `references/recruitment.md` | Recruitment methods, selection logic, and over-recruitment strategy |
| `references/screeners.md` | Screener question types, best practices, answer tagging, and templates |

## Installation

Clone this repository into your Claude Code skills directory or reference it directly via the skill path in your Claude Code configuration.

```bash
git clone https://github.com/milangautam/ux-research-planner.git
```
