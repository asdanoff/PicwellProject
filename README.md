# Introduction to Pandas with the Medical Expenditure Panel Survey (MEPS) Data

## Background

##### MEPS
The [MEPS](https://meps.ahrq.gov/mepsweb/), as decsribed on its website, is "a set of large-scale surveys of families and individuals, their medical providers, and employers across the United States. MEPS is the most complete source of data on the cost and use of health care and health insurance coverage."

MEPS currently has two major components: the Household Component and the Insurance Component. The Household Component provides data from individual households and their members, which is supplemented by data from their medical providers. The Insurance Component is a separate survey of employers that provides data on employer-based health insurance.  For our purposes, we will focus on the Household Component.

The Household Component (HC) collects data from a sample of families and individuals in selected communities across the United States, drawn from a nationally representative subsample of households that participated in the prior year's National Health Interview Survey (conducted by the National Center for Health Statistics).

During the household interviews, MEPS collects detailed information for each person in the household on the following: demographic characteristics, health conditions, health status, use of medical services, charges and source of payments, access to care, satisfaction with care, health insurance coverage, income, and employment.

The panel design of the survey, which features several rounds of interviewing covering two full calendar years, makes it possible to determine how changes in respondents' health status, income, employment, eligibility for public and private insurance coverage, use of services, and payment for care are related.


##### Pandas
Pandas is a powerful and widely-used python library for data manipulation and analysis.  There is extensive documentation and debugging support online.  You will use this extensively for this project.

## Getting Started with Pandas and MEPS
The raw data available on the MEPS website is rather cumbersome to work with (e.g. columns aren't labeled, and you determine field names and values by cross-referencing a codebook that changes year over year).  The first step will be getting familiar with the data and basic python data manipulation in the [data extraction notebook](./MEPSDataExtraction.ipynb).

Once you have completed this exercise, you can move on to data analysis and visualization notebook [here](./PandasDataExploration.ipynb).
# PicwellProject
