# English–Arabic Translation Evaluation 01 – Healthcare Translation

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

- [Project Information](#project-information)
- [Evaluation Objective](#evaluation-objective)
- [Prompt](#prompt)
- [Model Responses](#model-responses)
- [Evaluation Criteria](#evaluation-criteria)
- [Evaluation Methodology](#evaluation-methodology)
- [Initial Evaluation](#initial-evaluation)
- [Human Linguistic Analysis](#human-linguistic-analysis)
- [Revised Evaluation](#revised-evaluation)
- [Key Changes After Human Review](#key-changes-after-human-review)
- [Lessons Learned](#lessons-learned)
- [Skills Demonstrated](#skills-demonstrated)
- [Study Limitations](#study-limitations)
- [Overall Conclusion](#overall-conclusion)
- [References](#references)

---

## Project Information

| Item | Details |
|------|---------|
| **Project Type** | Comparative LLM Evaluation Case Study |
| **Primary Domain** | Machine Translation |
| **Secondary Domain** | Arabic Language Evaluation |
| **Task** | English → Modern Standard Arabic (MSA) Translation |
| **Models Compared** | ChatGPT (GPT-5.5), Google Gemini (3.6 Flash), Claude (Sonnet 5 Thinking) |
| **Evaluation Framework** | AI Evaluation Framework |
| **Methodology** | Translation Rubric, Arabic Language Rubric, Standard 1–5 Scoring Guide, Human Expert Review, Evidence-Based Revision |
| **Evaluation Workflow** | Initial Evaluation → Human Expert Review → Evidence Validation → Revised Evaluation |
| **Status** | Completed |
| **Version** | 1.1 |
| **Date** | July 2026 |

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

## Evaluation Methodology

This case study follows the **AI Evaluation Framework** to perform a structured, evidence-based comparison of English-to-Arabic translation quality.

The evaluation was conducted in four phases.

### Phase 1 – Initial Evaluation

A custom GPT implementing the AI Evaluation Framework generated the initial evaluation. The assessment applied the Translation Rubric, Arabic Language Rubric, standard scoring guide, and predefined decision rules to produce a structured evaluation report.

### Phase 2 – Human Expert Review

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

- **ChatGPT** stays closest to the wording and structure of the source while remaining natural.
- **Claude** is similarly accurate but introduces a slight stylistic expansion ("فهو قادر على") and uses the singular "اتخاذ القرار السريري."
- **Gemini** is the most stylistically polished, but "يرسم ملامح جديدة للرعاية الصحية" is a more interpretive rendering than the source's neutral "is transforming healthcare."

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

Gemini employs a more elevated and literary writing style than the source. The expression *"يرسم ملامح جديدة"* is elegant and well suited to literary or motivational writing, but it is more rhetorical than the source's neutral expression *"is transforming"*. The translation also demonstrates the strongest use of formal vocabulary, including *"إمكانات"* and *"أخصائيي الرعاية الصحية"*, both of which are highly appropriate for formal publications.

However, the adjective *"هائلة"* is more emphatic than the source's *"great"*, slightly amplifying the intended meaning. Furthermore, while *"ينبغي أن يكون مكمّلًا"* is grammatically correct, an expression such as *"ينبغي أن يكون له دورٌ مكمّل"* could communicate the supporting role of AI more explicitly. These observations reflect stylistic preferences rather than translation errors.

### ChatGPT

ChatGPT produces the most balanced translation for a journalistic or academic article. The grammar is accurate, the vocabulary is clear and precise, and the overall tone closely matches that of the original English text. The inclusion of *"أداةً"* effectively emphasizes that artificial intelligence serves as a supporting tool rather than a replacement for healthcare professionals while remaining faithful to the source.

The expression *"مكملة"* is appropriate and natural. Although alternatives such as *"مساندة"* or *"داعمة"* could provide a slightly more explicit description of the supporting role, this represents a stylistic preference rather than a translation issue.

### Claude

Claude occupies a middle ground between ChatGPT and Gemini. It combines ChatGPT's relatively faithful sentence structure with Gemini's preference for more elevated vocabulary, resulting in a translation that shares many of the strengths and minor stylistic characteristics of both.

Like Gemini, Claude uses the stronger adjective *"هائلة"*, which slightly increases the emphasis compared with the source text. At the same time, its sentence structure remains closer to the original, making it more stylistically balanced than Gemini while still exhibiting occasional literary tendencies.

---

# Revised Evaluation

## Revision Process

Following the Human Expert Review, all reviewer observations were independently assessed against the source text, the model responses, and the AI Evaluation Framework.

Each proposed revision was evaluated according to the following principles:

- Supported by direct textual evidence.
- Consistent with the Translation Evaluation Rubric.
- Consistent with the Arabic Language Evaluation Rubric.
- Compatible with the AI Evaluation Framework's scoring methodology and decision rules.

Observations that did not satisfy these requirements were not incorporated into the final evaluation.

## Scope of the Revisions

The revision process focused on improving:

- Supporting evidence.
- Consistency between scores and qualitative analysis.
- Stylistic fidelity assessment.
- Terminology analysis.
- Transparency of evaluation decisions.

The following aspects remained unchanged:

- Evaluation methodology.
- Evaluation criteria.
- Scoring guide.
- Decision rules.
- Source text.
- Model responses.

## Final Evaluation

The report below represents the final evidence-based assessment following completion of the Human-in-the-Loop evaluation workflow.

---

## Revised Standard Evaluation Report

### 1. Instruction Verification

| Requirement | Status | Evidence |
|-------------|--------|----------|
| Modern Standard Arabic | All satisfied | All translations use standard MSA. |
| Preserve meaning | All satisfied | No omissions or mistranslations. |
| Preserve tone and formality | Partially differentiated | Gemini and Claude introduce a slightly more literary register than the source. ChatGPT remains closest to the original neutral style. |
| Natural Arabic | All satisfied | All translations are fluent and publication-ready. |
| No summarization or omission | All satisfied | All source information is preserved. |

---

### 2. Evidence Summary

#### Shared Strengths

All three translations satisfy the prompt requirements and demonstrate a high standard of translation quality. Each accurately preserves the source meaning, uses appropriate healthcare terminology, and produces fluent, publication-quality Modern Standard Arabic without omissions or factual inaccuracies.

The primary differences between the translations arise from stylistic fidelity, vocabulary selection, and consistency with the source text's neutral register.

#### Key Differences

- **ChatGPT** maintains the most consistent neutral, journalistic style throughout.
- **Gemini** employs more elevated and formal vocabulary but also introduces literary expressions that slightly shift the source's tone.
- **Claude** combines ChatGPT's neutral structure with Gemini's elevated vocabulary, resulting in a mixed stylistic register.

---

### 3. Criterion-by-Criterion Evaluation

#### A. Google Gemini (3.6 Flash)

| Criterion | Score | Justification |
|-----------|:-----:|---------------|
| Meaning Preservation | **4.5 / 5** | Preserves all information but introduces stylistic adaptation beyond the source. |
| Accuracy | **5.0 / 5** | Medical meaning is fully preserved. |
| Language Quality | **5.0 / 5** | Excellent grammar and highly polished Arabic. |
| Fluency | **5.0 / 5** | Smooth and natural. |
| Style & Tone | **4.0 / 5** | Mixes a neutral informational style with literary wording. *يرسم ملامح جديدة* is more rhetorical than *is transforming*, while *هائلة* is stronger than *great*. |
| Terminology | **5.0 / 5** | Uses highly formal vocabulary such as *إمكانات* and *أخصائيي الرعاية الصحية*, both well suited to formal publications. |
| Instruction Following | **4.5 / 5** | Follows the task well but introduces stylistic changes that make the translation slightly less faithful to the source's register. |

**Evidence**

The assigned scores reflect the stylistic observations documented in the Human Linguistic Analysis. Gemini's use of metaphorical phrasing (*يرسم ملامح جديدة*) and stronger lexical emphasis (*هائلة*) results in a translation that is stylistically more elevated than the source while preserving its meaning.

---

#### B. ChatGPT (GPT-5.5)

| Criterion | Score | Justification |
|-----------|:-----:|---------------|
| Meaning Preservation | **5.0 / 5** | Fully preserves the original meaning. |
| Accuracy | **5.0 / 5** | No factual or terminological issues. |
| Language Quality | **5.0 / 5** | Excellent grammar and vocabulary suitable for journalistic and professional writing. |
| Fluency | **5.0 / 5** | Natural and highly readable. |
| Style & Tone | **5.0 / 5** | Closely matches the source's neutral professional tone. |
| Terminology | **5.0 / 5** | Clear, consistent terminology. The addition of *أداةً* effectively conveys AI's supporting role without altering the meaning. |
| Instruction Following | **5.0 / 5** | Fully satisfies all requirements. |

**Evidence**

The translation maintains the source's neutral professional tone, uses clear publication-quality Modern Standard Arabic, and consistently supports the assigned scores for stylistic fidelity and terminology.

---

#### C. Claude (Sonnet 5 Thinking)

| Criterion | Score | Justification |
|-----------|:-----:|---------------|
| Meaning Preservation | **5.0 / 5** | Meaning is fully preserved. |
| Accuracy | **5.0 / 5** | No translation errors. |
| Language Quality | **5.0 / 5** | Excellent Modern Standard Arabic. |
| Fluency | **5.0 / 5** | Smooth and natural. |
| Style & Tone | **4.5 / 5** | Combines neutral phrasing with elevated vocabulary, resulting in a mixed stylistic register. |
| Terminology | **4.5 / 5** | Strong terminology overall, though *إمكانات هائلة* is slightly stronger than the source and *اتخاذ القرار السريري* is marginally less faithful than the plural form in the source. |
| Instruction Following | **5.0 / 5** | Fully satisfies the prompt. |

**Evidence**

Claude combines a structure that closely follows the source with vocabulary that is slightly more elevated, producing a balanced translation consistent with the observations presented in the Human Linguistic Analysis.

---

### 4. Comparison Summary

| Model | Strengths | Minor Weaknesses |
|-------|-----------|------------------|
| **Google Gemini (3.6 Flash)** | Rich formal vocabulary (*إمكانات، أخصائيي الرعاية الصحية*) and elegant Arabic. | Literary opening (*يرسم ملامح جديدة*) and stronger adjective (*هائلة*) create a mixed tone and slightly reduce stylistic fidelity. |
| **ChatGPT (GPT-5.5)** | Most consistent tone, neutral style, excellent grammar, and clear vocabulary suitable for articles and journals. The use of *أداةً* clearly reinforces the supporting role of AI. | *مكملة* is appropriate, though a more explicit supporting adjective could be considered as a stylistic alternative. |
| **Claude (Sonnet 5 Thinking)** | Combines ChatGPT's faithful structure with Gemini's elevated vocabulary. Natural and fluent. | Shares Gemini's stronger wording (*هائلة*) while also introducing slight stylistic enhancements, resulting in a mixed register. |

---

### 5. Critical Evaluation Criteria

The critical criteria for this evaluation are **Meaning Preservation** and **Accuracy**. All three translations satisfy these criteria; therefore, no critical criterion determines the outcome. The preference is based on secondary criteria—particularly **Style & Tone**, **Terminology**, and **Instruction Following**—consistent with the AI Evaluation Framework.

**Decision Rule Applied:** Near-tie. Since all responses satisfy the critical criteria, the final ranking is based on qualitative differences in stylistic fidelity and consistency rather than numerical scores alone.

---

### 6. Overall Preference

🥇 **ChatGPT (GPT-5.5)**

The strongest overall translation. It best preserves the original's meaning, tone, and level of formality while using clear, publication-quality Modern Standard Arabic. Its style remains consistently neutral and aligns closely with the source text.

🥈 **Claude (Sonnet 5 Thinking)**

A very strong translation that combines the structural fidelity of ChatGPT with some of Gemini's elevated vocabulary. The mixture of neutral and literary elements makes it slightly less stylistically consistent than ChatGPT.

🥉 **Google Gemini (3.6 Flash)**

An excellent translation with sophisticated vocabulary and polished Arabic. However, the literary opening (*يرسم ملامح جديدة*) and the stronger adjective (*هائلة*) shift the register away from the source's neutral informational tone, making it the least faithful stylistically despite its high linguistic quality.

---

### 7. Confidence Rating

**High**

The conclusions are based on direct textual comparison using the Translation and Arabic Language rubrics. The differences are observable, supported by evidence, and concern stylistic fidelity rather than translation correctness.

---

### 8. Conclusion

All three translations are accurate, fluent, and suitable for publication. This remains a near-tie, as none fails the critical criteria of meaning preservation or accuracy. The deciding factor is consistency with the source's neutral tone and level of formality. ChatGPT achieves the best balance of fidelity, clarity, and natural Modern Standard Arabic, while Claude follows closely by blending neutral and elevated stylistic choices. Gemini demonstrates the richest formal vocabulary but introduces literary expressions and stronger wording that make its register less consistent with the original.

---

## Key Changes After Human Review

The Human Expert Review refined the initial AI-generated evaluation by strengthening the supporting evidence and improving consistency between qualitative observations and quantitative scores. The review confirmed the original ranking while identifying stylistic distinctions that warranted more detailed analysis.

The principal revisions included:

- A more nuanced assessment of stylistic fidelity and register.
- Expanded evidence supporting vocabulary and terminology choices.
- Improved consistency between assigned scores and supporting justifications.
- Clearer distinction between objective translation quality and stylistic preference.

No revisions affected the evaluation methodology, scoring framework, decision rules, or final ranking.

---

# Lessons Learned

This case study highlights several broader insights into evaluating AI-generated translations using a structured, evidence-based framework.

## 1. High-quality translations can differ stylistically

Multiple models may accurately preserve the source meaning while varying in tone, vocabulary, and stylistic register. Evaluating these differences requires criteria that extend beyond semantic correctness.

## 2. Structured evaluation improves consistency

Applying predefined rubrics, scoring guidance, and decision rules provides a transparent and reproducible basis for comparing translation quality and reduces reliance on subjective preference.

## 3. Human review strengthens evaluation quality

An independent human review can refine supporting evidence, clarify stylistic distinctions, and improve consistency between qualitative observations and quantitative scores without changing the underlying evaluation methodology.

## 4. Transparency supports reproducibility

Documenting the complete evaluation workflow—from initial assessment through evidence validation and final revision—allows others to understand, reproduce, and critically assess the evaluation process.

## Key Takeaway

A structured evaluation framework combined with evidence-based Human-in-the-Loop (HITL) review enables more transparent, consistent, and reproducible assessments of AI-generated translations.

---

# Skills Demonstrated

This case study demonstrates the practical application of a structured AI evaluation methodology to a real-world machine translation task.

## AI Evaluation Framework Application

- Applied a structured AI Evaluation Framework to assess LLM-generated translations.
- Used predefined rubrics, scoring guidance, and decision rules to ensure consistent and reproducible evaluations.
- Produced evidence-based evaluation reports aligned with the framework.

## Comparative LLM Evaluation

- Performed comparative evaluation of multiple LLMs on the same translation task.
- Identified qualitative differences using primary and secondary evaluation criteria.
- Applied structured decision rules to determine the final ranking.

## Translation Evaluation

- Evaluated meaning preservation, accuracy, stylistic fidelity, terminology, and Modern Standard Arabic quality.
- Distinguished objective translation quality from stylistic preference.
- Assessed compliance with prompt requirements.

## Human-in-the-Loop (HITL) Evaluation

- Integrated independent human review into the evaluation workflow.
- Validated reviewer observations against textual evidence and predefined rubrics.
- Incorporated only evidence-supported revisions into the final assessment.

## Evidence-Based Analysis

- Supported evaluation findings with observable textual evidence.
- Maintained consistency between qualitative analysis, quantitative scores, and final conclusions.
- Applied transparent reasoning throughout the evaluation process.

## Technical Documentation

- Produced a structured Markdown case study suitable for technical documentation and GitHub portfolios.
- Documented the complete evaluation workflow to support transparency and reproducibility.

---

# Study Limitations

This case study presents an evidence-based comparison of three large language models on a single English-to-Arabic healthcare translation task. Although the evaluation follows a structured and reproducible methodology, the findings are specific to the evaluated prompt, source text, and model versions, and should not be generalized without additional evidence.

## Evaluation Scope

- The evaluation is based on a single translation prompt and source text.
- Results should not be generalized to other translation domains, language pairs, or prompt designs without additional evaluation.

## Model Versions

- The findings apply only to the model versions evaluated in this case study.
- Future model updates may produce different outputs and rankings.

## Human Review

- The revised evaluation incorporates feedback from one independent reviewer with expertise in Modern Standard Arabic.
- Additional reviewers could provide further perspectives on stylistic preferences, although all accepted revisions in this study were supported by textual evidence and the evaluation framework.

## Subjectivity

- Assessment of style, tone, and naturalness involves informed human judgment.
- The AI Evaluation Framework reduces subjectivity through predefined criteria, structured scoring, evidence-based reasoning, and transparent decision rules, but it does not eliminate it entirely.

## Reproducibility

- The evaluation methodology is reproducible when applied to the same prompt, source text, model responses, and evaluation framework.
- Different prompts or evaluation objectives may produce different comparative outcomes.

## Future Work

Future case studies may extend this work by:

- Evaluating additional LLMs.
- Comparing multiple translation domains (e.g., medical, legal, technical, and literary).
- Using larger benchmark datasets.
- Measuring inter-rater agreement across multiple human reviewers.
- Investigating the impact of different prompting strategies on translation quality.

---

# Overall Conclusion

This case study demonstrates the value of combining a structured AI evaluation framework with evidence-based Human-in-the-Loop (HITL) review to assess machine translation quality. Although all three models produced accurate, publication-quality Modern Standard Arabic translations, the evaluation shows that stylistic fidelity, vocabulary selection, and consistency with the source text's register become the primary differentiators once meaning preservation and accuracy are satisfied.

The Human Expert Review strengthened the supporting evidence and improved the consistency between qualitative analysis and assigned scores while preserving the original methodology, decision rules, and overall ranking. This illustrates how structured human review can enhance the transparency and reliability of AI-assisted evaluations without altering their methodological integrity.

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
- Human Expert Review
- Revised Evaluation Report

## Document Information

- **Case Study:** English–Arabic Translation Evaluation 01 – Healthcare Translation
- **Version:** 1.1
- **Status:** Final
- **Workflow:** Human-in-the-Loop (HITL) Evaluation
- **Last Updated:** July 2026
