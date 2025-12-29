SOP – QA Checks for Text Annotation

Purpose:
    To define how annotation quality is checked on a daily basis.

Scope
  In scope:
    - Quality checking of completed annotation batches

  Out of scope:
    - Client-level audits
    - Automated QA tools

Who runs this:
  Data Annotation Intern

Inputs needed:
- Completed annotation batch
- Label specification document
- Access to Label Studio project

Outputs produced:
- QA status for the batch
- List of errors, if any

Tools touched:
- Label Studio
- Web browser

Timebox:
- 10–15 minutes per batch

Failure modes:
- Wrong label applied
- Inconsistent labeling
- Missed or skipped tasks

Assumption Ledger:
- Manual QA is sufficient for toy project
- Single annotator workflow is used

Step-by-step procedure:
1. Open completed batch in Label Studio  
2. Review each annotated task  
3. Verify label matches label specification  
4. Note any incorrect or unclear labels  

Quality checks:
- Correct label applied
- One label per task
- No task left unreviewed

Escalation rules:
- Stop if repeated labeling errors are found
- Stop if label definitions are unclear

Example run:
  Reviewed one completed batch and verified labels against the spec.
