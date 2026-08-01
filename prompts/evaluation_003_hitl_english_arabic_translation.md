# Evaluation 003 – Human-in-the-Loop English–Arabic Translation Evaluation
---

## Case Study Overview

This case study compares the English-to-Arabic translation capabilities of multiple large language models (LLMs) on a healthcare translation task.

The evaluation assesses meaning preservation, accuracy, stylistic fidelity, terminology, fluency, and publication-quality Modern Standard Arabic (MSA).

The assessment was conducted using a custom GPT implementing the **AI Evaluation Framework**, including its Translation Rubric, Arabic Language Rubric, scoring methodology, and decision rules to produce a structured evaluation report.

To improve reliability, the initial AI-generated assessment underwent an independent human expert review. Reviewer observations were validated against the framework and incorporated only when supported by textual evidence, demonstrating a structured **human-in-the-loop (HITL)** evaluation workflow.

This case study documents the complete evaluation process, including the initial evaluation, human expert review, evidence-based revision, and final assessment.

---

## Executive Summary

This case study compares the English-to-Arabic translation capabilities of ChatGPT (GPT-5.5), Google Gemini (3.6 Flash), and Claude (Sonnet 5 Thinking) using the AI Evaluation Framework.

All three models produced accurate, publication-quality Modern Standard Arabic translations. Following an evidence-based Human-in-the-Loop (HITL) evaluation workflow, ChatGPT was ranked first for its balance of meaning preservation, stylistic fidelity, and natural language quality, followed by Claude and Google Gemini.

---

## Table of Contents

1. [Project Information](#project-information)
2. [Evaluation Objective](#evaluation-objective)
3. [Evaluation Scope](#evaluation-scope)
4. [Prompt](#prompt)
5. [Model Responses](#model-responses)
6. [Evaluation Criteria](#evaluation-criteria)
7. [Evaluation Methodology](#evaluation-methodology)
8. [Initial Evaluation](#initial-evaluation)
9. [Human Linguistic Analysis](#human-linguistic-analysis)
10. [Revised Evaluation](#revised-evaluation)
11. [Key Changes After Human Review](#key-changes-after-human-review)
12. [Lessons Learned](#lessons-learned)
13. [Skills Demonstrated](#skills-demonstrated)
14. [Study Limitations](#study-limitations)
15. [Future Work](#future-work)
16. [Overall Conclusion](#overall-conclusion)
17. [References](#references)
18. [Document Information](#document-information)

---

## Project Information

| Field | Value |
|--------|-------|
| **Project ID** | Evaluation 003 |
| **Project Type** | LLM Evaluation Case Study |
| **Domain** | English–Arabic Machine Translation |
| **Task** | Translation Quality Evaluation |
| **Evaluation Method** | Human-in-the-Loop (HITL) Evaluation |
| **Models Compared** | ChatGPT (GPT-5.5), Google Gemini (3.6 Flash), Claude (Sonnet 5 Thinking) |
| **Evaluation Framework** | AI Evaluation Framework |
| **Status** | Completed |
| **Version** | 1.1 |
| **Date** | July 2026 |

> **Project Standard**

This evaluation follows the **LLM Evaluation Project Standard (LEPS) v1.0**, ensuring a standardized project structure, evaluation workflow, evidence-based scoring, transparent reporting, and reproducible methodology.

---

## Evaluation Objective

Evaluate and compare the English-to-Arabic translation capabilities of ChatGPT (GPT-5.5), Google Gemini (3.6 Flash), and Claude (Sonnet 5 Thinking) using the AI Evaluation Framework.

The evaluation assesses each model's ability to:

- Preserve the original meaning without omission or distortion.
- Maintain the source text's tone and level of formality.
- Produce natural, publication-quality Modern Standard Arabic (MSA).
- Use accurate and appropriate healthcare terminology.
- Follow all prompt instructions consistently.

This case study also demonstrates a Human-in-the-Loop (HITL) evaluation workflow in which an initial AI-generated evaluation is independently reviewed by a human expert. Only observations supported by textual evidence and consistent with the evaluation framework are incorporated into the final assessment.

---

## Evaluation Scope

This case study evaluates the translation quality of three large language models on a single English-to-Arabic healthcare translation task.

The evaluation focuses on:

- Meaning preservation
- Accuracy
- Style and tone
- Modern Standard Arabic quality
- Healthcare terminology
- Fluency
- Instruction following

The evaluation does **not** assess:

- Translation speed or latency
- Computational efficiency
- Cost or pricing
- General multilingual capabilities
- Performance on other translation domains or prompts

The findings apply only to the prompt, source text, and model versions evaluated in this case study.

---

## Prompt

Translate the following paragraph into **Modern Standard Arabic (MSA)**.

**Requirements:**

- Preserve the original meaning.
- Preserve the original tone and level of formality.
- Use natural Arabic suitable for publication.
- Do not summarize, omit, or add information.

### Source Text

> Artificial intelligence is transforming healthcare by helping doctors diagnose diseases more quickly and accurately. It can analyze medical images, identify patterns in patient data, and support clinical decision-making. While AI has great potential, it should complement healthcare professionals rather than replace them.

---

## Model Responses

### ChatGPT (GPT-5.5)

> يُحدث الذكاء الاصطناعي تحولًا في قطاع الرعاية الصحية من خلال مساعدة الأطباء على تشخيص الأمراض بسرعة أكبر وبدقة أعلى. ويمكنه تحليل الصور الطبية، وتحديد الأنماط في بيانات المرضى، ودعم عملية اتخاذ القرارات السريرية. وعلى الرغم من الإمكانات الكبيرة التي يتمتع بها الذكاء الاصطناعي، فإنه ينبغي أن يكون أداةً مكملةً لعمل المتخصصين في الرعاية الصحية، لا بديلًا عنهم.

---

### Google Gemini (3.6 Flash)

> يقوم الذكاء الاصطناعي برسم ملامح جديدة للرعاية الصحية من خلال مساعدة الأطباء على تشخيص الأمراض بسرعة ودقة أكبر؛ حيث يمكنه تحليل الصور الطبية، والتعرف على الأنماط في بيانات المرضى، ودعم اتخاذ القرارات السريرية. ورغم ما يمتلكه الذكاء الاصطناعي من إمكانات هائلة، إلا أنه ينبغي أن يكون مكملًا لدور أخصائيي الرعاية الصحية لا بديلًا عنهم.

---

### Claude (Sonnet 5 Thinking)

> يُحدِث الذكاء الاصطناعي تحوّلًا في مجال الرعاية الصحية من خلال مساعدة الأطباء على تشخيص الأمراض بسرعة ودقة أكبر. فهو قادر على تحليل الصور الطبية، والتعرّف على الأنماط في بيانات المرضى، ودعم عملية اتخاذ القرار السريري. ورغم ما يمتلكه الذكاء الاصطناعي من إمكانات هائلة، إلا أنه ينبغي أن يكون مكمّلًا لعمل المتخصصين في الرعاية الصحية لا بديلًا عنهم.

---

## Evaluation Criteria

The translations were evaluated using the **AI Evaluation Framework**, which applies the **Translation Rubric** (primary) and the **Arabic Language Rubric** (secondary).

Each translation was assessed against the following criteria:

| Criterion | Description |
|-----------|-------------|
| **Meaning Preservation** | Accuracy in conveying the original meaning without omission, distortion, or unnecessary additions. |
| **Accuracy** | Correct representation of factual content, relationships, and medical concepts. |
| **Language Quality** | Grammatical correctness, vocabulary choice, punctuation, and adherence to Modern Standard Arabic conventions. |
| **Fluency** | Naturalness, readability, and coherence of the translation. |
| **Style & Tone** | Faithfulness to the source text's tone, level of formality, and stylistic register. |
| **Terminology** | Appropriate and consistent use of healthcare and technical terminology. |
| **Instruction Following** | Compliance with all prompt requirements, including preserving meaning, tone, and completeness. |

Each criterion is scored on a **5-point scale**, where **5.0** represents excellent performance.

The final ranking follows the AI Evaluation Framework's decision rules. **Meaning Preservation** and **Accuracy** are treated as the primary evaluation criteria. When multiple translations satisfy these criteria, the final preference is determined using secondary criteria, including Style & Tone, Terminology, Instruction Following, and overall translation quality.

---

## Evaluation Workflow

This evaluation follows the workflow defined in the **LLM Evaluation Project Standard (LEPS) v1.0**.

1. Define the evaluation objective.
2. Prepare the source text and evaluation prompt.
3. Generate translations using the selected LLMs.
4. Perform the initial AI-generated evaluation.
5. Conduct an independent Human Linguistic Analysis.
6. Validate reviewer observations against the evaluation framework.
7. Revise the evaluation using evidence-based findings.
8. Document the final assessment, conclusions, and limitations.

---

## Evaluation Assets

The evaluation was conducted using the following assets:

| Asset | Description |
|--------|-------------|
| Source Text | Original English healthcare paragraph |
| Evaluation Prompt | English-to-Arabic translation task |
| ChatGPT Translation | GPT-5.5 generated translation |
| Gemini Translation | Google Gemini 3.6 Flash generated translation |
| Claude Translation | Claude Sonnet 5 Thinking generated translation |
| AI Evaluation Framework | Translation and Arabic Language Rubrics |
| Human Evaluation | Independent linguistic review |
| Revised Evaluation | Evidence-based Human-in-the-Loop assessment |

---

## Evaluation Methodology

This case study follows the **AI Evaluation Framework** to perform a structured, evidence-based comparison of English-to-Arabic translation quality.

The evaluation was conducted in four phases.

### Phase 1 – Initial Evaluation

A custom GPT implementing the AI Evaluation Framework generated the initial evaluation. The assessment applied the Translation Rubric, Arabic Language Rubric, standard scoring guide, and predefined decision rules to produce a structured evaluation report.

### Phase 2 – Human Linguistic Analysis

An independent reviewer with expertise in Modern Standard Arabic examined the initial evaluation. The review focused on:

- Linguistic accuracy
- Meaning preservation
- Stylistic fidelity
- Tone and formality
- Terminology
- Quality of supporting evidence
- Consistency between observations and assigned scores

### Phase 3 – Evidence Validation

Reviewer observations were independently validated against:

- The source text
- Each model response
- The Translation Rubric
- The Arabic Language Rubric
- The AI Evaluation Framework

Only observations supported by textual evidence and consistent with the evaluation methodology were accepted.

### Phase 4 – Revised Evaluation

Supported observations were incorporated into a revised evaluation. The final report retained the original evaluation methodology, scoring guide, and decision rules while improving the supporting evidence, score consistency, and linguistic analysis.

To reduce evaluator bias, each model response was evaluated independently before any comparison was performed. The subsequent Human-in-the-Loop (HITL) review independently reassessed the evaluation against the source text, model responses, and the AI Evaluation Framework. Only observations supported by direct textual evidence and consistent with the framework were incorporated into the final assessment.

### Evaluation Workflow

1. Prompt and model response generation.
2. Initial AI-generated evaluation.
3. Independent human expert review.
4. Evidence validation.
5. Revised evaluation.
6. Final conclusions.

---

# Initial Evaluation

The following evaluation was generated by the AI Evaluation Framework Custom GPT before any human review was performed. It represents the baseline assessment based solely on the prompt, source text, and model responses.

---

## Standard Evaluation Report

### 1. Instruction Verification

| Requirement | Status | Evidence |
|-------------|--------|----------|
| Translate into Modern Standard Arabic | All satisfied | All three use standard MSA. |
| Preserve original meaning | All satisfied | No significant omissions or mistranslations. |
| Preserve tone and formality | All satisfied | Formal, publication-appropriate register maintained. |
| Natural Arabic | All satisfied | All translations are fluent and idiomatic. |
| No summarization or omission | All satisfied | All major ideas are retained. |

---

### 2. Evidence Summary

#### Shared Strengths

- All three translations preserve the source meaning.
- All use appropriate medical terminology.
- All maintain the requested formal style.
- None omit any substantive information.

#### Key Differences

- ChatGPT stays closest to the source's neutral wording and sentence structure while remaining natural and publication-ready.

- Claude is similarly accurate but introduces a slight stylistic expansion through "فهو قادر على." Its use of the singular "اتخاذ القرار السريري" is a natural and acceptable rendering that does not materially affect translation quality.

- Gemini is the most stylistically polished, but "يرسم ملامح جديدة للرعاية الصحية" is a more interpretive and literary rendering than the source's neutral expression "is transforming healthcare." Additionally, "هائلة" conveys stronger emphasis than the source's "great."

---

### 3. Criterion-by-Criterion Evaluation

#### A. Google Gemini (3.6 Flash)

| Criterion | Score | Justification |
|-----------|:-----:|---------------|
| Meaning Preservation | **4.5 / 5** | Preserves meaning well. "يرسم ملامح جديدة" is slightly more expressive than the source. |
| Accuracy | **5.0 / 5** | Medical concepts and relationships remain accurate. |
| Language Quality | **5.0 / 5** | Excellent grammar, punctuation, and vocabulary. |
| Fluency | **5.0 / 5** | Reads naturally and smoothly. |
| Style & Tone | **4.5 / 5** | Slightly more literary than the original. |
| Terminology | **5.0 / 5** | Appropriate and consistent terminology throughout. |
| Instruction Following | **5.0 / 5** | Fully satisfies all requirements. |

---

#### B. ChatGPT (GPT-5.5)

| Criterion | Score | Justification |
|-----------|:-----:|---------------|
| Meaning Preservation | **5.0 / 5** | Very faithful to the source with no meaningful semantic shift. |
| Accuracy | **5.0 / 5** | All information is accurately conveyed. |
| Language Quality | **5.0 / 5** | Excellent Modern Standard Arabic suitable for publication. |
| Fluency | **5.0 / 5** | Smooth, natural, and highly readable. |
| Style & Tone | **5.0 / 5** | Closely matches the original's neutral professional tone. |
| Terminology | **5.0 / 5** | Consistent, precise medical terminology. |
| Instruction Following | **5.0 / 5** | Fully satisfies every instruction. |

---

#### C. Claude (Sonnet 5 Thinking)

| Criterion | Score | Justification |
|-----------|:-----:|---------------|
| Meaning Preservation | **5.0 / 5** | Preserves the original meaning accurately. |
| Accuracy | **5.0 / 5** | No factual or terminological errors. |
| Language Quality | **5.0 / 5** | Excellent Arabic with natural phrasing. |
| Fluency | **5.0 / 5** | Highly fluent and cohesive. |
| Style & Tone | **4.5 / 5** | Slight stylistic elaboration ("فهو قادر على") not present in the source. |
| Terminology | **4.5 / 5** | "اتخاذ القرار السريري" is acceptable, though "اتخاذ القرارات السريرية" aligns more closely with the plural "decision-making." |
| Instruction Following | **5.0 / 5** | Fully satisfies the prompt. |

---

### 4. Comparison Summary

| Model | Major Strength | Minor Weakness |
|-------|----------------|----------------|
| Google Gemini (3.6 Flash) | Elegant, highly polished Arabic | More interpretive opening ("يرسم ملامح جديدة") |
| ChatGPT (GPT-5.5) | Most faithful balance of meaning, tone, and naturalness | No meaningful weaknesses identified |
| Claude (Sonnet 5 Thinking) | Excellent fluency and readability | Slight stylistic additions and a less literal rendering of "clinical decision-making" |

---

### 5. Critical Evaluation Criteria

The applicable critical criteria are **Meaning Preservation** and **Accuracy**. All three responses satisfy these critical criteria; therefore, no critical criterion overrides the overall comparison. The final preference is based on qualitative differences in style, fidelity, and naturalness rather than numerical scores alone.

**Decision Rule Applied:** Since all responses meet the critical criteria, the comparison follows the tie-breaking approach based on instruction compliance, evidence quality, task fulfilment, and overall usefulness.

---

### 6. Overall Preference

🥇 **1st — ChatGPT (GPT-5.5)**

The closest match to the source text in meaning, tone, and style while remaining completely natural in Modern Standard Arabic. It preserves the original's neutral, professional voice with no unnecessary embellishment.

🥈 **2nd — Claude (Sonnet 5 Thinking)**

Very close to ChatGPT. Elegant and fluent, but introduces minor stylistic additions and a slightly less direct rendering of "clinical decision-making."

🥉 **3rd — Google Gemini (3.6 Flash)**

An excellent translation overall. The only meaningful difference is the more interpretive phrase "يرسم ملامح جديدة للرعاية الصحية," which subtly shifts the style from the source's straightforward wording.

---

### 7. Confidence Rating

**High**

The evaluation is based on direct comparison between the source text and the three translations. The distinctions are supported by observable textual evidence and do not require external verification.

---

### 8. Recommendations

- Prefer translations that remain as close as possible to the source's stylistic neutrality unless adaptation is explicitly requested.
- Avoid interpretive embellishments when the prompt emphasizes preserving the original tone.
- Maintain consistency between singular and plural concepts where the source expresses a general process (e.g., "clinical decision-making").

---

### 9. Conclusion

All three translations are publication-quality and fully satisfy the prompt. This is a near-tie, with only subtle stylistic differences separating them. ChatGPT is preferred because it achieves the strongest balance of meaning preservation, natural Modern Standard Arabic, and fidelity to the source's tone, while Gemini and Claude follow very closely.

---

## Human Linguistic Analysis

The human expert conducted an independent linguistic assessment of the three translations, focusing on stylistic fidelity, vocabulary selection, grammatical quality, and consistency with the source text. The review confirmed that all three models accurately preserved the original meaning and produced fluent, publication-quality Modern Standard Arabic. The principal differences were stylistic rather than semantic and concerned the level of formality, vocabulary selection, and fidelity to the source's neutral register. The observations below summarize the findings that were subsequently validated and incorporated into the revised evaluation.

### Google Gemini

Gemini employs a more elevated and literary writing style than the source. The expression *"يرسم ملامح جديدة"* is elegant and well suited to literary or formal writing, but it is more interpretive than the source's neutral expression *"is transforming"*. The translation also demonstrates the strongest use of formal vocabulary, including *"إمكانات"* and *"أخصائيي الرعاية الصحية"*, both of which are highly appropriate for publication-quality Modern Standard Arabic.

However, the adjective *"هائلة"* is more emphatic than the source's *"great"*, slightly amplifying the intended meaning. Despite these stylistic choices, the translation remains accurate, fluent, and well suited to formal Modern Standard Arabic. These observations reflect stylistic preferences rather than translation errors.

### ChatGPT

ChatGPT produces the most balanced translation for a journalistic or academic article. The grammar is accurate, the vocabulary is clear and precise, and the overall tone closely matches that of the original English text. Its sentence structure remains faithful to the source while maintaining natural, publication-quality Modern Standard Arabic.

The translation renders *"more quickly and accurately"* as *"بسرعة أكبر وبدقة أعلى"*, slightly strengthening the comparative emphasis while preserving the original meaning. Likewise, *"يتمتع بها"* is a natural and idiomatic expression, although it represents a modest stylistic expansion beyond the simpler wording of the source.

The translation also successfully conveys that artificial intelligence is intended to complement rather than replace healthcare professionals. The addition of *"أداةً"* makes this supporting role more explicit but also represents a slight stylistic expansion beyond the wording of the source text. These observations reflect stylistic choices rather than translation issues.

### Claude

Claude produces a translation that combines many of the strengths of both ChatGPT and Gemini. Its sentence structure remains close to the source while maintaining natural, publication-quality Modern Standard Arabic, making it stylistically close to the reviewer's preferred rendering.

Unlike ChatGPT, Claude avoids expanding the complement–replace relationship through the addition of "أداةً". However, it introduces minor stylistic elaborations such as "فهو قادر على" and "عملية", which slightly expand the source's wording without affecting its meaning.

Like Gemini, Claude also uses the stronger adjective "هائلة", which slightly increases the emphasis compared with the source.

The reviewer also noted that any claim that Claude's use of "اتخاذ القرار السريري" constitutes a terminology weakness is not linguistically supported. The English expression "clinical decision-making" is an uncountable process noun, and "اتخاذ القرار السريري" is a natural and idiomatic Modern Standard Arabic rendering of that general concept. Although "اتخاذ القرارات السريرية" is also acceptable, the singular formulation does not reduce fidelity to the source, alter the meaning, or constitute a terminology issue.

---

# Revised Evaluation

The Human Linguistic Analysis provided an independent review of the initial AI-generated evaluation. Reviewer observations were validated against the source text, model responses, and the AI Evaluation Framework before being incorporated into the final assessment.

The revised evaluation strengthens the supporting evidence, improves scoring consistency, and increases transparency while preserving the original evaluation methodology.

---

## Revision Process

Each reviewer observation was independently validated against:

- The source text.
- All three model responses.
- The AI Evaluation Framework.
- The Translation Evaluation Rubric.
- The Arabic Language Evaluation Rubric.
- The framework's scoring methodology and decision rules.

Only observations supported by direct textual evidence were accepted.

A cross-response consistency review was also performed to ensure that comparable linguistic phenomena were evaluated using the same standard across all three translations.

---

## Scope of the Revisions

The revised evaluation strengthens the original assessment without changing the underlying methodology.

The revision focused on improving:

- Supporting evidence.
- Score consistency.
- Stylistic fidelity.
- Comparative analysis.
- Transparency of evaluation decisions.

The following remained unchanged:

- Evaluation methodology.
- Evaluation criteria.
- Translation Evaluation Rubric.
- Arabic Language Evaluation Rubric.
- Standard Scoring Guide.
- Decision Rules.
- Source text.
- Model responses.
- Human-in-the-Loop (HITL) evaluation workflow.

---

## Final Evaluation

The following report presents the final evidence-based assessment after completion of the Human-in-the-Loop (HITL) evaluation workflow.

All accepted revisions were independently validated against:

- The source text.
- The three model responses.
- The AI Evaluation Framework.
- The Translation Evaluation Rubric.
- The Arabic Language Evaluation Rubric.

The final conclusions reflect only revisions supported by direct textual evidence and consistent with the framework's evaluation methodology.

---

# Revised Standard Evaluation Report

## 1. Instruction Verification

All three models satisfy the core translation requirements. The only meaningful distinction is stylistic fidelity, where ChatGPT remains closest to the source's neutral register while Gemini and Claude introduce a slightly more elevated writing style.

| Requirement | Status | Evidence |
|-------------|--------|----------|
| Modern Standard Arabic | Fully Satisfied | All translations use fluent, publication-ready MSA. |
| Preserve meaning | Fully Satisfied | No omissions, mistranslations, or factual changes were identified. |
| Preserve tone and formality | Partially Differentiated | ChatGPT remains closest to the source's neutral tone. Gemini and Claude adopt a slightly more literary register. |
| Natural Arabic | Fully Satisfied | All translations read naturally and are grammatically correct. |
| No summarization or omission | Fully Satisfied | All source information is retained. |

---

## 2. Evidence Summary

All three translations satisfy the prompt requirements and demonstrate a high standard of English-to-Arabic translation quality.

### Shared Strengths

- Accurate preservation of the source meaning.
- Fluent Modern Standard Arabic.
- Appropriate healthcare terminology.
- No omissions or factual inaccuracies.
- Publication-ready language quality.

### Key Differences

- **ChatGPT** stays closest to the source's neutral journalistic style while maintaining natural Arabic.
- **Gemini** uses more expressive vocabulary and rhetorical phrasing, producing a slightly more literary translation.
- **Claude** combines a neutral sentence structure with more formal lexical choices, creating a mixed stylistic register.

### Critical Observation

The primary distinction between the three responses is **stylistic fidelity rather than translation accuracy**. All preserve the original meaning, but they differ in how closely they reflect the source's neutral professional tone.

## 3. Cross-Response Parity Check

A parity check was performed before assigning the final scores to ensure that comparable linguistic phenomena were evaluated consistently across all three translations.

| Phenomenon | Gemini | ChatGPT | Claude | Assessment |
|------------|---------|----------|---------|------------|
| Meaning preservation | ✓ | ✓ | ✓ | All preserve the source meaning without omissions or factual changes. |
| Stylistic expansion | ✓ | Minor | ✓ | Gemini and Claude introduce more stylistic enhancement than ChatGPT. The difference is reflected only in the Style & Tone criterion. |
| Stronger lexical emphasis | ✓ | Minor | ✓ | Gemini strengthens emphasis (e.g., **هائلة**). ChatGPT and Claude remain closer to the source while using natural Arabic. |
| Elevated vocabulary | ✓ | — | ✓ | Gemini and Claude employ more formal vocabulary without changing the underlying meaning. |
| Medical terminology | ✓ | ✓ | ✓ | All use accurate and appropriate healthcare terminology. Acceptable lexical alternatives were treated equally. |
| Fluency and grammar | ✓ | ✓ | ✓ | All translations are grammatically correct and read naturally. |

### Consistency Check

The final scores apply the same evaluation standard across all three responses.

- Meaning-preserving lexical alternatives were treated as acceptable terminology.
- Stylistic variations were evaluated under **Style & Tone**, not **Accuracy** or **Meaning Preservation**.
- No response was penalized solely for using a different but valid translation.
- Score differences reflect only observable differences in stylistic fidelity to the source text.

---

## 4. Criterion-by-Criterion Evaluation

### A. Google Gemini (3.6 Flash)

| Criterion | Score |
|-----------|------:|
| Meaning Preservation | **4.5 / 5** |
| Accuracy | **5.0 / 5** |
| Language Quality | **5.0 / 5** |
| Fluency | **5.0 / 5** |
| Style & Tone | **4.0 / 5** |
| Terminology | **5.0 / 5** |
| Instruction Following | **4.5 / 5** |

### Justification

Gemini delivers an accurate, fluent, and publication-ready translation. The primary weakness is stylistic rather than semantic. It introduces more expressive language than the source, producing a slightly more literary register.

### Supporting Evidence

**Strengths**

- Preserves the complete source meaning.
- Uses accurate healthcare terminology.
- Excellent grammar and fluency.
- Reads naturally in Modern Standard Arabic.

**Weaknesses**

- Uses metaphorical phrasing such as **يرسم ملامح جديدة**, which is more rhetorical than the source's *is transforming*.
- Uses stronger lexical emphasis such as **هائلة**, creating a more emphatic tone than the original.
- Overall style is slightly more literary than the source's neutral professional register.

---

### B. ChatGPT (GPT-5.5)

| Criterion | Score |
|-----------|------:|
| Meaning Preservation | **5.0 / 5** |
| Accuracy | **5.0 / 5** |
| Language Quality | **5.0 / 5** |
| Fluency | **5.0 / 5** |
| Style & Tone | **5.0 / 5** |
| Terminology | **5.0 / 5** |
| Instruction Following | **5.0 / 5** |

### Justification

ChatGPT delivers the most faithful translation overall. It preserves the original meaning while maintaining the source's neutral professional style, natural Arabic, and consistent terminology.

### Supporting Evidence

**Strengths**

- Preserves the complete source meaning without additions or omissions.
- Maintains the source's neutral journalistic register.
- Uses clear, consistent healthcare terminology.
- Excellent grammar, fluency, and readability.
- Produces a natural translation suitable for professional and publication contexts.

**Minor Observation**

- The addition of **أداةً** ("as a tool") slightly reinforces AI's supporting role. This remains consistent with the source meaning and does not materially affect the translation's tone or accuracy.

---

### C. Claude (Sonnet 5 Thinking)

| Criterion | Score |
|-----------|------:|
| Meaning Preservation | **5.0 / 5** |
| Accuracy | **5.0 / 5** |
| Language Quality | **5.0 / 5** |
| Fluency | **5.0 / 5** |
| Style & Tone | **4.5 / 5** |
| Terminology | **5.0 / 5** |
| Instruction Following | **4.5 / 5** |

### Justification

Claude produces an accurate and fluent translation with strong language quality. Its primary weakness is a slight stylistic shift toward a more formal register, making it marginally less faithful to the source's neutral tone.

### Supporting Evidence

**Strengths**

- Fully preserves the source meaning.
- Uses accurate healthcare terminology throughout.
- Excellent grammar and natural Modern Standard Arabic.
- Clear sentence structure and high readability.

**Minor Weaknesses**

- Uses slightly more formal vocabulary than the source, resulting in a modest register shift.
- Adds mild stylistic emphasis while preserving the original meaning.
- The terminology **اتخاذ القرار السريري** is an acceptable translation and is not treated as a terminology error.

---

## 5. Comparison Summary

All three models produce high-quality translations that satisfy the prompt requirements. They preserve the original meaning, use appropriate medical terminology, and generate fluent Modern Standard Arabic.

The primary differences relate to stylistic fidelity rather than translation accuracy.

### Shared Strengths

- Preserve the original meaning.
- Use accurate healthcare terminology.
- Produce fluent, publication-ready Modern Standard Arabic.
- Contain no omissions or factual inaccuracies.

### Key Differences

| Aspect | Google Gemini | ChatGPT | Claude |
|--------|---------------|----------|---------|
| Meaning Preservation | Excellent | Excellent | Excellent |
| Stylistic Fidelity | More literary | Closest to the source | Slightly more formal |
| Language Quality | Excellent | Excellent | Excellent |
| Terminology | Accurate | Accurate | Accurate |
| Overall Register | Elevated | Neutral | Moderately elevated |

### Overall Assessment

- **ChatGPT** provides the closest match to the source's neutral professional style while preserving complete meaning.
- **Claude** performs similarly but adopts a slightly more formal register through lexical choices.
- **Gemini** remains fully accurate but introduces the greatest degree of stylistic adaptation.

---

## 6. Critical Evaluation Criteria

For this translation task, **Meaning Preservation** is the primary critical evaluation criterion.

All three translations satisfy this requirement.

Additional critical observations:

- No response introduces factual errors.
- No response omits source information.
- No response mistranslates medical concepts.
- All terminology is appropriate for a professional healthcare context.

The remaining differences are limited to stylistic fidelity and do not affect the overall meaning.

---

## 7. Decision Rule Applied

The responses were evaluated using the framework's qualitative decision process rather than numerical scores alone.

The final preference was determined in the following order:

1. Critical Evaluation Criteria
2. Instruction Compliance
3. Evidence Quality
4. Task Fulfilment
5. Overall Usefulness

Because all three responses satisfy the critical criterion of **Meaning Preservation**, the final ranking is based on stylistic fidelity to the source text.

ChatGPT is preferred because it most consistently preserves the source's neutral professional register while maintaining the same level of meaning preservation, accuracy, fluency, and terminology quality demonstrated by the other responses.

---

## 8. Overall Preference

All three models produce high-quality translations and successfully satisfy the core task requirements.

The differences are limited to stylistic fidelity rather than meaning, accuracy, or terminology.

### Final Ranking

1. **ChatGPT (GPT-5.5)**
2. **Claude (Sonnet 5 Thinking)**
3. **Google Gemini (3.6 Flash)**

### Rationale

ChatGPT is preferred because it most closely preserves the source's neutral professional style while maintaining complete meaning preservation, accurate terminology, and natural Modern Standard Arabic.

Claude is a close second. It matches ChatGPT in meaning preservation, accuracy, fluency, and terminology but adopts a slightly more formal register through lexical choices.

Gemini also delivers an accurate and fluent translation but introduces the greatest degree of stylistic adaptation, making it less faithful to the source's original tone.

---

## 9. Confidence Rating

**Confidence: High**

The evaluation is supported by:

- Direct comparison with the source text.
- Independent Human Linguistic Analysis.
- Cross-response consistency verification.
- Evidence-based scoring for every criterion.
- Validation against the AI Evaluation Framework, Translation Evaluation Rubric, and Arabic Language Evaluation Rubric.

The remaining differences are limited to minor stylistic judgments and do not materially affect the reliability of the overall conclusions.

---

## 10. Conclusion

The Human-in-the-Loop (HITL) review confirmed the overall findings of the initial AI-generated evaluation while improving the supporting evidence, scoring consistency, and comparative analysis.

All three models produce publication-quality Modern Standard Arabic translations that accurately preserve the source meaning.

The primary distinction is stylistic fidelity:

- **ChatGPT** remains closest to the source's neutral professional register.
- **Claude** introduces a slightly more formal style while preserving meaning.
- **Gemini** employs a more literary and expressive style without affecting translation accuracy.

Overall, **ChatGPT (GPT-5.5)** is the preferred translation because it best balances meaning preservation, linguistic quality, and fidelity to the source text.

---

## Results Summary

The Human-in-the-Loop (HITL) evaluation produced the following key findings:

- All three models generated fluent, publication-quality Modern Standard Arabic translations.
- All translations accurately preserved the source meaning and healthcare terminology.
- ChatGPT achieved the strongest balance of meaning preservation, stylistic fidelity, and natural language quality.
- Claude ranked a close second, differing mainly in stylistic register.
- Gemini remained highly accurate but adopted a more literary style than the source text.
- The human review confirmed the overall ranking while strengthening the supporting evidence and improving scoring consistency.

---

## Key Changes After Human Review

The Human Linguistic Analysis refined the initial AI-generated evaluation by strengthening the supporting evidence and improving consistency between qualitative observations and assigned scores.

The review confirmed the original ranking while providing a more detailed assessment of stylistic differences between the translations.

The principal revisions included:

- Refining the assessment of stylistic fidelity and register.
- Expanding the evidence supporting vocabulary and terminology choices.
- Improving consistency between assigned scores and supporting justifications.
- Clarifying the distinction between translation quality and stylistic preference.

The evaluation methodology, scoring framework, decision rules, and overall ranking remained unchanged.

---

# Lessons Learned

This case study highlights several broader insights into evaluating AI-generated translations using a structured, evidence-based framework.

## 1. High-quality translations can differ stylistically

Multiple models can preserve the source meaning while differing in tone, vocabulary, and register. Once meaning preservation is satisfied, stylistic fidelity becomes an important differentiator.

## 2. Structured evaluation improves consistency

Predefined rubrics, scoring guidance, and decision rules provide a transparent and reproducible basis for comparing translation quality while reducing subjective judgment.

## 3. Human review strengthens evaluation quality

Evidence-based human review can strengthen supporting evidence, refine stylistic analysis, and improve consistency between qualitative observations and assigned scores without changing the underlying evaluation methodology.

## 4. Transparency improves reproducibility

Documenting the complete evaluation workflow—from the initial assessment to the final revised evaluation—makes the evaluation easier to understand, reproduce, and audit.

## Key Takeaway

A structured AI evaluation framework combined with evidence-based Human-in-the-Loop (HITL) review enables more transparent, consistent, and reproducible assessments of AI-generated translations.

---

# Skills Demonstrated

This case study demonstrates the practical application of structured AI evaluation to a real-world English–Arabic translation task.

## AI Evaluation

- Applied a structured AI Evaluation Framework.
- Used predefined rubrics, scoring guidance, and decision rules.
- Produced evidence-based evaluation reports.

## Comparative LLM Evaluation

- Compared multiple LLMs on the same translation task.
- Identified qualitative differences using structured evaluation criteria.
- Applied evidence-based decision rules to determine the final preference.

## Translation Evaluation

- Evaluated meaning preservation, accuracy, terminology, stylistic fidelity, and Modern Standard Arabic quality.
- Distinguished translation quality from stylistic preference.
- Verified compliance with the prompt requirements.

## Human-in-the-Loop (HITL)

- Integrated independent human review into the evaluation workflow.
- Validated reviewer observations against textual evidence.
- Incorporated only evidence-supported revisions.

## Evidence-Based Analysis

- Supported conclusions with observable textual evidence.
- Maintained consistency between observations, scores, and final conclusions.
- Applied transparent evaluation throughout the study.

## Technical Documentation

- Produced a structured Markdown case study suitable for GitHub documentation.
- Documented the complete evaluation workflow to support transparency and reproducibility.

---

# Study Limitations

This case study compares three large language models on a single English–Arabic healthcare translation task. Although the evaluation follows a structured and reproducible methodology, the findings are limited to the evaluated prompt, source text, and model versions.

## Evaluation Scope

- Based on a single translation prompt and source text.
- Findings should not be generalized to other domains, language pairs, or prompt designs without additional evaluation.

## Model Versions

- Results apply only to the evaluated model versions.
- Future model updates may produce different outputs and rankings.

## Human Review

- The revised evaluation incorporates feedback from one independent reviewer with expertise in Modern Standard Arabic.
- Additional reviewers may provide further perspectives on stylistic differences, although all accepted revisions in this study were supported by textual evidence and the evaluation framework.

## Subjectivity

- Assessing style, tone, and naturalness requires informed human judgment.
- The AI Evaluation Framework reduces subjectivity through predefined criteria, evidence-based scoring, and transparent decision rules, but it does not eliminate it entirely.

## Reproducibility

The evaluation is reproducible when the same:

- Prompt
- Source text
- Model responses
- Evaluation framework
- Scoring methodology

are used.

Different prompts, source texts, or evaluation objectives may produce different comparative outcomes.

---

## Future Work

Future case studies could extend this work by:

- Evaluating additional LLMs.
- Comparing multiple translation domains (e.g., medical, legal, technical, and literary).
- Expanding the evaluation to larger benchmark datasets.
- Measuring inter-rater agreement across multiple human reviewers.
- Investigating the impact of different prompting strategies on translation quality.

---

## LEPS Compliance

This evaluation complies with the **LLM Evaluation Project Standard (LEPS) v1.0** by incorporating:

- Standardized project metadata
- Clearly defined evaluation objectives and scope
- Structured evaluation workflow
- Transparent evaluation methodology
- Evidence-based scoring and justification
- Human-in-the-Loop (HITL) validation
- Comparative model analysis
- Comprehensive reporting
- Documented limitations
- Reproducible evaluation process

The project demonstrates the application of LEPS to a structured Human-in-the-Loop evaluation of English–Arabic machine translation quality.

---

# Overall Conclusion

This case study demonstrates the value of combining a structured AI evaluation framework with evidence-based Human-in-the-Loop (HITL) review for evaluating English–Arabic machine translation.

All three models produced accurate, fluent, publication-quality Modern Standard Arabic translations. Once meaning preservation and translation accuracy were satisfied, the primary differences emerged in stylistic fidelity, vocabulary selection, and consistency with the source's neutral professional register.

The Human Linguistic Analysis strengthened the supporting evidence, improved consistency between qualitative observations and assigned scores, and increased the transparency of the evaluation while preserving the original methodology, decision rules, and overall conclusions.

This case study illustrates how structured human review can improve the reliability, consistency, and auditability of AI-assisted translation evaluations without changing the underlying evaluation framework.

---

# References

The following resources were used to conduct and document this evaluation.

## Evaluation Framework

- AI Evaluation Framework
- Translation Evaluation Rubric
- Arabic Language Evaluation Rubric
- Standard Scoring Guide
- Standard Evaluation Report Template

## Source Materials

- Original English healthcare text
- ChatGPT (GPT-5.5) translation
- Google Gemini (3.6 Flash) translation
- Claude (Sonnet 5 Thinking) translation

## Evaluation Documentation

- Initial Evaluation Report
- Human Linguistic Analysis
- Revised Evaluation Report

---

## Document Information

| Field | Value |
|--------|-------|
| **Project ID** | Evaluation 001 |
| **Document Title** | Human-in-the-Loop English–Arabic LLM Translation Evaluation Case Study |
| **Project Type** | LLM Evaluation Case Study |
| **Evaluation Method** | Human-in-the-Loop (HITL) Evaluation |
| **Version** | 1.1 |
| **Status** | Completed |
| **Last Updated** | July 2026 |
| **Project Standard** | LEPS v1.0 |
