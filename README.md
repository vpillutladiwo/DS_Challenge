# DS_Challenge

At diwo, you'll almost always be working with a diverse team, often including business analysts, engineers, and product managers. The ability to not just complete data science work, but also to explain and present your work is important.

With that in mind, please deliver your answers as if you were handing off work to another data scientist joining your team. Tying together your intent, code, analysis and results is the goal.

The following artifacts are valued:

* explanations of your intent, methods, conclusions and any assumptions

* clear, documented, and well-structured code

* instructions for running your code

* methods you attempted that didn't work

* ideas you didn't have time to complete but would have done with more time

* pertinent visualizations


While we recognize sharing code is a common practice in the open source community, we ask that you refrain from sharing any part of this interview submission publicly to ensure a fair and equal interview process for all.

We ask that any code written by others is sourced/cited appropriately. We are excited to review your work and your interpretation of the data.


Data Science Challenge: Card Transactions!

This coding and analysis challenge is designed to test your skill and intuition analyzing real[-ish] world data. For the challenge, we will use credit card transactions data. Note that this dataset loosely resembles real transactional data from credit card customers, but the entities and relations within are purely fictional. No persons, places, or things lost their identity in the making of this dataset.

Required Questions: Please answer completely all four required questions.

**Question 1: Load

Programmatically download and load into your favorite analytical tool the transactions data. This data, which is in line-delimited JSON format, can be found here

Please describe the structure of the data. Number of records and fields in each record?

Please provide some additional basic summary statistics for each field. Be sure to include a count of null, minimum, maximum, and unique values where appropriate.


**Question 2: Plot

Plot a histogram of the processed amounts of each transaction, the transactionAmount column.

Report any structure you find and any hypotheses you have about that structure.


**Question 3: Data Wrangling - Duplicate Transactions

You will notice a number of what look like duplicated transactions in the data set. One type of duplicated transaction is a reversed transaction, where a purchase is followed by a reversal. Another example is a multi-swipe, where a vendor accidentally charges a customer's card multiple times within a short time span.

Can you programmatically identify reversed and multi-swipe transactions?

What total number of transactions and total dollar amount do you estimate for the reversed transactions? For the multi-swipe transactions? (please consider the first transaction to be "normal" and exclude it from the number of transaction and dollar amount counts)

Did you find anything interesting about either kind of transaction?


**Question 4: Model

Fraud is a problem for any bank. Fraud can take many forms, whether it is someone stealing a single credit card, to large batches of stolen credit card numbers being used on the web, or even a mass compromise of credit card numbers stolen from a merchant via tools like credit card skimming devices.

Each of the transactions in the dataset has a field called isFraud. Please build a predictive model to determine whether a given transaction will be fraudulent or not. Use as much of the data as you like (or all of it).

Provide an estimate of performance using an appropriate sample, and show your work.

Please explain your methodology (modeling algorithm/method used and why, what features/data you found useful, what questions you have, and what you would do next with more time)

Thank you very much for your efforts! We look forward to reviewing your insights!
