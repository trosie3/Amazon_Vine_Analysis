# Amazon_Vine_Analysis

## Overview of the analysis: 
The purpose of this project is to analyze Amazon reviews written by members of the paid Amazon Vine program compared to non-Vine members for bias.

### Results: 
- Total reviews, Vine reviews and non-Vine reviews:

![image](https://github.com/trosie3/Amazon_Vine_Analysis/blob/main/Resources/totalreviews.png)
- Total 5-star reviews, Vine 5-star reviews, and non-Vine 5-star reviews:

![image](https://github.com/trosie3/Amazon_Vine_Analysis/blob/main/Resources/5starreviews.png)
- Percentage of Vine reviews that were 5 stars:

![image](https://github.com/trosie3/Amazon_Vine_Analysis/blob/main/Resources/paid5starpercent.png)
- Percentage of non-Vine reviews that were 5 stars:

![image](https://github.com/trosie3/Amazon_Vine_Analysis/blob/main/Resources/unpaid5starpercent.png)

## Summary: 
Positivity bias - being paid to write a review, leans towards writing more positive reviews.

Potential positivty bias for Amazon Vine Memebers to give a 5-star review is lower than I would have prediicted on my own. Just over 1/3 of Vine reviews were 5-star reviews which does indicate that there is a 1 in 3 chance if someone is paid they are likely to give a 5-star review so some potential positivity bias. However, when compared to unpaid reviewers where just over 1/2 were 5-star reviews, meaning a 1 in 2 chance someone will give a 5-star review when not paid, it appears that a paid reviewer is slightly less likely to give a 5-star review than an unpaid reviewer suggesting less positivity bias. 

#### additional recommended analysis that would likely support the above:
- Percentage of Vine 5-star reviews in all 5-star reviews as well as compared to total reviews. 
  - example of code:
  
  ![image](https://github.com/trosie3/Amazon_Vine_Analysis/blob/main/Resources/otheranalysis_codesample.png)
- Also, might be wise to pull in other datasets for example the two other Books datasets, to see if the pattern is the same there or if the extra data chances the story.
- However if we were to look into data of other star reviews to see if that pattern is similar or different to that of 5-star reviews it is possible to find a different outcome. For example if a Vine reviewer rarely rates anything a 1- or 2- star as compared to non-paid reviewers then perhaps there is stronger coorelation to say ther is positivity bias to give things at least a 3-star since being paid. 

### Resources used:
Data: https://s3.amazonaws.com/amazon-reviews-pds/tsv/index.txt Books_v1_01

Software: Google Colab, AWS, pgAdmin 4, posgres12.8
