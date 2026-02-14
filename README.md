Twitter NLP Analysis Dashboard

This project is a Twitter NLP Analysis Dashboard built using Power BI. It analyzes tweet text data to identify word frequency patterns and track language trends over time. The dashboard provides interactive visualizations to explore keyword usage and temporal evolution.

📌 Project Overview

This project presents a Twitter NLP Analysis Dashboard built entirely in Power BI.  
The dashboard analyzes tweet text data to identify keyword frequency patterns and temporal language trends using Power BI’s data transformation and visualization capabilities.

All preprocessing, transformation, and analysis were performed inside Power BI using Power Query and DAX.

🎯 Project Objectives

- Analyze Twitter text data
- Identify the most frequent words
- Track keyword trends over time
- Build interactive dashboard visualizations
- Extract meaningful language insights from tweet data

📂 Dataset Description

- Dataset Format: CSV / Excel
- Fields Used:
  - Tweet Text
  - Date
  - Year (Derived from Date)
- Time Range: 2010 – 2017

The dataset contains tweet text along with associated dates. The text data was processed to extract word-level information and analyze frequency trends across different years.

🔄 Data Processing in Power BI

🔹 Power Query (Data Transformation)

The following steps were performed inside Power Query Editor:

- Converted text to lowercase
- Removed punctuation and special characters
- Split tweet text into individual words
- Removed stopwords
- Expanded rows for word-level analysis
- Created a Year column from the Date field

🔹 Data Modeling

- Aggregated word counts
- Created relationships where required
- Structured data for word-level and year-wise analysis

🔹 DAX Measures

Created DAX measures for:

- Word Count
- Total Word Count
- Year-wise word aggregation
- Dynamic keyword filtering logic

📊 Dashboard Components

📈 Temporal Evolution of Key Language Trends

- Line chart visualization
- Shows yearly word frequency
- Tracks selected keywords such as:
  - love
  - happy
  - thank
  - president
  - obama

📊 Top 20 Most Frequent Words

- Bar chart visualization
- Displays the most commonly used words in tweets

📋 Word Frequency Summary

- Table visualization
- Shows word and count
- Includes total word count summary

🛠 Tools & Technologies Used

- Power BI Desktop
- Power Query Editor
- DAX (Data Analysis Expressions)
- CSV / Excel dataset

▶️ How to Use the Dashboard

1. Download the `.pbix` file from this repository
2. Open it in Power BI Desktop
3. Refresh the dataset if required
4. Use filters and slicers to explore keyword trends and word frequencies

🔎 Key Insights

- Word frequency increased significantly between 2014–2016.
- "Love" and "Thank" show strong engagement trends.
- Political keywords show spikes in specific years.
- Certain words dominate overall tweet communication patterns.
- Temporal trends reveal shifts in language usage over time.

⚠️ Challenges Faced

- Text splitting and transformation complexity in Power Query
- Stopword removal inside Power BI
- Handling large text datasets efficiently
- Creating dynamic keyword filtering logic
- Optimizing dashboard performance

🚀 Future Improvements

- Add sentiment scoring
- Add word cloud visualization
- Integrate live Twitter API data
- Implement topic clustering
- Deploy dashboard to Power BI Service

Screenshot of Dashboard

<img width="1294" height="730" alt="Twitter" src="https://github.com/user-attachments/assets/741ef8d2-108a-4cab-b013-13a034519323" />
