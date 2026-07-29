# English–Arabic Translation Evaluation 01 – Healthcare Translation

---

## Case Study Overview

This case study evaluates and compares the English-to-Arabic translation capabilities of multiple large language models (LLMs) on a healthcare translation task.

The evaluation focuses on meaning preservation, accuracy, stylistic fidelity, terminology, fluency, and publication-quality Modern Standard Arabic (MSA).

The evaluation was performed using a custom GPT built on the **AI Evaluation Framework**. The custom GPT applies the framework's evaluation methodology, Translation Rubric, Arabic Language Rubric, scoring guide, and decision rules to produce a structured evaluation report.

To improve reliability, the initial AI-generated evaluation was subsequently reviewed by a human evaluator with expertise in Modern Standard Arabic. Supported observations were incorporated into a revised evaluation, demonstrating a structured **human-in-the-loop evaluation workflow**.

This case study documents the complete evaluation process, including the initial assessment, human expert review, and the final evidence-based revision.

---

## Project Information

**Project Type:** Comparative LLM Evaluation Case Study

**Primary Domain:** Machine Translation

**Secondary Domain:** Arabic Language Evaluation

**Task:** English → Modern Standard Arabic (MSA) Translation

**Models Compared:**
- ChatGPT (GPT-5.5)
- Google Gemini (3.6 Flash)
- Claude (Sonnet 5 Thinking)

**Evaluation Framework:** AI Evaluation Framework

**Evaluation Methodology:**
- Custom GPT implementing the AI Evaluation Framework
- Translation Rubric (Primary)
- Arabic Language Rubric (Secondary)
- Standard 1–5 Scoring Guide
- Human Expert Review
- Evidence-Based Revision

**Evaluation Workflow:**
1. Initial evaluation using the AI Evaluation Framework Custom GPT.
2. Independent human expert review.
3. Validation of reviewer observations against the evaluation framework.
4. Revised evaluation incorporating supported feedback.

**Status:** Completed

**Version:** 1.1

**Date:** July 2026

---

## Evaluation Objective

Evaluate and compare the English-to-Arabic translation capabilities of ChatGPT (GPT-5.5), Google Gemini (3.6 Flash), and Claude (Sonnet 5 Thinking) using a structured evaluation methodology.

The evaluation examines each model's ability to:

- Preserve the original meaning without omission or distortion.
- Maintain the source text's tone and level of formality.
- Produce natural, publication-quality Modern Standard Arabic.
- Use accurate and appropriate healthcare terminology.
- Follow all prompt instructions consistently.

The evaluation also demonstrates a structured human-in-the-loop workflow, where an initial AI-generated assessment is reviewed by a human expert. Reviewer observations are validated against the AI Evaluation Framework before being incorporated into the final evaluation, improving transparency, consistency, and evidence-based decision-making.

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

The evaluation considers the following criteria:

- Meaning Preservation
- Accuracy
- Language Quality
- Fluency
- Style & Tone
- Terminology
- Instruction Following
- Overall Preference

Each criterion is scored on a **5-point scale**, where **5.0** represents excellent performance.

Small score differences (for example, **4.5 vs. 5.0**) indicate meaningful qualitative distinctions between high-quality translations rather than large differences in overall capability.

The final ranking is determined using the AI Evaluation Framework's decision rules. Critical criteria (Meaning Preservation and Accuracy) are evaluated first. When multiple responses satisfy the critical criteria, the final preference is based on qualitative differences in stylistic fidelity, terminology, instruction following, and overall translation quality.

---

## Evaluation Methodology

This case study follows the AI Evaluation Framework to perform a structured comparative evaluation of English-to-Arabic translation quality.

The initial evaluation was generated using a custom GPT specifically developed to implement the AI Evaluation Framework. The custom GPT applies the framework's evaluation methodology, Translation Rubric, Arabic Language Rubric, scoring guide, and decision rules to produce a standardized evaluation report.

To improve evaluation reliability, the initial report underwent an independent human expert review. The reviewer assessed the linguistic analysis, evidence, and scoring, providing qualitative observations on translation fidelity, stylistic choices, terminology, and Modern Standard Arabic usage.

Reviewer observations were not incorporated automatically. Each observation was validated against the source text, model responses, and the AI Evaluation Framework before determining whether revisions were warranted.

This human-in-the-loop workflow ensures that the final evaluation remains evidence-based, transparent, and consistent with the predefined evaluation methodology.

### Evaluation Workflow

1. Generate an initial evaluation using the AI Evaluation Framework Custom GPT.
2. Perform an independent human expert linguistic review.
3. Validate reviewer observations against the evaluation framework and textual evidence.
4. Revise the evaluation where supported by evidence.
5. Produce the final evaluation report.

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

# Human Expert Review

Following the initial evaluation, the report was independently reviewed by a human evaluator with expertise in Modern Standard Arabic.

The purpose of the review was not to replace the initial evaluation, but to assess whether the evidence, reasoning, and scoring accurately reflected the linguistic characteristics of the translations.

The review focused on:

- Meaning preservation
- Stylistic fidelity to the source text
- Modern Standard Arabic quality
- Vocabulary selection
- Tone and level of formality
- Healthcare terminology
- Translation naturalness
- Consistency between textual evidence and assigned scores

Reviewer observations were treated as qualitative feedback rather than authoritative corrections. Each observation was subsequently validated against the source text, the model responses, and the AI Evaluation Framework before determining whether revisions to the evaluation were warranted.

The following qualitative analysis summarizes the reviewer's observations.

## Human Linguistic Analysis

*(Qualitative Analysis of the Translations

All three models successfully satisfied the prompt requirements. They preserved the original meaning, maintained a formal register, and produced fluent Modern Standard Arabic suitable for publication. The differences lie primarily in stylistic choices, vocabulary selection, and consistency with the source text's tone.

Gemini

Gemini employs a more elevated and literary writing style than the source. The expression "يرسم ملامح جديدة" is elegant and effective in literary or inspirational contexts, but it is more rhetorical than the neutral expression "is transforming" used in the original text. The translation also demonstrates the strongest use of formal vocabulary, such as "إمكانات" and "أخصائيي الرعاية الصحية", which are highly appropriate for formal writing.

However, the adjective "هائلة" is more emphatic than the source's "great", slightly amplifying the intended meaning. Additionally, while "ينبغي أن يكون مكمّلًا" is grammatically correct, a formulation such as "ينبغي أن يكون له دورٌ مكمّل" would express the supporting role of AI more explicitly. Overall, Gemini introduces minor stylistic adaptations that make the translation less faithful to the source's neutral tone despite its excellent linguistic quality.

ChatGPT

ChatGPT produces the most balanced translation for a journalistic or academic article. The grammar is accurate, the vocabulary is clear and precise, and the tone closely matches the original English text. The inclusion of "أداةً" effectively emphasizes that artificial intelligence serves as a supporting tool rather than a replacement for healthcare professionals, while remaining faithful to the source.

The expression "مكملة" is appropriate and natural; however, a more explicit alternative such as "مساندة" or "داعمة" could further clarify the intended supporting role. This is a stylistic preference rather than a translation issue.

Claude

Claude represents a middle ground between ChatGPT and Gemini. It combines ChatGPT's relatively faithful sentence structure with Gemini's preference for more elevated vocabulary. As a result, it shares many of the strengths and minor weaknesses observed in both translations.

Like Gemini, Claude uses the stronger adjective "هائلة", which slightly increases the emphasis compared with the source. At the same time, its overall structure remains close to the original, making it more stylistically balanced than Gemini while still exhibiting occasional literary tendencies.)*

---

# Revised Evaluation

Following the human expert review, each observation was independently validated against the source text, the model responses, and the AI Evaluation Framework.

Only observations supported by textual evidence and consistent with the evaluation methodology were incorporated into the revised report. The overall evaluation methodology, scoring guide, and decision rules remained unchanged.

The revised evaluation presented below represents the final assessment for this case study.

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

- All three translations accurately preserve the source meaning.
- All use correct healthcare terminology.
- All are grammatically correct and suitable for publication.
- None omit or distort any information.

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

- *يرسم ملامح جديدة* is a metaphorical expression that elevates the style beyond the original.
- *هائلة* amplifies the intensity of *great potential*.
- *ينبغي أن يكون مكملاً* is correct, although an expression such as *له دور مكمل* could sound more explicit and natural in formal prose.

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

- Uses straightforward, publication-style Arabic.
- *أداةً مكملةً* clearly communicates that AI supports rather than replaces healthcare professionals.
- While *مكملة* is appropriate, alternatives such as *مساندة* or *داعمة* could also be effective stylistic choices; however, this does not affect translation quality.

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

- Uses *إمكانات هائلة*, similar to Gemini.
- Retains a sentence structure closer to ChatGPT.
- Represents a balance between literal fidelity and stylistic enhancement.

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

# Key Changes After Human Review

The human expert review refined the initial evaluation by validating the consistency between the assigned scores, supporting evidence, and the AI Evaluation Framework. The review did not alter the overall ranking of the models but strengthened the justification for the final conclusions.

## Accepted Revisions

### Instruction Verification

- Refined the assessment of **tone and formality** to distinguish stylistic differences between the translations.
- Recognized that ChatGPT remained closest to the source's neutral register, while Gemini and Claude adopted a slightly more literary style.

### Evidence Summary

- Expanded the comparison of stylistic differences between the three translations.
- Added evidence highlighting ChatGPT's consistent neutral style, Gemini's elevated vocabulary, and Claude's balanced approach.

### Gemini

- Revised the **Style & Tone** score from **4.5/5** to **4.0/5** to reflect the use of literary expressions beyond the source text.
- Revised **Instruction Following** from **5.0/5** to **4.5/5** because stylistic adaptations slightly reduced fidelity to the requested register.
- Added supporting evidence for:
  - *يرسم ملامح جديدة*
  - *إمكانات هائلة*
  - The discussion of *ينبغي أن يكون مكملاً* as a stylistic choice.

### ChatGPT

- Expanded the justification for terminology and stylistic fidelity.
- Added evidence explaining how *أداةً مكملةً* reinforces the supporting role of AI without altering the source meaning.
- Noted that alternatives such as *مساندة* or *داعمة* represent stylistic preferences rather than translation improvements.

### Claude

- Expanded the stylistic analysis to explain how Claude combines ChatGPT's structural fidelity with Gemini's elevated vocabulary.
- Added evidence regarding the stronger wording (*هائلة*) and the singular form (*اتخاذ القرار السريري*).

## Overall Impact

The human expert review strengthened the evidence base, improved the consistency between qualitative observations and assigned scores, and provided more detailed linguistic justification for the final evaluation.

The overall ranking remained unchanged:

1. 🥇 ChatGPT (GPT-5.5)
2. 🥈 Claude (Sonnet 5 Thinking)
3. 🥉 Google Gemini (3.6 Flash)

---

# Lessons Learned

This case study demonstrates several important principles for evaluating large language model (LLM) translations.

## 1. High-quality translations can still differ meaningfully

All three models produced accurate, fluent, publication-quality Modern Standard Arabic. The differences emerged primarily in stylistic fidelity rather than translation correctness.

## 2. Meaning preservation alone is not sufficient

Although all translations preserved the source meaning, subtle differences in tone, vocabulary, and register influenced the overall assessment. Expressions such as *يرسم ملامح جديدة* and *هائلة* illustrate how stylistic choices can shift a translation away from the source's neutral voice.

## 3. Human review improves evaluation quality

The human expert review strengthened the evaluation by identifying stylistic nuances that warranted additional evidence and minor score adjustments. The review improved consistency between qualitative observations and quantitative scores while preserving the original decision-making framework.

## 4. Evidence-based revisions increase transparency

Every modification in the revised evaluation was supported by observable textual evidence. Unsupported opinions or purely subjective preferences were not incorporated, ensuring that the evaluation remained objective and reproducible.

## 5. Ranking should not rely solely on numerical scores

This evaluation followed a qualitative decision-making approach. Since all models satisfied the critical criteria of Meaning Preservation and Accuracy, the final ranking was determined using secondary criteria, including stylistic fidelity, terminology, instruction following, and overall usefulness.

## Key Takeaway

A rigorous LLM evaluation combines structured scoring with evidence-based human validation. Human reviewers should refine and strengthen the evaluation rather than replace the evaluation framework, resulting in more reliable, transparent, and reproducible assessments.

---

# Skills Demonstrated

This case study demonstrates the following evaluation and analytical skills:

## AI Evaluation

- Comparative evaluation of multiple LLM responses.
- Application of structured evaluation rubrics.
- Evidence-based scoring and qualitative analysis.
- Consistent use of predefined decision rules.
- Identification of critical and secondary evaluation criteria.

## Translation Evaluation

- Assessment of meaning preservation.
- Evaluation of stylistic fidelity.
- Analysis of tone and level of formality.
- Evaluation of terminology consistency.
- Assessment of fluency and publication-quality Modern Standard Arabic.

## Human-in-the-Loop Evaluation

- Independent validation of AI-generated evaluations.
- Critical review of qualitative observations.
- Evidence-based revision of scores and justifications.
- Integration of expert linguistic feedback while maintaining methodological consistency.

## Analytical Skills

- Comparative reasoning across multiple model outputs.
- Identification of subtle linguistic differences.
- Separation of objective evidence from subjective preference.
- Transparent documentation of evaluation decisions.

## Technical Communication

- Production of structured evaluation reports.
- Clear presentation of supporting evidence.
- Consistent documentation of methodology.
- Reproducible evaluation workflow suitable for future case studies.

---

# Study Limitations

This case study provides a structured comparison of three LLM-generated translations under a single translation task. While the evaluation follows a consistent methodology, several limitations should be considered.

## Scope

- The evaluation is based on a single English-to-Arabic healthcare translation.
- Results should not be generalized to all translation domains, language pairs, or prompt types.

## Model Versions

- The findings apply only to the specific model versions evaluated in this case study.
- Future model updates may produce different outputs and evaluation outcomes.

## Human Review

- The revised evaluation incorporates feedback from a single human linguistic reviewer.
- Although all revisions were validated against the evaluation framework, additional independent reviewers could provide further perspectives on stylistic preferences.

## Subjectivity

- Translation evaluation contains an inherent degree of subjectivity, particularly when assessing style, tone, and naturalness.
- The evaluation framework minimizes subjectivity through predefined rubrics, evidence-based reasoning, and transparent decision rules, but it cannot eliminate it entirely.

## Reproducibility

- The methodology is reproducible when applied to the same prompt, source text, and model responses.
- Different prompts or source texts may lead to different comparative outcomes.

## Future Work

Future case studies may expand this evaluation by:

- Comparing additional LLMs.
- Evaluating multiple translation domains (medical, legal, technical, literary, etc.).
- Including larger translation datasets.
- Measuring inter-rater agreement using multiple human evaluators.
- Comparing performance across different prompt designs and translation strategies.

---

# References

The evaluation methodology and conclusions presented in this case study are based on the following resources:

## Evaluation Framework

- **AI Evaluation Framework** – Primary methodology used for planning, conducting, and documenting the evaluation.

## Evaluation Rubrics

- **Translation Evaluation Rubric** – Used to assess meaning preservation, accuracy, terminology, style, and instruction following.

- **Arabic Language Evaluation Rubric** – Used to evaluate Modern Standard Arabic quality, grammar, fluency, vocabulary, and naturalness.

## Scoring Methodology

- **Standard 1–5 Scoring Guide** – Applied consistently across all evaluation criteria.

- **Standard Evaluation Report Template** – Used to ensure a consistent structure for documenting findings.

## Evaluation Process

This case study followed a Human-in-the-Loop (HITL) evaluation workflow consisting of:

1. Initial AI-generated evaluation.
2. Independent human linguistic review.
3. Evidence validation against the evaluation framework.
4. Revised evaluation incorporating only supported observations.
5. Documentation of accepted revisions and final conclusions.

## Source Material

- Original English healthcare paragraph provided in the evaluation prompt.
- Translation responses generated by:
  - ChatGPT (GPT-5.5)
  - Google Gemini (3.6 Flash)
  - Claude (Sonnet 5 Thinking)

---

**Document Status:** Final  
**Version:** 1.1  
**Evaluation Status:** Completed  
**Last Updated:** July 2026
