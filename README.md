#  T20 World Cup 2022 Analytics Dashboard | End-to-End Data Engineering & Power BI Project

An end-to-end cricket analytics project that collects T20 World Cup 2022 data through web scraping, transforms and cleans the data using Python, and visualizes key insights through an interactive Power BI dashboard.



##  Project Overview

This project demonstrates a complete data analytics workflow:

- Scraping T20 World Cup 2022 data from ESPN Cricinfo
- Extracting match, batting, bowling, and player information
- Cleaning and transforming raw JSON data using Python
- Building fact and dimension tables for analysis
- Creating an interactive Power BI dashboard
- Generating player and team performance insights

The dashboard helps identify top-performing players and teams using data-driven metrics rather than subjective evaluation.



## Project Structure

```text
repo/
│
├── web_scraping_codes/
│   ├── t20_wc_match_results.js
│   ├── t20_wc_batting_summary.js
│   ├── t20_wc_bowling_summary.js
│   └── t20_wc_player_info.js
│
├── json_files/
│   ├── t20_wc_match_results.json
│   ├── t20_wc_batting_summary.json
│   ├── t20_wc_bowling_summary.json
│   └── t20_wc_player_info.json
│
├── preprocessing_nb/
│   └── t20_data_preprocessing.ipynb
│
├── csv_files/
│   ├── dim_match_summary.csv
│   ├── dim_players_no_images.csv
│   ├── fact_bating_summary.csv
│   └── fact_bowling_summary.csv
│
└── dashboard/
    ├── PROJECT_DASHBOARD_F.pbix
    ├── DAX-Measures-and-Calculated-Columns.xlsx
    └── Parameter-Scoping.pdf
```



## Tech Stack

### Data Collection
- JavaScript
- Web Scraping
- ESPN Cricinfo

### Data Processing
- Python
- Pandas
- Jupyter Notebook
- JSON

### Data Modeling
- Fact Tables
- Dimension Tables
- Star Schema

### Visualization
- Power BI
- DAX
- Interactive Dashboards


##  Dashboard Features

### Batting Analysis
- Runs Scored
- Batting Average
- Strike Rate
- Boundary Percentage
- Consistency Metrics

### Bowling Analysis
- Wickets Taken
- Economy Rate
- Bowling Average
- Bowling Strike Rate

### Team Insights
- Match Results
- Team Comparisons
- Win/Loss Trends
- Tournament Progression

### Player Insights
- Top Performers
- Role-Based Analysis
- Contribution Metrics



##  Data Pipeline

```text
ESPN Cricinfo
      │
      ▼
Web Scraping (JavaScript)
      │
      ▼
Raw JSON Files
      │
      ▼
Data Cleaning & Transformation (Python)
      │
      ▼
Fact & Dimension Tables
      │
      ▼
Power BI Data Model
      │
      ▼
Interactive Analytics Dashboard
```


##  Key Skills Demonstrated

- Data Analytics
- Data Cleaning
- ETL Pipeline Development
- Web Scraping
- Data Modeling
- Power BI Dashboard Development
- DAX Calculations
- Sports Analytics
- Business Intelligence



##  Business Problem

Cricket team selection often relies on subjective analysis. This project applies data analytics to objectively evaluate player performances during the ICC Men's T20 World Cup 2022 using batting and bowling metrics.



##  Future Improvements

- Automated data refresh pipeline
- Live match data integration
- Predictive player performance analysis
- Advanced player ranking models
- Power BI Service deployment



##  Author

**Mehar Arora**

