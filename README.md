# Fortune 100 Companies Analysis

## Project Overview
This project analyzes the largest companies in the United States based on revenue, using data from Wikipedia. The dataset is scraped, cleaned, and visualized to uncover insights into industry revenue distribution, employee count, and growth trends.

## Technologies Used
- **Python**: Data scraping, transformation, and visualization
- **BeautifulSoup**: Web scraping Wikipedia data
- **Pandas**: Data cleaning and manipulation
- **Matplotlib & Seaborn**: Data visualization and statistical analysis

## Features & Analysis
### 1. **Web Scraping**
- Extracts company data from [Wikipedia](https://en.wikipedia.org/wiki/List_of_largest_companies_in_the_United_States_by_revenue)
- Cleans and stores the data in a structured format (CSV file)

### 2. **Data Cleaning & Transformation**
- Converts revenue, growth percentage, and employee count to appropriate data types
- Splits headquarters locations into `City` and `State`
- Removes unnecessary columns for better data efficiency

### 3. **Exploratory Data Analysis (EDA)**
- **Top 10 Companies by Revenue**: A bar chart visualizing the highest-earning companies
- **Industry-wise Revenue & Growth**: Analysis of industry-wide revenue distribution and average growth rates
- **State-wise Company Distribution**: Identifies states with the highest number of Fortune 100 companies
- **Employee Distribution by Industry**: Pie chart representing workforce distribution across industries
- **Correlation Matrix**: Heatmap to analyze relationships between revenue, employees, and growth rates
- **Revenue vs. Employees Scatter Plot**: Highlights trends in company size and financial performance

## Insights Gained
- Certain industries dominate revenue generation in the U.S.
- Employee count does not always correlate with high revenue
- Specific states house the majority of Fortune 100 headquarters
- Revenue growth rates vary significantly across industries

## How to Run the Project
1. Install dependencies:  
   ```bash
   pip install beautifulsoup4 requests pandas matplotlib seaborn
   ```
2. Run the script:  
   ```bash
   python analysis.py
   ```
3. The CSV file `wikidata.csv` will be created, and visualization charts will be displayed.

## Future Enhancements
- Automate data updates with scheduled scraping
- Integrate additional financial metrics
- Build an interactive dashboard using Power BI or Streamlit

## Contact
For any questions or contributions, feel free to reach out!

