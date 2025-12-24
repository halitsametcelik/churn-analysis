📉 Customer Churn Analysis — Telecom Company
1. Business Problem

This dataset belongs to a telecom company providing subscription-based services.
The objective of this analysis is to identify customer behaviors that contribute to churn and to propose actionable business strategies to reduce customer loss.

Understanding the services used by churned customers plays a critical role in identifying the root causes of churn and developing sustainable retention strategies.

2. Dataset Overview

The dataset consists of 7,032 customers and 21 features, including demographic information, subscription details, service usage, payment behavior, and the target variable Churn.

The target variable indicates whether a customer has completely discontinued the service.

3. Initial Data Checks

Initial exploratory checks were conducted to understand the structure and quality of the dataset:

Data types were reviewed and logically validated.

No explicit missing values or extreme anomalies were observed.

Some variables required type validation (e.g., numerical values stored as objects), indicating the dataset may have undergone prior cleaning.

The primary focus of the analysis was placed on the Churn variable and the factors influencing it.

4. Key Insights
4.1 Churn Rate

The churn rate is approximately 26%, meaning more than one quarter of customers are lost.

This level of churn represents a significant business risk, both financially and in terms of customer loyalty.

4.2 Contract Type

Churn is most concentrated among month-to-month subscribers.

Long-term contract customers exhibit significantly lower churn rates.

This suggests that low switching barriers associated with short-term contracts may contribute to customer attrition.

4.3 Monthly Charges

Customers who churn tend to have higher monthly charges compared to retained customers.

While price sensitivity is an important factor, pricing alone does not fully explain churn behavior.

4.4 Service Usage & Perceived Value

A key pattern emerges when analyzing the services used by churned customers:

Churned customers rarely utilize value-added services such as:

Device protection

Online security

Technical support

Automatic backup services

These customers often pay higher prices while using fewer services.

This indicates that churn is strongly influenced by low perceived value, rather than price alone. Customers may not clearly understand what they are paying for, leading to dissatisfaction and eventual churn.

4.5 Revenue Impact

Customer churn corresponds to an estimated $3 million revenue loss, accounting for approximately 17% of total revenue.

This highlights churn as not only a customer experience issue but also a critical financial concern.

5. Business Recommendation

The analysis suggests that customer churn is driven more by perceived value than by pricing alone.

Primary Recommendation:

Improve value communication and value perception instead of relying solely on discounts.

Supporting actions include:

Clearly communicating the benefits of security and protection services.

Encouraging adoption of value-added services through targeted campaigns.

Promoting longer-term subscription plans to reduce switching flexibility.

Designing packages that align pricing with clearly communicated service value.

By focusing on why the service is worth its price, the company can reduce churn sustainably without engaging in aggressive discounting.

6. Conclusion

This analysis demonstrates that customer churn is a multi-dimensional problem driven by pricing, contract flexibility, and most importantly, perceived service value. Addressing churn through value-focused strategies offers a more sustainable long-term solution than price reductions alone.


🤖 Use of AI Assistance

During the data exploration phase, AI-based tools were used as a support mechanism to improve productivity and analytical clarity.

AI assistance was utilized for:

Interpreting exploratory data analysis results

Improving code readability and structure

All analytical decisions, feature interpretations, and business conclusions were made by the author.

This approach reflects real-world data analysis workflows, where AI is increasingly used to augment—not automate—decision-making processes.
