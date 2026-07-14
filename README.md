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

---

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
<img src="https://raw.githubusercontent.com/MFahim-Data/Full-Stack-Data-Analytics/main/Images/Excel/Excel%20Student%20Image%20%20-%20%201.png" width="60%">

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

<br><br>



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

<br><br>


### Gender Performance Comparison – Output
<img src="https://raw.githubusercontent.com/MFahim-Data/Full-Stack-Data-Analytics/main/Images/Excel/Excel%20Student%20Image%20%20-%20%203.png" width="40%">

<br>
*Average performance comparison between male and female students.*

<br>

**Formula Used:**  
`=AVERAGEIF(E:E,"male",D:D)`  
`=AVERAGEIF(E:E,"female",D:D)`

*These formulas calculate the average score for male and female students separately.*

<br><br>

### Class Average Score Analysis – Output
<img src="https://raw.githubusercontent.com/MFahim-Data/Full-Stack-Data-Analytics/main/Images/Excel/Excel%20Student%20Image%20%20-%20%204.png" width="30%">

<br>
*Average class performance across multiple grade levels.*

<br>

**Formula Used:**  
`=AVERAGEIF(C:C,"Six",D:D)`  
`=AVERAGEIF(C:C,"Five",D:D)`  
`=AVERAGEIF(C:C,"Eight",D:D)`  
`=AVERAGEIF(C:C,"Fifth",D:D)`  
`=AVERAGEIF(C:C,"Seven",D:D)`  
`=AVERAGEIF(C:C,"Three",D:D)`  
`=AVERAGEIF(C:C,"Four",D:D)`  
`=AVERAGEIF(C:C,"Nine",D:D)`

*These formulas calculate the average score for each class, allowing comparison across grade levels.*

<br><br>

### Top Performer Identification – Output
<img src="https://raw.githubusercontent.com/MFahim-Data/Full-Stack-Data-Analytics/main/Images/Excel/Excel%20Student%20Image%20%20-%20%205.png" width="40%">

<br>
*Top performer identification for each class using dynamic filtering.*

<br>

**Formula Used:**  
`=MAX(FILTER($D$2:$D$36, $C$2:$C$36=K2))`  
`=MAX(FILTER($D$2:$D$36, $C$2:$C$36=K3))`  
`=MAX(FILTER($D$2:$D$36, $C$2:$C$36=K4))`  
`=MAX(FILTER($D$2:$D$36, $C$2:$C$36=K5))`  
`=MAX(FILTER($D$2:$D$36, $C$2:$C$36=K6))`  
`=MAX(FILTER($D$2:$D$36, $C$2:$C$36=K7))`  
`=MAX(FILTER($D$2:$D$36, $C$2:$C$36=K8))`  
`=MAX(FILTER($D$2:$D$36, $C$2:$C$36=K9))`

*These formulas extract the highest score for each class by filtering student records dynamically.*

<br><br>

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
<img src="https://raw.githubusercontent.com/MFahim-Data/Full-Stack-Data-Analytics/main/Images/Global%20Health%20Insights%20Dashboard.png" width="100%">
*Introductory Tableau visual created using the GapminderHealth dataset.*

<br>

### Links
- [Tableau Public Dashboard](https://public.tableau.com/shared/CD8MMQ3PK?:display_count=n&:origin=viz_share_link)

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
<img src="https://raw.githubusercontent.com/MFahim-Data/Full-Stack-Data-Analytics/main/Images/Power%20Bi/Power%20Bi%20-%20Sales%20-%20Dashboard.PNG" width="100%">
*Interactive dashboard showing KPIs, category trends, regional breakdowns, Q&A insights, and drill‑downs.*

<br>

### Links
- [Power BI Dashboard](https://app.powerbi.com/links/PMd5n60xXh?ctid=3ea7c128-c601-4479-a003-e14d00c0b5cb&pbi_source=linkShare)

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
<img src="https://raw.githubusercontent.com/MFahim-Data/Full-Stack-Data-Analytics/main/Images/SQL/Customer_ERD.png" width="30%">

<br>

### Customer ERD (Version 2) – Output
<img src="https://raw.githubusercontent.com/MFahim-Data/Full-Stack-Data-Analytics/main/Images/SQL/Customer_ERD%202.png" width="30%">

<br>

### Links
- [SQL Essay Report (Word Online)](https://1drv.ms/w/c/2722934ae77427f3/IQAeRhJNbbVfSafS0-5Zcap5AULdBmFdP9x9hUCQ1Tx-_Bc?e=bTl076)

- [SQL Brief Report (Word Online)](https://1drv.ms/w/c/2722934ae77427f3/IQBnXIBq_8H2S7_pO0dhHzKuASakzefUuIymw9djoC_oc-M?e=XEAY77)


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
<img src="https://raw.githubusercontent.com/MFahim-Data/Full-Stack-Data-Analytics/main/Images/Azure/Azure%20-%20P%26W'S%20Schema.png" width="60%">
*Azure-based relational schema diagram.*

<br>

### Links
- [Azure Brief (Word Online)](https://1drv.ms/w/c/2722934ae77427f3/IQAYEa1QdaIeTZn3LAGkSwmGAVGETmNJAnaG2Yk6WwoKsFw?e=prkBzb)
- [Azure Full Report (Word Online)](https://1drv.ms/w/c/2722934ae77427f3/IQC2a7OqqfElQ4Qr9MwmZHKzAXSL9naO9gCDvcI-n2zbqUQ?e=We9bJV)


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
<img src="https://raw.githubusercontent.com/MFahim-Data/Full-Stack-Data-Analytics/main/Images/PANDAS/PANDAS%20-%20Pivot%20Table.png" width="60%">
*Pivot table summarising average student scores.*

<br>

### Links
- [Pandas Pivot Table Notebook](https://github.com/MFahim-Data/Full-Stack-Data-Analytics/blob/main/PANDAS_Pivot_Table.ipynb)

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
[↟ Back to Table of Contents](#table-of-contents)

This 6‑week data analytics portfolio reflects a broad and practical skill set across Excel, Tableau, Power BI, SQL, Azure, Pandas, and Python. The projects demonstrate structured analytical workflows, effective data visualisation, robust database design, and cloud‑based processing. I am continuing to advance my capabilities in BI development and data engineering, and I am seeking opportunities where I can apply these skills to deliver meaningful analytical value.

<br>

---

## Socials  
[↟ Back to Table of Contents](#table-of-contents)

- Email: mohammedfahim4@outlook.com  
- GitHub: https://github.com/MFahim-Data  
- LinkedIn: https://www.linkedin.com/in/mohammed-fahim-data/
