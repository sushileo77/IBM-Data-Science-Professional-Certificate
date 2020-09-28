# IBM-Data-Science-Professional-Certificate
Projects in Data Science and ML 

The Project is Based on Determining the Traffic Severity for Car Accidents


Introduction :-
       Road traffic injuries are currently estimated to be the eighth leading cause of death across all age groups globally, and are predicted to become the seventh leading cause  of death by 2030.

        Analysing a significant range of factors, including weather conditions, special events, roadworks, traffic jams among others, an accurate prediction of the severity of the accidents can be performed. 
        These insights, could allow law enforcement bodies to allocate their resources more effectively in advance of potential accidents, preventing when and where a severe accidents can occur as well as saving both, time and money. 

        In addition, this knowledge of a severe accident situation can be warned to drivers so that they would drive more carefully or even change their route if it is possible or to hospital which could have set everything ready for a severe intervention in advance.

         Governments should be highly interested in accurate predictions of the severity of an accident, in order to reduce the time of arrival and thus save a significant amount of people each year. Others interested could be private companies investing in technologies aiming to improve road safeness.  
      
Feature Determination and Selection :-
      Feature Selection Notebook descriobes data transformations performed for the feature selection. Raw Data is taken from the Kaggle Page and transformed to take relevant information.

**1. Introduction**
Globally, road traffic crashes are a leading cause of death among young people, and the main cause of death among those aged 15{29 years. Road traffic injuries are currently estimated to be the eighth leading cause of death across all age groups globally, and are predicted to become the seventh leading cause of death by 2030[1].

Leveraging the tools and all the information nowadays available, an extensive analysis to predict traffic accidents and its severity would make a di erence to the death toll. Analyzing a significant range of factors, including weather con-ditions, locality, type of road and lighting among others, an accurate prediction of the severity of the accidents can be performed. Thus, trends that commonly lead to severe traffic incidents can help identifying the highly severe accidents. This kind 

**2 Data**

       The users dataset was used to craft some new features:

•	number of users: total number of people involved in the accident.
•	pedestrians: whether there were pedestrians involved (1) or not (0).
•	severity : maximum gravity su ered by any user involved in the accident.
•	scathed or light injury (0), hospitalized wounded or death (1)

**3 Predictive Modeling**
       Four different approaches were used:
              1.	Decision Tree, Random

              2.	Forest Logistic Regression

              3.	K-Nearest Neighbour

              4.	Supervised Vector Machine

**4 Results**
       The metrics used to compare the accuracy of the models are the Jaccard
       Score, f1-score, Precision  and Recall. This table reports the results of the evaluation of each model.



Algorithm		Jaccard	f1-score	Precision	Recall	Time(s)
					
Random Forest		0.722	0.72	0.724	0.591	6.588
Logistic Regression		0.661	0.65	0.667	0.456	6.530
KNN		0.664	0.66	0.652	0.506	200.58
SVM		0.659	0.65	0.630	0.528	403.92


**5 Conclusion**

I was able to achieve 68% accuracy in the. However, there was still significant variance that could not be predicted by the models in this study. I think other features like speed or uninterrupted time of traveling could be used to predict a more accurate classi cation. These are characteristics that my be impossible of knowing right now, but at the incredible peace that technology is evolving nowadays, soon cars will be able of track them so that the emergency services could use them.

The next step on this problem could be to add a accident prediction model able to not just predict the accuracy but also the critical time and spots where potential accidents can occur in advance.

