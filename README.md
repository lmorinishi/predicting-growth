# predicting-growth
Here I predict user churn and future growth, using information from 9 months of user history. This site is a work in progress, as I clean up my original notebooks for human readability. Check back for updates!

### Background

Given a dataset of user transaction history from CompanyX over time, I wanted to classify users in ways that can be useful for Sales, Product, and other teams.

Ideally our segmentation will identify:

1. **users that churned** so we understand how we can better help them,
2. **consistent and productive users of CompanyX** so we understand why CompanyX works for them, and
3. **users with potential to grow** so we know where to focus next.


### What to look for
**Engagement:** It would be valuable to detect user churn before it happens. Where are the greatest dropoffs for users and how can we avoid them? This may have implications for product design, optimizing pricing to beat competition, or changing how and when we engage with users over time.

**Transactions throughout the day:** Looking at the number of transactions throughout the course of a day may reflect the time zone of the user's target market. Adoption of CompanyX's products in a particular geographical region may have implications for product development (ex: product localization/language).

