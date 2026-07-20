## Mohammed Fahim  
### Data Technician Trainee

Hi, I am a Data Technician Trainee building practical projects using Excel, Tableau, Power BI, SQL, Azure, Pandas, and Python.

This GitHub Pages site showcases all my course modules, including real code, visualisations, cloud work, and analysis tasks completed throughout the programme.

<br>

<a name="table-of-contents"></a>
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

<div style="border-top: 3px solid #ccc; margin: 40px 0;"></div>


## Portfolio Projects
In this section, I showcase my data analytics projects — outlining the problem, the data used, the approach taken, and the insights or business impact delivered.

<br>

---

<a name="project-1-excel"></a>
## Project 1 – Excel – Student Performance Analysis  
[↟ Back to Table of Contents](#table-of-contents)

### Problem
Using the imported **student.csv** dataset, I analysed student performance by:
- Creating a **Score Category** column using `IFS()`
- Counting students in each category using `COUNTIF()`
- Calculating **average performance by gender** using `AVERAGEIF()`
- Calculating **average class scores** using `AVERAGEIF()`
- Identifying the **best student in each class** using `MAX()` and `INDEX/MATCH`
- Producing an overall summary table of results

<br>

### Approach Taken
Developed new fields, applied conditional logic, used aggregate Excel functions, and built summary metrics to evaluate student performance across categories, genders, and classes.

<br>

### Insights
- Class Six performs strongly, while Class Four falls well below the average.  
- Female students outperform males by around **6%** on average.  
- Top‑scoring students don’t always reflect overall class performance.

<br>

### Impact
- Strengthen lower‑performing classes  
- Provide targeted support for male students  
- Rebalance class structures  

<br><br>

## Images

<br>

### Score Category Classification – Output
<img src="https://raw.githubusercontent.com/MFahim-Data/Full-Stack-Data-Analytics/main/Images/Excel/Excel%20Student%20Image%20%20-%20%201.png" width="80%">

<br>
*Student dataset analysis including score categories, averages, and top‑performer identification.*

<br>

**Formula Used:**  
`=IFS(
 D2>=80,"Outstanding Achiever",
 D2>=70,"First Class",
 D2>=60,"Second Class",
 D2>=40,"Pass",
 TRUE,"Fail"
)`

*This formula assigns each student a performance category based on their score.*


<br>

<br>



### Category Count Summary – Output
<img src="https://raw.githubusercontent.com/MFahim-Data/Full-Stack-Data-Analytics/main/Images/Excel/Excel%20Student%20Image%20%20-%20%202.png" width="60%">

<br>
*Summary table showing the number of students in each performance category.*

<br>

**Formula Used:**  
`=COUNTIF(F:F,"Outstanding Achiever")`  
`=COUNTIF(F:F,"First Class")`  
`=COUNTIF(F:F,"Second Class")`  
`=COUNTIF(F:F,"Pass")`  
`=COUNTIF(F:F,"Fail")`

*These formulas count how many students fall into each score category.*



<br>

<br>


### Gender Performance Comparison – Output
<img src="https://raw.githubusercontent.com/MFahim-Data/Full-Stack-Data-Analytics/main/Images/Excel/Excel%20Student%20Image%20%20-%20%203.png" width="70%">

<br>
Average performance comparison between male and female students.

<br>

*Formula Used:*  
=AVERAGEIF(E:E,"male",D:D)  
=AVERAGEIF(E:E,"female",D:D)

These formulas calculate the average score for male and female students separately.



<br>

<br>

### Links

- [View Full Dataset (Excel)](https://1drv.ms/x/c/2722934ae77427f3/IQA-_CRNiwAqS670eM3fbszRAXWdxx5I9o17spBvk7uiNjQ?e=3fLb2V)

*This link provides access to the full Excel dataset for further analysis done.*


<br>

<br>

---

<a name="project-2-tableau"></a>
## Project 2 – Tableau – Introductory Data Visualisation & Analysis  
[↟ Back to Table of Contents](#table-of-contents)

### Problem
Using Tableau, I created visualisations exploring global health trends:
- Life expectancy by continent  
- Life expectancy trends over time  
- Population distribution by gender  
- BMI vs life expectancy scatter plot  
- A final dashboard combining all visuals

<br>

### Approach Taken
Connected the dataset, checked data types, built multiple worksheets, and combined them into a dashboard titled **Global Health Insights**.

<br>

### Insights
- Europe and Oceania have the highest life expectancy; Africa the lowest.  
- Life expectancy has steadily increased over time.  
- Countries with healthier BMI levels tend to have higher life expectancy.  
- Population distribution varies widely across countries.  
- Gender distribution is generally balanced.

<br>

### Impact
- Plan future healthcare demand  
- Target public health campaigns  
- Benchmark UK performance  
- Allocate resources based on population density  
- Forecast pressures on healthcare services  

<br>

### Tableau Visual – Output
<img src="https://raw.githubusercontent.com/MFahim-Data/Full-Stack-Data-Analytics/main/Images/Global%20Health%20Insights%20Dashboard.png" width="120%">
*Tableau visual created using the GapminderHealth dataset.*

<br>

**Explanation:**  
This dashboard brings together multiple health indicators to show how life expectancy, BMI, gender distribution, and population vary across continents and over time. It helps identify global health gaps and long‑term trends that can guide public health planning.
<br>

### Links
- [Tableau Public Dashboard](https://public.tableau.com/shared/CD8MMQ3PK?:display_count=n&:origin=viz_share_link)

*This link provides access to the full TableAU Dashboard and Dataset for View.*

<br>

---

<a name="project-3-power-bi"></a>
## Project 3 – Power BI – Sales Performance Dashboard  
[↟ Back to Table of Contents](#table-of-contents)

### Problem
Build an interactive Power BI dashboard to analyse retail sales performance, identify trends, and provide dynamic insights.

<br>

### Approach Taken
- Cleaned data in Power Query  
- Created relationships between fact/dimension tables  
- Built interactive visuals with slicers  
- Used Q&A natural‑language insights  
- Implemented a decomposition tree  
- Designed a business‑ready dashboard layout  

<br>

### Insights
- Consumer segment is strongest  
- Customer segments are evenly distributed  
- Regional/category trends highlight strengths and weaknesses  
- Decomposition tree reveals root causes  
- Q&A speeds up insight discovery  

<br>

### Impact
- Prioritise high‑performing segments  
- Align sales strategies  
- Guide resource allocation  
- Identify root causes  
- Speed up decision‑making  

<br>

### Sales Performance Dashboard – Output
<img src="https://raw.githubusercontent.com/MFahim-Data/Full-Stack-Data-Analytics/main/Images/Power%20Bi/Power%20Bi%20-%20Sales%20-%20Dashboard.PNG" width="120%">
*Interactive dashboard showing KPIs, category trends, regional breakdowns, Q&A insights, and drill‑downs.*

<br>

**Explanation:**  
This dashboard provides a full breakdown of retail performance, allowing users to explore sales by region, category, and customer segment. Interactive slicers and drill‑downs help uncover root causes behind strong or weak performance, supporting data‑driven decision‑making.

<br>

### Links
- [Power BI Dashboard](https://app.powerbi.com/links/PMd5n60xXh?ctid=3ea7c128-c601-4479-a003-e14d00c0b5cb&pbi_source=linkShare)

*This link provides access to the full PowerBI Dashboard and Dataset for View.*

<br>

---

<a name="project-4-sql"></a>
## Project 4 – SQL – Retail Database Design & Implementation  
[↟ Back to Table of Contents](#table-of-contents)

### Dataset / Scenario
A corner shop needs a new database system to manage inventory, suppliers, customers, sales, and loyalty points.

<br>

### Problem
Design and build a relational database that:
- Stores supplier, inventory, sales, customer, and loyalty data  
- Defines primary/foreign keys  
- Supports daily operations  
- Includes SQL examples for table creation and data insertion  

<br>

### Approach Taken
Analysed requirements, designed schema, implemented tables using SQL, and ensured logical relationships.

<br>

### Insights
- Structure streamlines daily operations  
- Relational links provide full visibility  
- Schema is simple and easy to understand  
- Maintenance ensures long‑term reliability  

<br>

### Impact
- Efficient stock and sales management  
- Clear insight into trends  
- Reduced errors  
- Improved security and backups  
- Reliable system for daily operations  

<br>

### Customer ERD – Output
<img src="https://raw.githubusercontent.com/MFahim-Data/Full-Stack-Data-Analytics/main/Images/SQL/Customer_ERD.png" width="50%">


<img src="https://raw.githubusercontent.com/MFahim-Data/Full-Stack-Data-Analytics/main/Images/SQL/Customer_ERD%202.png" width="50%">

*Entity‑relationship diagrams showing customer, inventory, supplier, and sales relationships.*

<br>

**Explanation:**  
These ERDs map out how different tables in the retail database connect. They ensure the system supports accurate stock tracking, customer management, and sales recording. Clear relationships reduce errors and make the database easier to maintain and query.

<br>

### Links
- [SQL Essay Report (Word Online)](https://1drv.ms/w/c/2722934ae77427f3/IQAeRhJNbbVfSafS0-5Zcap5AULdBmFdP9x9hUCQ1Tx-_Bc?e=bTl076)

- [SQL Brief Report (Word Online)](https://1drv.ms/w/c/2722934ae77427f3/IQBnXIBq_8H2S7_pO0dhHzKuASakzefUuIymw9djoC_oc-M?e=XEAY77)


*This link provides access to the full Report and Brief in Word document Format*

<br>

---

<a name="project-5-azure"></a>
## Project 5 – Azure – Cloud Migration & Data Strategy (Paws & Whiskers)  
[↟ Back to Table of Contents](#table-of-contents)

### Problem
Migrate a small business from spreadsheets to a secure, scalable Azure cloud solution.

<br>

### Approach Taken
Designed Azure SQL Database, Synapse Analytics, Data Factory pipelines, and security controls (RBAC, Key Vault).

<br>

### Insights
- Azure replaces unreliable spreadsheets  
- Full compliance with GDPR, DPA, PCI DSS  
- Synapse + ML provide forecasting  
- Data Factory automates imports  
- Strong backup and failover protection  

<br>

### Impact
- Secure cloud‑based storage  
- Automated data updates  
- Stronger reporting and forecasting  
- Improved operational efficiency  
- Scalable long‑term growth  

<br>

### Azure Cloud Proposal – Output
<img src="https://raw.githubusercontent.com/MFahim-Data/Full-Stack-Data-Analytics/main/Images/Azure/Azure%20-%20P%26W'S%20Schema.png" width="80%">

<br>

*Azure-based relational schema diagram.*

<br>

**Explanation:**  
This schema shows how the business’s data flows through Azure services such as SQL Database, Synapse Analytics, and Data Factory. It highlights secure storage, automated pipelines, and scalable analytics — replacing spreadsheets with a reliable cloud architecture.
<br>

### Links
- [Azure Brief (Word Online)](https://1drv.ms/w/c/2722934ae77427f3/IQAYEa1QdaIeTZn3LAGkSwmGAVGETmNJAnaG2Yk6WwoKsFw?e=prkBzb)
- [Azure Full Report (Word Online)](https://1drv.ms/w/c/2722934ae77427f3/IQC2a7OqqfElQ4Qr9MwmZHKzAXSL9naO9gCDvcI-n2zbqUQ?e=We9bJV)

*This link provides access to the full Azure Report and Brief for View*

<br>

---

<a name="project-6-pandas"></a>
## Project 6 – Pandas – Student Data Analysis  
[↟ Back to Table of Contents](#table-of-contents)

### Dataset
student.csv

<br>

### Problem
Load, explore, slice, manipulate, aggregate, and export the dataset using Pandas.

<br>

### Approach Taken
Used read_csv, head, info, describe, loc, iloc, groupby, pivot_table, and to_csv to analyse and export data.

<br>

### Insights
- Clear performance gaps between classes  
- Female students outperform males  
- Pivot tables reveal mismatches between averages and top scorers  
- Filtering isolates underperforming groups  
- Exporting DataFrames supports database storage  

<br>

### Impact
- Targeted academic support  
- Balanced class structuring  
- Reliable database storage  
- Consistent querying  
- Foundation for dashboards and ML models  

<br>

### Pandas Pivot Table – Output
<img src="https://raw.githubusercontent.com/MFahim-Data/Full-Stack-Data-Analytics/main/Images/PANDAS/PANDAS%20-%20Pivot%20Table.png" width="80%">

<br>

*Pivot table summarising average student scores.*

<br>

**Explanation:**  
The pivot table groups student performance by class and gender, making it easy to compare averages across categories. It reveals patterns such as stronger classes, weaker classes, and gender‑based performance differences.

<br>

### Links
- [Pandas Pivot Table Notebook](https://github.com/MFahim-Data/Full-Stack-Data-Analytics/blob/main/PANDAS_Pivot_Table.ipynb)

*This link provides access to the full Google Collab Coding Session for View*

<br>

---

<a name="project-7-python"></a>
## Project 7 – Python – GDP & Student Visualisation Tasks  
[↟ Back to Table of Contents](#table-of-contents)

### Dataset
GDP (nominal) per Capita.csv & student.csv

<br>

### Problem
Load datasets, create visualisations, and interpret insights using Pandas, Matplotlib, and Seaborn.

<br>

### Approach Taken
Used read_csv, head, tail, plt.figure, plt.hist, sns.boxplot, sns.countplot, sns.barplot.

<br>

### Insights
- Most marks fall between 50–95  
- Females score more high marks  
- Class Six strongest; Class Nine weakest  
- Class sizes uneven  
- Average marks confirm gender gap  

<br>

### Impact
- Targeted interventions  
- Identify structural issues  
- Balanced class planning  
- Reliable database storage  
- Foundation for dashboards and ML models  

<br>

### Python Visualisation – Bar Chart
<img src="https://raw.githubusercontent.com/MFahim-Data/Full-Stack-Data-Analytics/main/Images/Python%20-/Python%20-%20Barchart%20-%201.png" width="80%">

<br>

*Countplot showing class size distribution.*

<br>

**Explanation:**  
This bar chart shows how many students are in each class. Uneven class sizes can affect teaching quality, resource allocation, and performance comparisons.

<br>

### Python Visualisation – Heatmap
<img src="https://raw.githubusercontent.com/MFahim-Data/Full-Stack-Data-Analytics/main/Images/Python%20-/Python%20-%20Heatmap%20-%201.png" width="80%">

<br>
*Correlation heatmap.*

<br>

**Explanation:**  
The heatmap highlights relationships between variables such as marks, class, and gender. Strong correlations help identify which factors influence student performance the most.
<br>

### Python Visualisation – Box & Whisker Plot
<img src="https://raw.githubusercontent.com/MFahim-Data/Full-Stack-Data-Analytics/main/Images/Python%20-/Python%20-%20Whiskers%20-%201.png" width="80%">

<br>

*Score distribution and outliers.*

<br>

**Explanation:**  
This boxplot shows score spread, median performance, and outliers. It helps identify students who are significantly underperforming or excelling compared to the rest of the group.

<br>

### Links
- [Student Data Analysis Notebook](https://github.com/MFahim-Data/Full-Stack-Data-Analytics/blob/main/Code%20-%20Student_Data_Analysis_Task_2_Cleaning_and_Visualising_data.ipynb)

*This link provides access to the full Google Collab Coding Session for View*

<br>

---

<a name="final-summary"></a>
## Final Summary  
[↟ Back to Table of Contents](#table-of-contents)

This 6‑week data analytics portfolio reflects a broad and practical skill set across Excel, Tableau, Power BI, SQL, Azure, Pandas, and Python. The projects demonstrate structured analytical workflows, effective data visualisation, robust database design, and cloud‑based processing. I am continuing to advance my capabilities in BI development and data engineering, and I am seeking opportunities where I can apply these skills to deliver meaningful analytical value.

<br>

---

## Socials  
[↟ Back to Table of Contents](#table-of-contents)


- Email: mohammedfahim4@outlook.com
  
- GitHub: https://github.com/MFahim-Data  

- LinkedIn: https://www.linkedin.com/in/mohammed-fahim-data/
