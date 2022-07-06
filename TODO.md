### Kaggle-titanic
This is a tutorial in an IPython Notebook for the Kaggle competition, Titanic Machine Learning From Disaster. The goal of this repository is to provide an example of a competitive analysis for those interested in getting into the field of data analytics or using python for Kaggle's Data Science competitions .

**Quick Start:** [View](http://nbviewer.ipython.org/urls/raw.github.com/Mieczmik/titanic-kaggle-competition/main/titanic.ipynb) a static version of the notebook in the comfort of your own web browser.

### Installation:

To run this notebook interactively:

1. Download this repository in a zip file by clicking on this [link](https://github.com/Mieczmik/titanic-kaggle-competition/archive/master.zip) or execute this from the terminal:
`git clone https://github.com/Mieczmik/titanic-kaggle-competition.git`
2. Install [virtualenv](http://virtualenv.readthedocs.org/en/latest/installation.html).
3. Navigate to the directory where you unzipped or cloned the repo and create a virtual environment with `virtualenv env`.
4. Activate the environment with `source env/bin/activate`
5. Install the required dependencies with `pip install -r requirements.txt`.
6. Execute `ipython notebook` from the command line or terminal.
7. Click on `titanic.ipynb` on the IPython Notebook dasboard and enjoy!
8. When you're done deactivate the virtual environment with `deactivate`.


### Kaggle Competition | Titanic Machine Learning from Disaster

>The sinking of the RMS Titanic is one of the most infamous shipwrecks in history.  On April 15, 1912, during her maiden voyage, the Titanic sank after colliding with an iceberg, killing 1502 out of 2224 passengers and crew.  This sensational tragedy shocked the international community and led to better safety regulations for ships.
>One of the reasons that the shipwreck led to such loss of life was that there were not enough lifeboats for the passengers and crew.  Although there was some element of luck involved in surviving the sinking, some groups of people were more likely to survive than others, such as women, children, and the upper-class.
>In this contest, we ask you to complete the analysis of what sorts of people were likely to survive.  In particular, we ask you to apply the tools of machine learning to predict which passengers survived the tragedy.
>This Kaggle Getting Started Competition provides an ideal starting place for people who may not have a lot of experience in data science and machine learning."
From the competition [homepage](http://www.kaggle.com/c/titanic-gettingStarted).

### Goal for this Notebook:
Show a simple example of an analysis of the Titanic disaster in Python using a full complement of Python utilities. This is aimed for those looking to get into the field or those who are already in the field and looking to see an example of an analysis done with Python.

### Goal for this Notebook:
Show a simple example of an analysis of the Titanic disaster in Python using a full complement of PyData utilities. This is aimed for those looking to get into the field or those who are already in the field and looking to see an example of an analysis done with Python.

#### This Notebook will show basic examples of:
#### Data Preprocessing
* Importing Data with Pandas
* Data Review
* Cleaning Data
* Creating Pipelines for Numerical and Categorical Data assembled from
  + Numeric/Categorical Column Selector
  + Missing Data Replacement with Imputer
  + Data Standarization with StandardScaler
  + join both pipelines using FeatureUnion 
#### Data Analysis
Training listed below machine learning models using GridSearchCV and Pipelines:
  + Linear Support Vector Classifier
  + Support Vector Classifier
  + Logistic Regression
  + k-Nearest Neighbors
  + Decission Tree Classifier
  + Random Forest
  + Bagging Classifier
  + Extra Trees Classifier
  + Adaptive Boosting (AdaBoost)
  + Gradient Boosting
  + Extreme Gradient Boosting (xgboost)
#### Summary
* Plotting results
* Export results


