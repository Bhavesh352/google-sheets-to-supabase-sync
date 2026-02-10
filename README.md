# google-sheets-to-supabase-sync
Automated data synchronization system integrating Google Sheets with Supabase via REST APIs, enabling real-time database updates, secure data transfer, and scalable cloud-based storage.

**1.Project Description**

This project implements an automated data synchronization solution between Google Sheets and a Supabase database table using RESTful API communication.
Whenever a new row is added or modified in Google Sheets, the system captures the change and securely transmits the structured data to Supabase, ensuring real-time updates and consistent cloud-based storage.

**2.Project Overview**

**What the System Does**

* Automatically synchronizes data from Google Sheets to a Supabase PostgreSQL database.

* Updates the database in real time whenever a row is added or modified in the spreadsheet.

* Ensures structured and consistent cloud-based data storage.

**How It Works (High-Level)**

* Detects changes made in Google Sheets.

* Converts spreadsheet rows into structured JSON format.

* Sends the formatted data securely to Supabase using REST API calls.

* Inserts or updates records in the PostgreSQL database.

**Use Cases**

* Lead and customer data management

* Form submission data storage

* Student or employee record management

* Inventory and stock tracking

**3.Tech Stack**

**1.Frontend / Data Source**

* Google Sheets

  * Used as the primary data input interface for users.

  * Acts as a lightweight frontend where users can add, edit, or update records.

**2.Backend Automation**

* Serverless Runtime

 * Handles automation logic
   
 * Executes on-edit triggers
   
 * Sends HTTP requests to Supabase
   
 * Acts as middleware between Google Sheets and database

**3.API Layer**

* Supabase REST API

* Automatically generated REST endpoints

* Handles secure data insertion

* Accepts JSON payloads from Apps Script

**4.Database**

* PostgreSQL (via Supabase)

  * Structured relational database

  * Stores sheet data
 
  * Supports indexing & constraints

  * Auto-generated id and created_at fields


