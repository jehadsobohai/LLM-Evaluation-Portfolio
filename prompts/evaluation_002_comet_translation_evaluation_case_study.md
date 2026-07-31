# Evaluation 002: COMET-Based Evaluation of English–Arabic LLM Translation Quality

## Project Information

| Field | Value |
|--------|-------|
| **Project ID** | Evaluation 002 |
| **Project Type** | LLM Evaluation Case Study |
| **Domain** | English–Arabic Machine Translation |
| **Task** | Translation Quality Evaluation |
| **Evaluation Method** | Hybrid (COMET + Human Evaluation) |
| **Models Compared** | ChatGPT (GPT-5.5), Google Gemini (3.6 Flash), Claude Sonnet 5 Thinking |
| **Status** | Completed |
| **Version** | 1.0 |
| **Date** | July 2026 |

> **Project Standard**

This evaluation follows the **LLM Evaluation Project Standard (LEPS) v1.0**, ensuring a standardized project structure, evaluation workflow, evidence-based scoring, transparent reporting, and reproducible methodology.

---

## Table of Contents

1. [Project Overview](#project-overview)
2. [Executive Summary](#executive-summary)
3. [Introduction](#introduction)
4. [What is COMET?](#what-is-comet)
5. [Why COMET?](#why-comet)
6. [Evaluation Scope](#evaluation-scope)
7. [Evaluation Workflow](#evaluation-workflow)
8. [Evaluation Criteria](#evaluation-criteria)
9. [Evaluation Assets](#evaluation-assets)
10. [Source Text](#source-text)
11. [Reference Translation](#reference-translation)
12. [Candidate Translations](#candidate-translations)
13. [Model Responses](#model-responses)
14. [COMET Evaluation Methodology](#comet-evaluation-methodology)
15. [Installing COMET](#installing-comet)
16. [Running COMET](#running-comet)
17. [COMET Results](#comet-results)
18. [Comparison with Human Evaluation](#comparison-with-human-evaluation)
19. [Discussion](#discussion)
20. [Limitations](#limitations)
21. [Conclusion](#conclusion)
22. [References](#references)

---

## Project Overview

This case study demonstrates how to evaluate the quality of English-to-Arabic machine translation produced by modern Large Language Models (LLMs) using the COMET automatic evaluation metric.

Three state-of-the-art LLMs were evaluated:

- ChatGPT (GPT-5.5)
- Gemini 3.6 Flash
- Claude Sonnet 5 Thinking

Each model translated the same English source text into Modern Standard Arabic. The translations were evaluated using two complementary approaches:

1. **Expert Human Evaluation** based on linguistic quality, fluency, terminology, accuracy, style, and faithfulness.
2. **Automatic Evaluation** using COMET (Crosslingual Optimized Metric for Evaluation of Translation), a neural evaluation metric trained on human judgments.

The objective is to compare automatic metric scores with expert human assessment and analyze where the two evaluation methods agree or differ.

---

## Executive Summary

Large Language Models have significantly improved machine translation quality, making automatic evaluation increasingly important for benchmarking and model comparison. Traditional automatic metrics such as BLEU rely primarily on n-gram overlap and often fail to capture semantic similarity or translation quality.

COMET addresses these limitations by using multilingual transformer models trained on human quality judgments. Instead of counting matching words, COMET evaluates whether a translation preserves the meaning of the source while remaining close to a high-quality reference translation.

In this project, ChatGPT, Gemini, and Claude translated the same English healthcare paragraph into Modern Standard Arabic. Their translations were evaluated using COMET and compared with an independent expert linguistic assessment.

The results showed that all three models produced excellent translations, with COMET scores above **0.90**, indicating a high degree of semantic similarity to the professional reference translation. Human evaluation similarly found all translations to be of publication quality, while highlighting subtle stylistic differences that automatic metrics cannot fully capture.

This case study illustrates how automatic evaluation metrics and expert human judgment complement each other when assessing translation quality.

---

## Introduction

Evaluating machine translation has traditionally relied on automatic metrics such as BLEU, METEOR, and TER. Although these metrics are useful for large-scale benchmarking, they often struggle to measure semantic equivalence, fluency, and natural language quality.

Recent advances in multilingual neural models have led to the development of COMET (Crosslingual Optimized Metric for Evaluation of Translation), which uses pretrained transformer models fine-tuned on human evaluation data. COMET consistently demonstrates stronger correlation with human judgments than traditional lexical overlap metrics.

Unlike BLEU, COMET evaluates:

- Semantic preservation
- Contextual meaning
- Fluency
- Translation adequacy
- Similarity to expert human translations

For this reason, COMET has become one of the leading automatic evaluation metrics in machine translation research and is widely used in academic benchmarks such as WMT (Workshop on Machine Translation).

This project applies COMET to compare English-to-Arabic translations generated by three leading LLMs and investigates how automatic evaluation aligns with detailed expert linguistic assessment.

---

## What is COMET?

COMET (Crosslingual Optimized Metric for Evaluation of Translation) is a neural machine translation evaluation framework developed by Unbabel.

Unlike traditional metrics that compare overlapping words or phrases, COMET uses multilingual transformer embeddings to estimate translation quality based on semantic understanding.

COMET receives three inputs:

- The original source sentence
- A professional reference translation
- The candidate translation produced by an LLM

Using these inputs, the model predicts a quality score that closely approximates human evaluation.

Typical COMET scores range approximately between **0 and 1**, where higher values indicate stronger semantic agreement with the reference translation.

General interpretation:

| COMET Score | Interpretation |
|-------------|----------------|
| > 0.90 | Excellent translation |
| 0.80–0.90 | Very good translation |
| 0.70–0.80 | Acceptable translation |
| < 0.70 | Significant translation issues |

Because COMET is trained directly on human judgments, it captures semantic fidelity far better than lexical-overlap metrics.

---

## Why COMET?

This project selected COMET because it provides a more reliable estimate of translation quality than traditional automatic evaluation metrics.

The main advantages of COMET include:

- Strong correlation with expert human evaluation.
- Semantic rather than lexical comparison.
- Robust handling of paraphrases.
- Support for multilingual translation evaluation.
- State-of-the-art performance on WMT benchmarks.

While COMET provides an objective and reproducible measure of translation quality, it is not intended to replace expert linguistic evaluation. Instead, it complements human assessment by providing consistent quantitative measurements that can be reproduced across different translation systems.

Accordingly, this case study combines COMET with expert human evaluation to provide both quantitative and qualitative perspectives on translation quality.

---

## Evaluation Scope

This evaluation focuses on a single English healthcare paragraph translated into Modern Standard Arabic by three leading Large Language Models.

The study aims to:

- Compare translation quality across multiple LLMs.
- Measure semantic similarity using COMET.
- Compare automatic evaluation with expert human assessment.
- Identify strengths and limitations of automatic translation evaluation.

The evaluation does not attempt to benchmark overall translation capability across multiple domains. Instead, it serves as a practical demonstration of combining automatic and human evaluation methodologies for LLM-generated translations.

---

## Evaluation Workflow

This evaluation follows the workflow defined in the **LLM Evaluation Project Standard (LEPS) v1.0**.

1. Define the evaluation objective.
2. Select the source text.
3. Create a professional reference translation.
4. Generate translations using the selected Large Language Models.
5. Perform automatic evaluation using COMET.
6. Compare automatic evaluation with expert human evaluation.
7. Analyze the results.
8. Document the findings, limitations, and conclusions.

---

## Evaluation Criteria

This project combines automatic and expert human evaluation.

### Automatic Evaluation

- Semantic Similarity (COMET)

### Human Evaluation

- Accuracy
- Faithfulness
- Fluency
- Terminology
- Style
- Overall Quality

---

## Evaluation Assets

The evaluation was conducted using the following assets:

| Asset | Description |
|--------|-------------|
| Source Text | Original English healthcare paragraph |
| Reference Translation | Professional Modern Standard Arabic translation |
| ChatGPT Translation | GPT-5.5 generated translation |
| Gemini Translation | Gemini 3.6 Flash generated translation |
| Claude Translation | Claude Sonnet 5 Thinking generated translation |
| Automatic Evaluation | COMET (wmt22-comet-da) |
| Human Evaluation | Expert linguistic assessment |

---

## Source Text

The following English paragraph was selected as the source text for evaluation. It represents a general healthcare passage containing both technical terminology and natural explanatory language, making it suitable for comparing translation quality across multiple LLMs.

> Artificial intelligence is transforming healthcare by helping doctors diagnose diseases more quickly and accurately. It can analyze medical images, identify patterns in patient data, and support clinical decision-making. Despite its enormous potential, AI should complement healthcare professionals rather than replace them.

---

## Reference Translation

A professional human reference translation was created to serve as the gold standard for COMET evaluation.

> الذكاء الاصطناعي يُحَول مجال الرعاية الصحية تحولًا كاملًا من خلال مساعدة الأطباء على تشخيص الأمراض بسرعة ودقة أكبر. ويمكنه تحليل الصور الطبية، والتعرف على الأنماط داخل بيانات المرضى، ودعم اتخاذ القرار السريري. وعلى الرغم من الإمكانات الكبيرة التي يمتلكها الذكاء الاصطناعي، فإنه ينبغي له أن يُكَمِّل دور أخصائيي الرعاية الصحية، لا استبدالهم.

This reference translation prioritizes:

- Semantic accuracy
- Natural Modern Standard Arabic
- Appropriate medical terminology
- Faithfulness to the original text
- Professional publication quality

The reference translation was used exclusively as the benchmark for COMET evaluation and was not shown to any of the evaluated language models.

---

## Candidate Translations

Three leading Large Language Models translated the source paragraph independently.

| Model | Description |
|-------|-------------|
| ChatGPT (GPT-5.5) | OpenAI Large Language Model |
| Gemini 3.6 Flash | Google Large Language Model |
| Claude Sonnet 5 Thinking | Anthropic Large Language Model |

Each model received the identical English source text without additional context or post-editing.

The generated translations were evaluated using both:

1. Expert human linguistic assessment
2. COMET automatic evaluation

---

## Model Responses

The following translations were generated independently by each Large Language Model using the same English source text without additional prompts or post-editing.

### ChatGPT (GPT-5.5)

> *يُحدث الذكاء الاصطناعي تحولًا في قطاع الرعاية الصحية من خلال مساعدة الأطباء على تشخيص الأمراض بسرعة أكبر وبدقة أعلى. ويمكنه تحليل الصور الطبية، وتحديد الأنماط في بيانات المرضى، ودعم عملية اتخاذ القرارات السريرية. وعلى الرغم من الإمكانات الكبيرة التي يتمتع بها الذكاء الاصطناعي، فإنه ينبغي أن يكون أداةً مكملةً لعمل المتخصصين في الرعاية الصحية، لا بديلًا عنهم.

*

---

### Gemini 3.6 Flash

> *يقوم الذكاء الاصطناعي برسم ملامح جديدة للرعاية الصحية من خلال مساعدة الأطباء على تشخيص الأمراض بسرعة ودقة أكبر؛ حيث يمكنه تحليل الصور الطبية، والتعرف على الأنماط في بيانات المرضى، ودعم اتخاذ القرارات السريرية. ورغم ما يمتلكه الذكاء الاصطناعي من إمكانات هائلة، إلا أنه ينبغي أن يكون مكملًا لدور أخصائيي الرعاية الصحية لا بديلًا عنهم.

*

---

### Claude Sonnet 5 Thinking

> *يُحدِث الذكاء الاصطناعي تحوّلًا في مجال الرعاية الصحية من خلال مساعدة الأطباء على تشخيص الأمراض بسرعة ودقة أكبر. فهو قادر على تحليل الصور الطبية، والتعرّف على الأنماط في بيانات المرضى، ودعم عملية اتخاذ القرار السريري. ورغم ما يمتلكه الذكاء الاصطناعي من إمكانات هائلة، إلا أنه ينبغي أن يكون مكمّلًا لعمل المتخصصين في الرعاية الصحية لا بديلًا عنهم.

*

---

Presenting the complete model outputs allows readers to perform their own qualitative comparison before reviewing the COMET scores and the expert human evaluation. This improves transparency and makes the evaluation methodology fully reproducible.

---

## COMET Evaluation Methodology

COMET evaluates translation quality by comparing:

- the original source sentence,
- a professional reference translation,
- and the candidate translation.

Unlike lexical metrics such as BLEU, COMET measures semantic similarity using multilingual transformer representations trained on human quality judgments.

The evaluation workflow consisted of the following steps:

1. Prepare the English source text.
2. Create a professional Arabic reference translation.
3. Generate Arabic translations using ChatGPT, Gemini, and Claude.
4. Save each translation as a separate UTF-8 text file.
5. Execute COMET using the `wmt22-comet-da` model.
6. Compare COMET scores with the independent expert human evaluation.

This methodology ensures that automatic evaluation remains reproducible while allowing qualitative analysis through human assessment.

---

## Installing COMET

The COMET framework was installed inside a dedicated Python virtual environment.

### Create a virtual environment

```bash
py -3.12 -m venv comet-env
```

### Activate the environment

**Windows**

```bash
comet-env\Scripts\activate
```

### Upgrade pip

```bash
python -m pip install --upgrade pip
```

### Install COMET

```bash
pip install unbabel-comet
```

### Verify installation

```bash
comet-score --help
```

A successful installation displays the COMET command-line interface and available options.

---

## Running COMET

The evaluation used four text files:

```text
source.txt
reference.txt
chatgpt.txt
gemini.txt
claude.txt
```

The COMET evaluation was executed using the downloaded `wmt22-comet-da` model checkpoint.

Example command:

```bash
comet-score ^
-s source.txt ^
-t chatgpt.txt gemini.txt claude.txt ^
-r reference.txt ^
--model "path/to/model.ckpt"
```

COMET evaluates each candidate translation against the reference translation and produces a numerical quality score.

Because all candidate translations were generated from the same source text, the resulting scores provide a direct comparison of semantic similarity and translation quality across the evaluated language models.

---

## Automatic Evaluation Results

The COMET evaluation was performed using the **wmt22-comet-da** model. Each candidate translation was compared against the professional Arabic reference translation.

### COMET Scores

| Model | COMET Score |
|--------|------------:|
| ChatGPT (GPT-5.5) | **0.9165** |
| Gemini 3.6 Flash | **0.9146** |
| Claude Sonnet 5 Thinking | **0.9097** |

### Ranking

| Rank | Model | Score |
|------|-------|------:|
| 🥇 1 | ChatGPT | **0.9165** |
| 🥈 2 | Gemini | **0.9146** |
| 🥉 3 | Claude | **0.9097** |

### Interpretation

All three language models achieved COMET scores greater than **0.90**, indicating excellent semantic similarity to the professional reference translation.

The differences between the models are relatively small:

- ChatGPT achieved the highest score.
- Gemini followed closely behind.
- Claude received a slightly lower score but remained within the same high-quality performance range.

The score difference between the highest and lowest ranked systems was less than **0.007**, suggesting that all three models produced translations of comparable overall quality.

---

## Comparison with Human Evaluation

The automatic COMET evaluation was compared with an independent expert linguistic assessment conducted separately.

### Human Evaluation Ranking

| Rank | Model |
|------|-------|
| 🥇 1 | ChatGPT |
| 🥈 2 | Claude |
| 🥉 3 | Gemini |

### COMET Ranking

| Rank | Model |
|------|-------|
| 🥇 1 | ChatGPT |
| 🥈 2 | Gemini |
| 🥉 3 | Claude |

### Agreement Between the Two Evaluations

Both evaluation methods identified **ChatGPT** as the strongest overall translation.

The only difference was the ordering of **Gemini** and **Claude**.

Human evaluation preferred Claude because its translation maintained a natural balance between accuracy, fluency, and stylistic neutrality. Gemini, while highly accurate, adopted a more literary and interpretive style that slightly departed from the tone of the source text.

COMET, however, ranked Gemini marginally higher than Claude. This difference is expected because COMET primarily measures semantic similarity to the reference translation rather than stylistic preference.

Importantly, the numerical difference between Gemini and Claude was only **0.0049**, indicating that both translations are of very similar quality.

Overall, the human evaluation and COMET results demonstrate strong agreement, with only minor differences in ranking attributable to the distinct evaluation criteria used by each approach.

---

## Results Summary

The automatic evaluation produced the following key findings:

- All three models achieved COMET scores greater than **0.90**, indicating excellent semantic similarity to the professional reference translation.
- ChatGPT achieved the highest COMET score (**0.9165**).
- Gemini and Claude produced similarly high-quality translations, with only minor score differences.
- The comparison between automatic and expert human evaluation showed strong agreement regarding overall translation quality, while minor ranking differences reflected stylistic preferences rather than semantic accuracy.

---

## Discussion

The findings illustrate both the strengths and limitations of automatic translation evaluation.

COMET successfully identified that all three LLMs generated high-quality English-to-Arabic translations with excellent semantic fidelity. Its rankings closely aligned with the independent human evaluation, reinforcing its value as a reliable automatic metric.

However, the comparison also highlights that automatic evaluation cannot fully replace expert human judgment.

Human evaluators consider factors that extend beyond semantic equivalence, including:

- stylistic consistency,
- naturalness,
- register,
- lexical appropriateness,
- readability,
- and overall translation quality.

These qualitative aspects influenced the human preference for Claude over Gemini, despite Gemini receiving a marginally higher COMET score.

The small disagreement between the two evaluation methods demonstrates that automatic metrics and human evaluation should be viewed as complementary rather than competing approaches.

Automatic evaluation provides:

- objective,
- reproducible,
- scalable measurements.

Human evaluation contributes:

- linguistic expertise,
- contextual understanding,
- stylistic assessment,
- domain-specific judgment.

Combining both approaches produces a more comprehensive and reliable evaluation framework for assessing the performance of Large Language Models in machine translation tasks.

---

## Limitations

Although this case study demonstrates a practical workflow for evaluating LLM-generated translations, several limitations should be acknowledged.

First, the evaluation is based on a single English healthcare paragraph. While this allows for detailed analysis, the findings cannot be generalized to all translation domains or text genres.

Second, COMET evaluates candidate translations against a single professional reference translation. Since multiple valid translations may exist for the same source text, slight stylistic variations can influence the final score even when the translation is linguistically correct.

Third, the human evaluation was conducted by a single expert reviewer. Incorporating multiple independent evaluators would improve reliability by reducing individual bias and enabling the calculation of inter-rater agreement.

Finally, this study focuses exclusively on COMET as the automatic evaluation metric. Future work could compare COMET with additional metrics such as BLEU, chrF, METEOR, or MetricX to provide a broader assessment of automatic evaluation methods.

Despite these limitations, the methodology presented in this case study provides a practical and reproducible framework for combining automatic and human evaluation when assessing the translation quality of Large Language Models.

---

## Conclusion

This case study evaluated the English-to-Arabic translation performance of three leading Large Language Models—ChatGPT (GPT-5.5), Gemini 3.6 Flash, and Claude Sonnet 5 Thinking—using both expert human evaluation and the COMET automatic evaluation metric.

The human evaluation found that all three systems produced fluent, accurate, and publication-quality Modern Standard Arabic translations. ChatGPT delivered the strongest overall translation due to its balanced style, precise terminology, and close adherence to the tone of the source text. Claude ranked a close second, while Gemini produced an equally accurate translation with a more literary and interpretive style.

The COMET evaluation confirmed these findings by assigning high scores to all three translations, with ChatGPT achieving the highest score (0.9165), followed by Gemini (0.9146) and Claude (0.9097). Although COMET ranked Gemini slightly above Claude, the numerical difference between the two models was minimal, indicating comparable translation quality.

The comparison between human evaluation and COMET demonstrates that the two approaches are complementary. COMET provides an objective, reproducible measure of semantic similarity, while human evaluation captures stylistic quality, register, fluency, and linguistic nuance that remain difficult to quantify automatically.

Overall, the results indicate that modern Large Language Models are capable of producing high-quality English-to-Arabic translations suitable for many professional applications. At the same time, the study highlights the continued importance of expert human evaluation when assessing translation quality beyond semantic accuracy alone.

---

## Lessons Learned

This case study demonstrates several important insights into LLM translation evaluation:

- COMET provides a reliable and reproducible measure of semantic translation quality.
- Automatic evaluation and expert human assessment are complementary rather than interchangeable.
- Minor differences in COMET scores may reflect stylistic variation instead of meaningful differences in translation quality.
- Combining neural evaluation metrics with expert linguistic review produces a more comprehensive assessment of LLM-generated translations.
- A standardized evaluation methodology improves transparency, reproducibility, and comparability across evaluation projects.

---

## Future Work

Future work may extend this evaluation by:

- Evaluating larger and more diverse translation datasets.
- Comparing additional automatic evaluation metrics such as BLEU, chrF, MetricX, and BERTScore.
- Including multiple independent human reviewers to measure inter-rater agreement.
- Expanding the evaluation to additional language pairs and specialized domains.
- Investigating the relationship between automatic evaluation metrics and human preferences across different translation styles.

---

## LEPS Compliance

This evaluation complies with the **LLM Evaluation Project Standard (LEPS) v1.0** by incorporating:

- Standardized project metadata
- Consistent evaluation workflow
- Clearly defined evaluation criteria
- Evidence-based scoring and justification
- Automatic and human evaluation
- Transparent reporting
- Documented limitations
- Reproducible evaluation methodology

The project demonstrates the application of LEPS to a hybrid evaluation combining neural automatic evaluation (COMET) with expert human linguistic assessment.

---

## References

1. Rei, R., Stewart, C., Farinha, A. C., & Lavie, A. (2022). *COMET: A Neural Framework for MT Evaluation*. Proceedings of the Workshop on Machine Translation (WMT).

2. Unbabel. *COMET: A Neural Framework for Machine Translation Evaluation*. https://github.com/Unbabel/COMET

3. Workshop on Machine Translation (WMT). https://www2.statmt.org/wmt/

4. OpenAI. *GPT-5.5 Documentation*. https://platform.openai.com/

5. Google DeepMind. *Gemini Documentation*. https://ai.google.dev/

6. Anthropic. *Claude Documentation*. https://docs.anthropic.com/

