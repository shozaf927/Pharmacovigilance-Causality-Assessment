# Machine Learning in Pharmacovigilance Causality Assessment

## 1. Potential applications
Machine learning and natural language processing may support:
- Extraction of drug names, event terms, dates, doses and outcomes from narratives.
- Identification of missing fields and inconsistencies.
- Duplicate and near-duplicate case detection.
- Similar-case retrieval for reviewer support.
- Triage and prioritisation of reports.
- Detection of patterns that warrant human review.

## 2. Why automated causality is difficult
Spontaneous reports are often incomplete, selectively reported and confounded by disease, concomitant medicines and reporting behaviour. A model trained on historical classifications may reproduce inconsistent labels rather than learn biological causation.

## 3. Suggested research workflow
1. Define the intended use: completeness support, triage or decision support—not autonomous diagnosis.
2. Use de-identified, lawfully accessible data with appropriate permissions.
3. Establish expert-adjudicated reference labels and inter-rater agreement.
4. Prevent patient-level leakage between training and test datasets.
5. Compare interpretable baselines with more complex models.
6. Evaluate sensitivity, specificity, precision, calibration and subgroup performance.
7. Validate externally across products, populations and reporting systems.
8. Provide explanations, uncertainty and an audit trail for reviewers.

## 4. Governance and safeguards
- Human pharmacovigilance review remains essential.
- Protect personal and health information.
- Document data provenance, versioning and model limitations.
- Monitor drift and subgroup performance.
- Do not convert association or co-occurrence into causal proof.
- Never recommend unsafe rechallenge or delay urgent medical care.

## 5. Portfolio extension idea
A future prototype could accept a fully fictional case narrative and extract a structured timeline, missing-data checklist and candidate alternative causes. The output should be labelled **decision support only** and should not automatically assign a final WHO–UMC category.

## Conclusion
AI can improve workflow efficiency and consistency when carefully validated. It cannot replace clinical reasoning, expert review or regulatory judgement.
