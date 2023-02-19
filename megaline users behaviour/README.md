# Goal
This study is aimed to find out, which prepaid plan of the telecom company Megaline brings in more revenue and should be advertized more, using information on behaviour of 500 clients (who the clients are, where they're from, which plan they use, and the number of calls they made and text messages they sent in 2018).

# Data description 

### Plans subset:
`plan_name` — calling plan name

`usd_monthly_fee` — monthly charge in US dollars

`minutes_included` — monthly minute allowance

`messages_included` — monthly text allowance

`mb_per_month_included` — data volume allowance (in megabytes)

`usd_per_minute` — price per minute after exceeding the package limits (e.g., if the package includes 100 minutes, the 101st minute will be charged)

`usd_per_message` — price per text after exceeding the package limits

`usd_per_gb` — price per extra gigabyte of data after exceeding the package limits (1 GB = 1024 megabytes)

### Users subset

`user_id` — unique user identifier

`first_name` — user's name

`last_name` — user's last name

`age` — user's age (years)

`reg_date` — subscription date (dd, mm, yy)

`churn_date` — the date the user stopped using the service (if the value is missing, the calling plan was being used when this database was extracted)

`city` — user's city of residence

`plan` — calling plan name

### Calls subset
`id` — unique call identifier

`call_date` — call date

`duration` — call duration (in minutes)

`user_id` — the identifier of the user making the call

### Messages subset
`id` — unique text message identifier

`message_date` — text message date

`user_id` — the identifier of the user sending the text

# Libraries used
pandas, numpy, matplotlib, seaborn, scipy
