SOP – Initiation: Tool Setup & Project Creation (Label Studio)

Purpose
To set up Label Studio and create a project for text annotation.

Scope:
In: Tool setup, project creation, data import  
Out: Annotation execution and QA

Owner Role:
Annotation Operator

Inputs Needed:
- support_messages.csv
- Label definitions
- Local system with Python installed

Outputs Produced:
- Label Studio project created
- Dataset imported successfully

Tools Touched:
- Label Studio (local)
- Web browser

Timebox Range + Drivers:
30–45 minutes depending on system setup and dataset size

Failure Modes (Top 5):
1. Label Studio not starting
2. Dataset import failure
3. Incorrect project name
4. Labels not saved
5. Browser port conflict

Escalation Rules (Stop-the-line):
- Stop if dataset does not load correctly
- Escalate if tool fails to launch after retry

Assumption Ledger:
- Operator has prior Python and CLI access
- Dataset is clean CSV

Step-by-Step Procedure:
1. Activate Python virtual environment  
   Expected Result: venv activated successfully
2. Start Label Studio server  
   Expected Result: Server running on localhost
3. Create new project named Support-Routing-60  
   Expected Result: Empty project dashboard visible
4. Import support_messages.csv  
   Expected Result: All tasks visible in task list

Embedded Quality Checks:
- Verify project name matches specification
- Verify task count equals dataset size

Artifacts Produced:
- Label Studio project
- Screenshots of setup

Example Run on 10 Items:
Imported dataset and verified first 10 tasks loaded correctly

One Failure-Case Walkthrough:
If server does not start, restart terminal and re-run command
