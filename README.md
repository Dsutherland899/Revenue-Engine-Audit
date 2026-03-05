# Revenue-Engine-Audit: Optimizing Sales Performance and Pipeline Health

**Project Background**
This dataset contains information about customer interactions, sales activities, and opportunities from a fictional company's CRM (Customer Relationship Management) system. The dataset contains the folllowing features listed below:

* Customer information (demographics, firmographics, etc.)
* Sales activities
* Opportunity data (deal size, stage, probability, etc.)
* Product/service information
* Sales team and performance metrics
* Time-series data (daily/weekly/monthly sales, etc.)

Insights and recommendations are provided on the following key areas:

**Sales Trend Analysis**: Sales trends over the past year are evaluated, focusing on Sales Velocity, Revenue and Average Sales Cycle (within Days)

**Pipeline Conversion and Identification**: Established and visualised sales pipeline to identify bottlenecks and areas of strength

**Product Level Performance**: Analysis of performance by product for both total and median revenue

**Sales Representative Outcomes**: Evaulated Sales Rep performance and how they trended throughout the year 

# **Data Structure**

The database is made up of 4 different tables shown below:

<img width="1024" height="744" alt="image" src="https://github.com/user-attachments/assets/5287f536-6047-4746-b603-678ec0bf8518" />


# **Executive Summary**

**Overview of Findings**

The sectors which poseess the highest amount of revenue for the company are Retail, Technology, and Medical. A significant commonality among these sectors is the dominance of the GTX Pro, which consistently records the highest sales volume. The concentration of revenue in these verticals can be attributed to high opportunity density, suggesting either a profound product-market fit driven by industry-specific demands or a highly effective, targeted prospecting strategy by the sales force.

Analysis of sales pipeline shows significant bottleneck between the stages 'Prospecting' to 'Engaging'.

<img width="2000" height="1156" alt="image" src="https://github.com/user-attachments/assets/1f00f822-2d2a-407b-aabe-9726864c647a" />


Furthermore, a comparative analysis of monthly performance reveals that these top-tier sectors are characterized by revenue stability. While lower-performing sectors, such as Employment, exhibit volatile "peaks and troughs," the Retail and Technology sectors maintain a consistent volume of closed-won opportunities. This steadiness indicates that sector success is predicated on both high lead volume and predictable monthly conversion rates.

<img width="1266" height="704" alt="image" src="https://github.com/user-attachments/assets/108f75fc-ca10-488f-a469-b113ab5ec52a" />


# Insights into Data

**Sales Reps Performance**

When looking at the top sales reps there are some interesting results we can pull:

<img width="1195" height="261" alt="image" src="https://github.com/user-attachments/assets/56b59396-ec8b-4d03-98c0-e07af412e684" />


* Top selling reps either have the highest win rate % or they have a very large pipeline with the highest amount of opportunties with all of the top 6 best performing reps having GTXPro bringing in the highest total amount of revenue but a mixture in each sales rep's best median selling product. Combined revenue of the top 6 performers is $3.42M (33.9% of total company revenue), showing heavy reliance on these 6 reps. 
* Darcel Schlecht very clearly generated the highest amount of revenue comapared to all over reps with a Total Deal Value of $1,153,214, selling into medical did well for him as this was his highest performing industry.
* For all top performers (apart from Vicki Laflamme) January is the worst performing month which is typical with most sales trends as consumers start to ramp up into the new year, most consisently have more than 8 won opportunities per month after this drought with peaks in April and July.
* As expected the average sales cycle is shorted in comparison to the average to worst performing sales reps, 
* all 3 of the most sold industries company wide are also the ones that the highest performing sales reps sold into. 

A critical assessment of the sales funnel reveals a structural bottleneck that currently caps the organization’s growth potential. While the sales team demonstrates high proficiency in initial outreach and lead generation—evidenced by the volume of deals entering the Prospecting phase—a significant logjam exists within the Engaging stage. The disparity between the volume of active engagements and final conversions indicates a breakdown in mid-funnel transition logic.

This friction point is the primary driver behind the current 47.99-day Average Sales Cycle. Deals that remain stagnant in the "Engaging" phase artificially inflate the sales cycle duration and suppress the overall Sales Velocity. Consequently, the daily revenue throughput is limited by the team's inability to efficiently move prospects from initial conversation to a finalized agreement.

**Strategic Recommendations for Revenue Growth**

1. Accelerate Sales Velocity through Pipeline Standardization
The current Sales Velocity of £208.49K per day is heavily constrained by the stagnation of deals within the "Engaging" stage. With 1.59K opportunities currently in this phase—more than triple the volume of the "Prospecting" stage—there is a clear conversion bottleneck.

Action: I recommend implementing a 72-Hour Engagement Protocol. Data suggests that high-velocity products like the GTX Pro close 8 days faster than the fleet average. By mandating a specific follow-up cadence and clear exit criteria for the Engaging stage, the firm can reduce the average sales cycle from 47.99 days to 42 days, which would theoretically increase daily sales velocity by 12.5% without increasing lead volume.

2. Optimize Total Revenue via Sector-Specific Resource Reallocation
While the Retail sector currently leads in total revenue volume, the Entertainment and Finance sectors demonstrate a higher Average Deal Size and a higher frequency of High-Value Wins. Retail provides the baseline, but Entertainment provides the margin.

Action: Shift propotion of regional marketing and prospecting budget from lower-performing, high-volatility sectors (such as Employment and Services) toward Entertainment and Finance. Focusing on these "high-density" sectors targets a higher median deal value, aiming to raise the Average Deal Size from £2.36K toward the £3K mark, directly impacting the $10.01M revenue ceiling.

3. Strategic Product Rationalization
The GTK 500 represents a significant resource leak in the current sales engine. It possesses the longest sales cycle (53.72 days) and the lowest sales volume (40 units), effectively tying up sales representatives for longer periods with a lower probability of closing.

Action: De-prioritize the GTK 500 in favor of the GTX Pro and GTX Plus Pro models, which account for over £6M of the total revenue. By incentivizing the sales force to lead with high-velocity products, the organization can "clear" the pipeline faster, allowing reps to handle a higher volume of opportunities per quarter, thereby compounding total annual revenue.
