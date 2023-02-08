# Data-Mining-and-Machine-Learning-1
DMML1 repository

# Credit Approval, Default Prediction and Fraud Detection using Stacked Learning

Credit card can be defined as the physical
manifestation of the credit value, similar to that which is offered
by any local currency, but without the hassle of actually
physically carrying money for spending. It helps both the
customers and businesses to track and manage transactions with
ease while speeding up the transaction time for each customer
waiting. Thanks to contactless payments and mobile app
payments, credit card usage has soared. With its increased usage
worldwide, it is critical to keep it safe and secure, to protect the
users from frauds and misuse. Despite the availability of
countless research on the subject of credit card fraud, approval
and default prediction, an elaborate application of stacked
learning model is lacking. This study aims to determine whether
the accuracy of credit card approval prediction, credit default
prediction and fraud detection be improved using Stacking of
supervised machine learning models and to find the best
performing model among them. Our analysis concluded with
Logistic regression as the best meta-classifier (99.5% accuracy)
followed by Decision Trees while Support Vector Classifiers and
K-Nearest Neighbors turned out to be very computationally
expensive when used as base learners in a Stacked Ensemble
model.

Conclusions: Stacked Ensemble Learning is the right approach when the
necessity for peak performance is essential no matter the
complexity and computational effort, however, such
algorithms are highly dependent upon dataset size and
complexity. While increasing complexity can improve
performance, it is not certain with SVC and KNN algorithms
that use spatial metrics for prediction. We also observed that
SVC and KNN are not preferably suitable for large datasets
and complex ensemble techniques as they become very
computationally expensive for each increased quantity of base
learner.
Simpler models (LR, DT, NB) when used as Base-learners
yield better results with Logistic Regression as Meta-Learner
with higher speed.
Our in-depth analysis, only halted by computational
capacity, completed the research with the inference that
Stacked Ensemble Techniques can improve the accuracy of
the models compared to other techniques, however, careful
evaluation and model selection will help in reducing
complexity and, increasing speed and feasibility.
Further analysis with improved infrastructure could
explore this limitation and provide further elaborate
conclusions.

-----------------------------------------------------------------------------------------------------------
ReadMe File for Code Execution:

1. All 3 datasets have been evaluated separately in their corresponding Jupyter Notebooks.
2. To view a Use case, open notebook and run cell by cell.
3. Running all the cells at once WILL hang your computer as heavy algorithms were used.
4. Summary of the analysis is given in the attached Project Report.
5. Some extra output files may get created while execution but will not impact the process.
6. Datasets can be found in the links for reproducibility of outputs: [Credit Approval Data](https://www.kaggle.com/rikdifos/credit-card-approvalprediction), [Credit Default Data](https://archive.ics.uci.edu/ml/datasets/default+of+credit+card+clients), [Fraud Detection Data](https://www.kaggle.com/mlg-ulb/creditcardfraud)
7. Links for datasets in public domain are also attached in the Project report for reference.
8. Presentation provides the steps taken for analysis in brief and concludes the Project submission.


NOTE: Running certain cells with comments as 'Too computationally intensive' is not 
recommended for quick review.
-----------------------------------------------------------------------------------------------------------
THANKS AND HAPPY CODING!

-----------------------------------------------------------------------------------------------------------
