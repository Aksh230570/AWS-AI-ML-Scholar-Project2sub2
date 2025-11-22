# AWS-AI-ML-Scholar-Project2sub2 
## Career Coach Assistant – Amazon Q Business

AI-powered tool that analyzes CVs and job descriptions to provide skill gap analysis, training recommendations, and training schedules.

### 📌 Project Overview

This project is part of the AWS AI & ML Scholar – Business Intelligence Course.
The application uses Amazon Q Business to automate and improve the efficiency of career coaching by generating insights from uploaded documents.

The system performs:

Skill gap analysis

Training recommendations

Weekly training schedules

Document-based question answering

Secure access control using S3 data sources & ACLs

Keyword blocking & content guardrails

App verification & sharing within the organization

### 🚀 Features Implemented
✔️ 1. Working Interface

A fully functional UI with the following cards (Page 1–2):

Career Coach Assistant Input

Coach Recommendation

Analyze Skill Gaps

Training Recommendations

Training Schedule

Screenshots show the updated interface and all cards functioning.

✔️ 2. Output Cards Implemented

As shown on Pages 1–3, output cards successfully display:

Skill gap insights

Relevant training courses

Weekly training schedule

✔️ 3. End-to-End Functionality Tested

A real coach recommendation was entered, and the model generated accurate structured outputs based on the input and uploaded documents (Page 3).

✔️ 4. S3 Bucket & Data Source Configuration

Per screenshots (Page 3):

S3 bucket successfully added

Data source synced

Indexing details displayed

File upload confirmed

✔️ 5. ACL File Added Successfully

As shown in the screenshot (Page 4):

ACL JSON file uploaded

Access permissions set for different catalog folders

"ALLOW" rules configured properly

✔️ 6. Access Control Validation

Screenshots show (Page 4):

Access denied state with authorization prompt

Access granted state where content loads successfully

✔️ 7. Keyword Blocking Enabled

On Page 5, keyword blocking configuration is visible:

Blocked word list added

Guardrail active

Chat personalization disable options shown

✔️ 8. App Sharing, Labels & Verification

Final screenshots (Page 6) confirm:

App labeled with AI, Course Advisor, Career Coaching

Sharing enabled for all org members

App marked Verified by Admin

App link generated

### 🏗️ Tech Stack
Component	Technology
AI Engine	Amazon Q Business
Storage	Amazon S3
Access Control	ACL JSON + Q Business Guardrails
Hosting	AWS Console (Q Business App)
Data Source	Q Business Index sourced from S3
