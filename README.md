# PowerBI-AdventureWorks-Purchassing-Analysis
## Project overview 
This project involves creating a comprehensive business intelligence dashboard for a global retail company called Superstore. The dashboard aims to provide senior management with actionable insights for market expansion strategies and strategic product selection.
## Dataset 
The analysis is based on three main datasets:
- Orders: Contains detailed transaction information from global sales
- People: Stores information about sales representatives across different regions
- Returns: Tracks returned transactions and related data
##  Technical Implementation
- Power BI for Visualization: Design dashboards to display key insights visually, using charts, tables, and KPIs.
- Data Processing: Use Power Query to clean and transform data, and structure a well-designed data model.
- Dynamic Filters: Set up dynamic filters to allow leadership to easily select suppliers, products, or time frames.
- Calculations and Measures: Use DAX to create measures such as profit, ROS.
## Design Thinking Steps 
### Stage 1 - Empathy 
#### First, start with 5W1H
![image](https://github.com/user-attachments/assets/b11df8c7-95d3-4993-a7c2-3651c6c11fea)
#### Now, become your users with empathy map and stakeholder journey 
![image](https://github.com/user-attachments/assets/7e5c87ae-1c57-44bc-81bb-2014e80b2635)
### Finally, see what we have with the Dataset
![image](https://github.com/user-attachments/assets/d3148981-7a02-4af7-9462-b3e04d91938c)
### Stage 2 - Define 
![image](https://github.com/user-attachments/assets/dc9d712c-2667-4848-9d3e-53176eec88c6)
#### Stage 3: Ideate 

#### Stage 4: Prototype and Review
Next, I proceeded with Step 4 - Prototype and Review multiple times and achieved the final result, which will be presented in the following section as a dashboard.
## DashBoard 
### Data Modeling 
![image](https://github.com/user-attachments/assets/f2c5c56b-9036-4e62-96ba-1f55f9df6731)
### View 1: Vendor Performance 
![image](https://github.com/user-attachments/assets/d57baa99-2a6b-47c1-8f56-9deb769979ae)
### View 2: Cost Efficiency 
![image](https://github.com/user-attachments/assets/62dcce51-0c8d-4836-9c4f-06befae026d2)
## Insight & Recommendation
### Vendor Performance 
#### Analysis
The "Vendor Performance" table evaluates the overall performance of suppliers based on several key metrics, such as the On-Time and In-Full (OTIF) rate, average shortage rate, and order rejection rate.
- OTIF Rate: This rate stands at 95.6%, reflecting a high capability of suppliers to meet order requirements on time and in full. However, there is a clear discrepancy between suppliers, indicating the need for adjustments or improvements for some suppliers.
- Average Shortage Rate: At 11.57, this rate suggests that demand forecasting and current inventory management may need improvement to avoid product shortages.
- Order Rejection Rate: This rate is at 6.37, indicating a significant portion of orders are rejected, affecting production processes and customer satisfaction.
#### Recommendations
- Enhance collaboration and performance management with suppliers: Although the overall OTIF rate is 95.6%, it is essential to establish regular performance evaluation meetings with suppliers who have lower rates to understand the issues and support them in improving. These issues may relate to logistics, production, or financial factors. Implement training programs, guidance, or process improvements to enhance performance.
- Improve demand forecasting and inventory management processes: The high shortage rate indicates inaccuracies in demand forecasting. Modern forecasting models, such as Machine Learning, should be utilized to improve accuracy in demand forecasting and inventory management. This will help minimize shortages and ensure products are always available for delivery.
- Analyze causes and reduce the order rejection rate: With the order rejection rate at 6.37, it is crucial to analyze the underlying causes leading to this situation. It could be due to product quality, order processing procedures, or unclear requirements. Implement corrective solutions such as improving quality control processes, enhancing order processing systems, and better communication with suppliers.
- Focus on collaboration with suppliers with high credit ratings and appropriate preferred vendor status: Suppliers with high Credit Ratings (2) and good Preferred Vendor Status show the highest performance in meeting requirements. The company should build long-term collaboration plans with these suppliers and reassess those that do not meet requirements to improve or adjust collaboration strategies.
### Cost Efficiency
#### Analysis
The "Cost Efficiency" table provides an overview of cost efficiency related to product price and quality, total cost of ownership, and the effectiveness of volume discounts.
- Price-Quality Rate: This index measures the ratio of product quality (determined by the rejection rate versus received products) to the average product price. At 0.03, it indicates that the quality of products received compared to the cost incurred is at an average level.
- Total Cost of Ownership: This index is at 1.08, indicating that the total costs, including product price, shipping fees, and taxes, are 8% higher than the average product price. This suggests that ancillary costs are significantly impacting total ownership costs.
- Volume Discount Effectiveness: The index of -18.86% shows that purchasing in bulk has helped reduce the average price by 18.86% compared to the overall average price. This means that the discount strategy is generally effective.
#### Recommendations
- Renegotiate with suppliers with lower credit ratings: Suppliers with the highest credit rating (CreditRating = 5) are providing products with the highest Price-Quality Rate (0.042). A high Price-Quality Rate may correspond to higher product prices with quality matching the price. However, to optimize costs, the company can consider collaborating with suppliers with lower credit ratings but who can still provide stable quality products. The goal is to find suppliers who can deliver quality products at lower prices, thus reducing overall costs without compromising product quality.
- Optimize ancillary costs such as shipping and taxes: With a Total Cost of Ownership Index of 1.08, it is necessary to review shipping processes and collaborate with logistics partners to renegotiate rates or change partners if necessary. Additionally, optimizing shipping plans, such as consolidating shipments or optimizing the quantity of goods per trip, can help reduce shipping costs and improve this index.
- Encourage larger volume purchases: The current Volume Discount Effectiveness index indicates that purchasing in bulk is providing significant cost benefits. Therefore, departments should be encouraged to purchase larger quantities or negotiate with suppliers to adjust discount thresholds, thereby enhancing the effectiveness of promotional and discount programs.
### Conclusion
Improving cost efficiency and supplier performance requires a comprehensive approach, including renegotiating prices, optimizing costs, improving supply chain management, and collaborating closely with capable suppliers. Implementing these strategies will not only help the company save costs but also enhance operational efficiency and customer satisfaction.


