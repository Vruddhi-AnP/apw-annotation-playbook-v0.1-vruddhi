SOP – Annotation Execution Flow

Purpose:
   To define the step-by-step process for executing text annotation work.

Scope
In scope:
- Batch-based annotation
- Single annotator workflow

Out of scope:
- Review by a second annotator
- Client delivery

Who runs this:
   Data Annotation Intern

Inputs needed:
- Approved batch plan
- Label specification document
- Access to Label Studio project

Outputs produced:
- Annotated tasks for the batch
- Completed batch status

Tools touched:
- Label Studio
- Web browser

Timebox:
- 20–30 minutes per batch
- Time depends on sentence complexity

Failure modes:
- Wrong label selection
- Task skipped accidentally
- Confusing sentence interpretation

Assumption Ledger:
- One annotator is working
- No separate review stage is configured

Step-by-step procedure
1. Open Label Studio project  
2. Select tasks for the assigned batch  
3. Start annotation using defined labels  
4. Annotate each task one by one  
5. Submit tasks after completion  

Quality checks:
- One label selected per task
- No task left unannotated
- Batch size matches plan

Escalation rules:
- Stop if labels are unclear
- Stop if tool does not save annotations

Example run:
Annotated 5 items as part of Batch 1 using defined label rules.

