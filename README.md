**UC Berekely-AIML Professional certificate. Module 20. Ensemble models**


**Majority rule, collective wisdom, and voting systems in machine learning and artificial intelligence**

**Introduction**

If someone wants to make a decision, tries to get idea from people and friends to make better decision. The collective knowledge is better than the knowledge of the few is foundation of decision making in individual and public decisions. For example, in politics and economics, referring to majority rule and collective wisdom is common and voting system in an option to get the idea of people about the public issues. Similar idea in AIML is working.

**VotingRegressor in AIML**

Suppose we want to understand the main drivers of diabetes, especial cancer, price of bitcoin, demand of energy; or any other thing that can be predicted with machine learning. We can use linear regression, non-linear regression, decision tree regression, knn regression, SVR and so on. In each regressors, we can define different parameters to check the best model. However, here is an option to improve efficiency by referring to the majority rule and voting system. In AIML, using VotingRegressor, we can define a pipeline and combine all regressors. VotingRegressor leads to higher score, if all regressors are independent.

**Ensemble models in AIML**

Ensemble working with majority rule and collective wisdom. Ensemble models combine multiple algorithms to improve the predictive performance of each algorithm individually. Ensemble models typically consist of two strategies—bagging and boosting—and there are many examples of predefined ensemble algorithms.

**Bootstrapping and Bagging in AIML**

Bagging classifiers and regressors are ensemble models that fit the regressor and classifier models to random subsets of the original dataset. A final prediction is created by combining the predictions from each model. In these meta-estimators, randomization is introduced into the model-building process. Finally, the outcomes are aggregated to reach a categorical outcome: the aggregation averages over the iterations for a numerical target variable.

**Random Forests as Ensemble model for decision trees**

Random forests are ensemble techniques that include multiple decision trees and a method called bootstrap aggregation, which is commonly referred to as bagging, and which can perform both regression and classification tasks. This method combines multiple decision trees into one final output rather than relying on individual decision trees. Criteria for making decision about the depth of trees is oob score (out of the bag score).

**Boosting to reduce bias in AIML**

Boosting is an ensemble learning technique that reduces the number of errors by combining weak learners into one strong learner. Boosting involves selecting a random sample of data, fitting a model, and then training each model sequentially. Three popular types of boosting are: Adaptive boosting (AdaBoost) Gradient boosting Extreme gradient boosting (XGBoost)

**This file has seven sections. In each section, I cover one issue.**

    Section one: Basic Aggregating of Models

    Section two: Comparing Aggregate Models for Regression

    ection three : Implementing Bootstrapping

    Section four: Implementing Bagging

    Section five: Implementing Random Forests

    Section six: Implementing the AdaBoost Algorithm

    Section seven: Gradient Boosting

