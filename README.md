# E-commerce User Behavior Analysis 📊
## Analysis of data from a furniture store website using SQL and LookerStudio

This project is ***based on an e-commerce database*** hosted in BigQuery. The dataset was generated through a SQL query and visualized using Looker Studio.

📌 The ***primary goal*** is to gather and analyze data to understand the dynamics of account creation, user engagement with emails (sending, opening, clicking), and evaluate user behavior across key attributes such as email sending interval, account verification status, and subscription preferences.

The data-driven analysis will enable the comparison of activity between countries, the identification of key markets, and the segmentation of users by various parameters.

***Tools & Technologies:*** SQL, BigQuery, Looker Studio

### Structure of the dataset:
- `date`;
- `country`;
- `send_interval` - sending interval;
- `is_verified` - whether the account is verified or not;
- `is_unsubscribed` - whether the subscriber has unsubscribed;
- `account_cnt` - number of created accounts;
- `sent_msg` - number of sent messages;
- `open_msg` - number of opened messages;
- `visit_msg` - number of visits to messages;
- `total_country_account_cnt` - the total number of created subscribers by country;
- `total_country_sent_cnt` - the total number of sent emails by country;
- `rank_total_country_account_cnt` - ranking of countries by the number of created subscribers;
- `rank_total_country_sent_cnt` - ranking of countries by the number of sent emails.

### The main metrics for accounts and emails, calculated by sections:
- `date` - for accounts - the date of account creation, for emails - the date of email sending;
- `country` ;
- `send_interval` - the sending interval set by the account;
- `is_verified` - whether the account is verified or not;
- `is_unsubscribed` - whether the subscriber has unsubscribed.

### Looker Studio Visualization
[Link to Dashboard](https://lookerstudio.google.com/reporting/7e6fcfad-794b-46cd-a3eb-3c4d7b410c41)
