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
* For all top performers (apart from Vicki Laflamme) January is the worst performing month which is typical with most sales trends as consumers start to ramp up into the new year, most sales reps consistently have more than 8 won opportunities per month after this drought with peaks in April and July.
* As expected the average sales cycle is shorted in comparison to the average to worst performing sales reps, 
* All 3 of the most sold industries company wide are also the ones that the highest performing sales reps sold into.

**Product Performance**

* The GTX Pro Generated the highest amount of total revenue at $3,510,578 with the GTK 500 and MG Special performing the worst with $400,612 and $43,768 total revenue earned respectivley. However, the GTK 500 achieved the highest median revenue out of all products with $24,899. This is largely due to it being the highest priced product ($26,768) and having a lowest amount of opportunties compared to other products which explains the product having the highest Average Deal Size of $26.71K. This could be an indication that there could be some price sensitivity amongst consumers. 
* On sales velocity the GTXPro has the highest Sales Velocity sitting at $76.77K a day with can be attributed to the its high number of opportunities (1.48K) compared to the rest of the product suite and it's win rate being the highest compared to other products (49.26%) alongside having the lowest average sales cycle of 45.73 days.
* GTK500 has an exteremly low win rate of 37.5% far below the prduct average of 48.16%, this could further support the price sensitivity assumption mentioned earlier amongst consumers.
* GTX Plus Pro has great performance considering it has the second lowest opportunities amongst the product suite (968), it has the second highest total and median revenue alongside a relatively short average sales cycle despite it being the second most expensive product.
  
**Pipeline Analysis**

<img width="571" height="265" alt="image" src="https://github.com/user-attachments/assets/9a14999f-1140-431c-be7b-713914f635e1" />


* Large disparity between 'Prospecting' stage and 'Engaging' stage, indicating that their could be a bottleneck issue between these two stages preventing them from being moved into Won or Lost. 
* Within the 'Lost' stage GTX Basic is the most common to be within this stage with 521 opportunities
* Without figures on what the revenue of these lost opportunities are it is hard to establish what lost out revenue figures would look like.

  **Sector Review**
  * The reatil sector generates the most revenue for the company with $1.87M contributed, however average deal size within this sector ($2.34K) is smaller compared to Softwarem Finance and Entertainment ($2.40K, $2.54K and $2.65K)
  * Marketing sectors sees the highest winrate with 59.94%, this can be attributed to the GTX Pro and the GTX Plus Pro success within this channel, especially for GTX Plus Pro as depsite having the second least deal opportunities within this sector it generated the second highest total and median revenue with $259,016 and $4,984.5 respectivley. 

# Strategic Recommendations for Revenue Growth

1. From the understanding we have of the product performance, the pricing strategy of the GTK500 should be undereview due to it's extrememly low win rate and long duration with it's sales cycle. Further investigation into price sensitivity can be conducted through techniques such as linear regression analysis, to understand the effects of the products price on the number of opportunities and/or average sales cycle.

2. While the Retail sector currently leads in total revenue volume, the Entertainment and Finance sectors demonstrate a higher Average Deal Size and a higher frequency of High-Value Wins. Retail provides the baseline, but Entertainment provides the margin. Shift propotion of regional marketing and prospecting budget from lower-performing, high-volatility sectors (such as Employment and Services) toward Entertainment and Finance. Focusing on these "high-density" sectors targets a higher median deal value, aiming to raise the Average Deal Size from £2.36K toward the £3K mark, directly impacting the $10.01M revenue ceiling.

3. Strategic Product Rationalization
The GTK 500 represents a significant resource leak in the current sales engine. It possesses the longest sales cycle (53.72 days) and the lowest sales volume (40 units), effectively tying up sales representatives for longer periods with a lower probability of closing. De-prioritize the GTK 500 in favor of the GTX Pro and GTX Plus Pro models, which account for over £6M of the total revenue. By incentivizing the sales force to lead with high-velocity products, the organization can "clear" the pipeline faster, allowing reps to handle a higher volume of opportunities per quarter, thereby compounding total annual revenue.
