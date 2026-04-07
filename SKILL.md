---
name: shengcai
description: Rewrite, restructure, polish, or review existing Markdown drafts into Shengcai Youshu essence posts and 龙珠-style longform posts. Use this when the user gives a written draft, notes, or a Markdown file and wants it reshaped into a high-signal 生财 article with stronger title, opening, structure, insights, and action value.
---

# Shengcai

Use this skill when the user wants to:

- write a 生财有术 / 龙珠风格精华帖
- rewrite an existing Markdown file into a stronger 生财精华帖
- turn raw experience, notes, chat logs, or project results into a publishable longform post
- improve a draft so it reads like a strong 生财精华文章
- extract a title, opening, structure, or key takeaways from a case
- review a draft against 生财-style expectations: concrete, useful, credible, and actionable

This skill merges three layers:

- `龙珠修行营`: how to find real value worth writing
- `龙珠精华文章写作框架List`: the core复盘 skeleton
- large-sample 生财精华 analysis: title patterns, opening rhythm, section flow, closing moves, and high-frequency insight sentence shapes

## Workflow

1. Read the Markdown draft first and identify the fixed facts that must not change.
2. Decide the article type and the strongest promise to the reader.
3. Map the existing material to the merged template before rewriting.
4. Rewrite the title and first two paragraphs early.
5. Rebuild the middle in numbered blocks with evidence, details, and takeaways.
6. Add only a few strong insight sentences; do not inflate with empty language.
7. Save the rewrite as a new Markdown file instead of overwriting the source, unless the user explicitly asks for in-place editing.
8. Close with a reusable lesson and a clear next action for the reader.

Read [references/ultimate-template.md](references/ultimate-template.md) when you need the full fill-in template, title formulas, opening options, paragraph rules, and closing checklist.

## Markdown Rewrite Mode

Default assumption: the user already has a draft, often a `.md` file, and wants it rewritten through the Shengcai template.

When working from an existing Markdown draft:

- preserve all real facts, results, names, tools, dates, prices, and links unless the user asks to change them
- do not invent screenshots, numbers, outcomes, or customer feedback
- prefer reordering, compressing, and reframing over adding unsupported content
- delete repetition, weak throat-clearing, and vague claims
- convert loose narration into: result, context, action, evidence, lesson
- keep the final output in Markdown
- preserve the source draft as-is by default

If the user gives a file path, default to writing a sibling file with the suffix `.shengcai.md`.

Examples:

- `draft.md` -> `draft.shengcai.md`
- `notes/opc.md` -> `notes/opc.shengcai.md`

Only overwrite the original Markdown file if the user explicitly asks for in-place editing.

## Article Type Decision

Choose one primary mode:

- `结果复盘型`: the strongest hook is a concrete result, growth, or business outcome
- `方法教程型`: the main value is a process, SOP, workflow, or teachable system
- `趋势判断型`: the main value is a market/platform/crowd insight and why it matters now
- `认知升级型`: the main value is reframing a problem or showing what actually matters
- `记录成长型`: the main value is a path from confusion to clarity, with lessons others can reuse

If the draft is fuzzy, default to `结果复盘型` or `方法教程型`. These are the easiest to make concrete.

## Raw Material Requirements

Before drafting, make sure the article can answer most of these:

- What exactly happened?
- What result was achieved?
- What problem or constraint existed at the start?
- What actions changed the outcome?
- What mistakes, costs, or failed attempts happened?
- What evidence exists: numbers, screenshots, examples, conversations, comparisons?
- Why should a 生财 reader care?
- What can a reader copy, avoid, or test next?

If these answers are thin, do not beautify. Keep the rewrite conservative and ask for missing facts when the gaps block credibility.

## Writing Rules

- Prefer concrete over complete. One sharp case beats vague coverage.
- Prefer “道 + 术”. Explain both why it works and how it was done.
- Put the result, tension, or usefulness early.
- Use numbered sections once the article enters the main body.
- Keep each section focused on one claim, one action, or one lesson.
- Insert evidence regularly: numbers, examples, screenshots, real dialogue, or before/after comparisons.
- End sections with a takeaway when the point is non-obvious.
- Avoid empty claims like “很重要”“很有帮助” unless followed by proof.
- When rewriting an existing draft, salvage the strongest lines and strongest evidence first.
- If a section has no proof, either trim it or rewrite it as a clearly marked judgment, not a fake certainty.
- If saving to a new file, keep links and relative asset paths compatible with the original file layout.

## Review Mode

When reviewing a draft, check these first:

1. Does the title carry result, object, and reason to read?
2. Do the first two paragraphs establish credibility and relevance?
3. Is the middle organized around decisions, actions, evidence, and lessons instead of loose narration?
4. Are there enough details to make the post believable?
5. Does the ending convert the story into reusable guidance?

If the user asks for a full article from an existing Markdown file, restructure first and only then rewrite sentence-level wording. Save to a new `.shengcai.md` file by default.
