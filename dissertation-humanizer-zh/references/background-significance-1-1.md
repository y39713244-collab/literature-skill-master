# 1.1 课题背景与研究意义写作方法

Use this reference when writing or revising Chinese dissertation section `1.1 课题背景与研究意义`. The goal is to establish the topic's necessity and value in a restrained master's-thesis style. Do not turn this section into `国内外研究现状`.

## Section Function

`1.1` should answer four questions:

1. Why this topic matters in the real world.
2. What practical contradiction exists in the target population, scene, device, or process.
3. Why the proposed technical route is necessary.
4. What theoretical and engineering value the thesis has.

Avoid naming and summarizing many individual scholars. Save "who did what" for `1.2 国内外研究现状`.

## Recommended Structure

Write 5-7 paragraphs.

1. **Macro background**: Start from a social, policy, industrial, clinical, training, engineering, or national-strategy need. For China-facing theses, use one or two authoritative Chinese policies only when they directly support the topic. Do not pile up guidelines.
2. **Target scenario**: Narrow the topic to the actual population and use environment, such as office sedentary workers, home training, eldercare, minimally invasive surgery, astronaut training, rehabilitation, or small-space equipment.
3. **Research object**: Introduce the action, device, process, or system studied by the thesis and explain why it matters in that scenario.
4. **Core contradiction**: State the bottleneck in concrete engineering terms, such as load instability, insufficient feedback, high cost, large equipment size, safety risk, operation difficulty, limited freedom, weak force control, or poor usability.
5. **Technical necessity**: Explain why the thesis' technical route can respond to the contradiction. Keep this conceptual; detailed formulas, algorithms, and experiments belong in later chapters.
6. **Research positioning**: Define what the system is and is not. For example, an exoskeleton may be a compensation and protection device rather than a device that replaces active user force.
7. **Research significance**: End with theoretical meaning and engineering or application value, aligned with the thesis chapters.

## Language Style

Use a clear Chinese engineering master's thesis tone:

- Prefer causal progression: "随着……", "在此背景下……", "然而……", "因此……".
- Use restrained judgments: "具有一定现实需求", "较为明显", "在一定程度上", "有助于", "可为……提供参考".
- Use concrete nouns and verbs instead of broad praise.
- Keep the research object visible throughout the section.
- Use long sentences for background and constraint explanation, and short sentences for core claims.
- End with a thesis-specific value statement, not a slogan.

Avoid:

- Turning the section into a literature review.
- Starting many sentences with "国内外学者".
- Explaining who did what in detail.
- Piling up policies, guidelines, statistics, or general social slogans.
- Saying only "容易受伤" when the real issue also includes load instability, usability, training effect, cost, precision, or control.
- Overstating the proposed system as replacing human action unless that is truly the research claim.

## Citation And Evidence Standards

Use citations to support specific claims, not to decorate paragraphs.

Prefer:

1. One authoritative Chinese policy, plan, standard, or official document for macro background when relevant.
2. Recent high-quality peer-reviewed literature from the last five years when it is directly relevant and reputable.
3. If recent literature is weak, use high-quality post-2010 journal articles, classic reviews, or top-venue work.
4. For engineering, robotics, exoskeleton, and control topics, prefer Nature, Science, IEEE journals, Elsevier/Springer/Wiley high-impact journals, reputable society journals, or clearly recognized top venues.
5. For sports science and biomechanics, prefer credible venues such as Sports Medicine, British Journal of Sports Medicine, Journal of Strength and Conditioning Research, Medicine & Science in Sports & Exercise, Clinical Biomechanics, Gait & Posture, or Journal of Biomechanics.

Reject:

- Preprints when a formal peer-reviewed paper can be used.
- Weak or predatory journals, suspicious special issues, unverifiable abstracts, marketing white papers, and news used as technical evidence.
- Sources that are recent but low quality.
- Sources that are high quality but do not actually support the sentence.

Citation placement:

- Put policy citations after claims about social demand, policy orientation, or national strategy.
- Put technical citations after claims about mechanisms, load, risk, performance, feasibility, or system capability.
- Do not add a citation to every sentence. A few strong, well-placed citations are better than a dense citation pile.

## General Writing Pattern

```text
社会/场景需求
→ target users or environment
→ current practice has value
→ current practice has a concrete limitation
→ proposed technical route can respond to the limitation
→ theoretical and engineering significance
```

Reusable skeleton:

```text
近年来，随着……，……需求不断增加。……政策/高质量研究指出……[1]。在这一背景下，面向……场景的……具有现实需求。

……是……中常见的……，具有……优势。然而，……并不简单，其过程受到……影响[2-3]。在……场景下，用户/操作者/系统容易出现……问题。

从……角度看，现有方式的核心不足并不只是……，还包括……。当……变化时，……也随之变化，导致……。因此，如何……成为提升……质量/安全性/可用性的关键问题。

相比传统……，……技术具有……特点。相关高质量研究表明，……可通过……改变/调节/辅助……[4-5]。这为……提供了新的技术路径。

基于上述背景，本文拟设计/研究……。该系统并非……，而是针对……，通过……实现……。

综上，开展……研究具有理论意义和工程应用价值。理论上，……；应用上，……。
```

## Special Pattern: Isotonic Knee Exoskeleton For Home Squat Training

When the thesis concerns an isotonic knee exoskeleton for home squat training:

- Start from office sedentary workers, home fitness, lower-limb activity insufficiency, small-space training, and scientific training demand.
- State that ordinary squats are convenient but difficult to control without coaching, equipment, or real-time feedback.
- Emphasize both training-load instability and knee protection. Do not write only about injury.
- Explain that ordinary squats are not ideal isotonic training because knee torque changes with knee angle, trunk posture, squat depth, and external load.
- Define the exoskeleton as an isotonic compensation and protection device, not as a device that replaces active user force.
- Use anchor terms repeatedly and consistently: "等张补偿", "膝关节力矩估算", "训练负荷稳定性", "居家深蹲训练", "膝关节保护".
- Leave detailed formulas, model assumptions, and control procedures to later chapters.

Preferred ending:

```text
从理论层面看，该研究可围绕……分析……形成原因，并建立……模型。从应用层面看，该系统可为……提供一种兼顾……的……方式，使……从依赖主观经验逐步转向基于……的人机协同过程。
```

