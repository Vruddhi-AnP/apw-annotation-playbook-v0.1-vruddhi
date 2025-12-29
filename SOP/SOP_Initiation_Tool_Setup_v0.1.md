SOP – Tool Setup and Toy Project (Label Studio)

Purpose
    -To set up Label Studio on my laptop and understand how a basic text annotation project works.

Scope
In scope:
- Installing and running Label Studio
- Creating a toy text annotation project
- Uploading sample data and doing annotation

Out of scope:
- Real client data
- Large projects or multiple annotators


Inputs needed
- Python already installed
- Internet connection
- Sample text file with 10 sentences
- Web browser

Outputs produced
- One toy project in Label Studio
- 10 annotated text tasks
- Exported annotation file (JSON)

Tools 
- Python
- Label Studio
- PowerShell
- Browser


Failure modes 
 1. Label Studio not starting
 2. Virtual environment not active
 3. Data file not importing properly
 4. Labels not visible during annotation


Step-by-step procedure
 1. Start Label Studio on localhost  
 2. Create a new toy text annotation project  
 3. Upload a text file with 10 sample sentences  
 4. Set labels as Positive, Negative, Neutral  
 5. Select “Label All Tasks”  
 6. Annotate all 10 tasks one by one

quality checks
- Check that 10 tasks are uploaded
- Check that only one label is selected per task
- Check that tasks show as completed


Example run on 10 items
 -I uploaded 10 sample sentences and annotated all of them successfully.

One failure-case walkthrough
     Issue: Only one task opened for annotation  
     Fix: Changed option from “Label 1 Task” to “Label All Tasks”
