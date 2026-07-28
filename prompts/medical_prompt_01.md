# Medical Prompt 01 – Patient Education

---

**Project Type:** Prompt Engineering Case Study

**Domain:** Medical AI

**Model:** Google Gemini (3.6 Flash)

**Status:** Completed

**Version:** 1.1

**Date:** July 2026

---

## Objective

Design and evaluate an LLM prompt that explains hypertension to a newly diagnosed patient using simple, non-medical language.

---

## Project Scope

This case study demonstrates a structured prompt engineering workflow using a single LLM and one representative task. Its objective is to illustrate how iterative prompt refinement can improve response quality for patient education rather than evaluate the overall capabilities of the model.

---

## Initial Prompt

```text
Explain hypertension.
```

---

## LLM Response (Initial Prompt)

Hypertension is the medical term for **high blood pressure**—a condition where the force of blood pushing against your artery walls is consistently too high.

Think of your circulatory system like a garden hose: if you crank the spigot high or narrow the hose, the pressure inside spikes. Over time, that extra pressure strains your heart and damages the lining of your blood vessels.

### Understanding the Numbers

Blood pressure is measured using two numbers in millimeters of mercury (mmHg):

- **Systolic (Top number):** The pressure in your arteries when your heart beats and pumps blood.
- **Diastolic (Bottom number):** The pressure in your arteries when your heart rests between beats.

| Category | Systolic (mmHg) | Diastolic (mmHg) |
|-----------|----------------:|-----------------:|
| Normal | Less than 120 | Less than 80 |
| Elevated | 120–129 | Less than 80 |
| Stage 1 Hypertension | 130–139 | 80–89 |
| Stage 2 Hypertension | 140 or higher | 90 or higher |

### Why It Is Called the "Silent Killer"

Hypertension rarely causes noticeable symptoms in its early or moderate stages. Millions of people have it without feeling sick at all. However, untreated high blood pressure silently causes severe complications over time, including heart attack, heart failure, stroke, kidney damage, and vision loss.

### Common Causes and Risk Factors

1. **Primary (Essential) Hypertension:** Usually develops gradually because of genetics, ageing, high sodium intake, obesity, stress, and physical inactivity.

2. **Secondary Hypertension:** Results from another medical condition such as kidney disease, thyroid disorders, sleep apnoea, or certain medications.

Most cases can be effectively managed through lifestyle changes and medications prescribed by a healthcare provider.

---

## Evaluation Framework

The initial response was evaluated using the following criteria:

- Medical Accuracy
- Clarity
- Instruction Following
- Audience Appropriateness
- Empathy
- User Friendliness

The evaluation focuses on how effectively the response meets the communication needs of a newly diagnosed patient.

---

## Evaluation of Initial Response

### Accuracy — 5/5

The response is medically accurate and provides comprehensive information about hypertension, including its definition, blood pressure categories, complications, causes, and management.

### Clarity — 3.5/5

The explanation of hypertension and its complications is clear. However, the blood pressure classification table, numerical ranges, and technical terms such as **systolic**, **diastolic**, and **mmHg** may confuse readers without a medical background.

### Instruction Following — 4/5

The model successfully explained hypertension as requested. However, the response was more detailed than necessary for a broad prompt and could have been shorter while still satisfying the request.

### Strengths

- Medically accurate.
- Well organised with headings.
- Covers causes, complications, and treatment.
- Provides reliable health information.

### Weaknesses

- Too detailed for a newly diagnosed patient.
- Uses technical medical terminology.
- Includes unnecessary numerical classifications.
- Lacks reassurance and empathy.
- Reads more like a health article than patient education.

### Overall Assessment

The response is medically reliable and comprehensive but is better suited for general educational reading than for explaining hypertension to a newly diagnosed patient.

---

## Prompt Refinement Strategy

Based on the evaluation, the following improvements were identified:

- Clearly define the target audience.
- Use simple, reassuring language.
- Reduce unnecessary medical terminology.
- Remove detailed blood pressure classifications.
- Keep the explanation concise.
- Encourage consultation with a healthcare professional.

---

## Improved Prompt

**Role:**

You are an experienced family physician.

**Task:**

A patient has just been diagnosed with hypertension and is worried. Explain hypertension in a way that is easy to understand and reassuring.

### Requirements

- Use simple, non-medical language.
- Keep the response under 150 words.
- Explain:
  - What hypertension is.
  - Why it is important to treat.
  - How lifestyle changes and medication can help.
- Avoid unnecessary medical terminology, classifications, and detailed blood pressure numbers.
- Use a calm, supportive, and reassuring tone.
- Encourage the patient to work with their healthcare provider for personalised treatment rather than self-managing the condition.
- End with one short reassuring sentence.

---

## LLM Response (Improved Prompt)

Here is what I would say as your family physician:

First, take a deep breath—you are going to be okay, and we can manage this together.

Think of your blood vessels like a garden hose. Blood pressure is simply the force of blood pushing against those vessel walls. When you have hypertension, or high blood pressure, that force is consistently higher than it should be.

Even though you likely feel completely fine right now, high blood pressure is important not to ignore. Over time, that extra pressure places unnecessary strain on your heart and can gradually damage your blood vessels.

The good news is that hypertension is very manageable. Healthy lifestyle changes—such as eating well, staying active, managing stress, and taking medication if prescribed—can help keep your blood pressure under good control.

Because everyone's situation is different, please work closely with your healthcare provider to create a treatment plan that is right for you rather than trying to manage it on your own.

---

## Comparison

| Aspect | Initial Prompt | Refined Prompt |
|--------|----------------|----------------|
| Prompt Detail | Minimal, open-ended instruction | Clearly structured with defined role, audience, and requirements |
| Target Audience | Not specified | Newly diagnosed patient |
| Language | No guidance provided | Simple, non-medical language |
| Tone | Not specified | Calm, supportive, and reassuring |
| Length | No limit | Under 150 words |
| Medical Terminology | Unrestricted | Minimized |
| Required Content | General explanation only | Explanation, importance of treatment, lifestyle changes, medication, and medical follow-up |
| Empathy | Not required | Explicitly required |
| Professional Advice | Not specified | Encourages consultation with a healthcare provider |
| Closing Statement | None | Ends with a brief reassuring sentence |
| Overall Response Quality | Accurate but technical and general | Accurate, patient-friendly, empathetic, and well aligned with the communication goal |
---

## Improvements Achieved

- Better adapted to the target audience.
- Clear and patient-friendly language.
- Reduced technical terminology.
- Removed unnecessary classifications.
- Improved empathy and reassurance.
- Stronger encouragement to seek professional medical advice.
- More focused and easier to understand.

---

## Lessons Learned

This project demonstrates that prompt engineering can significantly improve AI-generated responses without changing the underlying LLM.

By clearly defining the audience, tone, response length, and communication goals, the same model produced a response that was more understandable, empathetic, and appropriate for patient education.

Effective AI evaluation involves more than checking factual accuracy. It also requires assessing clarity, instruction following, audience appropriateness, safety, and overall user experience.

---

## Skills Demonstrated

- Prompt Engineering
- AI Response Evaluation
- Prompt Optimisation
- Medical Content Evaluation
- Audience Adaptation
- Instruction Design
- User Experience Analysis
- Comparative Response Analysis

---

## Conclusion

This case study demonstrates a complete prompt engineering workflow, including prompt design, response evaluation, structured refinement, and comparative analysis.

The results illustrate that carefully designed prompts can substantially improve AI-generated responses without changing the underlying model. By explicitly defining the audience, tone, communication goals, and response constraints, the refined prompt produced output that was more understandable, empathetic, and appropriate for patient education.

The project highlights the value of systematic prompt engineering as a practical method for improving the quality and usability of LLM-generated content.

---

## Study Limitations

This case study is based on a single prompt refinement task using one LLM and one medical education scenario. The findings demonstrate the impact of prompt engineering for this specific use case and should not be interpreted as a general measure of model performance across other medical topics or domains.

Response quality may vary depending on the model version, prompt design, and task complexity. Additional studies using different medical scenarios and multiple models would provide a broader assessment of prompt engineering strategies.

---

End of Report 
