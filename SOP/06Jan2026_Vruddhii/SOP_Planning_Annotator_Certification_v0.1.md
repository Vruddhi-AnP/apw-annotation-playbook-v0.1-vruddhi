SOP – Planning: Annotator Certification

Purpose
To validate annotator readiness before full-scale annotation.

Scope
In: Sample annotation and validation  
Out: Full dataset annotation

Owner Role:
Annotator / Reviewer

Inputs Needed
- Configured Label Studio project
- Label specification

Outputs Produced
- Verified annotator readiness

Tools Touched:
- Label Studio

Timebox Range + Drivers:
30–40 minutes depending on complexity

Failure Modes (Top 5):
1. Misclassification of categories
2. Missed entities
3. Confusion on edge cases
4. Incorrect submission
5. Inconsistent labeling

Escalation Rules (Stop-the-line):
- Stop if annotator misunderstands label intent

Assumption Ledger:
- Annotator has reviewed label definitions

Step-by-Step Procedure:
1. Annotate sample messages  
   Expected Result: Tasks submitted without error
2. Review labeled samples  
   Expected Result: Correct category and entity usage
3. Resolve ambiguities  
   Expected Result: Consistent decisions applied

Embedded Quality Checks:
- Review sample accuracy
- Check submission status

Artifacts Produced:
- Sample annotation screenshots

Example Run on 10 Items:
Annotated and reviewed 10 messages successfully

One Failure-Case Walkthrough:
If repeated errors occur, retrain annotator before proceeding
