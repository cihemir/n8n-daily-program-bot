# Academic Calendar Automation System (n8n & Google API Integration)

This project is an automation solution built on the n8n workflow automation platform. It dynamically retrieves university course schedule data from Google Sheets and provides a daily academic report to the user via Gmail.

## Project Overview
The system eliminates the need for manual tracking by ensuring the academic schedule reaches the user every morning at a scheduled time. Using a JavaScript-based filtering algorithm, only the data relevant to the current day is processed and transformed into a meaningful report.

## Technical Specifications
* **Scheduler (Schedule Trigger):** An optimized trigger mechanism for daily routine operations.
* **Google Sheets Integration:** Retrieval of "Gun" (Day), "Dersler" (Courses), and "Saat" (Time) columns via API from the spreadsheet acting as the database.
* **JavaScript Data Processing:** Parsing data based on the current date and managing "no-course" scenarios within a Code Node structure.
* **Secure Authorization:** A secure access layer provided by the OAuth 2.0 protocol via Google Cloud Console.

## Technologies Used
* **Automation:** n8n Workflow Automation
* **Data Management:** Google Sheets API
* **Communication Service:** Gmail API
* **Logic Layer:** Node.js / JavaScript

## Installation Instructions
1. Import the "workflow.json" file included in this repository into the n8n interface.
2. Enable the Sheets and Gmail APIs in your project created via Google Cloud Console.
3. Define your Client ID and Client Secret keys in the n8n Credentials section.
4. Activate the automation by toggling the "Active" button in the n8n interface.

---
*This project has been developed as part of engineering efforts to increase the efficiency of academic processes.*
