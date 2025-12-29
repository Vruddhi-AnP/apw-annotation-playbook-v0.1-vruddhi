SOP – Tool Setup and Toy Project (Label Studio)

Purpose
To set up Label Studio on my laptop and understand how a basic text annotation project works.

Scope
In scope:
   - Installing and running Label Studio
   - Creating a toy text annotation project

Out of scope:
   - Real client data
   - Large projects or multiple annotators

Who runs this (Owner role)
   -Data Annotation Intern

Inputs needed
   - Laptop with Windows 11
   - Python already installed
   - Internet connection
   - Sample text file with 10 sentences
   - Web browser

Outputs produced
   - One toy project in Label Studio
   - 10 annotated text tasks
   - Exported annotation file (JSON)

Tools touched
   - Python
   - Label Studio
   - PowerShell
   - Browser

Timebox (range) + drivers
   - Around 1 hour  
   - Takes longer if setup issues come

Failure modes (top 5)
1. Label Studio not starting
2. Virtual environment not active
3. Data file not importing properly
4. Labels not visible during annotation
5. Wrong task option selected while labeling

Escalation rules
   - Stop if tool does not start
   - Stop if tasks are not visible after import
   - Stop if annotations are not saving

Assumption Ledger
    - Single person is doing annotation
    - No review step is added
    - Completed tasks are treated as final output

Step-by-step procedure
1. Start Label Studio on localhost  
2. Create a new toy text annotation project  
3. Upload a text file with 10 sample sentences  
4. Set labels as Positive, Negative, Neutral  
5. Select “Label All Tasks”  
6. Annotate all 10 tasks one by one

Embedded quality checks
    - Check that 10 tasks are uploaded
    - Check that only one label is selected per task
    - Check that tasks show as completed

Artifacts produced
    - Annotation export file
    - Screenshots of project setup and completed tasks

Example run on 10 items
       -I uploaded 10 sample sentences and annotated all of them successfully.

One failure-case walkthrough:
    Issue: Only one task opened for annotation  
    Fix: Changed option from “Label 1 Task” to “Label All Tasks”
