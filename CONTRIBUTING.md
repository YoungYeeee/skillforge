# Contributing to SkillForge

Thank you for helping build a better way to learn with AI.

---

## What We Need Most

1. **New skill modules** — areas not yet covered
2. **Domain reviewers** — experts who can evaluate modules in their field
3. **Improvements to existing modules** — better prompts, clearer rubrics, more exercises
4. **Translations** — making modules accessible in more languages
5. **Real learner feedback** — what worked, what didn't, how long things actually took

---

## Before You Contribute

Read [docs/philosophy.md](./docs/philosophy.md) first. It's short. The key principle that disqualifies most contributions:

> **Every prompt must make itself eventually unnecessary.**

If your prompt is designed to do the work *for* the learner rather than *with* the learner, it doesn't belong here. That's what every other prompt collection is for.

---

## Becoming a Domain Reviewer

This is one of the most valuable ways to contribute.

Every skill module requires at least one **domain expert review** before merging. Reviewers ensure that content is accurate, representative of real expert practice, and that mastery criteria actually mean something.

**To apply:** Open an issue using the [Apply to be a Reviewer](./.github/ISSUE_TEMPLATE/reviewer-application.md) template.

You'll be added to [REVIEWERS.md](./REVIEWERS.md) and tagged on PRs in your domain. No minimum commitment — review when you have capacity, decline when you don't.

See [docs/review-process.md](./docs/review-process.md) for the full review system.

---

## How to Submit a New Skill Module

### 1. Check if it's needed

Search existing modules and [open issues](https://github.com/yourusername/skillforge/issues). If someone's already working on it, contribute to that instead.

### 2. Open an issue first

Before building, open a "Skill Proposal" issue with:
- The skill you want to add
- Why it belongs in SkillForge (not just "it's useful")
- Your proposed learning objectives (what will learners be able to do?)
- Your rough outline of the learning path

This gets early feedback before you invest significant time.

### 3. Build using the template

Copy `skills/_template/` to `skills/[skill-name]/`. Fill in every section — don't leave template placeholders.

**Required for a complete module:**
- [ ] `README.md` with all sections filled
- [ ] `prompts/01-self-assessment.md`
- [ ] At least 2 more prompts
- [ ] At least 1 exercise
- [ ] Graduation conditions that are specific and testable

### 4. Test it yourself

Use the module yourself before submitting. Report how long it actually took and whether the graduation conditions are achievable.

### 5. Submit a Pull Request

PR description should include:
- What skill this teaches
- Who it's for (prerequisites, target learner)
- How you tested it
- Any known gaps or limitations
- Suggested domain reviewer (optional — maintainers will find one if you don't know anyone)

### 6. Expert Review

After your PR is submitted, a maintainer will:
1. Assign domain labels
2. Invite a domain reviewer from [REVIEWERS.md](./REVIEWERS.md)
3. Optionally invite a pedagogy reviewer

The reviewer uses the [review checklist](./.github/PULL_REQUEST_TEMPLATE/skill-review.md). Expect 1–2 rounds of feedback. Reviews typically complete within 2–3 weeks.

Your module will be credited with the reviewer's name and credential when it merges.

---

## Review Criteria

All modules are reviewed against these standards:

**Does it teach or do?**
Prompts must coach learners, not complete work for them. "Write me a good argument" fails. "Ask me questions until I can construct a good argument myself" passes.

**Are the objectives concrete?**
"Understand X" fails. "Analyze X and identify Y without assistance" passes.

**Are graduation conditions testable?**
"Feel confident about X" fails. "Do X without AI assistance and meet these criteria" passes.

**Is the learning path logical?**
Skills should build on each other. The path should be sequenced so each step prepares you for the next.

**Is it honest about AI's role?**
Don't oversell what AI can teach. Some skills require human feedback, real-world practice, or things AI simply can't provide. Acknowledge this.

---

## Translation Guidelines

Translations live alongside originals in the same directory:

```
skills/critical-thinking/
├── README.md           (English — source of truth)
├── README.zh.md        (Simplified Chinese)
├── README.ja.md        (Japanese)
└── prompts/
    ├── 01-self-assessment.md
    ├── 01-self-assessment.zh.md
    └── ...
```

**Translation rules:**
- Translate meaning, not words. Prompts should feel natural in the target language.
- Maintain all structural elements (sections, rubrics, graduation conditions)
- Note if a cultural adaptation was made and why
- Add the language to the module's README language list

---

## Code of Conduct

Be direct. Be honest. Assume good intent.

If you disagree with a design decision, open an issue and explain your reasoning. We'll discuss it.

---

## Questions?

Open a [GitHub Discussion](https://github.com/yourusername/skillforge/discussions). We're friendly.
