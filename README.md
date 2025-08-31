# Website-Performance-Analysis-Project
🌐 Website Performance Analysis (Python Project)

This project demonstrates how to clean, transform, and analyze website performance data using Python (Pandas, NumPy, Matplotlib, Seaborn).

The dataset (data-export.csv) contains metrics such as users, sessions, engagement rate, events per session, and session channels. The goal is to prepare clean data for further analytics & visualization.

📌 Steps in the Project
1. Load the Dataset

Used pandas.read_csv() to import the raw data.
Initial inspection with .head() revealed unnamed columns and headers embedded inside the first row.

📷 Data Loading
2. Data Cleaning

Extracted proper headers using the first row.
Dropped redundant/unnecessary columns.
Converted columns into correct data types (int64, float64, datetime).
Renamed columns for readability.

📷Cleaning Process (Step 1)


📷Cleaning Process (Step 2)


3. Feature Engineering

Created a new column Hour extracted from the Datehour field.
Converted numeric columns to correct datatypes.
Structured the dataframe for deeper analysis.

4. Final DataFrame Structure

Columns after cleaning & transformation:
channel group – Source of traffic (Direct, Organic Social, etc.)
Datehour – Timestamp of sessions

Users – Total users
Sessions – Total sessions
Engaged sessions – Number of engaged sessions
Average engagement time per session
Engaged sessions per user
Events per session
Engagement rate
Event count
Hour – Extracted from Datehour

✅ This project shows how raw exported CSV data can be transformed into structured analytics-ready data using Python.
