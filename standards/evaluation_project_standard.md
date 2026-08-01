> | **Author** | Jehad Soboh |
| **Copyright** | © 2026 Jehad Soboh |
| **License** | MIT License |

---
# LLM Evaluation Project Standard

## Purpose

The **LLM Evaluation Project Standard (LEPS) v1.0** was developed by **Jehad Soboh** for the **LLM Evaluation Portfolio**.

Its purpose is to establish a consistent methodology for planning, conducting, documenting, and reporting Large Language Model (LLM) evaluation projects. By standardizing project structure, evaluation workflows, evidence-based scoring, and reporting practices, LEPS aims to ensure that all portfolio projects are transparent, reproducible, and directly comparable.

---

## Scope

LEPS applies to all evaluation projects published in the LLM Evaluation Portfolio, including translation evaluation, prompt evaluation, conversational AI assessment, retrieval-augmented generation (RAG), reasoning evaluation, and future benchmarking studies.

The standard defines project documentation requirements rather than prescribing a specific evaluation metric or benchmark.

---

> ## Note: 
The LLM Evaluation Project Standard (LEPS) is an original project standard developed by Jehad Soboh for the LLM Evaluation Portfolio. LEPS defines standardized project structure, evaluation workflows, documentation, and reporting practices for LLM evaluation projects. It is intended to complement—not replace—existing evaluation methodologies, benchmarks, metrics, and domain-specific evaluation frameworks.

---

# Definitions

For the purposes of this standard:

**Evaluation Criterion** — A characteristic used to assess model performance.

**Evaluation Method** — The procedure used to assess model outputs (e.g., human, automatic, hybrid).

**Evidence** — Observable information supporting evaluation findings.

**Project** — A documented AI evaluation conducted in accordance with LEPS.

**Reproducibility** — The ability for another evaluator to repeat the evaluation using the documented methodology and obtain comparable findings.

---

# LLM Evaluation Project Standard

## Document Information

| Field | Value |
|--------|-------|
| **Document ID** | LEPS-001 |
| **Title** | LLM Evaluation Project Standard |
| **Abbreviation** | LEPS |
| **Version** | 1.0 |
| **Status** | Active |
| **Author** | Jehad Soboh |
| **Repository** | LLM Evaluation Portfolio |
| **Effective Date** | August 2026 |
| **Last Updated** | August 2026 |

---

## Table of Contents

1. [Purpose](#purpose)
2. [Scope](#scope)
3. [Definitions](#definitions)
4. [Standard Project Information](#standard-project-information)
5. [Standard Project Structure](#standard-project-structure)
6. [Standard Evaluation Workflow](#standard-evaluation-workflow)
7. [Standard Evaluation Criteria](#standard-evaluation-criteria)
8. [Standard Scoring System](#standard-scoring-system)
9. [Scoring Calibration](#scoring-calibration)
10. [Standard Evidence and Justification](#standard-evidence-and-justification)
11. [Standard Reporting](#standard-reporting)
12. [Project Compliance Checklist](#project-compliance-checklist)
13. [Version History](#version-history)

---

# Standard Project Information

Every evaluation project must begin with the following metadata.

## Template

| Field | Description |
|--------|-------------|
| Project ID | Unique project identifier (e.g., Evaluation 001) |
| Project Type | Type of project (e.g., LLM Evaluation Case Study) |
| Domain | Evaluation domain (e.g., Machine Translation, Medical QA) |
| Task | Specific evaluation task |
| Evaluation Method | Human, Automatic, Hybrid, or Benchmark |
| Models Compared | List of evaluated models |
| Status | Draft, In Progress, or Completed |
| Version | Current project version |
| Date | Publication or completion date |

### Example

| Field | Value |
|--------|-------|
| Project ID | Evaluation 002 |
| Project Type | LLM Evaluation Case Study |
| Domain | English–Arabic Machine Translation |
| Task | Translation Quality Evaluation |
| Evaluation Method | Hybrid (COMET + Human Evaluation) |
| Models Compared | ChatGPT (GPT-5.5), Google Gemini (3.6 Flash), Claude Sonnet 5 Thinking |
| Status | Completed |
| Version | 1.0 |
| Date | July 2026 |

---

# Standard Project Structure

Every evaluation project should follow the same structure.

1. Project Information
2. Executive Summary
3. Introduction
4. Evaluation Objective
5. Evaluation Scope
6. Evaluation Methodology
7. Evaluation Workflow
8. Evaluation Criteria
9. Source Data / Prompt
10. Model Responses
11. Evaluation Results
12. Comparative Analysis
13. Discussion
14. Limitations
15. Conclusion
16. References

---

# Standard Evaluation Workflow

LEPS organizes every evaluation into a repeatable sequence of planning, execution, analysis, and reporting. Following the same workflow across all projects improves consistency, transparency, and reproducibility while making evaluation results easier to compare.

Every evaluation project should follow the workflow below.

```text
1. Define the evaluation objective
            ↓
2. Design the evaluation task
            ↓
3. Prepare the source data or prompt
            ↓
4. Generate responses from the selected models
            ↓
5. Apply automatic evaluation (if applicable)
            ↓
6. Conduct human evaluation (if applicable)
            ↓
7. Analyze and compare the results
            ↓
8. Document findings and conclusions
```

## Workflow Principles

- Clearly define the evaluation objective before testing.
- Use the same prompt or input for all models.
- Preserve model responses without modification.
- Apply consistent evaluation criteria across all models.
- Clearly distinguish automatic evaluation from human evaluation.
- Document all observations, limitations, and conclusions.

## Human Evaluation

When human evaluation is conducted:

- Apply the same evaluation criteria across all models.
- Evaluate responses independently whenever practical.
- Document evaluator assumptions.
- Support qualitative judgments with observable evidence.

Projects involving multiple evaluators are encouraged to document any review or calibration procedures used to improve scoring consistency.

## Reproducibility

Projects should document sufficient information to enable another evaluator to reproduce the evaluation, including:

- Evaluation prompts
- Model versions (when available)
- Evaluation methodology
- Evaluation criteria
- Scoring methodology
- Supporting evaluation assets

---

# Standard Evaluation Criteria

Evaluation criteria should be selected according to the project objectives. Not every project requires every criterion.

## Core Evaluation Criteria

| Criterion | Description |
|-----------|-------------|
| Accuracy | Correctness of the response. |
| Instruction Following | Degree to which the model follows the prompt. |
| Completeness | Extent to which the response addresses all required aspects. |
| Clarity | Readability and ease of understanding. |
| Fluency | Naturalness and grammatical quality of the language. |
| Terminology | Appropriate and consistent use of domain-specific terms. |
| Reasoning | Logical consistency and quality of the explanation. |
| Safety | Absence of harmful, misleading, or unsafe content. |
| Faithfulness | Consistency with the source material without unsupported additions. |
| Overall Quality | Overall assessment considering all applicable criteria. |

## Project-Specific Criteria

Additional criteria may be introduced when required by the evaluation task.

Examples include:

- Cultural Appropriateness
- Linguistic Fidelity
- Stylistic Consistency
- Hallucination Risk
- Context Awareness
- Retrieval Quality
- Citation Accuracy

---

# Standard Scoring System

A consistent scoring system should be used across evaluation projects whenever applicable.

## Rating Scale

| Score | Interpretation |
|--------|----------------|
| **5** | Excellent – Fully satisfies the evaluation criterion with no significant issues. |
| **4** | Good – Minor issues that do not substantially affect overall quality. |
| **3** | Acceptable – Meets the minimum requirements but has noticeable weaknesses. |
| **2** | Poor – Significant issues affecting quality or usability. |
| **1** | Very Poor – Fails to satisfy the evaluation criterion. |

## Overall Score

The overall score should summarize model performance across all applicable evaluation criteria.

Projects should clearly document how the overall score is calculated.

Acceptable approaches include:

- Arithmetic mean (equal weighting)
- Weighted mean
- Criterion-specific aggregation
- Benchmark-specific scoring methodologies

When weighted scoring is used, the weighting scheme and rationale should be documented.

### Example (Arithmetic Mean)

Overall Score = (Accuracy + Completeness + Clarity) ÷ Number of Criteria

Example:

(5 + 4 + 5) ÷ 3 = 4.67

## Example Score Table

| Model | Accuracy | Completeness | Clarity | Overall |
|--------|---------:|-------------:|---------:|--------:|
| ChatGPT | 5 | 5 | 5 | 5.0 |
| Gemini | 5 | 4 | 5 | 4.7 |
| Claude | 4 | 5 | 5 | 4.7 |

## Ranking

Projects comparing multiple models should include a final ranking based on the evaluation results.

Example:

| Rank | Model |
|------|-------|
| 1 | ChatGPT |
| 2 | Claude |
| 3 | Gemini |

---

# Scoring Calibration

To improve consistency across evaluation projects, evaluators should calibrate their scoring before assigning final ratings.

Calibration helps ensure that the same scoring standards are applied consistently across different models, projects, and evaluation sessions.

## Recommended Practices

- Define evaluation criteria before scoring begins.
- Review representative examples for each score level when available.
- Apply the same interpretation of the scoring scale to all evaluated models.
- Avoid changing scoring standards during an evaluation.
- Document any project-specific scoring rules or weighting schemes.

Projects involving multiple evaluators should document the calibration process or any procedures used to improve scoring consistency.

---

# Standard Evidence and Justification

## Evidence and Justification

Every conclusion presented in an evaluation should be supported by observable evidence. Quantitative scores should be accompanied by qualitative explanations, and any subjective observations should be clearly distinguished from objective findings.

## Principles

- Every assigned score should include a clear justification.
- Justifications should reference specific examples from the model response.
- Distinguish between objective findings and subjective observations.
- Avoid unsupported preferences or personal opinions.
- When applicable, support conclusions with automatic evaluation metrics and expert human review.

## Evidence Sources

Evidence may include:

- Source text or prompt
- Model responses
- Human evaluation
- Automatic evaluation metrics (e.g., COMET)
- Comparative analysis
- Domain-specific references

## Example

**Criterion:** Terminology

**Score:** 5/5

**Justification:**

The translation consistently uses appropriate Modern Standard Arabic medical terminology. Key concepts are translated accurately and remain faithful to the source text without introducing ambiguity.

---

**Criterion:** Faithfulness

**Score:** 4/5

**Justification:**

The response preserves the meaning of the source text but includes a minor stylistic expansion that is not explicitly present in the original. This does not alter the intended meaning but slightly reduces fidelity.

---

## Transparency

When uncertainty exists:

- Explain why.
- Document any assumptions.
- Clearly identify evaluation limitations.

---

# Standard Reporting

Every evaluation project should conclude with a standardized reporting structure to ensure consistency across the portfolio.

## Required Sections

### Results Summary

Provide a concise summary of the evaluation findings.

### Confidence Statement

Projects should briefly describe the confidence that can reasonably be placed in the evaluation findings.

Confidence may be influenced by factors such as:

- Sample size
- Evaluation methodology
- Human reviewer participation
- Automatic evaluation metrics
- Availability of supporting evidence

### Comparative Analysis

Compare model performance using the selected evaluation criteria.

Discuss:

- Major strengths
- Major weaknesses
- Significant differences
- Overall ranking

### Discussion

Interpret the evaluation results.

Address questions such as:

- Did the models satisfy the evaluation objective?
- Were there meaningful differences between models?
- Were automatic and human evaluations consistent?
- What insights were obtained?

### Limitations

Clearly state any limitations affecting the evaluation.

Examples:

- Small sample size
- Single prompt evaluation
- Human reviewer bias
- Domain-specific constraints
- Metric limitations

### Sample Size

Projects based on a limited number of prompts, datasets, or evaluation instances should clearly state that their findings may not generalize beyond the evaluated samples.

Such evaluations should be interpreted as exploratory unless supported by additional evidence.

### Conclusion

Summarize the overall findings without introducing new evidence.

### Lessons Learned

Document observations that may improve future evaluations.

### Future Work

Suggest possible improvements or extensions to the evaluation.

---

# Project Compliance Checklist

Before publishing an evaluation project, verify that it complies with the LLM Evaluation Project Standard.

A project is considered LEPS-compliant when it follows the required project structure, documents its evaluation methodology, applies transparent evaluation criteria, supports conclusions with evidence, and reports findings according to this standard.

## Project Metadata

- [ ] Project Information is complete.
- [ ] Version number is specified.
- [ ] Project status is specified.
- [ ] Evaluation method is identified.
- [ ] Models are listed.

---

## Evaluation Design

- [ ] Evaluation objective is clearly defined.
- [ ] Evaluation scope is documented.
- [ ] Evaluation workflow is described.
- [ ] Evaluation criteria are specified.

---

## Evaluation Assets

- [ ] Source prompt or input is included.
- [ ] Reference data is provided (if applicable).
- [ ] Model responses are documented.
- [ ] Evaluation rubric is included.

---

## Evaluation Results

- [ ] Scores are reported consistently.
- [ ] Overall scoring methodology is documented.
- [ ] Rankings are provided (when comparing multiple models).
- [ ] Automatic evaluation results are included (if applicable).
- [ ] Human evaluation results are included (if applicable).

---

## Evidence

- [ ] Every score includes a justification.
- [ ] Conclusions are supported by evidence.
- [ ] Limitations are documented.
- [ ] Assumptions are clearly stated.

---

## Reporting

- [ ] Comparative analysis is included.
- [ ] Discussion is included.
- [ ] Conclusion is supported by findings.
- [ ] Lessons learned are documented.
- [ ] References are provided.

---

## Reproducibility

- [ ] Evaluation methodology is documented.
- [ ] Required files are included.
- [ ] Evaluation process can be reproduced by another reviewer.

---

# Version History

| Version | Date | Description |
|----------|------|-------------|
| **1.1** | August 2026 | Added scoring calibration, explicit overall score calculation guidance, reproducibility recommendations, human evaluation guidance, confidence statements, terminology definitions, and enhanced compliance requirements. |
| **1.0** | August 2026 | Initial release of the LLM Evaluation Project Standard. |

---
> | **Author** | Jehad Soboh |
| **Copyright** | © 2026 Jehad Soboh |
| **License** | MIT License |
