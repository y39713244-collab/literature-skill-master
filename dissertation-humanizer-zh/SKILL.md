---
name: dissertation-humanizer-zh
description: Chinese dissertation and thesis prose polishing skill for reducing obvious AI-generated writing traces while preserving academic rigor, facts, technical terms, citations, argument logic, and original intent. Use when editing Chinese undergraduate, master's, doctoral, journal-style, proposal, literature review, chapter draft, abstract, introduction, discussion, conclusion, or defense text to make it more natural, readable, precise, and human-written without making it colloquial or non-academic.
---

# Dissertation Humanizer Zh

Use this skill to polish Chinese dissertation prose so it remains academic, accurate, and logically sound while reading less mechanical and less AI-like.

## Core Principle

Preserve meaning first. Keep facts, technical terms, variables, citations, data, research claims, chapter logic, and disciplinary tone intact. Improve expression only where wording, rhythm, structure, or unnecessary formulaic phrasing makes the text sound mechanical.

Do not over-humanize academic prose into casual writing. For dissertations, "natural" means clear, restrained, specific, and readable, not chatty.

## Workflow

1. Read the passage once for thesis meaning: research object, method, claim, evidence, relation between sentences, and required formality.
2. Mark AI-like patterns: empty transition words, excessive comma chains, rigid "first/second/third" structures, repeated near-synonyms, vague intensifiers, stacked abstract nouns, over-neat paragraph templates, and unnecessary summaries.
3. Rewrite at the smallest useful scope. Prefer sentence-level and paragraph-level repair over total rewriting.
4. Preserve academic terms. If a term is standard in the field, keep it. Replace only generic filler, promotional wording, or vague boilerplate.
5. Read the result aloud mentally. It should flow, vary in sentence length, and sound like a careful researcher wrote it.
6. Check that no evidence, conclusion, qualifier, citation, or logical relation was lost.

## Rewrite Rules

### Keep Academic, Reduce AI Traces

- Simplify over-polished wording, but do not add slang, jokes, or casual filler.
- Remove obvious AI service phrases such as "值得注意的是", "需要指出的是", "综上所述", "让我们", "我们来", when they do not add meaning.
- Avoid formulaic ordering words such as "首先、其次、再次、最后" unless the passage truly depends on sequence.
- Replace repetitive "一是、二是、三是" structures with varied transitions, merged sentences, or topic-based phrasing.
- Avoid excessive "的、了、到、过、会、有、能、把" chains when they make the sentence loose or padded.
- Merge comma-heavy sentences where the logic belongs together; split when the sentence carries too many claims.
- Delete logical connector clutter when the relation is already obvious.

### Improve Precision And Readability

- Replace bland words with more precise, discipline-appropriate expressions.
- Prefer concrete verbs over abstract noun stacks.
- Use shorter sentences for key claims and longer sentences for necessary explanation.
- Let paragraphs vary: some can begin directly with evidence, some with a claim, some with a contrast or problem.
- If the original has too-perfect parallelism, loosen it slightly while keeping the argument clear.
- If a sentence sounds written for readers rather than by the author, recast it as the researcher's own analysis.

### Add Human Texture Carefully

- Add mild human-like rhythm only where allowed by academic context: "这一点并不难理解", "更准确地说", "在这一意义上", "这也解释了为什么".
- Use restrained judgment where the thesis genre allows it: "较为明显", "在一定程度上", "可能与……有关", "这一解释仍需结合……理解".
- Allow slight asymmetry in sentence structure. Dissertation prose does not need every paragraph to have opening summary, middle explanation, and closing summary.
- Avoid making every sentence balanced, complete, and polished in the same way; real academic writing has changes in density.

### Remove Repetition

- Do not place near-synonyms side by side, such as "承认和肯定", unless both are analytically distinct.
- Do not repeat the same causal word in close succession, such as using "因此" several times in one paragraph.
- Do not repeat the same point with different wording. Keep the stronger version and delete the weaker one.
- Avoid piling "-性" nouns such as "精确性、及时性、复合性、系统性、可积累性、实质性".
- If the same subject appears in consecutive sentences, combine or vary the sentence pattern.

## Dissertation-Specific Guardrails

- Keep citations and reference markers exactly unless the user asks to change citation style.
- Keep equations, statistical values, sample sizes, dates, names, and terminology unchanged.
- Do not invent evidence, examples, references, or results to make the prose smoother.
- Do not weaken a precise claim into vague prose, and do not strengthen a cautious claim into certainty.
- When polishing methodology, preserve procedure order and variable relationships.
- When polishing literature review, preserve attribution: who argued what, in which context, and how it relates to the thesis.
- When polishing conclusion or discussion, distinguish findings, interpretation, limitation, and outlook.

## Output Format

When the user asks only for rewriting, provide:

1. Revised text.
2. Brief change summary if helpful.

When the user asks for diagnosis or teaching, provide:

1. Revised text.
2. Main problems found.
3. Specific editing principles applied.

Keep explanations short unless the user asks for detailed editorial notes.

## Reference

For the extracted source prompts and the full rule inventory summarized from the user's images, read `references/source-image-text.md` when needed.
