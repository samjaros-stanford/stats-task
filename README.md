
# Stats Task

This repository provides data and instructions for an applied statistical abilities test.

## Overview

You will be required to complete all of the questions in 24 hours. You may use R or Python to complete this task including any publicly available packages. Please make sure to read the entire question and answer all parts. When asked to explain your findings, please write out one or two sentences as though you are reporting your findings to a general audience in a scientific article. Make sure to put the results in context (i.e. "This statistically significant p-value means we found blood pressure decreases the risk of heart disease."). Please document your code and name variables appropriately.

When you are finished, please provide your code, any figures you generate, and your written answers. You may combine these into one document (like via RMarkdown) or turn them in separately.

## Data

The questions will require two data sets:

`MOUD_data.csv`

-   These data come from a hypothetical study of the effect of Medication for Opioid Use Disorder on withdrawal symptoms and subsequent relapse.

-   `id` is a unique patient identifier.

-   `sex` is the patient's sex.

-   `race` is the patient's race.

-   `tx_group` is the patient's treatment group, either taking MOUD ("MOUD") or not taking MOUD ("no_MOUD").

-   `withd_scale` is an invented scale describing the patient's withdrawal symptoms. 0 on this scale is no symptoms, and 10 on this scale is the most severe symptoms.

-   `did_relapse` is an indicator of whether the patient relapsed to Opioid Use Disorder while in recovery, either relapsed ("Relapse") or did not relapse ("No Relapse").

`sleep_data.csv`

-   These data come from the `lme4` package and include a hypothetical sleep study where patients are restricted to three hours of sleep for multiple nights and their reaction times are measured.

-   `Subject` is a unique patient identifier.

-   `Days` is the number of days of sleep deprivation.

-   `Reaction` is the patient's reaction time in milliseconds.

## Question 1

Using the MOUD data set, please run a statistical test to determine the association between MOUD treatment and reported withdrawal symptoms. What is the relationship between treatment group and reported withdrawal scale? How would you report this relationship in words in a scientific article?

## Question 2

Using the MOUD data set, please create a figure displaying the difference in withdrawal scale between the MOUD treatment and no MOUD treatment groups. The figure should be ready to hand off to a journal for publication and needs a title and properly labelled axes.

## Question 3

Using the MOUD data set, please run a statistical test to determine the association between reported withdrawal symptoms and the likelihood of relapse. What is the relationship here? How would you report this relationship in words in a scientific article?

## Question 4

Using the sleep data set, please run a statistical test to determine the association between days with reduced sleep and reaction time. Please make sure your chosen method takes into account that there are multiple measurements for each person. What is the relationship between these? How would you report this relationship in words in a scientific article?
