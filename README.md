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
>A total of 36,371 people were killed on Britain's roads between 1999 and 2010.

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
Our cleaning consisted in selecting the relevant columns for our analysis - as some of them did not give us the information we needed, converting some of the dtypes - to datetime specially, dropping the not-that-relevant columns with a high amount of null values and also the rows containing null values for the rest. We will also look for outliers, data that does not make sense and could bias our data and results. Renaming columns was not necessary but made the work easier, as there were columns with long names like "Did_Police_Officer_Attend_Scene_of_Accident".

Although our cleaning was enough for the exploratory and descriptive analysis, we had to prepare the data for the Machine Learning algorithm. This preprocessing step meant converting the categorical values into booleans and dummy variables. Furthermore, we scaled our numerical data in order to not bias the model.

<a name="analysis"></a>

## Analysis
Once we had our hypotheses done we started thinking about the hypothesis testing we could use as well as the best way to plot our results. One of the challenges we had during this part of the project was to handle the inbalance in the dataset, as we had only 1% of the accidents being fatal and 85 % being light accidents. Using matplotlib we were able to create beautiful plots which illustrate the situations we wanted to analyze.

<a name="model-training-and-evaluation"></a>

## Model Training and Evaluation
Even though our main goal at first was to create a good prediction model to predict the severity of an accident given the other features of the accident (like weather, road type and conditions, ...), we realised we need more knowledge on Machine Learning in order to create accurate models for real datasets. We managed to try a few models such as K-Nearest Neighbors, Linear and Logistic Reagressions and Random Forest and look for the best parameters with Grid Search and Random Search. The Random Forest was the best-performing algorithm but still gave us only an accuracy score of 48.7%.
<a name="conclusion"></a>

## Conclusion
* We got to confirm our hypotheses using descriptive statistics
* The model we created did better than a random prediction model so we think that with a more 

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
We used Trello to organise the tasks and Slack to contact each other. Also we worked collaborating in a GitHub repository. As we were two people some of the work was divided in order to be more time-efficient, for example the presentations slides and the readme, or the exploratory analysis and the preprocessing.

<a name="links"></a>

## Links
Include the links to your repository, slides and trello. Feel free to include any other links associated to your project. 

[Repository](https://github.com/miquelpetit/uk-accidents-project)  
[Slides](https://docs.google.com/presentation/d/1rIYSUW4NWSnklo8LfU6jOi5FVuZxarwkUWxcYiz2CZo/edit?usp=sharing)  
[Trello](https://trello.com/b/UMhqWOGZ/uk-accidents-final-project)  
