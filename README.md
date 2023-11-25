This project focuses on analyzing the user churn rate for a streaming video startup. The main objective is to gain insights into user churn behavior and provide valuable information for decision-making.

The project involves several key tasks, such as determining the company’s operating duration, identifying different user segments, analyzing the overall churn trend since the startup’s launch, and comparing churn rates between these user segments.


The marketing department is particularly interested in comparing churn rates for users acquired through two distinct channels. To conduct the analysis, a dataset containing subscription data is used.

The dataset contains one SQL table, subscriptions. Within the table, there are 4 columns:

id – the subscription id
subscription_start – the start date of the subscription
subscription_end – the end date of the subscription
segment – this identifies which segment the subscription owner belongs to


A minimum period for a subscription is 31 days, so a user can never start and end their subscription in the same month.


The results of the query indicate the churn rates for both segments and highlight fluctuations over time. It also draws attention to a significant increase in churn rate for both segments in March 2017, suggesting a potential issue that requires further investigation by the decision-makers. The findings emphasize the importance of addressing engagement levels for segment 87 and exploring new strategies to retain customers in that segment.
