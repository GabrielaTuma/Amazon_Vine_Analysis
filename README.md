# Amazon_Vine_Analysis
Module 16 - Big Data

## Project Overview

The goal of this project is to analyze Amazon reviews written by members and non-members of the paid Amazon Vine program. 

The Amazon Vine program is a service that allows manufacturers and publishers to receive reviews for their products. Companies like SellBy pay a small fee to Amazon and provide products to Amazon Vine members, who are then required to publish a review.

SellBy stakeholders are looking for an analysis that will determine if there is any bias toward favorable reviews from Vine members in the dataset. In this particular analysis we are going to use reviews provided by Amazon AWS regarding **toys**:

[Amazon Review Datasets](https://s3.amazonaws.com/amazon-reviews-pds/tsv/index.txt) 


#### Deliverable 1
- [x] 1. An Amazon Review dataset is extracted as a DataFrame
- [x] 2. The extracted dataset is transformed into four DataFrames with the correct columns
- [x] 3. All four DataFrames are loaded into their respective tables in pgAdmin

[Amazon_Reviews_ETL.ipynb](https://github.com/GabrielaTuma/Amazon_Vine_Analysis/blob/b311d2955b6a8644ce6760b5d639bfea5727756e/Amazon_Reviews_ETL.ipynb) 



#### Deliverable 2
- [x] 1. There is a DataFrame or table for the vine_table data using one of three methods
- [x] 2. The data is filtered to create a DataFrame or table where there are 20 or more total votes
- [x] 3. The data is filtered to create a DataFrame or table where the percentage of helpful_votes is equal to or greater than 50%
- [x] 4. The data is filtered to create a DataFrame or table where there is a Vine review
- [x] 5. The data is filtered to create a DataFrame or table where there isn’t a Vine review
- [x] 6. The total number of reviews, the number of 5-star reviews, and the percentage 5-star reviews are calculated for all Vine and non-Vine reviews

[Vine_Review_Analysis.ipynb](https://github.com/GabrielaTuma/Amazon_Vine_Analysis/blob/b311d2955b6a8644ce6760b5d639bfea5727756e/Vine_Review_Analysis.ipynb) 


#### Deliverable 3
- [x] 1. There is a title, and there are multiple sections
- [x] 2. Each section has a heading and subheading
- [x] 3. Links to images are working, and code is formatted and displayed correctly
- [x] 4. The purpose of this analysis is well defined
- [x] 5. There is a bulleted list that addresses the three questions for unpaid and paid program reviews
- [x] 6. The summary states whether or not there is bias, and the results support this statement
- [x] 7. An additional analysis is recommended to support the statement









## Resources 

- Sof

## Linear Regression to Predict MPG


<p align="center">
<kbd>
  <img src="https://github.com/GabrielaTuma/Amazon_Vine_Analysis/blob/b311d2955b6a8644ce6760b5d639bfea5727756e/Resources/Challenge%2016%20Images%20/percentages.png">
</kbd>  &nbsp;
</p>


The report should contain the following:

Overview of the analysis: Explain the purpose of this analysis.

Results: Using bulleted lists and images of DataFrames as support, address the following questions:

How many Vine reviews and non-Vine reviews were there?
How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?
What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?
Summary: In your summary, state if there is any positivity bias for reviews in the Vine program. Use the results of your analysis to support your statement. Then, provide one additional analysis that you could do with the dataset to support your statement.

