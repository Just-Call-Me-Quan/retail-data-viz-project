# retail-data-viz-project
Tableau dashboard analyzing 45K+ international online retail transactions. Includes monthly revenue trends, top products, and sales by country. Built using Google Sheets and Tableau.

In this project, I analyzed over 45,000 retail transactions to build a visual dashboard that surfaces key insights for business decisions. The dataset lacked a usable date field, so I created a custom InvoiceDate by combining separate Month, Day, Year, and Time columns using formula logic in Google Sheets. This enabled true chronological trend analysis in Tableau.

Along the way, I hit multiple roadblocks:

I lost access to a key SQL project due to a forgotten password, which forced me to pivot.

I ran into limitations with the dataset being pre-aggregated and had to rebuild a date structure from scratch.

Tableau threw performance warnings due to overly granular timestamp data, which I resolved by creating a simplified Month-Year field to reduce noise and improve visualization clarity.

Rather than scrap the project, I chose to pragmatically adapt and focus on deliverables that still showed business value. The final dashboard includes:

A Monthly Revenue Trend view

Top 10 Products by Revenue

Sales by Country visualization<img width="1063" height="794" alt="Online Retail Overview" src="https://github.com/user-attachments/assets/a8673b32-40b2-4cbf-8e09-5c0af06aaf8c" />
[Online retail clean.csv](https://github.com/user-attachments/files/21207648/Online.retail.clean.csv)
