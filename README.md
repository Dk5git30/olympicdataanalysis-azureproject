# Olympics 2021 Data Pipeline

## Project Overview
This project focuses on building a data pipeline in **Azure** to analyze the **2021 Olympics dataset**. Using **Azure Synapse Analytics, Azure Storage, and Azure Synapse SQL Pool**, I developed a structured ETL pipeline to ingest, transform, and visualize the data. The final insights are presented through an interactive **Power BI dashboard**.

## Dataset Description
The dataset consists of **5 files**, containing details about athletes, coaches, teams, entries by gender, and medal standings:
1. **Athletes.csv** - Details of athletes, their nationality, and the sport they competed in.
2. **Coaches.csv** - Information about coaches, their country, and associated disciplines.
3. **EntriesGender.csv** - Number of male and female participants in each discipline.
4. **Medals.csv** - Medal counts and rankings by country.
5. **Teams.csv** - Team names, disciplines, countries, and events they participated in.

## Tech Stack
- **Language**: SQL
- **Services**: Azure Synapse Analytics, Azure Storage, Azure Synapse SQL Pool, Power BI

## Architecture Diagram
*![image](https://github.com/user-attachments/assets/820ffaf8-2a04-453b-8e7e-363c3448e983)
*

## Implementation Steps
### 1. Data Ingestion
- Created an **Azure Storage Account** and uploaded the dataset into a **Blob Storage Container**.
- Configured appropriate access permissions for secure data retrieval.

### 2. Setting Up Azure Synapse Analytics
- Created an **Azure Synapse Analytics Workspace**.
- Provisioned a **Dedicated SQL Pool** within Synapse.
- Configured Linked Services to connect **Azure Storage** and **Azure Synapse**.

### 3. Data Modeling & Transformation
- Designed table structures in **Azure Synapse SQL Pool**.
- Used **PolyBase & COPY INTO** statements to load data efficiently from Azure Storage.
- Performed data cleansing and transformation using SQL scripts.

### 4. Data Analysis & Reporting
- Loaded the processed data into **Power BI**.
- Created interactive **visualizations** to analyze athlete participation, medal distributions, and country rankings.
- Published the Power BI dashboard to **Azure Synapse Workspace**.


## Key Learnings
- Leveraging **Azure Synapse SQL Pool** for efficient querying of large datasets.
- Using **PolyBase & COPY INTO** for high-performance data ingestion.
- Integrating **Power BI with Azure Synapse Analytics** for seamless reporting.
- Managing cloud resources effectively to optimize performance and cost.


## Conclusion
This project demonstrates the power of **Azure Synapse Analytics** in handling large datasets efficiently while providing insightful visualizations through **Power BI**. By leveraging cloud-based data warehousing and analytics, we can process and analyze **Olympics 2021 data** at scale.

---

📌 *Feel free to explore, contribute, or reach out for any questions!* 😊

