### Final-Project---Demystifying-ML

# Machine Learning - Exoplanet Exploration

For my ML Final project I will be taking a deep dive into the exoplants project and its Kepler space telescope dataset, which was introduced in class for WK 21.

By definition Machine Learning (ML) is the study of computer algorithms that can improve automatically through experence
and by the use of data. This study is seen as a part of Artificial Intelligence (AI).

ML can also be seen as the use and development of computer systems that are able to learn and adapt without following explicit instructions,
by isint algorithims and statitical models to analyze and draw inferences from patterns in data




![exoplanets.jpg](Images/exoplanets.jpg)

## Background

Over a period of nine years in deep space, the NASA Kepler space telescope has been out on a planet-hunting mission to discover hidden planets outside of our solar system.

For this final project Machine learning models were created to classify candidate exoplanets from the provided raw dataset, including all of its 40 sets of data (Features).

- - -
## Models
### Two Techniques selected
- Logistic Regression (LR)
- Random Forest Classifier (RFC)

### Model Design Approach
- Build a base model using the original dataset and all its 40 features.
- Use the base model to review feature importance, and remove the data that does not include relevant features data.
- Build a secondary model with select features, using the most relevent datasets.
- Use *GridSearchCV* to tune model perameters.
- Build the final model using the tuned parameters. 

## Model Comparison
The Random Forest Classifier model was shown to be more accurate when compared to Logistic Regression, if only by a small margin.

![models_eval](Images/models_eval.png)

## Conclusions
 Logistic regression measures the relationship between the categorical dependent variable and one or more independent variables by estimating probabilities using a logistic function, and the RFC or Random Forest Classifier is an ensemble learning method for classification, regression and other tasks that operates by constructing a multitude of decision trees at training time. The RFC model seemed to create probability clusters similar to the estimated probabilites done with the Logistic regression model. 

 With the Kepler data set, the RFC model made the best "Guesses" based on its decision bases at the time of training

 
