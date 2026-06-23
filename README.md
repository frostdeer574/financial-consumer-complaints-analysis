# financial-consumer-complaints-analysis
This project is dedicated to analyzing consumer complaints on financial products &amp; services for the Bank of America from 2017 to 2023. The dataset used for this project is publicly available on [Maven Analytics](https://mavenanalytics.io/data-playground/financial-consumer-complaints) and was sourced from the Consumer Financial Protection Bureau ([CFPB](https://www.consumerfinance.gov/data-research/consumer-complaints/#download-the-data)).

During the data cleaning process, I have removed the duplicates, ensured there are no incorrect string values in the categorical columns, dealed with missing values, ensured there are no outliers in date columns. As a result, are still left with over 62.5 thousand rows of data.

After conducting the data analysis, we've derived multiple insights:
- Most consumer complaints on financial products & services are related to fraud, incorrect account information, and problems related to deposits and withdrawals.
- Consumers complained the most about checking accounts, general purpose prepaid cards, credit reporting, conventional home mortgage, and refund anticipation checks.
- The frequency of consumer complaints peaks in summer in July, then remains relatively low in winter and autumn.
- On average, it takes companies about 1.2 days to receive consumer complaints from CFPB.
- Companies most frequently responded to consumer problems through providing an explanation or monetary relief.
  - It is worth noting that most companies do not provide a public response to customer's complaints.
- In most cases, companies failed to provide a timely response to issues regarding the usage of debit or ATM cards, information belonging to someone else, unauthorized transaction, and opened accounts as a result of fraud.

**Actionable insights:**
- Improve coordination between CFPB and companies using the services of the Bank of America to increase the rate of timely responses
- Investigate security vulnerabilities related to deposits, credit and debit cards, and checking accounts
- Prepare for higher customer complaint rate before summer and July
- Enforce stricter data verification & validation methods to reduce issues related to fraud and incorrect data.
