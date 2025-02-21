# Sales Snapshot: CRM Insights for Managers 

# About this project
I played the role of a Business Intelligence Analyst for a company that specializes in selling computer hardware to large businesses. They've been using a new CRM system to track their sales opportunities but have no visibility of the data outside of the platform.

I created an interactive Power BI dashboard to enable sales managers to track their team's quarterly performance.

# The Dataset
The dataset contained records exported from company's CRM from October 2016 to December 2017. It held details of opportunities with associated information such as product, account, and whether the sale was won or lost.

# Key Assumptions
Sales managers primarily need to track their team's performance and gain insights that help them take action. The key questions they seek answers to are:

1. How is my team (both collectively and individually) performing against our key KPIs?
2. Are there specific team members who need extra support in certain areas?
3. Where should I focus my efforts for the remainder of the quarter to drive better performance?
4. How does my team’s performance compare to other teams across the business?

While the main KPI is the total dollar value of sales, other metrics such as sales count, conversion rates, and average sales value are important for a full understanding of performance.
Sales managers may occasionally want to analyze performance trends over the year or compare their team’s performance against other sales teams. The most important aspect for them is having a view that focuses on their own team. They can explore other teams’ data when needed, but there’s no requirement for restricting access to this information.

In this case, I have assumed that "Current quarter" refers to Q4 2017, the most recent period in the dataset. Ideally, the dashboard would update automatically as new data is added.

# The Dashboard
### First page
This is the main page of the report, containing the most critical information for sales managers. Users select their name from the sales manager filter, and this populates all pages of the dashboard with their team's information.

<img width="701" alt="image" src="https://github.com/user-attachments/assets/3b35ee9e-878b-4fda-8ce6-c0d54304e634" />

### Second page
In the second section, users can dive deeper into the sales breakdown for the current quarter. This helps them to understand where they've had success and even see itemised sales data if required.
<img width="699" alt="image" src="https://github.com/user-attachments/assets/d4ffd97c-efbd-421a-a202-168686d33fa4" />

### Third page
From the potential to close card, managers can also dive deeper into all opportunities labelled as engaging for their team. They can use this detail to prioritise actions such as following up offers to close before end of quarter, and CRM cleanups e.g., opportunities that have been open for too long and need to be marked as lost.

<img width="699" alt="image" src="https://github.com/user-attachments/assets/52d4ee6d-2caf-4e09-b552-064747e1ed61" />

### Fourth page
While it's not the most important goal for the sales managers, they would also like to be able to see how their team is performing in comparison to the remaining sales team. The current quarter performance by team page allows them to do this, by ranking all sales teams across the key metrics, and highlighting the selected team so managers can easily see where they stand.

<img width="703" alt="image" src="https://github.com/user-attachments/assets/41955cd8-565e-4ee1-856d-1fc199617b09" />

### Fifth page
The final page of the dashboard allows sales managers to view their team's performance over the previous quarters to identify trends.

<img width="704" alt="image" src="https://github.com/user-attachments/assets/3e1085a7-7ed1-4cd8-b71b-332e92a9ddec" />






