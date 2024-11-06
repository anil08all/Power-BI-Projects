### CRM SALES 

### Overview 
For the Maven Sales Challenge, I played the role of a BI Developer for MavenTech, a company that specializes in selling computer hardware to large businesses. They've been using a new CRM system to track their sales opportunities but have no visibility of the data outside of the platform.

I created an interactive Power BI dashboard to enable sales managers to track their team's quarterly performance.

### Data Set 
The dataset contained records exported from MavenTech's CRM from October 2016 to December 2017. It held details of opportunities with associated information such as product, account, and whether the sale was won or lost.



### Key Assumptions
I made the following key assumptions which I used to guide my dashboard design.

The main goal for sales managers is viewing the current state of play for their team, and obtaining actionable information. The key questions they want to answer are:
How is my team (as a whole and individual team members) tracking against our key KPIs?
Are there team members who require extra support in certain areas?
Where should I focus my efforts for the rest of the quarter to improve performance?
Is my team performing above average compared to the rest of the business?
Their main KPI is the dollar value of sales made, however related metrics such as number of sales, conversion %, and average sales value are also important and help to understand their total sales value.
They may also at times want to dive deeper and look at their team's performance over the year or in comparison to the other sales teams.
As the dashboard is intended for the sales managers, the most important view to them is to see their own team, rather than an Exec dashboard with higher level team comparisons. They may however like to look at other sales teams in more detail and there is no requirement for row level security to prevent them access to other team data.
It is assumed that the "Current quarter" is Q4 2017, which is the latest time period recorded in the dataset, however in reality this dashboard would continuously update over time as new data is added.



### The Dashboard
This is the main page of the report, containing the most critical information for sales managers. Users select their name from the sales manager filter, and this populates all pages of the dashboard with their team's information.

The key KPIs are shown clearly at the top of the page, with figures for the previous quarter and the average figure across all sales team for each metric provided below for additional context. This allows the sales manager to see their own figures and understand generally how they are tracking against the remaining teams and towards their own goals.

Users can click the question mark to view more information about the dashboard, and see a definition of how each metric has been calculated, to assist with interpreting the dashboard.

From the total sales card, users can click the arrow to dive deeper into the sales breakdown for the current quarter. This helps them to understand where they've had success and even see itemised sales data if required.

From the potential to close card, managers can also dive deeper into all opportunities labelled as engaging for their team. They can use this detail to prioritise actions such as following up offers to close before end of quarter, and CRM cleanups e.g., opportunities that have been open for too long and need to be marked as lost.

The current quarter performance page then steps deeper into the data, with the key KPIs listed against each individual sales agent, and conditional formatting highlighting in red which team members may be struggling in a particular area. This allows the sales manager to identify both areas they can focus on to improve the performance, and individuals who may require additional support. The product level breakdown also helps identify specific areas of improvement for the team as a whole and individuals.

### Performance by Team
While it's not the most important goal for the sales managers, they would also like to be able to see how their team is performing in comparison to the remaining sales team. The current quarter performance by team page allows them to do this, by ranking all sales teams across the key metrics, and highlighting the selected team so managers can easily see where they stand.

### Performance Over Time
The final page of the dashboard allows sales managers to view their team's performance over the previous quarters to identify trends.

