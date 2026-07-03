---
name: dissertation-humanizer-zh
description: Chinese dissertation and thesis writing skill for polishing academic prose, reducing obvious AI-generated writing traces, strengthening argument logic, and adding high-quality recent literature and China-relevant policy context. Use when editing or drafting Chinese undergraduate, master's, doctoral, proposal, literature review, abstract, introduction, discussion, conclusion, or defense text that must preserve facts, citations, disciplinary terms, data, and original intent while becoming more natural, rigorous, locally grounded, and publication-aware. Also use when writing or revising section "1.1 课题背景与研究意义" in an applied engineering thesis without turning it into a literature review.
---

# Dissertation Humanizer Zh

Use this skill to revise Chinese dissertation prose in two passes: first improve the language, then strengthen the scholarship. The result should read like careful academic writing by a real researcher, not like a generated summary or a pile of decorative citations.

## Core Principle

Preserve meaning before improving style. Keep facts, technical terms, variables, citations, data, research claims, chapter logic, and disciplinary tone intact.

For Chinese dissertations, "natural" means clear, restrained, precise, and readable. Do not turn academic prose into casual speech. Do not hide weak evidence behind smooth language. Do not invent sources, policy statements, data, or conclusions.

## Default Workflow

1. Diagnose the passage: identify the research object, claim, evidence, method, and chapter function.
2. Polish the language first: repair awkward syntax, repeated wording, mechanical transitions, overlong comma chains, and stiff paragraph rhythm.
3. Recheck meaning: confirm that no claim, qualifier, citation, statistic, or disciplinary term has changed.
4. Strengthen evidence only after the prose is clear: add or suggest high-quality recent sources, policy documents, standards, or authoritative Chinese context where the argument actually needs support.
5. Integrate references into the argument, not into a citation list. Each added source must support a specific claim, contrast, method choice, policy background, or research gap.
6. Flag uncertainty. If a needed source cannot be verified, say so and provide a search direction instead of fabricating a citation.

## Language Polishing Rules

### Reduce AI Traces Without Losing Academic Tone

- Remove empty signposting such as "首先、其次、最后、综上所述、值得注意的是、需要指出的是" when it does not add logic.
- Replace rigid list structures with topic-based transitions, causal links, contrast, or direct continuation.
- Avoid repeated near-synonyms such as "承认和肯定" unless both terms are analytically distinct.
- Reduce abstract noun piles, especially repeated "-性" expressions like "系统性、精确性、复合性、可积累性".
- Merge sentences only when the logic is unified; split overloaded sentences when one sentence carries too many claims.
- Keep necessary academic connectors, but delete connector clutter where the relation is already obvious.
- Vary sentence length. Use short sentences for claims and longer sentences for explanation, evidence, or limitation.

### Make The Prose More Researcher-Like

- Prefer concrete verbs and precise disciplinary wording over vague intensifiers.
- Let paragraphs vary. Do not force every paragraph into "opening summary - explanation - closing summary".
- Add restrained judgment only where the thesis genre allows it: "较为明显", "在一定程度上", "可能与……有关", "仍需结合……理解".
- Avoid promotional words, exaggerated certainty, and emotional adjectives unless the field and evidence justify them.
- Keep the author's analytical stance visible: the writing should sound like a researcher advancing an argument, not a model completing a template.

## Evidence And Citation Rules

When the user asks to add references, deepen scholarship, or make the text suitable for a dissertation, read `references/evidence-and-policy.md`.

When the user asks to write, revise, summarize the method for, or imitate the style of section `1.1 课题背景与研究意义`, read `references/background-significance-1-1.md` before drafting. This is especially important when the section should follow a Chinese engineering master's thesis style and avoid becoming `国内外研究现状`.

Use the following hierarchy:

1. Recent high-quality peer-reviewed literature from 2021-2026, preferably top journals, JCR Q1/Q2 journals, high-impact society journals, Nature/Science/Cell family journals, or field-recognized venues. Use pre-2021 literature only when it is a classic foundation, a still-authoritative policy document, a standard, or a very high-impact source that the field continues to rely on.
2. Authoritative Chinese policy documents, national plans, official regulations, standards, white papers, and ministry-level guidance when the topic involves China, governance, education, technology, public policy, or industry application.
3. Chinese academic sources only when they are credible and relevant: CSSCI, CSCD, Peking University Core, authoritative university journals, recognized think-tank reports, or official statistical yearbooks.

Do not use low-quality sources to pad citations. Avoid predatory journals, unverified conference abstracts, suspicious special issues, citation farms, paper-mill-like articles, non-authoritative blog posts, and sources with no clear author, venue, date, or evidence base.

## China Context Rules

- Match the argument to Chinese institutional reality: policy hierarchy, governance language, education system, industry setting, regional differences, and official terminology.
- Prefer official Chinese documents for policy claims. Use international literature to frame theory, mechanism, method, and comparative evidence.
- Do not import foreign assumptions mechanically. Explain how a concept applies, does not apply, or needs adjustment in the Chinese context.
- When discussing AI, data, governance, education, or platforms in China, consider the principles of lawful use, data security, personal information protection, transparency, accuracy, reliability, development-security balance, and responsible innovation.

## Dissertation Guardrails

- Keep citations and reference markers exactly unless the user asks to change citation style.
- Keep equations, statistical values, sample sizes, dates, names, and terminology unchanged.
- Do not invent evidence, examples, references, or results.
- Do not weaken a precise claim into vague prose, and do not strengthen a cautious claim into certainty.
- In methodology sections, preserve procedure order, variable relationships, and reproducibility details.
- In literature reviews, preserve attribution: who argued what, in which context, and how it relates to the thesis.
- In discussion and conclusion sections, distinguish findings, interpretation, limitation, implication, and outlook.

## Output Format

When rewriting only:

1. Revised text.
2. Brief change summary if useful.

When strengthening scholarship:

1. Revised text.
2. Added or recommended evidence, with source quality noted.
3. Remaining citation gaps or verification cautions.

Keep explanations concise unless the user asks for detailed editorial notes.

## References

- Read `references/evidence-and-policy.md` for source-selection rules, recent high-quality literature examples, and China-context guidance.
- Read `references/background-significance-1-1.md` when drafting or revising `1.1 课题背景与研究意义`, especially for engineering, robotics, exoskeleton, medical device, aerospace, eldercare, fitness, rehabilitation, or intelligent equipment theses.
- Read `references/source-image-text.md` only when the original image-derived prompt inventory is needed.
