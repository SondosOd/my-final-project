# BikeShare Data Analysis Project

This project allows users to explore bikeshare data for **Chicago, New York City, and Washington**.  
Users can filter the data by **month** and **day** to analyze trends in bike usage.

## Project Overview
The program interacts with the user to:
- Select a city and filter the data by month and/or day.
- Display statistics on **popular travel times, stations, trip durations, and user demographics**.
- Optionally show raw data upon request.

## Features
### 🔹 **System Functions**
- **Clear Screen:** Clears the terminal before running or restarting the script.
  - Works on both **Windows** (`cls`) and **Mac/Linux** (`clear`).

### 🔹 **User Input Handling**
- **City Selection:** Users can choose between `Chicago`, `New York City`, and `Washington`.
- **Time Filters:** 
  - Can filter data by `month`, `day`, `both`, or `none`.
  - Available months: `January - June`
  - Available days: `Monday - Sunday`
- **Input Validation:** Ensures the user provides a valid input before proceeding.

### 🔹 **Data Processing**
- **Load Data:** Reads city-specific CSV files and applies selected filters.
- **Convert Datetime Columns:** Converts `'Start Time'` to a datetime format.
- **Extract New Features:** Adds `'Month'` and `'Day'` columns for filtering.

### 🔹 **Statistics & Insights**
- **Popular Travel Times:**
  - Most common `month`, `day of the week`, and `hour` for bike rides.
- **Station Analysis:**
  - Most frequently used **start station** and **end station**.
  - Most common **trip route**.
- **Trip Duration:**
  - **Total travel time** (formatted in `days:hours:minutes:seconds`).
  - **Average travel time** per trip.
- **User Demographics:**
  - **User Type** distribution (Subscriber vs Customer).
  - **Gender Breakdown** (if available).
  - **Birth Year Insights** (earliest, most recent, most common).
- **Raw Data Display:** Users can view data in chunks of 5 rows.


