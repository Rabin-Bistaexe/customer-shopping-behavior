# Customer Shopping Behavior Analysis

This project analyzes the shopping behavior of retail customers to help a company identify trends, improve engagement, and optimize marketing and product strategies.

The full workflow includes data cleaning in Python, business analysis using PostgreSQL, and an interactive Power BI dashboard.

### Project Workflow
1. Data preparation and cleaning using **Python (Jupyter Notebook + Pandas)**
2. Business analysis with **10 SQL queries in PostgreSQL**
3. Interactive dashboard built in **Power BI**
4. Project report and presentation

### Dataset
- 3,900 customer purchases
- Demographics: age, gender, location, subscription status
- Purchase details: category, item, amount, season, review rating, shipping type, payment method, discounts, etc.

**Overall figures:**
- Total Revenue: $233,081
- Average Purchase: $59.76
- Average Review Rating: 3.75

### Key Insights
- Only **27%** of customers have a subscription
- **Clothing** is the highest revenue and sales category
- **Young Adults** generate the highest total revenue
- Discounts were applied on nearly half of purchases but did not increase average purchase value
- None of the female customers in the dataset have a subscription
- Top-rated / strong performing items include Gloves, Sandals, Boots, Jewelry, and Blouse

### Tools Used
- Python (Pandas, Jupyter Notebook)
- PostgreSQL
- Power BI
- Gamma (presentation)

### Dashboard Screenshots

**Main Dashboard** 

<img width="1356" height="742" alt="dashboard" src="https://github.com/user-attachments/assets/a0bc73f6-c3c3-4cec-9ede-8ccd7f3ef7c5" />


**Revenue by Category**  

<img width="350" height="200" alt="revenue_by_category" src="https://github.com/user-attachments/assets/6443bc34-37b8-4885-a362-6d6491dbdc3b" />


**Revenue by Age Group**  

<img width="527" height="195" alt="revenue_by_age" src="https://github.com/user-attachments/assets/b798037e-564e-484a-9a40-da3fcc27615d" />


### How to View
1. Download the `.pbix` file
2. Open it in Power BI Desktop
3. Use the filters (Subscription, Gender, Category, Shipping Type) to explore the data

### Project Structure
- `/python` → Jupyter Notebook (cleaning + EDA)
- `/sql` → PostgreSQL queries
- `/powerbi` → Power BI dashboard
- `/report` → Full project report
