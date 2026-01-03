

🚀 PHPTRAVELS - Manual Testing & UAT Portfolio
Tester: Shivam Yadav

Project: Comprehensive Quality Assurance (QA) & User Acceptance Testing (UAT)

📌 Project Overview
The goal of this project was to perform end-to-end manual testing on the PHPTRAVELS booking platform. I focused on validating the user journey from registration to order management, identifying critical functional bugs, and evaluating the UI/UX for better accessibility.

🛠 Testing Scope
Functional Testing: Sign-up, Login, Profile Updates, and Password Reset.

UAT (User Acceptance Testing): Order creation flow and business logic validation.

Security & Validation: Email syntax and mobile number input checks.

UI/UX Evaluation: Consistency in fonts, colors, and dashboard navigation.

🐞 Critical Bugs Identified
1. Order Deletion - 404 Error (Critical)
Issue: Clicking the 'Delete' button on a previous order redirects to a "404 Page Not Found" error.

Impact: Breaks the user experience and leaves the database cluttered with unwanted orders.

2. Mobile Number Validation (Major)
Issue: The system accepts any number of digits (e.g., 1234 or 123456789012345) instead of restricting it to a 10-digit format.

Impact: High risk for data integrity and communication failure in a real-world scenario.

📂 Deliverables in this Repo
Shivam_QA_Report.xlsx: Detailed Test Case document with Steps, Expected vs Actual Results, and Status.

Bug Screenshots: Visual proof of the 404 error and validation issues.

💡 Key Learnings & Suggestions
Logic over Code: Understood how business rules (like blocking new orders until previous ones are paid) protect business revenue.

UX Suggestion: The dashboard is clean but adding more interactive images/icons would make it more engaging for first-time users.

Healthcare Context: This experience is directly applicable to platforms like KareXpert, where data accuracy (Mobile/Email) is vital for patient safety.
