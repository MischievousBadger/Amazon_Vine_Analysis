# Amazon_Vine_Analysis

## Overview/Purpose of the Analysis
The purpose of this analysis is to successfully analyze Amazon reviews written by members of the (paid) Amazon Vine program, where consumers are paid by manufacturers to write a review for their products. Using the Amazon Vine outdoors products reviews dataset, PySpark, AWS RDS, and pgAdmin, the dataset will be extracted, transformed and loaded to be analyzed to determine if there is bias towards favorable reviews from Vine members vs. unpaid, non-Vine reviews.  

## Results

- Number of Vine (paid) reviews - 107
- Number of non-Vine (unpaid) reviews - 39,869

![Screen Shot 2022-04-15 at 9 47 18 PM](https://user-images.githubusercontent.com/90944163/163658581-a2b6c203-b544-4a22-b6e1-1e8687a4a10d.png)

- Number of 5-star Vine (paid) reviews - 56
- Number of 5-star non-Vine (unpaid) reviews - 21,005

![Screen Shot 2022-04-15 at 9 49 34 PM](https://user-images.githubusercontent.com/90944163/163658653-8c287f60-e96f-4184-b59c-485c37a2012e.png)

- Percentage of 5-star Vine (paid) reviews - 52.34%
- Percentage of 5-star non-Vine (unpaid) reviews - 52.69%

![Screen Shot 2022-04-15 at 9 50 48 PM](https://user-images.githubusercontent.com/90944163/163658687-4c7293df-93b9-45bd-80e6-e6d98beb213b.png)

## Summary
Based on the results noted above, there does not appear to be positivity bias for the reviews in the Vine program.  The percentage difference in 5-star reviews between paid and unpaid is 0.35%, with the unpaid reviews having the greater percentage of 5-star reviews. However, this is only based on one review dataset (outdoors equipment).  A larger study sampling more review datasets would be useful to further support a hypothesis that paid Vine reviews do not show positivity bias. 
