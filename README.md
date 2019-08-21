<img src="https://bit.ly/2VnXWr2" alt="Ironhack Logo" width="100"/>

# What about traffic accidents?
*Emanuele De Sanctis and Miquel Petit Sierra*

*Bootcamp in Data Analytics, Full-Time, June 2019*

## Content
- [Project Description](#project-description)
- [Hypotheses / Questions](#hypotheses-/-questions)
- [Dataset](#dataset)
- [Cleaning](#cleaning)
- [Analysis](#analysis)
- [Model Training and Evaluation](#model-training-and-evaluation)
- [Conclusion](#conclusion)
- [Future Work](#future-work)
- [Workflow](#workflow)
- [Organization](#organization)
- [Links](#links)

<a name="project-description"></a>

## Project Description
Even though technology improves continuously, specially in the car industry, traffic accidents are one of the main death causes in our society. Given the importance of the topic, we've chosen to analyze a dataset filled with 1.6 million UK traffic accidents with 34 features each.

<a name="hypotheses-/-questions"></a>

## Hypotheses
* The severity of an accident is predictable with Machine Learning using other attributes.
* During the night the accidents tend to be more severe.
* During the weekend (Friday - Sunday) the number of accidents increases.

<a name="dataset"></a>

## Dataset
* We got our data from Kaggle, concretely from [here](https://www.kaggle.com/daveianhickey/2000-16-traffic-flow-england-scotland-wales).
* Our dataset contains data from 2005 to 2014, in total 1.6 million rows and 34 columns.
* Given the great amount of features, the limit on our analysis is just time.

<a name="cleaning"></a>

## Cleaning
1. First we will explore our data:
- Checking and adjusting dtypes.
- Dealing with null values, we will drop the non-relevant columns with a high amount of null values and the rows for the rest.
- We will also look for outliers, data that does not make sense and could bias our data and results.

<a name="analysis"></a>

## Analysis
* Overview the general steps you will go through to analyze your data in order to test your hypothesis.
* Document each step of your data exploration and analysis.
* Include charts to demonstrate the effect of your work. 
* If you use ML in your final project, describe your feature selection process.

<a name="model-training-and-evaluation"></a>

## Model Training and Evaluation
*Include this section only if you chose to include ML in your project.*
* Describe how you trained your model, the results you obtained, and how you evaluated those results.

<a name="conclusion"></a>

## Conclusion
* Summarize your results. What do they mean?
* What can you say about your hypotheses?
* Interpret your findings in terms of the human-understandable question you try to answer.

<a name="future-work"></a>

## Future Work
Questions we could try to answer:
- Which are the deadliest points?
- Are accidents caused by exceeding the speed limit?

<a name="workflow"></a>

## Workflow
The workflow we followed during the project is the following:

1. We first thought of the topic.
- Brainstorming and deciding which learning area we wanted to work on.
- We looked for data and luckily we found this huge Kaggle dataset.
2. Creating the repo, .gitignore and README file.
- Also organising ourselves with a Trello board.
- Downloading and merging data.
- As our data was divided in three periods, we merged them using a notebook with pandas.
3. Data cleaning.
- Dropping columns, dealing with nan values, adjusting dtypes.
4. Exploratory analysis.
- Understanding our data is key to work with it.
- First analysis to answer some of our hypothesis.
- Using descriptive statistics and plots.
5. Preprocessing.
- preparing our data of Machine Learning.
- Scaling the data to not bias our model.
6. Machine Learning.
- Choosing the model.
- Looking for the models that best fit our problem.
- Training and testing our model.
- Dividing randomly our data.
7. Extracting conclusions.
- Writing the paper on our project and preparing slides for the presentation.

<a name="organization"></a>

## Organization
We used Trello to organise the tasks and Slack to contact each other. Also we worked collaborating in a GitHub repository.

<a name="links"></a>

## Links
Include the links to your repository, slides and trello. Feel free to include any other links associated to your project. 

[Repository](https://github.com/miquelpetit/uk-accidents-project)  
[Slides](https://docs.google.com/presentation/d/1rIYSUW4NWSnklo8LfU6jOi5FVuZxarwkUWxcYiz2CZo/edit?usp=sharing)  
[Trello](https://trello.com/b/UMhqWOGZ/uk-accidents-final-project)  
