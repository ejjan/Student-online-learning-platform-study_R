# Capstone_proj: Online Learning Behavior Study
My first repository on GitHub.
This project is about student online learning behavior.

**Project Goal:** find what the most important factors that impact students’ engagement and better understand student online learning behavior.  

**Methodology:** Logistic regression and stepwise regression methods were applied to predict whether a student was “incomplete” (i.e. dropped out of the course) or “complete” (i.e. did not drop out of the course) for a given quarter based on different combinations of survey, engagement, and attendance data.

**Model Performance:** The best predictive model had the highest average ROC AUC (0.8383), average sensitivity (0.5394), and average specificity (0.9257).
Best model used stepwise selection method and selected parts of the predictors.(14 out of 27)

From the best model, I found the variable importance for the ten most important variables.
Here, importance is based on the absolute value of the t-statistic for each model parameter. Based on this criteria, the most important variable for prediction is the “week_range” variable which represents the range of the first and last weeks a student logged onto the platform. 

By the feature importance, we could give recommendation to both mentor and platform developer to enhance students’ engagement and improve the user interface and optimize the function of online learning platform.
