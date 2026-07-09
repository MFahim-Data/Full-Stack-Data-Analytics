# Mohammed Fahim  
### Data Technician Trainee

---

Hi, I am a Data Technician Trainee building practical projects using Excel, Tableau, Power BI, SQL, Azure, Pandas, and Python.

This GitHub Pages site showcases all my course modules, including real code, visualisations, cloud work, and analysis tasks completed throughout the programme.

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

### Project 1 – Excel – Student Performance Analysis

**Problem:**  
Using the imported **student.csv** dataset, I analysed student performance by:  
- Creating a **Score Category** column using `IFS()`  
- Counting students in each category using `COUNTIF()`  
- Calculating **average performance by gender** using `AVERAGEIF()`  
- Calculating **average class scores** using `AVERAGEIF()`  
- Identifying the **best student in each class** using `MAX()` and `INDEX/MATCH`  
- Producing an overall summary table of results

**Approach Taken:**  
Developed new fields, applied conditional logic, used aggregate Excel functions, and built summary metrics to evaluate student performance across categories, genders, and classes.

**Insights:**  
The analysis shows clear performance gaps between classes — Class Six performs strongly, while Class Four falls well below the average. Female students also outperform males by around **6%** on average.

The data highlights that **top‑scoring students don’t always match overall class performance**. For example, Classes Eight and Five rank 3rd and 4th in average score, yet their highest‑scoring students achieved lower marks than the top students in Classes Five and Six.

**Impact:**  
- Strengthen lower‑performing classes  
- Provide targeted support for male students  
- Rebalance class structures to improve overall performance  

See the image below for a visual breakdown of these insights.

---

#### Student Performance Data – Output  
<img src="https://raw.githubusercontent.com/MFahim-Data/Full-Stack-Data-Analytics/main/Images/Excel/Excel%20Student%20Image%201.png" width="100%">
<br>
*Student dataset analysis including score categories, averages, and top‑performer identification.*

---

#### Additional Summary View – Output  
<img src="https://raw.githubusercontent.com/MFahim-Data/Full-Stack-Data-Analytics/main/Images/Excel/Excel%20Student%20Image%202.png" width="100%">
<br>
*Additional view of the student performance calculations and summary tables.*

<br>

### Links  
- [Download Student Dataset (Excel)](https://github.com/MFahim-Data/Full-Stack-Data-Analytics/blob/main/Files/Excel/Student%20Dataset.xlsx)


<br>
---

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
The analysis shows clear differences in sales performance across segments — Consumer sales consistently lead, highlighting a strong opportunity for targeted marketing and product focus. Customer segments are evenly distributed, meaning businesses can specialise their sales strategy based on the segment that best aligns with their goals.

The dashboard also reveals clear regional and category trends, and the decomposition tree makes it easy to drill from region → segment → country to understand where performance strengths or weaknesses originate. The Q&A feature further enhances exploration by allowing natural‑language questions, helping users quickly uncover insights without manual filtering.

**Impact:**  
- Focus sales efforts on high‑performing segments such as Consumer  
- Tailor sales strategies to the customer segment that best fits business needs  
- Use decomposition tree drill‑downs to identify root causes of strong or weak performance  
- Leverage Q&A analysis to speed up insight discovery and support data‑driven decisions  
- Improve strategic planning by understanding regional and category‑level trends  

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

### Project 6 – Azure – Cloud Migration & Data Strategy for Paws & Whiskers

**Scenario:**  
Paws & Whiskers is transitioning from spreadsheets to Azure.

**Problem:**  
I produced an Azure proposal covering compliance, services, modelling, storage, security, backup, and scalability.

**Approach Taken:**  
Mapped requirements, selected Azure services, designed schema, recommended storage formats, outlined security and scalability.

**Insights & Impact:**  
Azure enables secure storage, automation, analytics, and scalable infrastructure.

---

#### Azure Cloud Proposal – Output  
<img src="https://raw.githubusercontent.com/MFahim-Data/Full-Stack-Data-Analytics/main/Images/Azure/Azure%20-%20P%26W'S%20Schema.png" width="60%">
<br>
*Azure-based relational schema diagram for the Paws & Whiskers project.*

---

### Links  
- [Azure Brief Report (PDF)](https://github.com/MFahim-Data/Full-Stack-Data-Analytics/blob/main/Files/Azure/Azure%20-%20Brief.pdf)  
- [Azure Full Report (PDF)](https://github.com/MFahim-Data/Full-Stack-Data-Analytics/blob/main/Files/Azure/Azure%20-%20Report.pdf)

---

### Project 8 – Pandas – Student Data Analysis

**Dataset:** student.csv

**Problem:**  
Using Pandas, I loaded, explored, sliced, manipulated, aggregated, and exported the dataset.

**Approach Taken:**  
Performed indexing, slicing, created new columns, grouped values, built pivot tables, sorted results, exported final dataset.

**Insights & Impact:**  
Demonstrated practical data‑analysis skills using Pandas.

---

#### Pandas Pivot Table – Output  
<img src="https://raw.githubusercontent.com/MFahim-Data/Full-Stack-Data-Analytics/main/Images/PANDAS/PANDAS%20-%20Pivot%20Table.png" width="60%">
<br>
*Pivot table summarising average student scores by class and gender.*

---

### Links  
- [Pandas Pivot Table Notebook](https://github.com/MFahim-Data/Full-Stack-Data-Analytics/blob/main/PANDAS_Pivot_Table.ipynb)

---

### Project 9 – Python – GDP & Student Visualisation Tasks

**Dataset:** GDP (Nominal) Per Capita.csv & student.csv

**Problem:**  
Using Pandas, Matplotlib, and Seaborn, I created multiple visualisations.

**Approach Taken:**  
Loaded datasets, inspected rows, created histograms, scatter plots, boxplots, countplots, and barplots.

**Insights & Impact:**  
GDP dataset showed missing values; student visuals revealed performance patterns.

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

### Socials  
- Email: mohammedfahim4@outlook.com  
- [GitHub](https://github.com/MFahim-Data)  
- [LinkedIn](https://www.linkedin.com/in/mohammed-fahim-data/)
