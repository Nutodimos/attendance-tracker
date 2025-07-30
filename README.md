Project Title: Automated Youth Attendance Tracker: Streamlining Operations with Google Apps Script & Sheets

Overview:
Developed a custom web application using Google Apps Script and Google Sheets to automate and simplify Youth attendance tracking for small to medium-sized audience. This solution replaces manual logging and reduces errors.

The Challenge:
Our client, a youth church, relied on a physical sheet which was then copied into a google sheet manually. This process was prone to human error, consumed significant administrative time, and was subject to damage or loss

My Solution:
I designed and built a user-friendly web application, hosted within Google Workspace, that allows the administrator to quickly and easily check in and out members who are present. 

Key Features:

Intuitive Web Interface: A simple, clean web page for quick check-ins and check-outs.

Real-time Data Capture: Attendance data is instantly logged into a Google Sheet.

Automated Reporting: Scripts generate daily and weekly attendance summaries, highlighting absences or late arrivals.

Data Integrity: Implemented validation to prevent duplicate entries and ensure accurate timestamps.

Scalable Design: Utilized batch operations (SpreadsheetApp.getRange().getValues() and setValues()) to efficiently handle data for up to 200+ members, ensuring the app remains responsive even with growing data volumes.    

Technical Stack:

Backend Logic: Google Apps Script (JavaScript ES6+)

Database: Google Sheets

Frontend UI: HTML Service, CSS, Client-side JavaScript

Google Services Used: HtmlService, SpreadsheetApp, Utilities

Results & Impact:

Time Savings: Reduced administrative time spent on attendance management by an estimated 75% (approx. 5-7 hours per week).

Improved Accuracy: Eliminated manual transcription errors, leading to near 100% data accuracy for payroll.

Enhanced Visibility: Executives now have real-time access to attendance data, improving daily operational planning.

