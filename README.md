# Project-1-Investigate-a-dataset

## Attracting Developers to a Startup with technology

This repository contain the below files:

*  Investigating-Dataset.ipynb

This is the Jupyter notebook file that contain the analysis and the findings

*  survey_results_public_2017.csv

The Data set that is used for this project


### Project Description and motivation:

This project uses the result of the 2017 developer survey of stackoverflow and asks some questions that could be useful for people who want to start a tech company and their aim is to offer technologies and practices that are associated with higher job satisfaction. After taking a look at the dataset I came up with the following 3 questions.

* #### Which Programming Languages Have Higher Job Satisfaction?
* #### What are the top 5 used frameworks by Companies by size?
* #### Which performance metric is well liked by developers?

I imported Pandas and Numpy for data manipulation and to benefit from Dataframe and Numpy structures and functions. Moreover, I imported Matplotlib and seaborn for the purpose of data visualization.

I had to drop the rows missing my columns of interest which may lead to bias in the data:

* JobSatisfaction
* HaveWorkedLanguage
* HaveWorkedFramework
* MetricAssess

My clean up involved separating the semicolon separated values and counting them individually. Sometimes I opted to explode the rows, based on the context. I have also changed the data type of CompanySize from string to Categorical so it's easier to sort and manipulate the data.

My findings for those questions are:

* 1. Programmers who use a more niche programming languages seem to have a better overall satisfaction
* 2. Companies of all sizes are using popular newer frameworks with large support and community engagement
* 3. Developers seem to like their assessment to be provided by their higher ups rather than other metrics

So with all these findings what could we conclude? I'm not sure but a smaller company (<500 Employees) that uses a framework that's built on Node.JS and leverages Typescript might be a good place to work in.
