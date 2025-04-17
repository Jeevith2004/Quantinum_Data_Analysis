<h1>Quantinum_Data_Analysis</h2>

<h2> Problem Background </h2>

A dataset of retail sales used by the company Quantinum to Conduct analysis on your client's transaction dataset and identify customer purchasing behaviours to generate insights and provide commercial recommendations.

<h2> Data Structure & Initial checks </h2>

![Screenshot 2025-04-17 233604](https://github.com/user-attachments/assets/dd97d172-d09e-4b26-8a21-1a5e5dd516f3) 

![Screenshot 2025-04-17 233613](https://github.com/user-attachments/assets/e7785d0d-1921-486d-93d1-4a99fb3085fa)





<h2> Executive Summary </h2>

![Screenshot 2025-04-17 212749](https://github.com/user-attachments/assets/fc0309d9-0968-4e9f-a32f-3b38a0b6be9e)


- The executive summary dashboard presents a comprehensive view of overall sales performance. The __total sales recorded stand at 1.93 million, reflecting a strong revenue generation__ over the selected period. A 
  total of 505,000 units were sold, highlighting a healthy sales volume. The customer base is also impressive, with over __72,640 loyalty cardholders, suggesting a strong, engaged, and trackable audience. Among 
  all product categories, the Kettle brand emerges as the top-selling brand, showing clear brand preference, __while the 175g product size is the most popular, indicating an ideal pack size that resonates well 
  with customer buying patterns__.

- When analyzing the sales trend over time (from July 2018 to May 2019), there are __noticeable peaks in January and March 2019, possibly due to promotions or seasonal demand. However, there’s a dip in February 
  and April__, suggesting possible seasonality effects or gaps in marketing strategy. The dotted trendline indicates a gradual decline in overall sales over time, which may be an early signal of saturation or 
  competitive 
  pressure.

  <h2> Customer Analysis </h2> 

![Screenshot 2025-04-17 223550](https://github.com/user-attachments/assets/9fd956e8-3bb2-4987-989e-2fbae461008b)

  - This dashboard provides a deeper dive into customer behavior and segmentation, particularly across different lifestage groups and their impact on total sales. The “Contribution to Total Sales” chart shows a 
    clear dominance of mainstream and budget segment customers across most lifestage groups. Notably, __older families and retirees contribute significantly through mainstream purchases__, whereas premium 
    purchases are relatively low across all segments. This aligns with the previous insight that premium sales are underperforming. Among all groups, __young singles/couples and midage singles/couples show a 
    higher share of budget and mainstream products, indicating possible price sensitivity in these demographics__.

   - In the “Lifestage-wise Buying Behavior” visual, the average product quantity per transaction is relatively consistent across groups, hovering just below 2 units. However, there is a significant drop in 
    transaction count among new families and young singles/couples, with new families recording the lowest number of transactions, suggesting lower engagement or lesser targeting of this group. Interestingly, 
    older families and retirees exhibit both high transaction counts and consistent product quantity, making them valuable segments for retention and upselling efforts.

  - The “Repeat Customers” trend shows a stable and slightly upward trajectory, with the __number of repeat customers ranging between 16K to 17.5K over the year__. There’s a notable dip in February, possibly due 
     to  seasonal slowdowns, but it recovers steadily. __December records the highest repeat customer count, likely due to holiday season purchases or end-of-year campaigns__. This shows customer loyalty is 
     relatively well maintained, but there's room to grow by turning occasional buyers into loyal ones.

- From January to June, returning customers consistently outnumber new customers, __indicating a loyal customer base that repeatedly engages with the brand__. However, a significant change occurs in July, where 
  new customer count sharply rises, surpassing returning customers. This spike suggests a successful marketing campaign, seasonal promotion, or product launch that attracted a large influx of first-time buyers 
  during that month.

- Following this peak, new customer numbers decline steadily from August onward, while returning customers gradually increase again, regaining dominance by October and maintaining it through December. This trend 
 implies that although __many new customers were acquired mid-year, a considerable portion converted into repeat buyers__, contributing to a rise in returning customers later in the year. Overall, the chart 
 reflects a healthy cycle of customer acquisition followed by customer retention, which is vital for long-term business growth

<h2> Product Analysis </h2>

![Screenshot 2025-04-17 223601](https://github.com/user-attachments/assets/1e107504-ee65-4870-8b41-b627d1ab4d97)

- From the "Total Sales by Product Name" chart, it is evident that the top-selling products are quite evenly matched in terms of total sales. Dorito Corn Chip Supreme leads slightly, followed closely by various Smith's Crinkle Chips and Kettle varieties, indicating that customer preferences are spread across a range of popular snack items rather than being concentrated on a single product. This balanced distribution of product sales suggests a healthy and diverse product portfolio with broad customer appeal.

The "Total Sales from Each Store" visualization highlights that some stores significantly outperform others. The top-performing store stands out with total sales around 17.6K, while several others fall closer to 14.5K. The color-coded bar chart (green to red gradient) clearly illustrates this disparity. This performance gap presents an opportunity to explore what successful stores are doing differently—be it through better location, effective promotions, or superior customer service—and to implement similar strategies in lower-performing stores to boost overall revenue.

Lastly, the "Transaction Values" line chart reveals customer activity over time from July 2018 to May 2019. The transaction volume remains relatively stable between 20K and 23K, showing steady engagement. There is a noticeable dip in February 2019, potentially due to seasonal effects or external factors, followed by a strong recovery in March. These patterns suggest that while customer transactions are generally consistent, certain months may require targeted marketing or promotional activities to maintain sales momentum.

<h2> Sales Analysis </h2>

![Screenshot 2025-04-17 225155](https://github.com/user-attachments/assets/f5a1ba98-83c1-4f65-853a-149dcf5fd475)

- From the bar chart at the top center, __Dorito Corn Chip Supreme 380g leads in average sales per transaction, indicating strong preference and possibly higher unit price or volume per purchase__. It records 
 around 12.27 average sales per transaction. Other products like Smiths Crinkle Chips (various flavors) and Cheezels Cheese 330g follow closely with values in the range of 10.3 to 11.5. These __insights can guide 
 bundling strategies or promotional focus__.

- The table on the right lists 16 stores, none of which are underperforming (marked “No” in the Is_Underperforming column).__ Store number 3 and 6 are the top contributors with sales of 12,802.45 and 12,486.90, 
  respectively__. In contrast, __stores like 14 and 16 have much lower sales (<2,000)__, even though they’re not flagged as underperforming, which might require further investigation (e.g., are these newly opened 
  or operating in low-traffic regions?).

This matrix at the bottom provides a deep dive into how different lifestyle segments are contributing to sales for each product:

Top contributing product overall:

-  Dorito Corn Chip Supreme 380g with 39,052 total units.
-  Followed closely by Smiths Crinkle Chip Orgnl Big Bag 380g (36,368) and Smiths Crinkle Chips Salt & Vinegar 330g (34,804).

Top lifestyle groups driving sales:

-  Older Singles/Couples (72,040 units total)
-  Retirees (67,107 units total)
-  These two segments combined are the largest contributors across all products, highlighting their significant purchasing power in this category.

Lower contribution segments:

-  New Families (9,245) and Young Singles/Couples (48,754), though smaller, still represent important demographics for potential growth.

  <h2>Recomendation:</h2>

  - Increase efforts to promote premium products (cross-selling, bundling, loyalty bonuses) to close the 4.28% gap from the goal. Focus marketing around Kettle, the top-performing brand—consider limited-time 
    offers or exclusive packs.
    
  - Personalize campaigns for underperforming segments like New Families—bundle smaller pack sizes or child-friendly flavors.For top-performing lifestages like Older Families and Retirees, consider loyalty 
    programs or subscription models to increase retention.

-   Offer exclusive deals or early access to premium customers to drive volume.Experiment with product samples or trials in the budget segment to upgrade some customers to premium.

-  Set up automated re-engagement campaigns (email/SMS offers) targeting new customers post first purchase.Use referral incentives to keep the new customer inflow steady beyond promotional months like July.

-  Run a store-level diagnostic—analyze store traffic, regional preferences, stock variety.For lower-volume stores, consider inventory optimization or local promotional efforts to boost numbers.

-  Feature bestsellers in front-of-store displays, online banners, or combo packs.Use lower-performing products in bundle offers with top-sellers to clear stock and boost exposure.

 -  Run targeted campaigns for underperforming lifestyles on digital platforms with personalized messaging.Collaborate with retailers to host lifestyle-based promotions (e.g., “Family Week” or “Singles’ Value 
    Packs”).


