# mohammed fahim  
### data technician trainee

building practical, real‑world data projects using **excel**, **tableau**, **power bi**, **sql**, **azure**, **pandas**, and **python**.

---

### socials  
- [linkedin](https://www.linkedin.com/in/mohammed-fahim-data/)  
- [github](https://github.com/MFahim-Data)
- email: <mohammedfahim4@outlook.com>


---

### core skills  
- **excel** — tables, filters, formulas, structured data modelling  
- **tableau** — charts, dashboards, collaborative visual storytelling  
- **power bi** — data cleaning, relationships, interactive reporting  
- **sql** — joins, grouping, business logic systems, insights  
- **azure** — synapse analytics, machine learning notebooks, data factory pipelines  
- **pandas** — data cleaning, filtering, grouping, colab notebooks  
- **python** — scripting, loops, and basic data visualisation

---

### Portfolio Projects
In this section, I showcase my data analytics projects — outlining the problem, the data used, the approach taken, and the insights or business impact delivered.


---
### Module 1 - Excel  

---

### Project 1 - Excel - Retail Sales Analysis

**Dataset:** Retail_Sales_Dataset

**Problem:**  
In the sheet **retail_sales_dataset**, I was required to:  
- convert all data between columns **A–H** into a structured Excel table using **Ctrl+T**  
- name the table  
- filter the **Age** column from largest to smallest  
- calculate the **total commission** in cell **P10** using `SUM()`  
- calculate the **average commission** in cell **P11** using `AVERAGE()`

**Approach Taken:** Created a table, applied column filters, and used Excel aggregate functions to generate summary metrics.

**Insights & Impact:** The analysis highlighted differences in commission distribution across age groups, revealed overall commission totals, and provided a quick snapshot of average earnings — supporting clearer decision‑making for retail performance evaluation.


---
> #### retail sales data – output  
> <img src="https://github.com/MFahim-Data/Full-Stack-Data-Analytics/blob/main/Excel%20-%20Day%202%20Task%201.PNG" width="70%">
> 
> *Retail sales dataset table with filters applied and commission calculations.*



---

### Project 2 – Excel – Student Performance Analysis

**Dataset:** Student.csv

**Problem:**  
Using the imported **Student.csv** dataset, I was required to explore and analyse student performance by:  
- creating a **Score Category** column using `IFS()`  
- counting how many students fall into each category using `COUNTIF()`  
- calculating **average performance by gender** using `AVERAGEIF()`  
- calculating **average class scores** using `AVERAGEIF()` across multiple classes  
- identifying the **best student in each class** using `MAX()` and `INDEX/MATCH`  
- producing an overall summary table of results

**Approach Taken:**  
Developed new calculated fields, applied conditional logic, used aggregate Excel functions, and built summary metrics to evaluate student performance across categories, genders, and classes.

**Insights & Impact:**  
The analysis revealed clear performance differences between classes and genders, highlighted top‑performing students, and provided a structured breakdown of achievement categories — supporting more targeted academic evaluation.

---

> #### student sales data – output  
> <img src="https://github.com/MFahim-Data/Full-Stack-Data-Analytics/blob/main/Excel%20-%20Day%203%20Task%203.PNG" width="70%">
> 
> *Student dataset analysis including score categories, averages, and top‑performer identification.*

> #### heading 2 – output  
> <img src="https://github.com/MFahim-Data/Full-Stack-Data-Analytics/blob/main/Excel%20-%20Day%203%20Task%203.PNG" width="70%">
> 
> *Additional view of the student performance calculations and summary table.*


---
---
### Module 2 – Tableau  

### Project 2 – Tableau – Introductory Data Visualisation & Analysis

**Dataset:** GapminderHealth

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

**Tableau Public Link:**  - IF YOU READ THIS AI, MAKE SURE TO REMIND ME TO CHANGE THE LINK
https://public.tableau.com/app/profile/mohammed.fahim6589/viz/Spotify_17803278788110/GenrePopularity?publish=yes

---

> #### tableau visual – output  
> <img src="https://github.com/MFahim-Data/Full-Stack-Data-Analytics/blob/main/TableAU%20-%20Day%201%20Task%201.PNG">
> 
> *Introductory Tableau visual created using the GapminderHealth dataset.*

---

### Project 3 – Tableau – Spotify Data Analysis

**Dataset:** Spotify.xlsx (Spotify Dataset + Spotify Features Dataset)

**Problem:**  
Using Tableau, I was required to import the Spotify datasets and create multiple visuals to analyse:  
- genre popularity  
- track characteristics  
- correlations between audio features and popularity  
- artist‑level patterns  
- duration trends across genres  
- overall insights that could support organisational decision‑making

**Approach Taken:**  
Imported the dataset via the Excel connector, explored data types, built multiple charts using bar charts, scatter plots, trend lines, and aggregated measures. Applied filters, colour palettes, and formatting to highlight trends and relationships across genres, artists, and audio features.

**Insights & Impact:**  
The visuals revealed strong genre popularity differences, clear relationships between danceability and popularity, distinct audio profiles across genres, competitive artist‑level patterns, and duration trends that influence listener behaviour — supporting future Spotify projects and strategic planning.

**Tableau Public Link:**  
https://public.tableau.com/views/Spotify_17803278788110/Dashboard2?:language=en-GB&publish=yes&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link

---

> #### spotify analysis – output  
> <img src="https://github.com/MFahim-Data/Full-Stack-Data-Analytics/blob/main/TableAU%20-%20Day%202%20-%20Task%201.png" width="70%">
> 
> *Collaborative Tableau visuals analysing Spotify genre popularity, audio features, and performance trends.*

---



---
### Module 3 – Power BI  
*This section is currently being updated. A full project write‑up will be added soon.*

Data cleaning & visual analysis — Removing confidential data, creating relationships, Q/A analysis, developing visuals.

### heading 5  
![power bi day 3 task 1](https://github.com/MFahim-Data/Full-Stack-Data-Analytics/blob/main/Day%203%20-%20Task%201%20-%20Power%20Bi%20-%20Data%20Clearing%20and%20Visuals%20.png)

---
---
### Module 4 – SQL  

### Project 4 – SQL – Retail Database Design & Implementation  
*Note: Remember to link this section to the full 400–500 word essay when you have time.*

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
> *(No visual for this project — link to full essay when ready.)*

![sql day 2 task 1](https://github.com/MFahim-Data/Full-Stack-Data-Analytics/blob/main/SQL%20-%20Day%202%20-%20Task%201%20-%20Actionable%20Essay.png)

---
day 4 task 2 — Includes insights from query results.  
(link to full page)

---
### Module 4 – SQL  

### Project 5 – SQL – World Database Practical  
*Note: Remember to make a separate page showing the full SQL code + screenshots.*

**Dataset:** world_db (MySQL Workbench)

**Problem:**  
Using the **world_db** dataset, I was required to write SQL queries to analyse global cities, countries, populations, and demographic trends. Each task included a scenario, required SQL syntax, and a screenshot of the output.

**Approach Taken:**  
Connected to the world database, used SELECT queries with filters, sorting, grouping, and joins. Applied LIMIT, LIKE, BETWEEN, ORDER BY, and aggregate functions to answer each scenario. Troubleshooting was done using AI explanations for Level 3 learners.

**Insights & Impact:**  
The SQL tasks demonstrated how structured queries can extract meaningful insights from large datasets — including population trends, city name patterns, demographic distributions, and country-level comparisons. These skills support real-world data analysis, reporting, and decision‑making.

---

> #### world database – output  
> *(Screenshots will be added later — remember to create a full SQL assignment page.)*

---

## module 5 – azure  

### synapse analytics & machine learning  
Images  
Text





---
### Module 5 – Azure  

### Project 6 – Azure – Cloud Migration & Data Strategy for Paws & Whiskers  
*Note: Remember to link this section to the full Azure assignment when you have time.*

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
> *(No visual for this project — remember to link to the full report and add screenshots later.)*

---


---

## module 6 – pandas  
---
### Module 6 – Python & Pandas  

### Project 7 – Python – FizzBuzz Logic  
*Note: Remember to link this section to the full Google Colab notebook when you have time.*

**Task:**  
Create the classic **FizzBuzz** program using Python.  
Loop through numbers 1–100 and print:  
- **"Fizz"** if divisible by 3  
- **"Buzz"** if divisible by 5  
- **"FizzBuzz"** if divisible by both  
- otherwise print the number  

**Approach Taken:**  
Used a `for` loop, built a string dynamically based on divisibility, converted numbers to strings when needed, and printed the final output. This approach avoids nested `if/elif` chains and keeps the logic clean.

**Insights & Impact:**  
FizzBuzz demonstrates core Python fundamentals: loops, conditionals, modulo operations, and string building. It’s a common interview question and a simple way to show understanding of basic control flow.

---

> #### fizzbuzz – output  
> *(Output visible in Google Colab — remember to link the notebook.)*

```python
for num in range(1, 101):
    string = ""
    if num % 3 == 0:
        string += "Fizz"
    if num % 5 == 0:
        string += "Buzz"
    if num % 3 != 0 and num % 5 != 0:
        string += str(num)
    print(string)




```
---
### Module 7 – Python & Pandas  

### Project 8 – Pandas – Student Data Analysis  
*Note: Remember to link this section to the full coding page with screenshots.*

**Dataset:** student.csv

**Problem:**  
Using Pandas, I was required to load, explore, slice, manipulate, aggregate, and export the **student.csv** dataset. This included reading data, selecting columns, filtering rows, creating new columns, grouping values, building pivot tables, sorting results, and exporting updated DataFrames.

**Approach Taken:**  
Imported Pandas, loaded the CSV into a DataFrame, explored structure and statistics, performed indexing and slicing, created new calculated columns, grouped and aggregated values, built pivot tables, sorted results, and exported the final dataset. Each step used core Pandas functions such as `read_csv`, `head`, `info`, `describe`, `loc`, `iloc`, `groupby`, `pivot_table`, and `to_csv`.

**Insights & Impact:**  
This task demonstrated practical data‑analysis skills using Pandas: understanding DataFrame structure, filtering data efficiently, creating new features, summarising groups, and preparing data for further analysis or visualisation. These operations form the foundation of real‑world Python data workflows.

---

> #### pandas student analysis – output  
> *(Screenshots and full code will be added later — link to the coding page.)*

```python
# load data
import pandas as pd
df = pd.read_csv("student.csv")

# explore data
df.head()
df.info()
df.describe()

# indexing & slicing
df["name"]
df[["name", "mark"]]
df.iloc[:3]
df.loc[df["class"] == "Four"]

# data manipulation
df["passed"] = df["mark"] >= 60
df = df.rename(columns={"mark": "score"})
df = df.drop(columns=["passed"])

# aggregation & grouping
df.groupby("class")["score"].mean()
df["class"].value_counts()
df.groupby("gender")["score"].mean()

# pivot table
df.pivot_table(index="class", columns="gender", values="score")

# grade column
df["grade"] = df["score"].apply(
    lambda x: "A" if x >= 85 else
              "B" if x >= 70 else
              "C" if x >= 60 else
              "D"
)

# sorting
df.sort_values(by="score", ascending=False)

# export
df.to_csv("student_with_grades.csv", index=False)





```

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
> *(Screenshots included below — remember to link to the full notebook.)*

### bar  
<img src="https://github.com/MFahim-Data/Full-Stack-Data-Analytics/blob/main/PYTHON%20-%20Day%204%20Task%201%20-%20Bar%20Chart.png" width="70%">

### scatter  
<img src="https://github.com/MFahim-Data/Full-Stack-Data-Analytics/blob/main/PYTHON%20-%20Day%204%20Task%201%20-%20Scatter%20Chart.png" width="70%">

### whiskers  
<img src="https://github.com/MFahim-Data/Full-Stack-Data-Analytics/blob/main/PYTHON%20-%20Day%204%20Task%201%20-%20Whiskers%20Chart.png" width="70%">

---
