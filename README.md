# -DASHBOARD-DEVELOPMENT

COMPANY :CODTECH IT SOLUTIONS

NAME :SIDDAMMAGARI CHANDANA

INTERN ID :CT06DF1118

DOMAIN :DATA ANALYTICS 

DURATION :6 WEEKS

MENTOR :NEELA SANTHOSH KUMAR 

*Global COVID-19 Dashboard – Power BI*

This project presents an interactive one-page dashboard is created using *Microsoft Power BI, designed to visualize the global impact of the COVID-19 pandemic.It aims to deliver a clear, intuitive, and dynamic visual overview of confirmed COVID-19 cases, deaths, and recoveries across various countries and over time using real-world data.

*Project Objective*

The objective of this task was to create a functional and interactive dashboard that provides actionable insights  from a dataset by using any one of the industry-standard visualization tools such as Power BI, Tableau, or Dash. The goal was to build a single -page dashboard that highlights trends, comparisons, and summaries with the help of  clean visual layouts and interactive filtering options. Power BI was chosen due to its robust capabilities in both data modeling and visualization, along with its user-friendly drag-and-drop interface.

*Dataset Information*

The dataset used for this project is titled *"COVID-19 Clean Complete", originally sourced from Kaggle, and compiled by [Imdevskp](https://www.kaggle.com/imdevskp). This dataset provides daily records of COVID-19 cases from early 2020 to mid-2021, across multiple countries and regions. It includes fields for:

* Date: The specific date of the recorded entry
* Country/Region: The name of the country
* Confirmed: Total confirmed cases as of that date
* Deaths: Total deaths as of that date
* Recovered: Total recovered patients
* Lat and Long: Geographic coordinates used for mapping

This dataset was selected because of its wide scope, **clean structure, and **rich time-series nature, which makes it well-suited for both trend analysis and country-wise comparison.

*Data Preparation*

In Power BI, data was loaded and transformed using Power Query Editor. Several preparation steps were applied:

* Converted the Date field into proper datetime format
* Removed null values or missing data entries
* Created a new calculated column for Active Cases using:

  Active = Confirmed - Recovered - Deaths

* Ensured correct data types (e.g., integers for numerical columns)
* Formatted numbers with commas for readability (e.g., 1,000,000 instead of 1000000)

These steps ensured a clean, reliable dataset ready for visualization.

*Dashboard Layout*

The dashboard is designed to fit on a single report page to maximize usability. It includes the following sections:

KPI Cards (Top Row)

Three KPI cards provide quick-glance statistics:

* Total Confirmed Cases
* Total Deaths
* Total Recovered

These help summarize the overall global situation instantly for users.

*Line Chart*

A line chart displays the trend of confirmed COVID-19 cases over time. This visual helps users identify peaks, growth rates, and periods of control across global timelines.

*Grouped & Stacked Bar Charts*

* A stacked bar chart shows the proportion of Recovered vs Deaths for each country, highlighting how different nations have responded or been affected.
* A grouped bar chart compares Confirmed, Deaths, and Recovered side-by-side for selected countries.

*Country Slicer*

An interactive Slicer enables filtering of the dashboard by country. This allows users to view metrics and trends specific to the country they are interested in without cluttering the global view.

*Features Summary*

* KPI Cards: Global totals for Confirmed, Deaths, and Recovered
* Line Chart: Visualizes confirmed case trends over time
* Stacked Bar Chart: Compare deaths and recoveries by country
* Grouped Bar Chart: Country-wise breakdown of all key metrics
* Country Slicer: Dynamic filtering for country-specific insights
* Clean One-Page Layout: Minimal scrolling, maximum visibility

*Key Insights*

* The United States,Brzile, and India reported the highest number of confirmed COVID-19 cases during the pandemic.
* Recovery rates  improved steadily in most countries over time, indicating better health response systems, increased vaccinations, and global cooperation.
* Certain countries showed high death-to-confirmed ratios, prompting a closer look at medical infrastructure, early detection, and response time.
* With the use of slicers, analysts can quickly switch context  to focus on any individual country and analyze its trend and outcomes.
* The global trend shows multiple waves of outbreaks, with sharp rises during 2020 and early 2021.

*Dataset Source*

Kaggle – COVID-19 Clean Complete Dataset
URL: [https://www.kaggle.com/imdevskp/corona-virus-report](https://www.kaggle.com/imdevskp/corona-virus-report)

*Conclusion*

This project demonstrates proficiency in using Power BI to transform, model, and visualize data in a way that supports quick decision-making and deep analysis.The dashboard is clean, informative, and interactive, making it valuable for stakeholders, analysts, or anyone seeking to understand the impact of COVID-19 on a global scale.

*OUTPUT*


![Image](https://github.com/user-attachments/assets/c54b7b30-6090-4f8c-87ff-9a6a93577692)
