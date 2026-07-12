<img width="739" height="597" alt="image" src="https://github.com/user-attachments/assets/a3889a66-3b10-40fe-ae20-e7d15ed8375f" /># Mohammed Fahim 
## Data Technician Trainee

Hi, I am a Data Technician Trainee building practical projects using Excel, Tableau, Power BI, SQL, Azure, Pandas, and Python.

This GitHub Pages site showcases all my course modules, including real code, visualisations, cloud work, and analysis tasks completed throughout the programme.

<br>


### Table of Contents – Core Skills  
- **[Excel](#project-1-excel)** — tables, filters, formulas, structured data modelling  
- **[Tableau](#project-2-tableau)** — charts, dashboards, collaborative visual storytelling  
- **[Power BI](#project-3-power-bi)** — data cleaning, relationships, interactive reporting  
- **[SQL](#project-4-sql)** — joins, grouping, business logic systems, insights  
- **[Azure](#project-5-azure)** — Synapse Analytics, Machine Learning notebooks, Data Factory pipelines  
- **[Pandas](#project-6-pandas)** — data cleaning, filtering, grouping, Colab notebooks  
- **[Python](#project-7-python)** — scripting, loops, and basic data visualisation
- **[Final Summary](#final-summary)** — closing statement  
- **[Socials](#socials)** — email, GitHub, LinkedIN


<br>

*Click the Links to be Transferred to the Section*

<br>

---

### Portfolio Projects  
In this section, I showcase my data analytics projects — outlining the problem, the data used, the approach taken, and the insights or business impact delivered.

<br>

---
<a name="project-1-excel"></a>

### Project 1 – Excel – Student Performance Analysis

**Problem:**  
Using the imported **student.csv** dataset, I analysed student performance by:  
- Creating a **Score Category** column using `IFS()`  
- Counting students in each category using `COUNTIF()`  
- Calculating **average performance by gender** using `AVERAGEIF()`  
- Calculating **average class scores** using `AVERAGEIF()`  
- Identifying the **best student in each class** using `MAX()` and `INDEX/MATCH`  
- Producing an overall summary table of results

<br>

**Approach Taken:**  
Developed new fields, applied conditional logic, used aggregate Excel functions, and built summary metrics to evaluate student performance across categories, genders, and classes.

<br>

**Insights:**  
- Class Six performs strongly, while Class Four falls well below the average, showing clear performance gaps between classes.  
- Female students outperform males by around **6%** on average.  
- Top‑scoring students don’t always reflect overall class performance — Classes Eight and Five rank 3rd and 4th in average score, yet their highest scorers achieved lower marks than the top students in Classes Five and Six.

<br>

**Impact:**  
- Strengthen lower‑performing classes  
- Provide targeted support for male students  
- Rebalance class structures to improve overall performance  

See the image below for a visual breakdown of these insights.

<br>


#### Student Performance Data – Output  
<img src="https://raw.githubusercontent.com/MFahim-Data/Full-Stack-Data-Analytics/main/Images/Excel/Excel%20Student%20Image%201.png" width="100%">
<br>
*Student dataset analysis including score categories, averages, and top‑performer identification.*

<br>

<br>



#### Additional Summary View – Output  
<img src="https://raw.githubusercontent.com/MFahim-Data/Full-Stack-Data-Analytics/main/Images/Excel/Excel%20Student%20Image%202.png" width="100%">
<br>
*Additional view of the student performance calculations and summary tables.*

<br>



### Links  
- [Download Student Dataset (Excel)](https://github.com/MFahim-Data/Full-Stack-Data-Analytics/blob/main/Files/Excel/Student%20Dataset.xlsx)


<br>
<br>

---
<a name="project-2-tableau"></a>

### Project 2 – Tableau – Introductory Data Visualisation & Analysis

**Problem:**  
Using Tableau, I created a series of visualisations to explore global health trends, including:  
- Life expectancy by continent  
- Life expectancy trends over time  
- Population distribution by gender  
- BMI vs life expectancy scatter plot  
- A final dashboard combining all visuals

**Approach Taken:**  
Connected the dataset, checked data types, built multiple worksheets using basic Tableau features, and combined them into a dashboard titled **Global Health Insights**.


**Insights:**  
- Life expectancy differs strongly across continents — Europe and Oceania score highest, while Africa scores lowest, reflecting differences in healthcare access and living conditions.  
- Life expectancy has steadily increased over time, suggesting improvements in medicine, vaccination, sanitation, and public health.  
- Countries with healthier BMI levels tend to have higher life expectancy, highlighting the importance of lifestyle and obesity prevention.  
- Population distribution varies widely — countries like India and Indonesia have extremely large populations, shaping healthcare demand and long‑term planning.  
- Gender distribution is generally balanced across most countries, supporting planning for gender‑specific healthcare services.


**Impact:**  
- Plan future healthcare demand for an ageing population  
- Target public health campaigns to improve lifestyle and BMI outcomes  
- Benchmark UK performance against higher‑performing regions  
- Allocate resources based on population density and growth  
- Forecast pressures on GP services, emergency care, and chronic disease management  

See the image below for a visual breakdown of these insights.


---

#### Tableau Visual – Output  
<img src="https://raw.githubusercontent.com/MFahim-Data/Full-Stack-Data-Analytics/main/Images/Global%20Health%20Insights%20Dashboard.png" width="100%">
<br>
*Introductory Tableau visual created using the GapminderHealth dataset.*

<br>

### Links
- [Tableau Public Dashboard](https://public.tableau.com/shared/CD8MMQ3PK?:display_count=n&:origin=viz_share_link)

*Click the link to view my TableAU public dashboard to view and edit*

---

<br>
---
<a name="project-3-power-bi"></a>

### Project 3 – Power BI – Sales Performance Dashboard



*PROBLEM:*  
To build an interactive Power BI dashboard to analyse retail sales performance, identify trends, and provide dynamic insights across categories, regions, and time periods. The dashboard needed to support real‑time filtering, drill‑downs, and natural language Q&A exploration.

*APPROACH TAKEN:*  
Performed end‑to‑end BI development including:  
- Removing confidential data during Power Query cleaning  
- Creating relationships between fact and dimension tables  
- Building interactive visuals linked through slicers and cross‑filtering  
- Using Q&A analysis to generate insights through natural language queries  
- Implementing a decomposition tree for deep drill‑down analysis  
- Designing a clean, business‑ready dashboard layout  


**Insights:**  
- Consumer sales are the strongest overall, showing a clear opportunity for targeted marketing and product focus.  
- Customer segments are evenly distributed, meaning businesses can specialise their strategy depending on which segment aligns best with their goals.  
- Regional and category trends highlight where sales performance is strongest or weakest across the business.  
- The decomposition tree reveals how performance breaks down from region → segment → country, helping pinpoint the exact source of trends.  
- The Q&A feature enables fast, natural‑language exploration, allowing users to uncover insights without manually adjusting filters.

**Impact:**  
- Prioritise high‑performing segments such as Consumer to maximise revenue.  
- Align sales strategies with the customer segment that best fits business objectives.  
- Use regional and category trends to guide strategic planning and resource allocation.  
- Apply decomposition tree drill‑downs to identify root causes of strong or weak performance.  
- Speed up insight discovery and decision‑making through Q&A‑driven analysis.

See the image below for a visual breakdown of these insights.

---

#### Sales Performance Dashboard – Output  
<img src="https://raw.githubusercontent.com/MFahim-Data/Full-Stack-Data-Analytics/main/Images/Power%20Bi/Power%20Bi%20-%20Sales%20-%20Dashboard.PNG" width="100%">
<br>
*Interactive dashboard showing KPIs, category trends, regional breakdowns, Q&A insights, and decomposition tree drill‑downs.*

---

### Links
- [Power BI Dashboard](https://app.powerbi.com/links/PMd5n60xXh?ctid=3ea7c128-c601-4479-a003-e14d00c0b5cb&pbi_source=linkShare)

*Click the link to view my Power BI dashboard and explore the interactive visuals.*


---

<a name="project-4-sql"></a>

### Project 4 – SQL – Retail Database Design & Implementation


*Dataset / Scenario:*  
A small corner shop needs a new database system to manage inventory, suppliers, customers, sales, and loyalty points. The goal is to streamline operations and support staff and managers with accurate, structured data.

*Problem:*  
I was required to design and build a relational database that:  
- stores supplier, inventory, sales, customer, and loyalty programme data  
- defines clear primary and foreign key relationships  
- supports daily operations such as stock checks, sales recording, and loyalty tracking  
- includes SQL examples for creating tables, inserting data, and maintaining accuracy

*Approach Taken:*  
I analysed the business requirements, identified the essential tables, designed a relational schema, and implemented it using SQL CREATE TABLE, INSERT, and FOREIGN KEY statements. I ensured each table connected logically to support real‑world shop operations.

**Insights:**  
- The database structure streamlines daily operations by clearly organising suppliers, inventory, customers, sales, and loyalty data.  
- Relational links allow products to be traced from supplier → inventory → sale → customer → loyalty points, giving staff and managers full visibility across the system.  
- The schema is simple and easy for non‑technical users to understand, helping staff confidently check stock, record sales, and update loyalty points.  
- Maintenance practices such as stock validation, updating customer details, monitoring loyalty points, and weekly backups ensure long‑term accuracy and reliability.

**Impact:**  
- Staff can efficiently manage stock levels, sales transactions, and loyalty updates.  
- Managers gain clearer insight into sales trends, supplier performance, and restocking needs.  
- Foreign key relationships reduce errors and keep data consistent across all tables.  
- Regular maintenance and controlled access improve security and prevent data loss.  
- The shop benefits from a reliable, structured system that supports smooth daily operations.

See the image below for a visual breakdown of these insights.


---

#### Customer ERD – Output  
<img src="https://raw.githubusercontent.com/MFahim-Data/Full-Stack-Data-Analytics/main/Images/SQL/Customer_ERD.png" width="30%">
<br>

#### Customer ERD (Version 2) – Output  
<img src="https://raw.githubusercontent.com/MFahim-Data/Full-Stack-Data-Analytics/main/Images/SQL/Customer_ERD%202.png" width="30%">
<br>

---

### Links
- [SQL Essay Report (PDF)](https://github.com/MFahim-Data/Full-Stack-Data-Analytics/blob/main/Files/SQL/SQL%20-%20Essay.pdf)  
  *This is the full SQL report containing my complete database design, table creation, relationships, and detailed explanations of how I built and implemented the retail database.*

- [SQL Brief Report (PDF)](https://github.com/MFahim-Data/Full-Stack-Data-Analytics/blob/main/Files/SQL/SQL%20-%20Brief.pdf)  
  *This brief report outlines the core requirements of the project and summarises the key deliverables for the retail database task.*


---
<a name="project-5-azure"></a>

### Project 5 – Azure – Cloud Migration & Data Strategy for Paws & Whiskers


*Dataset / Scenario:*  
A small corner shop needs a new database system to manage inventory, suppliers, customers, sales, and loyalty points. The goal is to streamline operations and support staff and managers with accurate, structured data.

*Problem:*  
I was required to design and build a relational database that:  
- stores supplier, inventory, sales, customer, and loyalty programme data  
- defines clear primary and foreign key relationships  
- supports daily operations such as stock checks, sales recording, and loyalty tracking  
- includes SQL examples for creating tables, inserting data, and maintaining accuracy

*Approach Taken:*  
I analysed the business requirements, identified the essential tables, designed a relational schema, and implemented it using SQL CREATE TABLE, INSERT, and FOREIGN KEY statements. I ensured each table connected logically to support real‑world shop operations.



**Insights:**  
- Azure SQL Database replaces unreliable spreadsheets with secure, centralised storage that keeps customer, sales, and inventory data consistent and compliant.  
- GDPR, DPA, PCI DSS, and cybersecurity requirements are fully supported through Azure’s encryption, RBAC access controls, and Key Vault for protecting sensitive customer and payment data.  
- Azure Synapse Analytics and Machine Learning provide deeper visibility into sales trends, seasonal demand, customer behaviour, and future stock needs.  
- Azure Data Factory automates data imports from POS systems, spreadsheets, and supplier files, ensuring accurate, up‑to‑date data without manual effort.  
- Azure’s support for CSV, JSON, and Parquet — combined with Backup, Site Recovery, and Power BI integration — enables reliable analytics, strong continuity, and scalable growth as the business expands.

**Impact:**  
- Replaces unreliable spreadsheets with secure, compliant, cloud‑based storage.  
- Ensures customer and payment data meets GDPR, DPA, PCI DSS, and cybersecurity requirements.  
- Automates data imports and updates, reducing manual errors and saving staff time.  
- Provides managers with stronger reporting, forecasting, and customer insight through Synapse and Machine Learning.  
- Improves operational efficiency with accurate stock tracking, sales visibility, and supplier management.  
- Enhances security through encryption, RBAC, and Key Vault, preventing unauthorised access or data breaches.  
- Strengthens business continuity with automated backups and regional failover protection.  
- Supports long‑term growth with scalable storage, compute, and analytics tools.  

See the image below for a visual breakdown of these insights.
---

#### Azure Cloud Proposal – Output  
<img src="https://raw.githubusercontent.com/MFahim-Data/Full-Stack-Data-Analytics/main/Images/Azure/Azure%20-%20P%26W'S%20Schema.png" width="60%">
<br>
*Azure-based relational schema diagram for the Paws & Whiskers project.*

---

### Links  
- [Azure Brief Report (PDF)](https://github.com/MFahim-Data/Full-Stack-Data-Analytics/blob/main/Files/Azure/Azure%20-%20Brief.pdf)

 *This is the full SQL report containing my complete database design, table creation, relationships, and detailed explanations of how I built and implemented the retail database.
 
- [Azure Full Report (PDF)](https://github.com/MFahim-Data/Full-Stack-Data-Analytics/blob/main/Files/Azure/Azure%20-%20Report.pdf)

  *This brief report outlines the core requirements of the project and summarises the key deliverables for the retail database task.*

**

---

<a name="project-6-pandas"></a>

### Project 6 – Pandas – Student Data Analysis

--- 
*Dataset:* student.csv

*Problem:*  
Using Pandas, I was required to load, explore, slice, manipulate, aggregate, and export the *student.csv* dataset. This included reading data, selecting columns, filtering rows, creating new columns, grouping values, building pivot tables, sorting results, and exporting updated DataFrames.

*Approach Taken:*  
Imported Pandas, loaded the CSV into a DataFrame, explored structure and statistics, performed indexing and slicing, created new calculated columns, grouped and aggregated values, built pivot tables, sorted results, and exported the final dataset. Each step used core Pandas functions such as read_csv, head, info, describe, loc, iloc, groupby, pivot_table, and to_csv.


**Insights:**  
- Pandas makes it easy to explore the *student.csv* dataset, revealing clear performance gaps between classes — Class Six performs strongly while Class Four falls well below average.  
- Gender analysis shows female students outperform males by around 6%, a pattern highlighted through grouping and aggregation.  
- Pivot tables and groupby operations show that top‑scoring students don’t always align with overall class performance, with Classes Eight and Five ranking higher on averages despite lower top‑scorer results.  
- Creating new calculated columns and filtering rows helps isolate underperforming groups and understand where support is most needed.  
- Exporting cleaned DataFrames ensures the insights can be stored in a database, enabling more reliable long‑term tracking than Excel.

**Impact:**  
- Enables targeted academic support, such as strengthening lower‑performing classes and providing additional help for male students.  
- Helps educators identify mismatches between class averages and top‑scorer performance, guiding more balanced class structuring.  
- Storing the processed data in a database (instead of Excel) improves reliability, prevents accidental overwrites, and supports scalable reporting.  
- Database storage allows staff to run consistent queries (e.g., “lowest‑performing classes” or “gender performance gaps”) without re‑processing spreadsheets.  
- Creates a foundation for dashboards, automated reports, and future machine‑learning models that track student performance over time.



---

#### Pandas Pivot Table – Output  
<img src="https://raw.githubusercontent.com/MFahim-Data/Full-Stack-Data-Analytics/main/Images/PANDAS/PANDAS%20-%20Pivot%20Table.png" width="60%">
<br>
*Pivot table summarising average student scores by class and gender.*

---

### Links  
- [Pandas Pivot Table Notebook](https://github.com/MFahim-Data/Full-Stack-Data-Analytics/blob/main/PANDAS_Pivot_Table.ipynb)

*CLick the link to view the full queries of Project on PANDAS*


---

<a name="project-7-python"></a>

### Project 7 – Python – GDP & Student Visualisation Tasks


*Dataset:* GDP (nominal) per Capita.csv & student.csv

*Problem:*  
Using Pandas, Matplotlib, and Seaborn, I was required to:  
- load and explore the GDP dataset  
- print specific rows and columns  
- upload and analyse the student dataset  
- create multiple visualisations (histogram, scatter, boxplot, countplot, barplot)  
- interpret each chart with clear insights

*Approach Taken:*  
Loaded the GDP dataset using read_csv, inspected the first and last rows, and selected specific columns.  
Installed and imported Matplotlib/Seaborn, uploaded the student dataset, and created visualisations showing mark distribution, gender differences, class performance, class sizes, and average marks.  
Used functions such as head, tail, df[...], plt.figure, plt.hist, sns.boxplot, sns.countplot, and sns.barplot.
**Insights & Impact:**  
GDP dataset showed missing values; student visuals revealed performance patterns.

**Insights:**  
- The histogram shows most student marks fall between 50–95, with a strong concentration in the 80–90 range and one clear outlier around 20.  
- The gender scatter plot highlights that females have a wider mark range and score more of the highest marks, while males show a narrower distribution and fewer marks above 90.  
- The boxplot reveals class‑level performance gaps: Class Six performs strongest, Classes Three, Four, Seven also pass consistently, while Class Nine sits below 50 and requires support.  
- Class size analysis shows uneven distribution — Classes Eight and Nine have very few students, while Classes Six, Seven, and Four are overcrowded, suggesting potential rebalancing.  
- Average‑mark comparison confirms females score around 5–6% higher than males, while “NaN” entries need investigation to ensure accurate gender categorisation.

**Impact:**  
- Enables targeted academic interventions, such as supporting low‑performing classes (e.g., Class Nine) and addressing gender‑based performance gaps.  
- Helps identify structural issues like uneven class sizes, informing decisions about merging or redistributing students.  
- Highlights mismatches between class averages and top‑scorer performance, guiding more balanced class planning.  
- Storing these insights in a database (instead of Excel) ensures reliable long‑term tracking, prevents accidental overwrites, and supports consistent querying (e.g., “highest‑risk classes” or “gender performance trends”).  
- Creates a foundation for dashboards, automated reporting, and future predictive models that monitor student performance over time.

---

#### Python Visualisation – Bar Chart  
<img src="https://raw.githubusercontent.com/MFahim-Data/Full-Stack-Data-Analytics/main/Images/Python%20-/Python%20-%20Barchart%20-%201.png" width="100%">
<br>
*Countplot showing class size distribution.*

---

#### Python Visualisation – Heatmap  
<img src="https://raw.githubusercontent.com/MFahim-Data/Full-Stack-Data-Analytics/main/Images/Python%20-/Python%20-%20Heatmap%20-%201.png" width="100%">
<br>
*Correlation heatmap highlighting relationships between student performance variables.*

---

#### Python Visualisation – Box & Whisker Plot  
<img src="https://raw.githubusercontent.com/MFahim-Data/Full-Stack-Data-Analytics/main/Images/Python%20-/Python%20-%20Whiskers%20-%201.png" width="100%">
<br>
*Box‑and‑whisker plot showing score distribution and outliers.*

---

### Links  
- [Student Data Analysis Notebook](https://github.com/MFahim-Data/Full-Stack-Data-Analytics/blob/main/Code%20-%20Student_Data_Analysis_Task_2_Cleaning_and_Visualising_data.ipynb)

---
<a name="final-summary"></a>
## Final Summary
This 6‑week data analytics portfolio reflects a broad and practical skill set across Excel, Tableau, Power BI, SQL, Azure, Pandas, and Python. The projects demonstrate structured analytical workflows, effective data visualisation, robust database design, and cloud‑based processing. I am continuing to advance my capabilities in BI development and data engineering, and I am seeking opportunities where I can apply these skills to deliver meaningful analytical value.

---

### Socials  
- Email: mohammedfahim4@outlook.com  
- [GitHub](https://github.com/MFahim-Data)  
- [LinkedIn](https://www.linkedin.com/in/mohammed-fahim-data/)

<a name="socials"></a>
