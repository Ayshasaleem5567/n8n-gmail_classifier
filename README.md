# Email Automation System using n8n

## Project Overview

This project is an automated email processing system built using **n8n** that streamlines inbox management by automatically handling incoming emails. It continuously monitors the mailbox, processes each new email, and performs actions based on its content.
When a new email arrives, the workflow first analyzes and classifies it into a relevant category. Based on this classification, it checks whether an appropriate label already exists in the email system. If the label is not found, it is created dynamically. The email is then assigned the correct label to ensure proper organization and easy tracking.
After organizing the email, the system automatically generates and sends a reply to the sender, ensuring timely acknowledgment without requiring manual intervention.
Overall, this automation reduces manual effort, improves email organization, and ensures faster response handling.



## Workflow Steps

1. Email Trigger:Detects new incoming emails in real time.
2. Email Fetching:Retrieves email content, sender information, and metadata.
3. Classification:Analyzes email content and assigns a relevant category.
4. Label Management
   Checks if a corresponding label exists.
   Creates a new label if it does not already exist.
5. Label Assignment:Applies the appropriate label to the email.
6. Automated Reply:Sends a context-based response to the sender.



## Key Features

Fully automated email handling
Dynamic label creation
Intelligent email classification
Automatic response generation
Reduced manual inbox management
Faster email processing and organization



## Tech Stack

n8n (Workflow Automation)
Email Integration (Gmail/SMTP)
AI-based classification (if applicable)
Webhooks / Triggers



## Project Files

`workflow.json` → Exported n8n workflow
`README.md` → Project documentation
`video.mp4` → Demo of workflow in action 




## Author

Built as an automation project using n8n to demonstrate workflow automation and intelligent email processing.
