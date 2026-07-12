# Mohammed Fahim  
## Data Technician Trainee

Hi, I am a Data Technician Trainee building practical projects using Excel, Tableau, Power BI, SQL, Azure, Pandas, and Python.

This GitHub Pages site showcases all my course modules, including real code, visualisations, cloud work, and analysis tasks completed throughout the programme.

<br>

## Table of Contents – Core Skills
- **[Excel](#project-1-excel)** — tables, filters, formulas, structured data modelling  
- **[Tableau](#project-2-tableau)** — charts, dashboards, collaborative visual storytelling  
- **[Power BI](#project-3-power-bi)** — data cleaning, relationships, interactive reporting  
- **[SQL](#project-4-sql)** — joins, grouping, business logic systems, insights  
- **[Azure](#project-5-azure)** — Synapse Analytics, Machine Learning notebooks, Data Factory pipelines  
- **[Pandas](#project-6-pandas)** — data cleaning, filtering, grouping, Colab notebooks  
- **[Python](#project-7-python)** — scripting, loops, and basic data visualisation  
- **[Final Summary](#final-summary)** — closing statement  
- **[Socials](#socials)** — email, GitHub, LinkedIn  

<br>
*Click the links to jump to each section.*
<br>

---

## Portfolio Projects
In this section, I showcase my data analytics projects — outlining the problem, the data used, the approach taken, and the insights or business impact delivered.

<br>

---

<a name="project-1-excel"></a>
## Project 1 – Excel – Student Performance Analysis

### Problem
Using the imported **student.csv** dataset, I analysed student performance by:
- Creating a **Score Category** column using `IFS()`
- Counting students in each category using `COUNTIF()`
- Calculating **average performance by gender** using `AVERAGEIF()`
- Calculating **average class scores** using `AVERAGEIF()`
- Identifying the **best student in each class** using `MAX()` and `INDEX/MATCH`
- Producing an overall summary table of results

### Approach Taken
Developed new fields, applied conditional logic, used aggregate Excel functions, and built summary metrics to evaluate student performance across categories, genders, and classes.

### Insights
- Class Six performs strongly, while Class Four falls well below the average.  
- Female students outperform males by around **6%** on average.  
- Top‑scoring students don’t always reflect overall class performance.

### Impact
- Strengthen lower‑performing classes  
- Provide targeted support for male students  
- Rebalance class structures  

### Student Performance Data – Output
<img src="https://raw.githubusercontent.com/MFahim-Data/Full-Stack-Data-Analytics/main/Images/Excel/Excel%20Student%20Image%201.png" width="100%">
*Student dataset analysis including score categories, averages, and top‑performer identification.*

<br>

### Additional Summary View – Output
<img src="https://raw.githubusercontent.com/MFahim-Data/Full-Stack-Data-Analytics/main/Images/Excel/Excel%20Student%20Image%202.png" width="100%">
*Additional view of the student performance calculations and summary tables.*

<br>

### Links
- [Download Student Dataset (Excel)](https://github.com/MFahim-Data/Full-Stack-Data-Analytics/blob/main/Files/Excel/Student%20Dataset.xlsx)

<br>

---

<a name="project-2-tableau"></a>
## Project 2 – Tableau – Introductory Data Visualisation & Analysis

### Problem
Using Tableau, I created visualisations exploring global health trends:
- Life expectancy by continent  
- Life expectancy trends over time  
- Population distribution by gender  
- BMI vs life expectancy scatter plot  
- A final dashboard combining all visuals

### Approach Taken
Connected the dataset, checked data types, built multiple worksheets, and combined them into a dashboard titled **Global Health Insights**.

### Insights
- Europe and Oceania have the highest life expectancy; Africa the lowest.  
- Life expectancy has steadily increased over time.  
- Countries with healthier BMI levels tend to have higher life expectancy.  
- Population distribution varies widely across countries.  
- Gender distribution is generally balanced.

### Impact
- Plan future healthcare demand  
- Target public health campaigns  
- Benchmark UK performance  
- Allocate resources based on population density  
- Forecast pressures on healthcare services  

### Tableau Visual – Output
<img src="https://raw.githubusercontent.com/MFahim-Data/Full-Stack-Data-Analytics/main/Images/Global%20Health%20Insights%20Dashboard.png" width="100%">
*Introductory Tableau visual created using the GapminderHealth dataset.*

<br>

### Links
- [Tableau Public Dashboard](https://public.tableau.com/shared/CD8MMQ3PK?:display_count=n&:origin=viz_share_link)

<br>

---

<a name="project-3-power-bi"></a>
## Project 3 – Power BI – Sales Performance Dashboard

### Problem
Build an interactive Power BI dashboard to analyse retail sales performance, identify trends, and provide dynamic insights.

### Approach Taken
- Cleaned data in Power Query  
- Created relationships between fact/dimension tables  
- Built interactive visuals with slicers  
- Used Q&A natural‑language insights  
- Implemented a decomposition tree  
- Designed a business‑ready dashboard layout  

### Insights
- Consumer segment is strongest  
- Customer segments are evenly distributed  
- Regional/category trends highlight strengths and weaknesses  
- Decomposition tree reveals root causes  
- Q&A speeds up insight discovery  

### Impact
- Prioritise high‑performing segments  
- Align sales strategies  
- Guide resource allocation  
- Identify root causes  
- Speed up decision‑making  

### Sales Performance Dashboard – Output
<img src="https://raw.githubusercontent.com/MFahim-Data/Full-Stack-Data-Analytics/main/Images/Power%20Bi/Power%20Bi%20-%20Sales%20-%20Dashboard.PNG" width="100%">
*Interactive dashboard showing KPIs, category trends, regional breakdowns, Q&A insights, and drill‑downs.*

<br>

### Links
- [Power BI Dashboard](https://app.powerbi.com/links/PMd5n60xXh?ctid=3ea7c128-c601-4479-a003-e14d00c0b5cb&pbi_source=linkShare)

<br>

---

<a name="project-4-sql"></a>
## Project 4 – SQL – Retail Database Design & Implementation

### Dataset / Scenario
A corner shop needs a new database system to manage inventory, suppliers, customers, sales, and loyalty points.

### Problem
Design and build a relational database that:
- Stores supplier, inventory, sales, customer, and loyalty data  
- Defines primary/foreign keys  
- Supports daily operations  
- Includes SQL examples for table creation and data insertion  

### Approach Taken
Analysed requirements, designed schema, implemented tables using SQL, and ensured logical relationships.

### Insights
- Structure streamlines daily operations  
- Relational links provide full visibility  
- Schema is simple and easy to understand  
- Maintenance ensures long‑term reliability  

### Impact
- Efficient stock and sales management  
- Clear insight into trends  
- Reduced errors  
- Improved security and backups  
- Reliable system for daily operations  

### Customer ERD – Output
<img src="https://raw.githubusercontent.com/MFahim-Data/Full-Stack-Data-Analytics/main/Images/SQL/Customer_ERD.png" width="30%">

<br>

### Customer ERD (Version 2) – Output
<img src="https://raw.githubusercontent.com/MFahim-Data/Full-Stack-Data-Analytics/main/Images/SQL/Customer_ERD%202.png" width="30%">

<br>

### Links
- [SQL Essay Report (PDF)](https://github.com/MFahim-Data/Full-Stack-Data-Analytics/blob/main/Files/SQL/SQL%20-%20Essay.pdf)  
- [SQL Brief Report (PDF)](https://github.com/MFahim-Data/Full-Stack-Data-Analytics/blob/main/Files/SQL/SQL%20-%20Brief.pdf)

<br>

---

<a name="project-5-azure"></a>
## Project 5 – Azure – Cloud Migration & Data Strategy (Paws & Whiskers)

### Problem
Migrate a small business from spreadsheets to a secure, scalable Azure cloud solution.

### Approach Taken
Designed Azure SQL Database, Synapse Analytics, Data Factory pipelines, and security controls (RBAC, Key Vault).

### Insights
- Azure replaces unreliable spreadsheets  
- Full compliance with GDPR, DPA, PCI DSS  
- Synapse + ML provide forecasting  
- Data Factory automates imports  
- Strong backup and failover protection  

### Impact
- Secure cloud‑based storage  
- Automated data updates  
- Stronger reporting and forecasting  
- Improved operational efficiency  
- Scalable long‑term growth  

### Azure Cloud Proposal – Output
<img src="https://raw.githubusercontent.com/MFahim-Data/Full-Stack-Data-Analytics/main/Images/Azure/Azure%20-%20P%26W'S%20Schema.png" width="60%">
*Azure-based relational schema diagram.*

<br>

### Links
- [Azure Brief Report (PDF)](https://github.com/MFahim-Data/Full-Stack-Data-Analytics/blob/main/Files/Azure/Azure%20-%20Brief.pdf)  
- [Azure Full Report (PDF)](https://github.com/MFahim-Data/Full-Stack-Data-Analytics/blob/main/Files/Azure/Azure%20-%20Report.pdf)

<br>

---

<a name="project-6-pandas"></a>
## Project 6 – Pandas – Student Data Analysis

### Dataset
student.csv

### Problem
Load, explore, slice, manipulate, aggregate, and export the dataset using Pandas.

### Approach Taken
Used read_csv, head, info, describe, loc, iloc, groupby, pivot_table, and to_csv to analyse and export data.

### Insights
- Clear performance gaps between classes  
- Female students outperform males  
- Pivot tables reveal mismatches between averages and top scorers  
- Filtering isolates underperforming groups  
- Exporting DataFrames supports database storage  

### Impact
- Targeted academic support  
- Balanced class structuring  
- Reliable database storage  
- Consistent querying  
- Foundation for dashboards and ML models  

### Pandas Pivot Table – Output
<img src="https://raw.githubusercontent.com/MFahim-Data/Full-Stack-Data-Analytics/main/Images/PANDAS/PANDAS%20-%20Pivot%20Table.png" width="60%">
*Pivot table summarising average student scores.*

<br>

### Links
- [Pandas Pivot Table Notebook](https://github.com/MFahim-Data/Full-Stack-Data-Analytics/blob/main/PANDAS_Pivot_Table.ipynb)

<br>

---

<a name="project-7-python"></a>
## Project 7 – Python – GDP & Student Visualisation Tasks

### Dataset
GDP (nominal) per Capita.csv & student.csv

### Problem
Load datasets, create visualisations, and interpret insights using Pandas, Matplotlib, and Seaborn.

### Approach Taken
Used read_csv, head, tail, plt.figure, plt.hist, sns.boxplot, sns.countplot, sns.barplot.

### Insights
- Most marks fall between 50–95  
- Females score more high marks  
- Class Six strongest; Class Nine weakest  
- Class sizes uneven  
- Average marks confirm gender gap  

### Impact
- Targeted interventions  
- Identify structural issues  
- Balanced class planning  
- Reliable database storage  
- Foundation for dashboards and ML models  

### Python Visualisation – Bar Chart
<img src="https://raw.githubusercontent.com/MFahim-Data/Full-Stack-Data-Analytics/main/Images/Python%20-/Python%20-%20Barchart%20-%201.png" width="100%">
*Countplot showing class size distribution.*

<br>

### Python Visualisation – Heatmap
<img src="https://raw.githubusercontent.com/MFahim-Data/Full-Stack-Data-Analytics/main/Images/Python%20-/Python%20-%20Heatmap%20-%201.png" width="100%">
*Correlation heatmap.*

<br>

### Python Visualisation – Box & Whisker Plot
<img src="https://raw.githubusercontent.com/MFahim-Data/Full-Stack-Data-Analytics/main/Images/Python%20-/Python%20-%20Whiskers%20-%201.png" width="100%">
*Score distribution and outliers.*

<br>

### Links
- [Student Data Analysis Notebook](https://github.com/MFahim-Data/Full-Stack-Data-Analytics/blob/main/Code%20-%20Student_Data_Analysis_Task_2_Cleaning_and_Visualising_data.ipynb)

<br>

---

<a name="final-summary"></a>
## Final Summary
This 6‑week data analytics portfolio reflects a broad and practical skill set across Excel, Tableau, Power BI, SQL, Azure, Pandas, and Python. The projects demonstrate structured analytical workflows, effective data visualisation, robust database design, and cloud‑based processing. I am continuing to advance my capabilities in BI development and data engineering, and I am seeking opportunities where I can apply these skills to deliver meaningful analytical value.

<br>

## Socials
- Email: mohammedfahim4@outlook.com  
- [GitHub](https://github.com/MFahim-Data)  
- [LinkedIn](https://www.linkedin.com/in/mohammed-fahim-data/)
