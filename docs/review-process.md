# Review Process

SkillForge uses an **invited expert review** system. Every skill module must be reviewed by at least one domain expert before merging.

This is what separates SkillForge from a random prompt collection.

---

## Why Expert Review?

Anyone can write a prompt. Few people can write a prompt that:
- Accurately reflects how experts in a field actually think
- Catches the specific misconceptions beginners bring to the subject
- Sequences learning in a way that builds genuine understanding
- Defines mastery criteria that are meaningful, not just measurable

A writing prompt reviewed by a professional writer is fundamentally different from one written by someone who once read about writing. We enforce that distinction.

---

## Two Types of Review

### 1. Domain Review
*"Is the content actually correct and representative of expert practice?"*

Conducted by: domain experts in the skill area
Examples: a logician reviews `logical-reasoning`, a senior engineer reviews `debugging-mindset`, a published author reviews `persuasive-writing`

### 2. Pedagogy Review
*"Does the learning path actually teach? Are the prompts Socratic rather than prescriptive?"*

Conducted by: educators, learning designers, or experienced SkillForge contributors
This review can be done by maintainers for early modules, but the goal is to build a dedicated pedagogy reviewer pool.

---

## The Review Flow

```
Contributor opens PR
        │
        ▼
Maintainer assigns domain label(s)
        │
        ▼
Maintainer invites domain reviewer(s) from REVIEWERS.md
        │
        ▼
Reviewer has 14 days to complete review
  (if no response, maintainer invites next reviewer)
        │
        ▼
Reviewer submits review using the checklist
        │
   ┌────┴────┐
   │         │
Approve   Request Changes
   │         │
   │    Contributor revises → re-review
   │
   ▼
Pedagogy review (maintainer or pedagogy reviewer)
        │
        ▼
Merge + add reviewer credit to module
```

---

## What Reviewers Evaluate

Full checklist in [`.github/PULL_REQUEST_TEMPLATE/skill-review.md`](../.github/PULL_REQUEST_TEMPLATE/skill-review.md).

**Domain Review covers:**
- Factual accuracy of all content
- Representative of how experts actually practice this skill
- Common beginner misconceptions are addressed
- Graduation conditions reflect real-world competence

**Pedagogy Review covers:**
- Prompts coach rather than do
- Learning path is sequenced logically
- Each step prepares for the next
- Self-assessment rubric is calibrated (novice vs. expert descriptions are meaningfully different)
- Graduation test is achievable but genuinely challenging

---

## Reviewer Credits

Reviewers are credited in the module they reviewed:

```markdown
*Reviewed by: [@username](link) — [brief credential, e.g., "Professor of Cognitive Psychology, MIT"]*
```

Reviewers are also listed in [REVIEWERS.md](../REVIEWERS.md) with their domain expertise.

Reviewing is voluntary and unpaid. We recognize it in the module, in the repository, and in our community.

---

## Becoming a Reviewer

If you have domain expertise and want to review modules in your field:

1. Open an issue using the **"Apply to be a Reviewer"** template
2. State your domain(s) and relevant background
3. Optionally: link to public work that demonstrates your expertise

Maintainers will add you to REVIEWERS.md within a week.

You can review as many or as few modules as you like. No commitment required. When a module in your domain is submitted, we'll tag you — you can decline if you don't have capacity.

---

## Expedited Review for High-Demand Skills

Some skill areas will have high demand but few available reviewers. In these cases:

- Maintainers may merge with a single review and flag the module as `needs-second-review`
- Modules pending second review are marked with a banner in their README
- The community can vote on prioritizing second reviews via GitHub reactions

---

## Appealing a Review Decision

If you disagree with a reviewer's decision:

1. Respond in the PR with specific, reasoned objections
2. If unresolved after 3 days, a maintainer will mediate
3. In case of genuine expert disagreement, a second domain reviewer will be invited

We expect disagreements to be handled professionally. The goal is a better module, not winning an argument.
