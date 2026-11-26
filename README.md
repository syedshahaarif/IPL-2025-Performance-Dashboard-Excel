# IPL 2025 Performance Dashboard (Microsoft Excel & Power Pivot)

An interactive two-page cricket analytics dashboard built in **Microsoft Excel** using **Power Pivot (Star Schema Data Modeling)**, **DAX Measures**, **PivotTables**, **PivotCharts**, and **Dynamic Slicers** to analyze team and player performance across the IPL 2025 season.

## Project Highlights
- **Data Model (Star Schema):** Connected `fact_match` and `fact_player` tables with `dim_team`, `dim_player`, and `dim_venue` dimension tables in Power Pivot.
- **Dynamic KPIs:** Automated KPI cards using `GETPIVOTDATA` and DAX measures that update dynamically with slicer selections.
- **Interactive Filtering:** Filter insights across teams and stadiums using connected `Team_Name` and `Venue_Name` slicers.

## Dashboards

### 1. Team Performance Dashboard
Tracks **60 Matches**, **8 Franchises**, **20,944 Total Runs**, and **799 Total Wickets**, with visual breakdowns for:
- Team vs. Total Runs
- Venue vs. Matches
- Win Type Distribution (Win by Run vs. Win by Wickets)
- Team vs. Total Wins

<img width="819" height="597" alt="Team Performance Dashboard" src="https://github.com/user-attachments/assets/6cef61c6-b167-40ab-9a4d-c54f1a1f3b04" />

### 2. Player Performance Dashboard
Tracks batting and bowling efficiency across **33 Players**, covering Total Runs, Total Wickets, Average Strike Rate, and Average Bowling Economy:
- Player vs. Total Runs
- Player vs. Total Wickets
- Strike Rate & Economy Comparisons

<img width="819" height="594" alt="Player Performance Dashboard" src="https://github.com/user-attachments/assets/1a3d51ff-bc10-43dd-aa3e-86c1b9fcba32" />

## Tools & Skills Used
- **Microsoft Excel** (PivotTables, PivotCharts, Slicers, `GETPIVOTDATA`)
- **Power Pivot & Data Modeling** (Fact & Dimension table relationships)
- **DAX** (Custom measures for Runs, Wickets, Strike Rate, and Economy)

## How to Use
1. Download `IPL_2025_Performance_Dashboard.xlsx`.
2. Open in Microsoft Excel (Desktop) and click **Enable Content** if prompted.
3. Use the `Team_Name` and `Venue_Name` slicers to explore team and player stats interactively.
