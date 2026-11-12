# Pharmacovigilance Causality Assessment

An educational portfolio project on evaluating whether an adverse event is causally related to a suspected medicinal product. It covers clinical evidence review, the Naranjo Algorithm, WHO–UMC categories, worked case studies, AEFI assessment and emerging machine-learning support.

## Learning objectives
- Distinguish an adverse event from an adverse drug reaction (ADR).
- Assess drug-, event-, patient- and clinical-course-related factors.
- Apply the Naranjo Algorithm transparently and reproduce its score.
- Classify individual cases using WHO–UMC categories.
- Explain why vaccine AEFI assessment has a distinct framework.
- Recognise the limits of automated causality prediction.

## Repository map
- `docs/`: core concepts and methods.
- `case-studies/`: fictional teaching cases with explicit assumptions.
- `assessment-tools/`: reusable worksheets and templates.
- `outputs/`: comparison and classification summary.
- `REFERENCES.md`: primary guidance and foundational literature.

## Important methodological distinction
Naranjo and WHO–UMC are not interchangeable:
- Naranjo yields **Definite, Probable, Possible or Doubtful** based on a 10-question score.
- WHO–UMC yields **Certain, Probable/Likely, Possible, Unlikely, Conditional/Unclassified or Unassessable/Unclassifiable** based on structured clinical judgement.

Therefore, this project uses WHO–UMC when presenting the requested labels Certain, Probable and Possible. It retains Naranjo's own category names when reporting its score.

## Educational use and safety
All case studies are fictional. They are not real patient reports, regulatory submissions or medical advice. Do not upload identifiable patient information to GitHub. Do not deliberately rechallenge a patient with a suspected harmful medicine merely to establish causality. Clinical decisions and regulatory reporting must follow applicable institutional and national requirements.

## Suggested workflow
1. Read the causality factors guide.
2. Review the Naranjo and WHO–UMC methods separately.
3. Complete the assessment worksheets for each fictional case.
4. Compare results and explain any disagreement.
5. Record missing information and uncertainty rather than inventing facts.

See [REFERENCES.md](REFERENCES.md) for source material.
