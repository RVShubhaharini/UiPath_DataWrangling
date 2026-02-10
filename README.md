UiPath Automation Projects

Overview
This repository documents the automation workflows developed using UiPath Studio as part of hands-on learning and applied automation practice.
The automations focus on web data extraction, local system automation, file handling, and email-based notifications, demonstrating practical Robotic Process Automation (RPA) use cases commonly adopted in industry.

Tools & Technologies Used
UiPath Studio
UiPath Recorder (Modern)

Data Scraping Wizard
Excel Activities
File System Activities
Email Automation (SMTP / Outlook)
Selectors & UI Explorer
Control Flow Activities

Automations Implemented
1. Website Data Scraping Automation
Automated extraction of structured data from dynamic websites using UiPath Data Scraping Wizard.
Handled pagination and repeated UI patterns.
Extracted data stored into a DataTable and exported to Excel for further processing.
Used modern selectors and browser automation techniques.

Key Activities Used
Open Browser
Extract Structured Data
Write Range
Close Tab / Close Browser

2. Local File System Automation
Automated monitoring and management of local directories.
Processed files based on file type and naming patterns.
Automatically moved, copied, or organized files into target folders.

Example Use Cases
Moving all PDF files to a specific folder
Organizing downloaded files based on extension

Key Activities Used
For Each File in Folder
If Condition
Move File
Copy File
Path Exists

3. File Reading and Data Processing Automation
Automated reading of local files such as text files and Excel files.
Performed conditional checks and basic content analysis.
Logged execution details for traceability and debugging.

Key Activities Used
Read Text File
Read Range
Assign
Log Message
If / Switch

4. Email Notification Automation
Automated email notifications based on task completion or file availability.
Triggered emails when specific conditions were met (e.g., file created, task completed).
Used secure email configuration methods.

Key Activities Used
Send Outlook Mail Message
or
Send SMTP Mail Message
Path Exists
Build String

5. End-to-End Automation Workflow
Integrated web scraping, file processing, and notification into a single automated workflow.
Ensured proper sequencing and exception handling.
Implemented logging to track execution status.

Workflow Flow
Open and scrape website data
Save extracted data to local system
Process or validate stored data
Send notification email upon successful execution
Control Flow & Error Handling
Used control flow activities to manage execution logic.
Implemented conditional branching and looping mechanisms.
Applied logging for monitoring and debugging automation runs.

Activities Used
Try Catch
If
For Each
While
Delay

Skills Demonstrated
Robotic Process Automation (RPA)
Web automation and data extraction
File system automation
Email-based workflow notifications
UiPath selectors and UI handling
Workflow orchestration and debugging  

Outcome
This project demonstrates practical implementation of UiPath RPA workflows to automate repetitive and rule-based tasks, 
aligning with real-world enterprise automation scenarios such as data collection, file management, and automated reporting.
