# Task Management Tracker 
## Overview
This project presents a **Task Management Tracker Dashboard** built entirely in **Microsoft Excel**.  
It is designed for project managers and team leads to efficiently track, visualize, and manage multiple ongoing tasks in one place.

The dashboard transforms raw task data into an interactive management tool that highlights priorities, monitors deadlines, and visualizes team progress in real time.

---

## Purpose
Managing projects across teams often involves multiple dependencies, priorities, and shifting deadlines.  
This dashboard simplifies that process by consolidating all essential insights—helping managers focus on what matters most: completing tasks on time and maintaining productivity.

---

## Key Features
- **Dynamic KPIs and Charts:** Summarizes total tasks, status distribution, priority breakdown, and overdue trends.  
- **Interactive Filters:** Slicers for task ID, priority, status, pending age, and overdue condition enable quick, data-driven exploration.  
- **Automated Visual Indicators:** Conditional formatting highlights overdue and completed tasks.  
- **Detailed Task Table:** Displays comprehensive task details including ownership, start/due dates, completion date, and pending age.

---

## Tools and Techniques
- **Software:** Microsoft Excel  
- **Techniques:** Pivot Tables, Charts, Slicers, Conditional Formatting  
- **Formulas Used:**
  ```excel
  IF(), DATEDIF(), TODAY(), TEXT()
  **Used to calculate pending days and overdue status automatically.**

  Insights

From the sample dataset of 15 tasks:

34% of tasks are completed.
8 tasks are overdue, mostly high-priority.
Majority of tasks fall within a 0–5 day pending age, indicating short project cycles.
These insights help identify bottlenecks, prioritize workloads, and enhance time management.

How to Use This?
<img width="1763" height="783" alt="Task_mgmt_tracker screenshot" src="https://github.com/user-attachments/assets/f92a321a-ad8f-4bdc-9d8d-dbc19a3a4c1f" />

Download and open the Excel file : <https://github.com/Andrea-simon-tech/Excel_projects/blob/main/Task%20management%20Tracker.xlsm>
Use the slicers to filter data dynamically.
Update the task table to automatically refresh visuals and summaries.

Learnings

This was my first Excel visualization project. It provided hands-on experience in:
Structuring data for dashboards
Combining Pivot Tables and charts for dynamic reporting
Using formatting and interactivity to tell a data story

Future Enhancements

Add progress KPIs and timeline visualizations
Include Gantt chart integration
Automate updates with Power Query or VBA


Developed by Andrea Simon

Excel Visualization | Project Management | Data Analytics
