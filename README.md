# Google Ads Sales Data Analysis
This project focuses on cleaning, preprocessing, and analyzing a Google Ads sales dataset to evaluate campaign performance and generate actionable marketing insights. Using Python and data analysis techniques, the raw dataset was transformed into a structured format and explored through statistical analysis and visualizations.
## Project Objectives
*  Clean and preprocess raw advertising data
*  Clean and preprocess raw advertising data
*  Standardize categorical variables
*  Perform Exploratory Data Analysis (EDA)
*  Calculate key marketing metrics such as CTR, CPC, Conversion Rate, and ROAS
*  Visualize trends and relationships in advertising performance
## Tools & Technologies
*  Python
*  Pandas – Data cleaning and analysis
*  NumPy – Numerical operations
*  Matplotlib & Seaborn – Data visualization
*  Plotly – Interactive visualizations
*  Jupyter Notebook
## Data Preprocessing
The dataset required several preprocessing steps before analysis:
*  Standardized text values in Location, Campaign_Name, Device, and Keyword
*  Removed currency symbols from Cost and Sale_Amount
*  Converted numeric columns to proper data types
*  Standardized Ad_Date to datetime format
*  Handled missing values using device-based mean imputation
*  Recalculated Conversion Rate after cleaning
## Exploratory Data Analysis
EDA was conducted using statistical summaries and 13 visualizations, including:
*  Histograms for distribution analysis
*  Bar charts for device and keyword comparisons
*  Box plots for revenue distribution and outlier detection
*  Scatter plots for metric relationships
*  Line charts for time-based trends
*  Pie charts for device share
*  Heatmaps for correlation analysis
*  Interactive Plotly charts for deeper exploration
## Key Insights
*  Advertising costs and clicks were relatively consistent across devices.
*  Tablet devices showed slightly lower conversion rates.
*  “Data Analytics Course” keyword generated the highest engagement and ROAS.
*  A strong negative correlation between CTR and CPC suggests that higher engagement can reduce cost per click.
*  A noticeable spike in cost and conversions around Nov 14 2024, indicates a likely targeted campaign event.
## Recommendations
*  Allocate more budget toward high-performing keywords.
*  Optimize ad creatives and landing pages for tablet users.
*  Use conversion-focused bidding strategies for higher-value audiences.



