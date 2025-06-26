# DataGotTalent2024 - Movies Revenue Analysis
> *Project conducted: Late 2023 – Early 2024 (was not uploaded at the time)*

Unlocking insights from raw data to actionable strategies through preprocessing, visualization, and storytelling.

---

## Introduction

A competition held at Da Nang University of Economics. Data Got Talent is more than just a playground; it is a journey to discover exceptional talent in data analytics. It offers students a platform to shine and an opportunity to learn and grow their skills.

This project was developed as part of the **DataGotTalent 2024** competition, where participants are challenged to transform raw business datasets into compelling data stories. The dataset revolves around the movie industry, capturing transactional and customer information related to movie ticket sales. 

In this project, I performed extensive data preprocessing using **Excel** and **Python (Pandas, NumPy)** to clean and reshape the original dataset. The processed data was then visualized using **Power BI**, where I built an interactive dashboard to explore patterns, trends, and revenue insights.

The goal was to identify key drivers of movie revenue and provide data-driven decisions for business improvement. A complete set of **insights** and **recommendations** has been documented in the attached PDF report.

---

## Dataset

### Source
The dataset was provided by the DataGotTalent competition committee. It consists of transactional records from a fictional movie ticketing system, combining information from three key tables: **Customer**, **Film**, and **Ticket**.

### Key Columns (after preprocessing)
- `customerid`: Unique customer ID  
- `DOB`, `gender`, `job`: Customer demographics  
- `show_id`, `title`, `director`, `cast`, `release_year`, `country`: Film details  
- `orderid`, `ticketcode`, `saledate`, `total`, `cashier`: Ticket sales transaction details

The raw dataset required significant cleaning due to mixed header rows, multilingual labeling (Vietnamese + English), and table segmentation.

---

## Tools & Technologies

- **Languages**: Python, Excel  
- **Libraries**: pandas, numpy  
- **Visualization**: Power BI  
- **Deliverables**: Dashboard (.pbix), Insight Report (.pdf)

---

## Project Workflow

1. **Data Cleaning & Preprocessing**:
   - Merged fragmented tables into a unified dataset
   - Cleaned headers and standardized column names
   - Handled missing values and data inconsistencies

2. **Exploratory Data Analysis**:
   - Conducted univariate and bivariate analysis in Jupyter Notebook
   - Identified patterns related to customer behavior and revenue streams

3. **Dashboard Development (Power BI)**:
   - Built interactive charts for:
     - Total revenue by movie, director, and release year
     - Customer segmentation by demographics
     - Sales trends over time
   - Added slicers and filters for dynamic data exploration
   - Link [PowerBI Dashboard](https://app.powerbi.com/view?r=eyJrIjoiZjBiZmUxNjItNGVhMy00ZTA0LWIyZDMtODJiZjg5YTkzZTg4IiwidCI6ImJjNWMxMGQwLTY5OWEtNDA1Mi1hNDk2LWM2NjY1NTU3NzYyZSIsImMiOjEwfQ%3D%3D&fbclid=IwZXh0bgNhZW0CMTAAYnJpZBExaHI5aDU0UWpxNkhjYnRUQwEeQ0JMmxYUzPMmv1H7PGjIU6S5zSYNbGgAhTJSsM2RLicuPnDaZOQpBA32hh4_aem_hktMWJaEfM1HNHNgasILNQ)

4. **Insight Generation & Reporting**:
   - Extracted key business insights from visual analysis
   - Compiled actionable recommendations in the `Insights & Decisions.pdf`

---

## Key Insights (Preview)

For full insight breakdowns and strategic recommendations, please refer to the `Insights & Decisions.pdf` included in this repository.

---

## Learning Outcomes

- Mastered real-world data cleaning techniques on multi-table Excel files  
- Designed a Power BI dashboard tailored for stakeholder decision-making  
- Practiced storytelling and business communication through data reporting
