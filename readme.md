# MongoDB Coffee Shop Database Project

## Project Overview
This project involves designing and implementing a MongoDB database for a coffee shop in New York City. The aim was to manage and analyze data related to customers, products, staff, and transactions efficiently. MongoDB's flexibility and scalability make it an ideal choice for handling semi-structured data, enabling real-time analytics and personalized customer experiences.

## Objectives
The primary objectives of this project were:
1. Create a MongoDB database to store and organize coffee shop data.
2. Apply data validation rules to ensure data quality.
3. Perform queries and aggregations to extract actionable business insights.
4. Optimize query performance using indexing.

## Problem Statement
The coffee shop, operating in a fast-paced city, needed a solution to store and analyze data efficiently. Traditional relational databases lacked the flexibility to manage semi-structured data, such as customer information and receipts. A NoSQL solution like MongoDB was chosen to address this challenge, enabling real-time analytics and improved decision-making.

## Methodology
### Data Importation
- Imported datasets into MongoDB after ensuring they were in JSON or CSV format.
- Organized data into collections: `Customers`, `Products`, `Staff`, and `Receipts`.

### Data Validation
- Applied validation rules to mandatory fields in each collection:
  - Ensured correct data types (e.g., integers for IDs, strings for names).
  - Defined constraints like non-negative values and specific enumerations (e.g., `M`, `F`, `N` for gender).
  
### Indexing
- Created indexes to enhance query performance and prevent duplicate entries.
- Indexed key fields like customer IDs, product IDs, and transaction dates.

### Queries and Aggregations
- Designed 10+ queries to extract business insights:
  - Top-performing sales outlets by transaction volume and profit.
  - Best customers based on total spending.
  - Most and least sold products.
- Used aggregations with multiple stages to analyze trends and summarize data.

### Analysis
- Identified patterns such as popular products, customer preferences, and profitable locations.
- Provided actionable insights to optimize inventory, marketing campaigns, and store operations.

## Key Insights
1. **Top Sales Outlet**:
   - Store 8 had the highest transaction volume (17,071 transactions).
2. **Most Profitable Sales Outlet**:
   - Generated $79,528.25 in profit.
3. **Best Customers**:
   - Identified top spenders to target loyalty programs.
4. **Product Trends**:
   - Highlighted popular and underperforming products for better inventory management.

## Benefits of MongoDB Implementation
- **Real-Time Analytics**: Enabled quick analysis of sales and customer behavior.
- **Personalized Customer Experience**: Facilitated loyalty programs and targeted marketing.
- **Optimized Operations**: Reduced waste and improved inventory planning.
- **Scalability**: Accommodated growing data needs with a cost-effective solution.

## Deliverables
1. **Report**: Documenting design decisions, methodology, and outcomes.
2. **Backup**: Full database backup (`group_k.bson`).
3. **Query File**: Text file with all queries and aggregations (`group_k.txt`).
4. **Presentation**: PowerPoint summarizing the project methodology and results.

## Conclusion
The MongoDB implementation provided the coffee shop with an efficient, scalable solution for managing and analyzing data. This project demonstrates how NoSQL databases can drive data-driven decision-making and operational efficiency in a dynamic business environment.
