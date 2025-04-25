# Module 12 Report Template

## Overview of the Analysis

In this section, describe the analysis you completed for the machine learning models used in this Challenge. This might include:

* Explain the purpose of the analysis.
* Explain what financial information the data was on, and what you needed to predict.
* Provide basic information about the variables you were trying to predict (e.g., `value_counts`).
* Describe the stages of the machine learning process you went through as part of this analysis.
* Briefly touch on any methods you used (e.g., `LogisticRegression`, or any other algorithms).

## Results

Using bulleted lists, describe the accuracy scores and the precision and recall scores of all machine learning models.

* Machine Learning Model 1:
    * Description of Model 1 Accuracy, Precision, and Recall scores.

## Summary

Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. For example:

* Which one seems to perform best? How do you know it performs best?
* Does performance depend on the problem we are trying to solve? (For example, is it more important to predict the `1`'s, or predict the `0`'s? )

If you do not recommend any of the models, please justify your reasoning.

****************** Credit Risk Analysis ********************

**Purpose**

The purpose of this analysis is to build and evaluate a **logistic regression model** that can classify loan applications as either **high risk (1)** or **healthy (0)**. By training the model on historical loan data, the goal is to provide an automated and reliable way to assess credit risk, which can help financial institutions make better-informed lending decisions and reduce potential losses from high-risk loans.

---

**Model Evaluation Metrics**

Based on the classification report, the model achieved:

- **Accuracy**: 0.99  
- **Precision**:
  - For healthy loans (`0`): 1.00
  - For high-risk loans (`1`): 0.84
- **Recall**:
  - For healthy loans (`0`): 0.99
  - For high-risk loans (`1`): 0.94

---

**Model Summary**

The logistic regression model demonstrates **excellent performance** overall, especially in identifying **healthy loans**, where it achieves near-perfect precision and recall. It also performs strongly on high-risk loans, with a precision of **84%** and recall of **94%**, indicating that it is effective at flagging most high-risk applicants while keeping false positives relatively low.

Given its **high accuracy (99%)** and its ability to effectively detect both healthy and high-risk loans, I would **recommend this model for deployment**. It can provide valuable insights and support in the loan approval process. However, additional testing on real-time or imbalanced datasets and consideration of business risk tolerance would further solidify its practical utility.
