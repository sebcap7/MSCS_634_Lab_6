MSCS_634_Lab_6

Overview

This lab explores market basket analysis using the Online Retail Dataset from the UCI Machine Learning Repository. The Apriori and FP-Growth algorithms were applied to identify frequent itemsets, generate association rules, and compare the performance of both algorithms.

Dataset

Online Retail Dataset
Source: UCI Machine Learning Repository
Transactions Used: United Kingdom transactions only
Basket Matrix Size: 18,668 transactions × 4,188 products
Objectives

Prepare and clean transactional retail data
Discover frequent itemsets using Apriori
Discover frequent itemsets using FP-Growth
Generate association rules using support, confidence, and lift
Compare the performance of Apriori and FP-Growth
Results

Metric	Value
Apriori Runtime	4.36 seconds
FP-Growth Runtime	8.53 seconds
Frequent Itemsets Discovered	368
Association Rules Generated	65
Key Findings

The most frequently purchased products included:

WHITE HANGING HEART T-LIGHT HOLDER
JUMBO BAG RED RETROSPOT
REGENCY CAKESTAND 3 TIER
PARTY BUNTING
LUNCH BAG RED RETROSPOT
Both Apriori and FP-Growth identified the same frequent itemsets when using a minimum support threshold of 2%.

Strong association rules were found among:

ROSES REGENCY TEACUP AND SAUCER
GREEN REGENCY TEACUP AND SAUCER
PINK REGENCY TEACUP AND SAUCER
One of the strongest rules achieved:

Confidence: 70.33%
Lift: 18.68
These results indicate that customers frequently purchase related products together, making the discovered rules useful for recommendation systems and marketing strategies.

Challenges

Managing a dataset containing thousands of unique products.
Installing required Python libraries such as openpyxl and mlxtend.
Cleaning the dataset by removing cancelled transactions and records with missing product descriptions.
Conclusion

Both Apriori and FP-Growth successfully identified meaningful purchasing patterns within the Online Retail dataset. The generated association rules revealed strong product relationships and provided actionable insights into customer purchasing behavior.
