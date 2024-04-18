# Forecasting covid cases in R
I will explore several linear models to forecast COVID-19 cases. The objective is to predict case counts two weeks ahead for all five health authorities.

I have two data sets in my repo, `bc-covid-train` and `bc-covid-test`. Both have 6 variables: HA, date, cases+14, cases+0, cases-7, cases-14. `cases+14` is the response: it is the total number of cases observed in the week ending 14 days after `date`. The other `cases` variables are features: the total number of cases in the week ending on the date, 1 week earlier and 2 weeks earlier.

![Covid cases by Health Authorities](https://github.com/didemch/Forecasting-Covid-Cases/blob/main/Covid%20Cases.png)
