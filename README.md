🗃️ IPL SQL Analysis: Query Breakdown
📋 Database Setup
Create Database: CREATE DATABASE ipl; creates a new database named ipl to store IPL match data.
Set Active Database: USE ipl; sets the ipl database as the active database for subsequent queries.
Inspect Table Structure: DESC DELIVERIES; displays the structure (schema) of the DELIVERIES table, showing columns like MATCH_ID, INNING, OVER, BALL, etc.
View All Data: SELECT * FROM deliveries; retrieves all rows and columns from the DELIVERIES table to inspect the data.
🔍 Query 1: List Deliveries with Specific Details
Purpose: Selects specific columns (match_id, inning, over, ball) from the DELIVERIES table.
Outcome: Lists delivery details for all entries in the dataset.
