Project: Option 3

Imagine you are working at a large dating app. In addition to basic features, the app also offers a premium subscription that provides access to a number of important additional features. An A/B test was conducted in which the premium subscription price* for new users from several countries was changed when purchasing through two new payment systems. The cost of the trial period remained the same.

Check:

Whether the experiment was successful overall.
Analyze whether the innovation makes sense among any specific user groups.
*The subscription fee is charged monthly until the user cancels it.

Data

There are three groups in total: test, control_1, and control_2. For each of them:

users_*.csv – user information:

uid – user identifier

age – age

attraction_coeff – attractiveness coefficient (from 0 to 1000, (\frac{likes}{views}*1000))

coins – number of coins (in-app currency)

country – country

visit_days – days after registration when the user visited the app (e.g., on day 1, then on day 7)

gender – gender

age_filter_start – search filter, minimum value

age_filter_end – search filter, maximum value

views_count – number of received ratings

was_premium – whether the user has ever been premium (either trial premium status or purchased)

is_premium – whether the user is currently premium

total_revenue – normalized revenue

transactions_*.csv – user payment information:


uid – user identifier

country – country

joined_at – registration date and time

paid_at – purchase date and time

revenue – normalized revenue

payment_id – payment identifier

from_page – source page from which the user navigated to the payment page

product_type – product type (trial_premium – trial premium subscription, premium_no_trial – premium subscription without trial, coins – subscription for in-app currency, other_type – other)
