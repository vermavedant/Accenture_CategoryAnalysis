# Accenture Category Analysis

## Objective
The primary objective of this to assist Company, a rapidly expanding technology unicorn, in effectively scaling its operations on a global level. We will focus on three key areas to support this goal:

**Identification of Top 5 Popular Content Categories:** Analyzing and identifying the most popular content categories to help Social Buzz optimize its content strategy and enhance user engagement.

**Audit of Big Data Practice:** Conducting a thorough audit of Company's Big Data practices to ensure they are robust, scalable, and aligned with best practices, thus enabling the company to handle its growing data needs effectively.

**IPO Readiness Recommendations:** Providing strategic recommendations to prepare company for a successful Initial Public Offering (IPO), including financial, operational, and governance considerations.

### Company's Requests
- Top 5 popular categories of content
- How many unique categories are there?
- How many reactions are there to the most popular category?
- What was the month with the most posts?

## Data Source
The data is provided by Accenture Virtual Intership.

## Tools & Technologies
- **Excel:** For initial data exploration and preparation.
- **Power BI:** To transform data, create interactive dashboards and visualizations

## Process Overview 
### 1. Data Exploration & Understanding
The three datasets, Content, Reactions and Reaction Type are properly explored and understand which fields are required for analysis and whcih fields need to drop.


### 2.Data Cleaning
After exploring the datasets, some fileds that are of no use are removed and empty cells are deleted from the dataset


### 3.Data Modeling
In this stage we have have merged the datasets with the help of common column using VLOOKUP function. After merging the fileds, the final dataset has been reviewed for blanks and data type consistency.

### 4. Data Analysis
In this stage, the data is analyzed. After analyzing, We came to know that top 5 Content categories are Animal, Science, Healthy Eating, Technology and Food.
Based on this insights and other insights too, we will visualization in Power BI.


### 6. Visualize the data in Power BI

### Visualizations

Cards, Stacked Bar Chart, Area Chart, Line Chart, Donut Chart and Filters

#### 1. Cards

The card is used to show number of negetive/positive sentiments and total score for content category.

#### 2. Stacked Bar Chart

Shows top 5 categories with their correspond score

#### 3. Area Chart

Shows count of reactions by top 10 categories.

#### 4. Line Chart

It shows the count of reaction by months.

#### 5. Donu Chart

This chart represents the negetive nad positive sentiments by reaction type.

#### 6. filter

Filter is used to list out all the categories

https://github.com/user-attachments/assets/f04b0147-d1a2-4a17-8dbe-b350c85955f3

### Conclusion from Analysis
Based on the data, here are some insights and findings that can be derived using the visualizations from Power BI:

- There are total 16 Unique categories
- Top 5 Content categories are Animal, Science, Healthy Eating, Technology and Food.
- 1897 reactions are associated with the Animal category.
- May Month with most post, having total reactions of 2138.
- There are around 14k positive sentiments 7695 negative and 3071 neutral sentiments.
