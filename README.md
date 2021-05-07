# Police Violence and Racial Equity Analysis

![link](https://images.squarespace-cdn.com/content/v1/55ad38b1e4b0185f0285195f/1593639080742-I0422XS5N9K41NTO3LUL/ke17ZwdGBToddI8pDm48kPTrHXgsMrSIMwe6YW3w1AZ7gQa3H78H3Y0txjaiv_0fDoOvxcdMmMKkDsyUqMSsMWxHk725yiiHCCLfrh8O1z4YTzHvnKhyp6Da-NYroOW3ZGjoBKy3azqku80C789l0k5fwC0WRNFJBIXiBeNI5fKTrY37saURwPBw8fO2esROAxn-RKSrlQamlL27g22X2A/accountable.jpg?format=2500w)

## Introduction 

From Rodney King to Trayvon Martin to Ma'Khia Bryant: the police violence against civilians in the United States is a fact, a significant socio-political challenge and a major human tragedy. In 2020, when one of the four police officers at the scene murdered a black American man George Floyd by kneeling on his neck for 9 minutes and 29 seconds, Floyd's last words 'I can't breath' became a slogan that lead to mass uprising in the US and across the world. Yet, since the arrest of his murderer Derek Chauvin, at least 3 people were [killed by the police](https://www.nytimes.com/2021/04/17/us/police-shootings-killings.html) every day. 

This project intends to analyze police violence (while police violence can be interpeted in various ways, in this instance we are recording only fatal for the civilians encounters with the law enforcement) across the United States in 2013-2020, detect the states where the police is more prone to violence and analyze whether there is racial and/ or other bias in violent police behavior. The project is also looking to compare the budgets of the police departments in the states where police violence is at highest. Among other things the project is looking at: correlation between the age of the victims and whether they attempted to flee the scene; comparisons between US population by race and US police victims by race. For a brief project review, refer to the project presentation [slides](https://docs.google.com/presentation/d/1aULhBseskY9bSc43wZSjO4jBaIV-M7Q0WGX64fDIav8/edit#slide=id.gd840a24403_2_75). For a more detailed outline continue reading below. 

## Project Team 

[Amanda Thomson](https://www.linkedin.com/in/acfthomson/)

[Nigel Rowser](https://www.linkedin.com/in/nigelrowser/)

[Shivam Mittal](https://www.linkedin.com/in/shivammittalbi/)

[Tamara Grigoryeva](https://www.linkedin.com/in/tamaragrigoryeva/)


## Questions 

The project research is focused around the following questions: 

#### - [x] MAIN QUESTION: IS THERE RACIAL BIAS IN POLICE VIOLENCE IN THE US? 

##### SUPPORTING QUESTIONS: 
- [x] WHAT ARE THE TOP STATES/ COUNTIES FOR POLICE VIOLENCE IN 2013-2020?
- [x] WHAT IS THE DEATHS BREAKDOWN BY RACE VS. COUNTRY POPULATION BY RACE?
- [x] IS THERE A CORRELATION BETWEEN THR AGE OF TH VICTIM AND WHETHER THEY FLED?
- [x] WHAT ARE THE POLICE DEPARTMENTS' BUDGETS?
- [x] CAN POLICE VIOLENCE IN THE US BE PREDICTED BASED ON FACTORS SUCH AS RACE? 


![link](https://i.guim.co.uk/img/media/fd398259625476ea51106180ab608f1f55d1b7e4/0_306_5344_3207/master/5344.jpg?width=465&quality=45&auto=format&fit=max&dpr=2&s=993b25ee7d5bf9bb4568e8b5a08e55d8)

## Communications Protocols 

The project team is parking all the project documents in this GitHub repository under various branches and on [Google Drive](https://drive.google.com/drive/folders/1XFVpMkhayZw_rGAlpjGC60XuhsebHg0z). The team has set up a board of tasks on [GitHUb Project](https://github.com/orgs/PoliceViolenceResearchers/projects/1) and [Trello](https://trello.com/b/LevAf2W4/final-project-board) that need to be accomplished on a weekly basis using Agile project management's Scrum methodology. The team meets twice a week (see the [team calendar](https://docs.google.com/document/d/1QDvCv2GM66mny9WziS2Iv2anesQr8L_l/edit) for reference) via videocalls (Microsoft Teams and Google Meet), twice a week during the bootcamp classes and casually during teaching assistants' office hours. The team also communicates daily via Slack and Gmail. 

## Resources 

The project has used the [Police Killings in 2013-2020 dataset](https://github.com/TamaraGR/Police_Violence_Analysis/blob/machine_learning/2013-2020_Police_Killings_Revised.xlsx) as the main resource. Below are some of the supporting datasets that the project has also leaned on:

- [x] [Police Stations/ Departments Budgets](https://github.com/TamaraGR/Police_Violence_Analysis/blob/database/City_Budget.csv)
- [x] [Washington Post Police Shooting Data 2015-2021](https://github.com/washingtonpost/data-police-shootings)
- [x] [Kaggle Datasets on Police Violence and racial Equity](https://www.kaggle.com/jpmiller/police-violence-in-the-us)

The project has used the following documentation tools:

- [x] [Pandas Categorical Data](https://pandas.pydata.org/pandas-docs/stable/user_guide/categorical.html)
- [x] [Seaborn Documentation](https://seaborn.pydata.org/introduction.html)
- [x] [imbalanced-learn documentation](https://imbalanced-learn.org/stable/index.html)
- [x] [scikit-learn documentation](https://scikit-learn.org/stable/supervised_learning.html)

#### Dependencies
- [x] Jupyter Notebook
- [x] Python v3.x
- [x] Pandas
- [x] Numpy
- [x] Seaborn
- [x] Matplotlib
- [x] SciKit-Learn
- [x] Imbalanced-Learn
- [x] SQLAlchemy
- [x] MySQL
- [x] JSON
- [x] Pyscopg2

## Technology at use 

- [x] Database: The project used Postgres SQL and Python Pandas were used to load, clean and analyze the data (for data loading documentation refer [here](https://github.com/TamaraGR/Police_Violence_Analysis/tree/database), including the ERD [here](https://github.com/TamaraGR/Police_Violence_Analysis/blob/database/ERD_database.png)).  
- [x] Host Instance: The project data is stored in AWS RDS. 
- [x] Machine Learning (Python): The project used SciKitLearn to create and test the machine learning (ML) model. THe ML model is tetsing a predictive statistic (For further details please refer [here](https://github.com/TamaraGR/Police_Violence_Analysis/blob/machine_learning/Police_Violence_Clean.ipynb)).
- [x] Visualization: The project used visuals from the ML analysis as well as Tableau to visualize the analysis. Data is visualized in a simplified manner for all stakeholders to be able to access the validity of it. Data is presented in a story format (To review the dashboard in Tableau please refer [here](https://public.tableau.com/profile/shivam.mittal2652#!/vizhome/PoliceVoliencemockups/PoliceVolience)). 

## Initial Data Analysis

To start off the project the team performed initial analysis of the data. Below are some of the findings: 

- [x] Despite the wide-spread misconception that growing attention to the police violence is improving the situation, the rate at which the law enforcement officers commit murder and other violence against the civilians remains the same: 

![link](https://github.com/TamaraGR/Police_Violence_Analysis/blob/main/Prototype%20Images/Police%20Killings%20Over%20Time.png)

- [x] While George Floyd's murderer was just convicted, overall there's little accountability for police brutality:

![link](https://github.com/TamaraGR/Police_Violence_Analysis/blob/main/Prototype%20Images/Visuals3.JPG)

- [x] However, the nature of the police violence is evolving:

![link](https://github.com/TamaraGR/Police_Violence_Analysis/blob/main/Prototype%20Images/Visuals2.JPG)

- [x] Black people are most likely to be killed by the police in the United States:

![link](https://github.com/TamaraGR/Police_Violence_Analysis/blob/main/Prototype%20Images/Visuals.JPG)

- [x] And black people are killed at higher rates than white people in 47 out 50 states: 

![link](https://github.com/TamaraGR/Police_Violence_Analysis/blob/main/Prototype%20Images/Racial%20Disparities.png)

## The ERD 

Below is the project data's entity relationship diagram (ERD): 

![link](https://github.com/TamaraGR/Police_Violence_Analysis/blob/main/QuickDBD-exportupdate2.png)

## ML Description 

Below is the description of the [initial machine learning (ML) model mockup](https://github.com/TamaraGR/Police_Violence_Analysis/blob/main/New_ML_Model_Mockup.ipynb). This model is likely to be significantly modified and evolve at project's next steps. 

#### Balanced Random Forest Classifier
The Balanced Random Forest Classifier is an ensemble method where each tree in the ensemble is built from a sample drawn with replacement (bootstrap sample) from the training set. Instead of using all the features, a random subset of features is selected, which further randomizes the tree. As a result, the bias of the forest increases slightly, but since the less correlated trees are averaged, its variance decreases, which results in an overall better model.

Once the data were balanced and trained, the balanced random forest algorithm gave the following scores:

![random_forest_scores](https://user-images.githubusercontent.com/73897240/115964224-65631d00-a4f1-11eb-8220-66d26f830100.PNG)

Balanced Accuracy Score: 0.292

This algorithm's balanced accuracy score is 0.292, which means only 29% of class predictions were correct and 71% were incorrect.

Balanced Random Forest's average precision score of 0.47 means that this algorithm predicted positive class predictions 47% of the time on this dataset.

An average recall score of 0.26 means that 26% of class predictions made out of all positive examples in this dataset were correct, whereas 74% were incorrect.

#### Prediction:
The Balanced Random Forest Classifier predicted the following races as having the highest incidences of police-related violence:

![rf_pred](https://user-images.githubusercontent.com/73897240/116002684-e3debe00-a5c8-11eb-8ac4-b7a66bc94558.PNG)



#### Easy Ensemble AdaBoost Classifier
The Easy Ensemble AdaBoost Classifier combine multiple weak or low accuracy models to create a strong, accurate models. This algorithm uses one-level decision trees as weak learners that are added to the ensemble sequentially. This is an iterative process, so each subsequent model attempts to correct predictions made by the previous model in the sequence.

Once the data were balanced and trained, the Easy Ensemble AdaBoost Classifier algorithm gave the following scores:

![easy_ensemble_scores](https://user-images.githubusercontent.com/73897240/115965431-410a3f00-a4f7-11eb-8898-3b980d20e2a7.PNG)

Balanced Accuracy Score: 0.271

Easy Ensemble AdaBoost Classifier's accuracy score of 0.271 means that its predictions were correct only 27% of the time and 73% were incorrect.

This algorithm's precision score of 0.49 means that it predicted positive class predictions 49% of the time on this dataset.

The average recall score of 0.33 means that 33% of class predictions made out of all positive examples in this dataset were correct.

#### Prediction:
The Easy Ensemble AdaBoost Classifier predicted the following races as having the highest incidences of police-related violence:

![ee_pred](https://user-images.githubusercontent.com/73897240/116002626-aa0db780-a5c8-11eb-9711-8125bc0355d8.PNG)


#### Why this model was chosen
The team will continue to conduct additional testing and evaluation on machine learning models before deciding on a model.  Models that will be tested include Decision Tree, Random Forest, and Support Vector Classifier (SVC).

## Conclusion 

At the initial state of the project our conclusion is that racial bias is present in police behavior across the United states, and that further analysis must be performed. 
