# Stats Task

This repository provides data and instructions for an applied statistical abilities test.

## Overview

You will be required to complete all of the questions in 24 hours. You may use the software of your choice to complete this task including any publicly available packages. Please make sure to read the entire question and answer all parts. When asked to explain your findings, please write out one or two sentences as though you are reporting your findings to a general audience in a scientific article. Make sure to put the results in context (i.e. “This statistically significant p-value means we found blood pressure decreases the risk of heart disease.”). Please document your code and name variables appropriately.

When you are finished, please provide your code, any figures you generate, and your written answers. You may combine these into one document or turn them in separately.

## Data

The questions will require two data sets:

`MOUD_data.csv` - These data come from a hypothetical study of the effect of Medication for Opioid Use Disorder on withdrawal symptoms (withd_scale, higher is more symptoms) and subsequent relapse (did_relapse).

`sleep_data.csv` - These data come from the `lme4` package and include a hypothetical sleep study where patients are restricted to three hours of sleep for multiple nights and their reaction times are measured. The first reaction time has no sleep restriction.

## Question 1

Most academic papers create a “Table 1” to describe what participants are in their study. They normally consist of the different treatment groups across the columns and then relevant characteristics as rows. Here are a few examples: [Example 1](https://pmc.ncbi.nlm.nih.gov/articles/PMC4478141/#T1), [Example 2](https://pmc.ncbi.nlm.nih.gov/articles/PMC4866634/#T1).

Examine the MOUD data set. Clean any data points that seem to be errors, documenting the choices you make. Calculate the relevant data points in code and put them in a document as a Table 1.

## Question 2

Using the MOUD data set, please create a figure displaying the difference in withdrawal scale between the MOUD treatment and no MOUD treatment groups. The figure should be ready to hand off to a journal for publication.

## Question 3

Using the MOUD data set, please run a statistical test to determine the association between reported withdrawal symptoms and the likelihood of relapse. What is the relationship here? How would you report this relationship in words in a scientific article?

## Question 4

Using the sleep data set, pivot the data so that each row is one person and the columns are the number of nights of sleep deprivation with reaction times filled in as the values. Some participants will have missing reaction times for some of the days. Print the first five rows of this data set.

Use a t-test to compare the baseline reaction times to nine nights of sleep deprivation.

## Question 5

Using the sleep data set, please run a statistical test to determine the association between days with reduced sleep and reaction time. Please make sure your chosen method takes into account that there are multiple measurements for each person. What is the relationship between these? How would you report this relationship in words in a scientific article?

## Question 6

Imagine you are tasked with creating a data repository for two ongoing research projects. These projects collect data on some shared measures (e.g. age, gender, and race) and some project-specific measures (e.g. one studies depression, the other anxiety). You get data from your collaborators in two formats: one project collects and shares data via Qualtrics, and the other sends you Excel files via email. The repository must meet the following requirements:

1.  Centralized storage: All data must be located in one secure, central location.

2.  Secure access and ability to share: Data must be accessible to external collaborators with appropriate permissions.

3.  Harmonization: Shared measures across both projects must be harmonized for consistency.

4.  Tracking and Inventory: A system of tracking which measures are included and the dates of the most recent updates.

In a short paragraph, please explain how you would approach this task. Feel free to include questions or concerns that you would ask your study manager, and how might their responses change your plan.
