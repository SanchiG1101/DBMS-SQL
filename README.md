# DBMS-SQL
Blood Donation Management System
📌 Overview
This system manages the end-to-end blood donation process, ensuring smooth interaction between **donors, blood banks, hospitals, and patients.

🗃️ Database Schema
The system consists of the following tables:

Donor - Stores donor details.
Blood_Bank - Manages blood storage.
Donation - Tracks blood donations.
Clinical_Analyst - Analyzes and approves blood quality.
Patient - Stores patient details who receive blood.
Registration_Team - Handles patient registrations.
Hospital - Manages hospital requests for blood.
Manager - Supervises hospital operations and inventory.
📜 SQL Scripts
blood_bank_management.sql - Contains database schema, including tables and relationships.

queries.sql - Contains SQL queries for retrieving, inserting, updating, and deleting records.

triggers_procedures.sql - Includes triggers and stored procedures for automation and validation.

PROCESSS -- Donor donates to Blood Bank via the Donation process. -- Blood Bank stores Blood, and Blood is analyzed by the Clinical Analyst. -- Patient receives blood and is registered by the Registration Team. -- Hospital contacts Blood Bank for blood requirements, and the Manager supervises the hospital operations.

🚀 How to Run
Import blood_bank_management.sql into MySQL.
Execute triggers_procedures.sql to enable automation.
Run queries.sql for sample queries.
Integrate with a web application (if required).
