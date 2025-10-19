# Automated Credit Card Approval System 
## Introduction and Goal
   The current credit card approval process is still heavily reliant on manual tasks, which leads to significant issues such as long processing times, high error rates, and excessive resource consumption. These shortcomings not only hinder internal operational efficiency but also directly impact customer satisfaction.
   This project was developed to comprehensively solve these problems using a Robotic Process Automation (RPA) solution built on the UiPath platform. The primary goal is to create an automated processing system that runs 24/7 to drastically reduce wait times, ensure complete accuracy, and free employees from repetitive work. This will make the process both flexible and easily scalable to meet evolving business needs.
## Key Features
The bot is programmed to perform a series of tasks automatically:
- Automated Application Intake: Automatically fetches new application data from Google Sheets.
- OCR Data Extraction: Uses OCR technology to “read” and extract information from scanned identity documents (ID cards, Passports, Visas).
- Data Validation: Checks the completeness and validity of applications and cross-references information with a simulated database.
- Credit Assessment: Automatically checks CIC scores, validates income, and applies business rules to calculate a proposed credit limit.
- Human-in-the-Loop Exception Handling: Pauses the process and requests a manual review from an employee for complex cases (e.g., a customer with no CIC credit history).
- Document Generation and Notification: Automatically generates a PDF contract for approved applications or a rejection letter, then sends a final notification email to the customer with the relevant documents attached.
### Demo Video: https://drive.google.com/file/d/1pJvHkW-NAQ3bhmLN52HXNUVXKHoFG6CS/view?usp=sharing
## Technology Stack
- Platform: UiPath Studio, UiPath Orchestrator
- Technologies: Robotic Process Automation (RPA), Optical Character Recognition (OCR)
- Integrations: Microsoft Office (Excel, Word), GSuite (Google Sheets), Mail
## Challenges and Future Work
- Challenges: Lack of real-world APIs (requiring the use of simulated data); OCR accuracy with low-quality documents; difficulties integrating code from parallel development branches.
- Future Development: Expand the automation to corporate customer applications; upgrade and integrate AI for enhanced analytics and decision-making capabilities.
