# Consumer Complaint Analysis

## Project Overview
This project analyzes consumer complaints spanning multiple financial categories, locations, and companies. It is a three-page Power BI report that identifies patterns in complaints, evaluates company responses, and highlights areas of concern for regulators and consumers.

## Project Statement
Consumers continue to file numerous complaints about financial products and services, but there is limited insight into patterns, company responsiveness, and key problem areas. This lack of analysis hinders transparency, accountability, and effective regulatory action, creating a need to examine the data to identify trends and areas of concern.

## Objectives

Identify trends in consumer complaints across products and regions

Evaluate company responsiveness and resolution efficiency

Analyze the relationship between market share and complaint volume

Highlight companies with poor reputation or enforcement history

Provide actionable insights for regulators and stakeholders

## Dataset
The dataset is a consumer complaint dataset tracked from submission through complaint response. It has two tables

## Methodology

### Tools
- Power BI
- PowerPoint

### DAX Measures
For the four KPIs I created 

- Total Complaints

  ```SUM(Total Complaints)```

- SLA Rate
  
    ```DIVIDE([Within SLA], [Total Complaints],0)```

- Average Response Days
 
    ```AVERAGE('Complaints (Fact)'[Response_Time_Days])```
  
## Key Analysis & Insights

### Complaint Trends

Identified high-volume complaint products 
Seasonal spikes in complaint submissions

### Regional Analysis

States and census regions show significantly higher complaint rates

### Response Efficiency

Average response days varies significantly across companies
