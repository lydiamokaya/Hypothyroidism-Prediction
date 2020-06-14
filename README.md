# Hypothyroidism Prediction Using Decision Trees and Support Vector Machine.
## a) Specifying the Question
Nairobi Hospital conducted a clinical camp to test for hypothyroidism. The data collected focused on Thyroid patients. As a data scientist i have been tasked to build a model that determines whether or not the patient's symptoms indicate that the patient has hypothyroid.

## b) Defining the Metric for Success
This project will be successful when:

1)We Identify the most crucial independent variables that affect Hypothyroidism.

2)The model achieves atleast 90% accuracy

3)Have the lowest RMSE score possible

## c) Understanding the context
Hypothyrodism is a condition where the body produces too little thyroxine. Low thyroxine levels cause problems with development if it occurs when an individual is young. In adults, thyroxine deficiency will lower the metabolic rate, causing weight gain, memory problems, infertility, fatigue, and muscle stiffness.

Thyroxine: is a hormone secreted in the thyroid glands into the bloodstream. It plays a crucial role in heart and digestive function, metabolism, brain development, bone health, and muscle control. It affects almost all of the body's systems, which means proper thyroxine levels are vital for health.
## d) Recording the Experimental Design
The following are the experimental design i took in order to complete this project:

Exploratory Data Analysis

Data Cleaning

Univariate Analysis

Bivariate Analysis

Multivariate Analysis

Decision Trees: Random Forests , Ada Boosted Trees , Gradient Boosted Trees

Support Vector Machines: Kernel = polynomial , linear , rbf

### Conclusion
Our conclusion is  that all our models performed well since they all had low RMSE and accuracy scores of above 90%. But since our analysis is on thyroid patients we would like to go with the best score since we dealing with human life. Hence in decision trees we would recommend the Gradient boosting model while in the SVM we go with the linear kernel for best predictions.



## e) Data Relevance
Source [link]

The Dataset has the following Columns Age, Sex, on_thyroxine, query_on_thyroxine, on_antithyroid_medicationthyroid_surgery, query_hypothyroid, query_hyperthyroid, pregnant, sick, tumor, lithium, goitre, TSH_measured, TSH, T3_measured, T3, TT4_measured and TT4. This will help us determines whether or not the patient's symptoms indicate that the patient has hypothyroid.
