SOP – Planning: Label Specification Creation

Purpose
To define and configure labels for support message routing.

Scope:
In: Label definition and configuration  
Out: Annotation execution

Owner Role:
Annotation Planner

Inputs Needed:
- Category list
- Entity definitions

Outputs Produced:
- Configured labeling interface in Label Studio

Tools Touched:
- Label Studio UI

Timebox Range + Drivers:
20–30 minutes depending on label complexity

Failure Modes (Top 5):
1. Incorrect label names
2. Missing entity labels
3. Multiple categories enabled
4. Label changes not saved
5. Misconfigured entity spans

Escalation Rules (Stop-the-line):
- Stop if labels do not match specification exactly

Assumption Ledger:
- Single category per message
- Entities captured only if explicitly present

Step-by-Step Procedure:
1. Open Labeling Interface settings  
   Expected Result: Label config panel visible
2. Add category choices  
   Expected Result: All 5 categories listed
3. Add entity labels (order_id, phone, email)  
   Expected Result: Entity tagging enabled
4. Save configuration  
   Expected Result: Labels available during annotation

Embedded Quality Checks:
- Cross-check label names against spec
- Test on sample task

Artifacts Produced:
- Label configuration screenshots

Example Run on 10 Items:
Annotated 10 sample messages to validate labels

## One Failure-Case Walkthrough
If wrong label appears, delete and reconfigure before proceeding
