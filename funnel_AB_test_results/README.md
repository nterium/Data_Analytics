# A/B-test results assessment

NOTE: The information inside notebook is in Russian but you can assess the code at least. The translation is in process.

## The purpose

The A/B-test was conducted to assess the effectiveness of the new payment funnel. 

The assessment included:

1. Assessment of conducting the test in accordance with the technical task
2. Assessment of test correctness 
3. Statistical processing and analysis of test results
4. Conclusions and recommendations

## The result

Generally, the test showed that the new recommender system had a negative impact to payment funnel, and should not be applied, however, due to the test discrepancy to the technical task as well as some data oddities, intersection with marketing activities, Cristmas and New Year the obtained results should not be trusted. It is strongly recommended to repeat the A/B-test.

Recommendations:

- try to avoid test intersection with marketing activities and hollidays: it can affect users behavior
- check spliting users between parallel A/B-tests
- check test compliance to technical task

## Data

The following data are available:

**1. New users data:**

- user ids
- registration date
- region
- device

**2. New users' actions data:**

- user ids
- date and time of purchase
- type of event
- additional information (f.e, sum in dollars).

**3. Test participants data:**

- user ids
- test name
- test group.

**4. Marketing activities data:**

- marketing activity name
- region
- start date of marketing activity
- end date of marketng activity

## Python Libraries

- pandas
- numpy
- seaborn
- matplotlib.pyplot
- plotly
- math
- scipy
