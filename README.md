# Gravity Books Data Analysis Project

### Author: Devkumar Chhatriwala  
*Course: CIS-525: Applied Data Structures & Database Management*  
*Instructor: Liz Henley*  
*Date: December 7, 2023*

---

## Project Overview

The Gravity Books Data Analysis project utilizes data structures and SQL queries to extract actionable insights for business decision-making. The analysis focuses on optimizing inventory, identifying underperforming book languages, selecting top authors for promotional efforts, and suggesting potential warehouse locations based on customer order data.

---

## Key Components

### 1. Book Language Analysis
- **Objective**: Identify book languages with the lowest demand to optimize inventory.
- **Technique**: SQL queries were used to count the number of orders per language and determine which languages had fewer than five orders.
- **Insight**: Languages like Latin, Portuguese, and Middle English had the lowest demand, suggesting they could be considered for discontinuation.

### 2. Author Promotion Strategy
- **Objective**: Identify the top-performing author based on book orders for promotional campaigns.
- **Technique**: SQL queries ranked authors by the number of books ordered, focusing on the most popular author.
- **Insight**: Stephen King emerged as the top author, with 33 books ordered, making him an ideal candidate for special promotions.

### 3. Top Customer Identification
- **Objective**: Recognize the most valuable customers for targeted marketing.
- **Technique**: SQL queries were used to list the top 10 customers based on unique order counts.
- **Insight**: The analysis provided a prioritized list of customers for potential loyalty programs and personalized outreach.

### 4. Warehouse Location Analysis
- **Objective**: Recommend an optimal warehouse location to improve shipping efficiency.
- **Technique**: SQL queries analyzed order destinations to identify the city with the highest order volume.
- **Insight**: Palmerston North, New Zealand, was recommended as the best location for a new warehouse, given the high volume of orders.

---

## Business Recommendations

1. **Inventory Optimization**: Reduce or discontinue stocking books in languages with low demand.
2. **Author Promotions**: Feature popular authors like Stephen King in marketing efforts to boost sales.
3. **Customer Engagement**: Implement personalized communication and exclusive offers for top customers to increase loyalty.
4. **Warehouse Strategy**: Conduct a feasibility study for setting up a warehouse in Palmerston North to optimize shipping.

---

## Technical Details

- **Tools Used**: SQL, ER diagrams, database management concepts.
- **SQL Queries**: Custom queries were crafted to extract and analyze data effectively.
- **Data Structures**: Leveraged efficient data structures to manage and analyze large datasets.

---

## References

- Coronel, C., & Morris, S. (2014). *Database Systems: Design, Implementation, and Management*.
- Kleppmann, M. (2017). *Designing Data-Intensive Applications*.
- Sadalage, P. J., & Fowler, M. (2012). *NoSQL Distilled*.
- van de Laar, E. (2015). *Pro SQL Server Wait Statistics*.

---
