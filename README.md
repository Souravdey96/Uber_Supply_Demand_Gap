# Uber_Supply_Demand_Gap
🚗 Uber Ride Demand, Revenue & Supply Loss Analysis

This project analyzes Uber ride request data to understand customer demand, revenue drivers, and operational inefficiencies.
It follows a complete end-to-end analytics workflow:

Python → SQL → Excel Dashboards

The objective is to identify:

When and where customers request rides

Where Uber generates revenue

Where Uber loses customers and money due to supply gaps

🧠 Business Questions Answered

What are the peak demand hours and time slots?

Do Airport or City rides generate more value?

Which time slots have the longest trips?

When do cancellations and no-car cases occur most?

How much demand is lost due to supply shortages?

🗂️ Dataset

The dataset contains Uber ride request records with:

Request & drop timestamps

Pickup location (City / Airport)

Ride status (Completed, Cancelled, No Cars Available)

Driver ID

From this data, additional features were engineered:

Request hour

Time slot (Morning, Evening, Night, Off-Peak)

Day of week

Trip duration

⚙️ Tools & Technologies
Stage	Tools
Data Cleaning & Feature Engineering	Python (Pandas)
Exploratory Analysis & Validation	Python
Business Querying	SQL (SQLite)
Dashboards & Reporting	Microsoft Excel
Visualization	Excel Pivot Charts, Slicers
🔁 Workflow

Raw data cleaned and enriched in Python

Processed data loaded into SQLite for SQL queries

SQL-validated data imported into Excel

Interactive dashboards built using Pivot Tables and Slicers

This replicates how data flows in real analytics teams.

📊 Dashboards
1️⃣ Demand & Operations Dashboard

Shows:

Total requests

Completed, cancelled, and no-car cases

Fulfillment rate

Peak hour and busiest time slot

Airport vs City demand

Purpose:
Understand customer demand and service quality.

2️⃣ Revenue & Trip Quality Dashboard

Uses trip duration as a revenue proxy and shows:

Average trip duration

Long trip percentage

Total driving hours

Highest revenue time slot

Highest revenue location

Purpose:
Understand where Uber makes money.

3️⃣ Supply Loss & Operational Efficiency Dashboard

Shows:

Fulfillment rate

Cancellation rate

No-car rate

Idle demand

Supply loss by time slot

Requests vs completed trips

Purpose:
Identify where Uber is losing customers and revenue.

📈 Key Insights

Demand peaks during morning and night time slots

City rides generate more total revenue than airport rides

Off-Peak hours have the longest trips

More than 50% of demand is lost due to cancellations and no-car availability

Night time has major driver shortages

Morning time has high customer cancellations

🎯 Business Impact

This analysis highlights where Uber should:

Add driver incentives during night hours

Improve morning supply to reduce cancellations

Focus on high-value city and off-peak rides

🏁 Conclusion

This project demonstrates how raw ride data can be converted into actionable business insights using Python, SQL, and Excel — mirroring real-world analytics workflows used in tech and mobility companies.
