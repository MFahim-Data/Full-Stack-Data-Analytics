# Mohammed Fahim  
### Data Technician Trainee

Hi, I am a Data Technician Trainee building practical projects using Excel, Tableau, Power BI, SQL, Azure, Pandas, and Python.

This GitHub Pages site showcases all my course modules, including real code, visualisations, cloud work, and analysis tasks completed throughout the programme.

---

### Socials  
- [LinkedIn](https://www.linkedin.com/in/mohammed-fahim-data/)  
- [GitHub](https://github.com/MFahim-Data)  
- Email: mohammedfahim4@outlook.com

---

### Core Skills  
- **Excel** — tables, filters, formulas, structured data modelling  
- **Tableau** — charts, dashboards, collaborative visual storytelling  
- **Power BI** — data cleaning, relationships, interactive reporting  
- **SQL** — joins, grouping, business logic systems, insights  
- **Azure** — Synapse Analytics, Machine Learning notebooks, Data Factory pipelines  
- **Pandas** — data cleaning, filtering, grouping, Colab notebooks  
- **Python** — scripting, loops, and basic data visualisation

---

### Portfolio Projects  
In this section, I showcase my data analytics projects — outlining the problem, the data used, the approach taken, and the insights or business impact delivered.

---
### Module 1 – Excel  

---

### Project 1 – Excel – Student Performance Analysis

**Excel Link:** [Download Student Dataset (Excel)](https://github.com/MFahim-Data/Full-Stack-Data-Analytics/blob/main/Files/Excel/Student%20Dataset.xlsx)

**Problem:**  
Using the imported **Student.csv** dataset, I analysed student performance by:  
- creating a **Score Category** column using `IFS()`  
- counting students in each category using `COUNTIF()`  
- calculating **average performance by gender** using `AVERAGEIF()`  
- calculating **average class scores** using `AVERAGEIF()`  
- identifying the **best student in each class** using `MAX()` and `INDEX/MATCH`  
- producing an overall summary table of results

**Approach Taken:**  
Developed new calculated fields, applied conditional logic, used aggregate Excel functions, and built summary metrics to evaluate student performance across categories, genders, and classes.

**Insights & Impact:**  
The analysis revealed clear performance differences between classes and genders, highlighted top‑performing students, and provided a structured breakdown of achievement categories — supporting more targeted academic evaluation.

---

> #### student performance data – output  
<img src="https://raw.githubusercontent.com/MFahim-Data/Full-Stack-Data-Analytics/main/Images/Excel/Excel%20Student%20Image%201.png" width="100%">
> *Student dataset analysis including score categories, averages, and top‑performer identification.*

---

> #### additional summary view – output  
<img src="https://raw.githubusercontent.com/MFahim-Data/Full-Stack-Data-Analytics/main/Images/Excel/Excel%20Student%20Image%202.png" width="100%">
> *Additional view of the student performance calculations and summary tables.*

---

### Module 2 – Tableau  
---
### Project 2 – Tableau – Introductory Data Visualisation & Analysis

**Tableau Public Link:**  
https://public.tableau.com/shared/CD8MMQ3PK?:display_count=n&:origin=viz_share_link


**Problem:**  
Using Tableau, I was required to create a series of visualisations to explore global health trends, including:  
- life expectancy by continent  
- life expectancy trends over time  
- population distribution by gender  
- BMI vs life expectancy scatter plot  
- a final dashboard combining all visuals

**Approach Taken:**  
Connected the dataset, checked data types, built multiple worksheets using basic Tableau features (filters, colours, axis formatting, aggregation changes), and combined them into a dashboard titled **Global Health Insights**.

**Insights & Impact:**  
The visuals revealed clear differences in life expectancy across continents, steady improvements over time, relationships between BMI and health outcomes, and major population distribution patterns — supporting global health planning and analysis.




---

> #### tableau visual – output
<img src="https://raw.githubusercontent.com/MFahim-Data/Full-Stack-Data-Analytics/main/Images/Global%20Health%20Insights%20Dashboard.png" width="100%">
> *Introductory Tableau visual created using the GapminderHealth dataset.*
---

### MODULE 3 – POWER BI

---

### PROJECT 3 – POWER BI – SALES PERFORMANCE DASHBOARD

**POWER BI PUBLIC LINK:**  
https://app.powerbi.com/links/PMd5n60xXh?ctid=3ea7c128-c601-4479-a003-e14d00c0b5cb&pbi_source=linkShare

**PROBLEM:**  
To build an interactive Power BI dashboard to analyse retail sales performance, identify trends, and provide dynamic insights across categories, regions, and time periods. The dashboard needed to support real‑time filtering, drill‑downs, and natural language Q&A exploration.

**APPROACH TAKEN:**  
Performed end‑to‑end BI development including:  
- Removing confidential data during Power Query cleaning  
- Creating relationships between fact and dimension tables  
- Building interactive visuals linked through slicers and cross‑filtering  
- Using Q&A analysis to generate insights through natural language queries  
- Implementing a decomposition tree for deep drill‑down analysis  
- Designing a clean, business‑ready dashboard layout  

**INSIGHTS & IMPACT:**  
The dashboard revealed clear differences in category performance, highlighted regional sales trends, and enabled dynamic drill‑downs using the decomposition tree. Interactive visuals allow employers to click any chart and instantly see related changes across the entire dashboard — demonstrating strong BI interactivity and user‑focused design.

---

#### SALES PERFORMANCE DASHBOARD – OUTPUT  
<img src="https://raw.githubusercontent.com/MFahim-Data/Full-Stack-Data-Analytics/main/Images/Power%20Bi/Power%20Bi%20-%20Sales%20-%20Dashboard.PNG" width="100%">

*Interactive dashboard showing KPIs, category trends, regional breakdowns, Q&A insights, and decomposition tree drill‑downs.*

---
### Module 4 – SQL  


### Project 4 – SQL – Retail Database Design & Implementation  

---

> **FULL SQL ESSAY REPORT:**  
> [View SQL – Essay (PDF) →](https://github.com/MFahim-Data/Full-Stack-Data-Analytics/blob/main/Files/SQL/SQL%20-%20Essay.pdf)

---
> **FULL SQL BRIEF REPORT:**  
> [View SQL – Brief (PDF) →](https://github.com/MFahim-Data/Full-Stack-Data-Analytics/blob/main/Files/SQL/SQL%20-%20Brief.pdf)
---


**Dataset / Scenario:**  
A small corner shop needs a new database system to manage inventory, suppliers, customers, sales, and loyalty points. The goal is to streamline operations and support staff and managers with accurate, structured data.

**Problem:**  
I was required to design and build a relational database that:  
- stores supplier, inventory, sales, customer, and loyalty programme data  
- defines clear primary and foreign key relationships  
- supports daily operations such as stock checks, sales recording, and loyalty tracking  
- includes SQL examples for creating tables, inserting data, and maintaining accuracy

**Approach Taken:**  
I analysed the business requirements, identified the essential tables, designed a relational schema, and implemented it using SQL `CREATE TABLE`, `INSERT`, and `FOREIGN KEY` statements. I ensured each table connected logically to support real‑world shop operations.

**Insights & Impact:**  
The database structure supports efficient stock management, accurate sales tracking, customer loyalty monitoring, and secure data handling. Clear relationships between tables make it easy for staff and managers to understand and use the system, improving reliability and operational flow.

---

> #### retail database – output
> #### CUSTOMER ERD – OUTPUT  
<img src="https://raw.githubusercontent.com/MFahim-Data/Full-Stack-Data-Analytics/main/Images/SQL/Customer_ERD.png" width="30%">
> *Entity–relationship diagram showing customer, orders, and relational structure.*

---

> #### CUSTOMER ERD (VERSION 2) – OUTPUT  
<img src="https://raw.githubusercontent.com/MFahim-Data/Full-Stack-Data-Analytics/main/Images/SQL/Customer_ERD%202.png" width="30%">
> *Alternative ERD layout highlighting table relationships and key constraints.*


---
### Module 5 – Azure  

### Project 6 – Azure – Cloud Migration & Data Strategy for Paws & Whiskers  


> **FULL AZURE BRIEF REPORT:**  
> [View Azure – Brief (PDF) →](https://github.com/MFahim-Data/Full-Stack-Data-Analytics/blob/main/Files/Azure/Azure%20-%20Brief.pdf)

---

> **FULL AZURE REPORT:**  
> [View Azure – Full Report (PDF) →](https://github.com/MFahim-Data/Full-Stack-Data-Analytics/blob/main/Files/Azure/Azure%20-%20Report.pdf)


**Scenario:**  
Paws & Whiskers is a growing pet shop transitioning from spreadsheets to Microsoft Azure to improve data storage, security, automation, and analytics. The goal is to modernise operations and support data‑driven decision‑making.

**Problem:**  
I was required to analyse the business needs and produce a structured Azure proposal covering:  
- GDPR & DPA compliance  
- recommended Azure services  
- data types and modelling  
- storage formats  
- security, backup, and scalability  
- how Azure improves daily operations

**Approach Taken:**  
Reviewed UK/EU data laws, mapped business requirements, selected appropriate Azure services (SQL Database, Synapse, Machine Learning, Data Factory), designed a relational data model, recommended secure storage formats, and outlined backup, visualisation, and scalability strategies.

**Insights & Impact:**  
Azure provides secure, compliant storage, automated data pipelines, advanced analytics, and scalable infrastructure. This enables Paws & Whiskers to replace spreadsheets with reliable cloud systems, improve reporting, forecast demand, protect customer data, and support long‑term business growth.

---

> #### azure cloud proposal – output  
<img src="https://raw.githubusercontent.com/MFahim-Data/Full-Stack-Data-Analytics/main/Images/Azure/Azure%20-%20P%26W'S%20Schema.png" width="60%">
> *Azure-based relational schema diagram for the Paws & Whiskers project.*


---


---

## module 6 – pandas  
---
### Project 8 – Pandas – Student Data Analysis  
*Note: Remember to link this section to the full coding page with screenshots.*


---
**Notebook Link:**  
[Pandas Pivot Table – Student Analysis](https://github.com/MFahim-Data/Full-Stack-Data-Analytics/blob/main/PANDAS_Pivot_Table.ipynb)
--- 
**Dataset:** student.csv

**Problem:**  
Using Pandas, I was required to load, explore, slice, manipulate, aggregate, and export the **student.csv** dataset. This included reading data, selecting columns, filtering rows, creating new columns, grouping values, building pivot tables, sorting results, and exporting updated DataFrames.

**Approach Taken:**  
Imported Pandas, loaded the CSV into a DataFrame, explored structure and statistics, performed indexing and slicing, created new calculated columns, grouped and aggregated values, built pivot tables, sorted results, and exported the final dataset. Each step used core Pandas functions such as `read_csv`, `head`, `info`, `describe`, `loc`, `iloc`, `groupby`, `pivot_table`, and `to_csv`.

**Insights & Impact:**  
This task demonstrated practical data‑analysis skills using Pandas: understanding DataFrame structure, filtering data efficiently, creating new features, summarising groups, and preparing data for further analysis or visualisation. These operations form the foundation of real‑world Python data workflows.

---

> #### pandas – pivot table output  
<img src="https://raw.githubusercontent.com/MFahim-Data/Full-Stack-Data-Analytics/main/Images/PANDAS/PANDAS%20-%20Pivot%20Table.png" width="60%">
> *Pivot table summarising average student scores by class and gender using Pandas.*





---
### Module 7 – Python & Pandas  

### Project 9 – Python – GDP & Student Visualisation Tasks  
*Note: Remember to link this section to the full coding page with screenshots.*

**Dataset:** GDP (nominal) per Capita.csv & student.csv

**Problem:**  
Using Pandas, Matplotlib, and Seaborn, I was required to:  
- load and explore the GDP dataset  
- print specific rows and columns  
- upload and analyse the student dataset  
- create multiple visualisations (histogram, scatter, boxplot, countplot, barplot)  
- interpret each chart with clear insights

**Approach Taken:**  
Loaded the GDP dataset using `read_csv`, inspected the first and last rows, and selected specific columns.  
Installed and imported Matplotlib/Seaborn, uploaded the student dataset, and created visualisations showing mark distribution, gender differences, class performance, class sizes, and average marks.  
Used functions such as `head`, `tail`, `df[...]`, `plt.figure`, `plt.hist`, `sns.boxplot`, `sns.countplot`, and `sns.barplot`.

**Insights & Impact:**  
The GDP dataset showed missing values in IMF estimates for a few countries.  
Student visualisations revealed clear mark ranges, gender differences, class performance gaps, outliers, and class size imbalances.  
These tasks demonstrate practical Python data‑analysis skills and the ability to interpret visual insights.

---

> #### python visualisations – output
**Notebook Link:**  
[Student Data Analysis – Task 2 (Cleaning & Visualising Data)](https://github.com/MFahim-Data/Full-Stack-Data-Analytics/blob/main/Code%20-%20Student_Data_Analysis_Task_2_Cleaning_and_Visualising_data.ipynb)


### bar  
<img src="https://github.com/MFahim-Data/Full-Stack-Data-Analytics/blob/main/PYTHON%20-%20Day%204%20Task%201%20-%20Bar%20Chart.png" width="70%">

### scatter  
<img src="https://github.com/MFahim-Data/Full-Stack-Data-Analytics/blob/main/PYTHON%20-%20Day%204%20Task%201%20-%20Scatter%20Chart.png" width="70%">

### whiskers  
<img src="https://github.com/MFahim-Data/Full-Stack-Data-Analytics/blob/main/PYTHON%20-%20Day%204%20Task%201%20-%20Whiskers%20Chart.png" width="70%">

---
