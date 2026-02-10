# google-sheets-to-supabase-sync
Automated data synchronization system integrating Google Sheets with Supabase via REST APIs, enabling real-time database updates, secure data transfer, and scalable cloud-based storage.

1.Project Description

This project implements an automated data synchronization solution between Google Sheets and a Supabase database table using RESTful API communication.
Whenever a new row is added or modified in Google Sheets, the system captures the change and securely transmits the structured data to Supabase, ensuring real-time updates and consistent cloud-based storage.

2.Project Overview

What the System Does

Automatically synchronizes data from Google Sheets to a Supabase PostgreSQL database.
Updates the database in real time whenever a row is added or modified in the spreadsheet.
Ensures structured and consistent cloud-based data storage.

How It Works (High-Level)

Detects changes made in Google Sheets.

Converts spreadsheet rows into structured JSON format.

Sends the formatted data securely to Supabase using REST API calls.

Inserts or updates records in the PostgreSQL database.
