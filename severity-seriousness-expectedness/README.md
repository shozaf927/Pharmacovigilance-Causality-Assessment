# ADR Severity, Seriousness & Expectedness Classification

**Project type:** Educational pharmacovigilance case-classification portfolio  
**Frameworks:** ICH E2A; ICH E2D(R1); India PvPI/IPC guidance; EMA GVP  
**Case set:** Five fictional cases with explicit reference-safety-information (RSI) excerpts

## Purpose
This project teaches a reproducible assessment of suspected adverse drug reactions (ADRs) across three independent dimensions:
1. **Severity** — intensity of the reaction (mild, moderate, severe).
2. **Seriousness** — regulatory outcome/action criteria (serious or non-serious).
3. **Expectedness** — consistency with the applicable product information/RSI (expected or unexpected).

These are not interchangeable. A severe event can be non-serious; a mild event can be serious if it meets a seriousness criterion; and neither severity nor seriousness determines expectedness.

## Project contents
- `docs/concepts-and-definitions.md` — terminology and core distinctions.
- `docs/seriousness-assessment.md` — seriousness criteria and decision pathway.
- `docs/severity-assessment.md` — intensity grading and limitations.
- `docs/expectedness-assessment.md` — RSI comparison and listedness.
- `docs/integrated-workflow.md` — end-to-end case review workflow.
- `docs/india-and-global-reporting-context.md` — reporting context and jurisdiction caveats.
- `case-studies/` — five worked fictional cases.
- `tools/classification-worksheet.md` — reusable worksheet.
- `tools/decision-tree.md` — quick decision tree.
- `outputs/case-classification-matrix.md` — consolidated results.
- `REFERENCES.md` — primary regulatory sources.

## Learning outcomes
By completing this project, a learner should be able to:
- Distinguish AE, ADR, severity, seriousness, expectedness and causality.
- Assess each seriousness criterion independently and document the evidence.
- Grade intensity without using hospitalisation as a shortcut for severity.
- Compare the reported reaction with the correct, current RSI and assess nature, specificity and severity.
- Record uncertainty, missing information and the rationale for each classification.
- Explain why reporting obligations depend on jurisdiction, product type, report source and applicable regulatory pathway.

## Important limitations
- All cases and product-information excerpts are **fictional teaching examples**. They are not real patient records and are not substitutes for current approved product labels.
- The cases do not establish causality. Classification of seriousness and expectedness is separate from causality assessment.
- Do not infer that a non-serious or expected event should not be reported. PvPI encourages reporting of suspected ADRs irrespective of seriousness or whether known/unknown.
- This is educational material, not medical advice, a validated safety database, or a regulatory SOP.

## Suggested study sequence
1. Read the concepts and three assessment-method documents.
2. Apply the worksheet to each case before reading its worked answer.
3. Compare the outputs in the case matrix.
4. Review the reporting-context document and primary references.

## Related portfolio work
This module is part of the broader [Pharmacovigilance Causality Assessment](../README.md) repository. Causality, seriousness, severity and expectedness are complementary but separate assessments.
