Day 1 :  Initiation

- Set up Label Studio locally on my laptop
- Created a toy text annotation project
- Uploaded a sample text file with 10 sentences
- Configured labels: Positive, Negative, Neutral
- Annotated all 10 tasks end-to-end
- Faced task queue issue while labeling and fixed it
- Exported annotation output

Day 2 – Planning

- Created label specification for text sentiment annotation
- Defined clear rules for Positive, Negative, and Neutral labels
- Documented confusing cases in edge case library
- Added handling rules for mixed and unclear sentences
- Created spec readiness checklist before starting annotation
- No tool changes were required today
- All planning work was documented in GitHub
- Assumed single-annotator workflow for this project

Day 3 – Execution

- Created batch plan to divide annotation work into smaller units
- Defined step-by-step annotation execution flow in SOP
- Added batch release checklist before starting annotation
- Execution logic documented based on toy project experience
- No new annotation was run in the tool today
- Focus was on defining repeatable execution process
- Assumed single annotator and no separate review stage
- All execution documents added to GitHub

Day 4 – Monitoring & Control

- Created SOP for manual QA checks on annotated batches
- Added QA report template to document quality results
- Created change request template for handling rule or process updates
- Defined escalation rules for repeated quality issues
- No new annotation was run in the tool today
- Focus was on monitoring, quality control, and change handling
- Assumed manual QA is sufficient for toy project
- All monitoring documents added to GitHub

Day 5 – Closure

- Exported final annotated data from Label Studio
- Added acceptance signoff and project retrospective templates
- Completed delivery and closure gate checklists
- Uploaded final export and closure evidence
- Project documentation finalized and archived
- No further annotation work planned
- All required deliverables completed as per guidelines
- Project formally closed

---   ---  ---

---

Day 1 – Label Studio Execution (Support Routing)

- Tool used: Label Studio (local)
- Project created: Support-Routing-60
- Dataset: support_messages.csv (60 tasks)
- Labels configured:
  - refund_request
  - order_status
  - product_issue
  - account_access
  - spam_other
- Annotated 15 sample tasks end-to-end
- Verified submit flow and task completion status
- Exported annotations as JSON for evidence
- Evidence added under EVID/DayX_LabelStudio
- Assumption: Single-label routing per ticket
- Decision: Annotated subset (15) sufficient to validate workflow


Day 2 – Completion, QA & Delivery (Support Routing)

- Completed annotation for remaining messages (total 60/60 labeled)
- Performed self-review on 15 messages (25% sample)
- Identified and corrected minor labeling issues during review
- Exported final annotations from Label Studio
- Created clean CSV output (pred_text.csv) with required schema
- Prepared QA report and defect log templates
- Compiled final delivery pack under DELIVERY_PACK/Support-Routing-60
- Evidence screenshots and exports finalized under EVID/06Jan2026_Vruddhi

Assumption: Entity fields are populated only when explicitly present in text
Outcome: Dataset ready for downstream routing model usage






