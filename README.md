# Diploma_deb_credit_model_optimization

## Abstract
The thesis focuses on Ukraine’s Banking credit market, proposing a quantita-
tive modeled solution to management of debt collection. By using advanced data-
processing techniques and machine learning algorithms to analyze the relationship
between specific actions in the debt collection process, we recommend next best action
that would maximize probability of debt repayment. The study compares multiple
binary machine learning models utilizing XGBoost, LightGBM, and regression-based
approach. Finally, the thesis proposes XGBoost with 5 k-fold cross validation as a
best model that chooses set of actions maximizing debt repayment. We compare this
new multi-step procedure with traditional rule-based roadmaps and demonstrate that
a personalized, algorithmic selection of the next action yields better outcomes than
generic scenarios. In practice, we train models to detect success and failure and then
run the binary model for each possible action on a new client profile, then select the
action with the highest predicted probability of success.
The results indicate that such “best next action” algorithmic models can enhance
the effectiveness of standard rule-based strategies, providing higher predictive accu-
racy and potential cost savings by redirecting resources from less productive contacts
to those with a greater likelihood of resulting in repayment.

# How to run the code?
1) As our original dataset is pretty big we downloaded all the needed files to the Google Drive storage, so you need to click on the link and download the folder. There you will find all datasets and main.ipynb with the code.
2) You need to run main.ipynb from the very beginning (this will include both preprocessing the data and preparation for the modeling) or start running from the part "Start of the modeling (to skip preprocessing part)".
3) See the model training outputs and the final result.

I have also added the .ipynb file here in case you want to review the code here.

Thank you!
