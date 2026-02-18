# Revenue-Engine-Audit: Optimizing Sales Performance and Pipeline Health

Objective: To analyze a B2B sales dataset to identify high-value sectors, diagnose bottlenecks in the sales funnel, and provide data-backed recommendations to increase total revenue and sales velocity.

**Code Source**
https://archive.ics.uci.edu/dataset/352/online%2Bretail?

**Executive Summary**

This audit provides a comprehensive evaluation of TechGear Solutions’ fiscal year performance, focusing on revenue distribution, pipeline health, and operational efficiency. By leveraging SQL-driven data extraction and Power BI visualization, the analysis identifies high-value growth sectors and critical friction points within the sales funnel. The objective is to provide actionable intelligence to optimize resource allocation and accelerate sales velocity.

**Sector Performance and Market Demand**

This analysis identifies Retail, Technology, and Medical as the organization’s primary revenue pillars. A significant commonality among these sectors is the dominance of the GTX Pro, which consistently records the highest sales volume. The concentration of revenue in these verticals can be attributed to high opportunity density, suggesting either a profound product-market fit driven by industry-specific demands or a highly effective, targeted prospecting strategy by the sales force.

Furthermore, a comparative analysis of monthly performance reveals that these top-tier sectors are characterized by revenue stability. While lower-performing sectors, such as Employment, exhibit volatile "peaks and troughs," the Retail and Technology sectors maintain a consistent volume of closed-won opportunities. This steadiness indicates that sector success is predicated on both high lead volume and predictable monthly conversion rates.

**Pipeline Dynamics and Operational Bottlenecks**

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
