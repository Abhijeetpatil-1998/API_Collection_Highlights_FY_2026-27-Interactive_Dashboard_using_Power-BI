## API Collection Highlights FY 2026-27 (Interactive Dashboard using Power BI)

### Project Objective
Create a one-page management dashboard for API billing, collections, overdue ageing and recovery actions, so leadership can track how much has been invoiced and collected, and act quickly on pending merchants and account managers.

## Note :
Due to data privacy and company confidentiality policies, raw datasets, customer records, and the original workbook are proprietary and cannot be shared publicly.

### Dataset Used
Invoice-level data for FY 2026-27 with Invoice No., Account Name (account manager), API Partner (merchant) Name, Invoice Amount, Received Amount, Pending Amount, Month/Quarter and Due Week. Data is updated as of 25-10-2026.

Questions (KPIs)
- How many invoices were raised and what is the total amount raised?
- How much has been received till date, and what is the collection %?
- How much is outstanding and across how many invoices?
- How do invoiced and received amounts compare month by month?
- Which top 5 merchants have the highest pending dues?
- When are the outstanding amounts due (weekly ageing)?
- How are the account managers performing on collection?

### Process
- Checked the data for missing values and duplicate invoices and cleaned them.
- Made sure amounts, dates and names were consistent (Lac / Cr units).
- Created measures for Total Raised, Received, Outstanding, Collection % and Outstanding Invoices.
- Built the visuals: KPI cards, monthly Invoice vs Received column chart, top 5 pending merchant table, weekly ageing table and account manager scorecard.
- Combined everything into one page with the month/quarter view for easy tracking.

### Dashboard
![API Marchant Collection Dasboard](https://github.com/Abhijeetpatil-1998/API_Collection_Highlights_FY_2026-27-Interactive_Dashboard_using_Power-BI/blob/main/API%20Marchant%20Collection%20Dasboard.jpeg)

### Project Insights
- Collection is strong at about 94.63%: 31.38 Cr received out of 33.16 Cr raised.
- Only 1.78 Cr (about 5%) is outstanding, spread over 20 of the 174 invoices.
- Invoiced and received amounts match closely from April to September; the gap appears in October (invoiced is higher than received), which is the current outstanding.
- Most of the outstanding falls due in early November (about 114.5 Lac in Week 1), so recovery follow-up should be prioritised now.
- A few merchants hold most of the pending amount; the top 5 pending merchants account for about 162 Lac of the dues, led by Alphadbit Sales Technologies and Instanow Info Systems.
- Girish has a collection rate of about 96%, while Melvin is at about 71% with the larger share of pending dues (157.35 Lac).

### Final Conclusion

Overall collection health is good, but recovery should focus on the top pending merchants and on Melvin's accounts, where most dues sit. Prioritise follow-ups for the amounts falling due in the first week of November, and review the monthly invoice vs received gap regularly to keep collection above 95%

### Tools Used
- Power BI Desktop (Data Modeling, DAX, Custom Combo Charts, Visual Slicers)
- Microsoft Excel (Data cleaning & validation)
