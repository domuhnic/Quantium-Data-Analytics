# Quantium-Data-Analytics

# Project Background
You are part of Quantium’s retail analytics team and have been approached by your client, the Category Manager for chips, who wants to better understand the types of customers who purchase chips and their purchasing behaviour within the region.

The insights from your analysis will feed into the supermarket’s strategic plan for the chip category in the next half year.

Insights and recommendations are provided on the following key areas:

Pack Sizes: Focus more on products 175 grams or less.
Top Brands: Increase production of brands like Kettle and consider the removal of poor performing brands such as Cheetos.
Lifestage: Target younger populations to capture a large segment of potential customers.
Trial Stores: Changes to Store 77 should be applied since it outperformed its benchmark significantly.

# Data Structure & Initial Checks

We are working with a dataset consisting of 260k+ records along with another dataset consisting of customer info. We first clean the data by: ensuring data types are correct, removing outliers, pulling and correcting brand names, and finally joining the two datasets.

# Executive Summary

## Overview of findings

- Products less than or equal to 175 grams tend to perform better in terms of sales
- Large drop-off in sales during February of 2019 before reaching a yearly high in March
- Top brand is Kettle, followed by Doritos and Smiths
- Older customers account for over half our sales
- Mainstream customers make up nearly 39% of total sales

- Trial store 77 outperformed its control store (41). Store 77 saw an increase in sales during March while store 41 had a decrease in sales
- Trial store 88 and control store 201 were very similar, however store 88 saw slightly greater sales figures over the 3-month period
- Trial store 86 and control store 231 took identical paths, but store 231 outperformed store 88 in sales

<img width="897" height="503" alt="image" src="https://github.com/user-attachments/assets/e433f85a-45c8-4a31-ae4c-02697d948915" />
<img width="883" height="501" alt="image" src="https://github.com/user-attachments/assets/f0d8df25-0c5f-4b41-8d12-f1bccffb3783" />

# Insights Deep Dive
### Pack Sizes:

<img width="907" height="520" alt="image" src="https://github.com/user-attachments/assets/85a2139b-27db-4782-9cbc-05caea0d0623" />

We can see that our best performing pack size is 175 grams. Everything under that size performs fairly well. Anything greater than 175 and less than 250 grams performs poorly. Sales are decent for anything above 250 grams, but insignificant compared to products 175 grams or less.


### Top Brands:
<img width="904" height="513" alt="image" src="https://github.com/user-attachments/assets/095032ec-dcb8-4324-a4ab-0fa29d9a73ce" />

Our top performing brand by a large margin is Kettle, followed by Doritos, Smiths, and Pringles. Brands like Burger, French, and Sunbites perform very poorly, not even reaching $10k in sales. We must consider discontinuing poor-performing products.


### Lifestage:
<img width="908" height="522" alt="image" src="https://github.com/user-attachments/assets/2d9df145-2ce5-494d-8c95-40ae14f302b2" />
<img width="911" height="516" alt="image" src="https://github.com/user-attachments/assets/380da51c-2280-4b64-90e3-7fd2f6cf6654" />
<img width="910" height="520" alt="image" src="https://github.com/user-attachments/assets/72f02c69-1979-41e1-a71c-e86bc9419bf5" />

The older population makes up over half of our sales. The younger population still makes up a considerable amount of our customers, and it may be worth targeting that segment. I would also like to point out that mainstream customers are our largest segment of customer type and account for nearly 39% of our sales.


### Trial Stores:
<img width="1003" height="356" alt="image" src="https://github.com/user-attachments/assets/8af66c3b-b104-464d-a278-396b7124321d" />

The only significant change was with trial store 77. It outperformed its benchmark significantly in March. The other trial stores either slightly outperformed or underperformed the control stores.

# Recommendations:
Based on the insights and findings above, we would recommend the Category Manager to consider the following:

We recommend focusing on products under 175 grams, increase production of Kettle chips, focus on mainstream, younger customers. Changes made to trial store 77 should be applied to others, while changes to 86 should be reverted.

In terms of sales, our smaller products tend to perform better. Brands like Kettle, Doritos, and Smiths are very successful while brands like Burger are not selling well. Consider discontinuing products under $10k in sales while ramping up production on our top brands.






