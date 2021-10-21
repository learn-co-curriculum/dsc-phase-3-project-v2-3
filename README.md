
# Phase 3 Project Description

Congratulations! You've made it through another _intense_ module, and now you're ready to show off your newfound Machine Learning skills!

![awesome](https://raw.githubusercontent.com/learn-co-curriculum/dsc-phase-3-project-v2-3/main/images/smart.gif)

All that remains in Phase 3 is to put your new skills to use with another large project!

In this project description, we will cover:

* Project Overview
* Deliverables
* Grading
* Getting Started

## Project Overview

For this project, you will engage in the full data science process from start to finish, solving a **classification** problem using a **dataset of your choice**.

### Business Problem and Data

Similar to the Phase 2 project, it is up to you to define a stakeholder and business problem. Unlike the Phase 2 project, you are also responsible for choosing a dataset.

For complete details, see [Phase 3 Project - Choosing a Dataset](https://github.com/learn-co-curriculum/dsc-phase-3-choosing-a-dataset).

### Key Points

#### Classification

Recall the distinction between *classification* and *regression* models:
 * Classification is used when the target variable is a *category*
 * Regression is used when the target variable is a *numeric value*

You already practiced performing a regression analysis in Phase 2, and you will have additional opportunities to work on regression problems in later phases, but **for this project, you must be modeling a classification problem**.

#### Findings and Recommendations

In the previous two projects, the framing was primarily *descriptive* and *inferential*, meaning that you were trying to understand the distributions of variables and the relationship between them. For this project you can still use these techniques, but make sure you are also using a ***predictive*** approach.

A predictive *finding* might include:

* How well your model is able to predict the target
* What features are most important to your model

A predictive *recommendation* might include:

* The contexts/situations where the predictions made by your model would and would not be useful for your stakeholder and business problem
* Suggestions for how the business might modify certain input variables to achieve certain target results

#### Iterative Approach to Modeling

The expectations from the Phase 2 project still stand:

> You should demonstrate an iterative approach to modeling. This means that you must build multiple models. Begin with a basic model, evaluate it, and then provide justification for and proceed to a new model. After you finish refining your models, you should provide 1-3 paragraphs in the notebook discussing your final model.

With the additional techniques you have learned in Phase 3, be sure to explore:

1. Model features and preprocessing approaches
2. Different kinds of models (logistic regression, k-nearest neighbors, decision trees, etc.)
3. Different model hyperparameters

At minimum you must build three models:

* A simple, interpretable baseline model (logistic regression or single decision tree)
* A more-complex model (e.g. random forest)
* A version of either the simple model or more-complex model with tuned hyperparameters

#### Classification Metrics

**You must choose appropriate classification metrics and use them to evaluate your models.** Choosing the right classification metrics is a key data science skill, and should be informed by data exploration and the business problem itself. You must then use this metric to evaluate your model performance using both training and testing data.

## Deliverables

There are three deliverables for this project:

* A **non-technical presentation**
* A **Jupyter Notebook**
* A **GitHub repository**

The deliverables requirements are almost the same as in the Phase 1 and Phase 2 projects. The only difference between the Phase 2 and Phase 3 project checklist is that the "Regression Results" element has been replaced with an "Evaluation" element.

### Non-Technical Presentation

Recall that the non-technical presentation is a slide deck presenting your analysis to ***business stakeholders***, and should be presented live as well as submitted in PDF form on Canvas.

We recommend that you follow this structure, although the slide titles should be specific to your project:

1. Beginning
    - Overview
    - Business and Data Understanding
2. Middle
    - Modeling
    - **Evaluation**
3. End
    - Recommendations
    - Next Steps
    - Thank you

Make sure that your discussion of classification modeling is geared towards a non-technical audience! Assume that their prior knowledge of machine learning is minimal. You don't need to explain the details of your model implementations, but you should explain why classification is useful for the problem context. Make sure you translate any metrics or feature importances into their plain language implications.

The graded elements for the non-technical presentation are the same as in [Phase 1](https://github.com/learn-co-curriculum/dsc-phase-1-project-v2-3#deliverables) and Phase 2.

### Jupyter Notebook

Recall that the Jupyter Notebook is a notebook that uses Python and Markdown to present your analysis to a ***data science audience***. You will submit the notebook in PDF format on Canvas as well as in `.ipynb` format in your GitHub repository.

The graded elements for the Jupyter Notebook are:

* Business Understanding
* Data Understanding
* Data Preparation
* Modeling
* **Evaluation**
* Code Quality

### GitHub Repository

Recall that the GitHub repository is the cloud-hosted directory containing all of your project files as well as their version history.

The requirements are the same as in [Phase 1](https://github.com/learn-co-curriculum/dsc-phase-1-project-v2-3#github-repository) and Phase 2, except for the required sections in the `README.md`.

For this project, the `README.md` file should contain:

* Overview
* Business and Data Understanding
  * Explain your stakeholder audience and dataset choice here
* Modeling
* **Evaluation**
* Conclusion

Just like in Phase 1 and 2, the `README.md` file should be the bridge between your non technical presentation and the Jupyter Notebook. It should not contain the code used to develop your analysis, but should provide a more in-depth explanation of your methodology and analysis than what is described in your presentation slides.

## Grading

***To pass this project, you must pass each project rubric objective.*** The project rubric objectives for Phase 2 are:

1. Attention to Detail
2. ML Communication
3. Data Preparation for Machine Learning
4. Nonparametric and Ensemble Modeling

### Attention to Detail

Just like in Phase 1 and 2, this rubric objective is based on your completion of checklist items. ***In Phase 3, you need to complete 80% (8 out of 10) or more of the checklist elements in order to pass the Attention to Detail objective.***

**NOTE THAT THE PASSING BAR IS HIGHER IN PHASE 3 THAN IT WAS IN PHASE 2!**

The standard will increase with each Phase, until you will be required to complete all elements to pass Phase 5 (Capstone).

#### Exceeds Objective

90% or more of the project checklist items are complete

#### Meets Objective (Passing Bar)

80% of the project checklist items are complete

#### Approaching Objective

70% of the project checklist items are complete

#### Does Not Meet Objective

60% or fewer of the project checklist items are complete

### ML Communication

Recall that communication is one of the key data science "soft skills". In Phase 3, we are specifically focusing on ML Communication. We define ML Communication as:

> Communicate the **performance** of and **insights** generated by machine learning models to diverse audiences via writing, live presentation, and visualization

High-quality ML Communication includes rationale, results, limitations, and recommendations:

* **Rationale:** Explaining why you are using machine learning rather than a simpler form of data analysis
  * What about the problem or data is suitable for this form of analysis?
  * For a data science audience, this includes your reasoning for the changes you applied while iterating between models.
* **Results:** Describing the classification metrics
  * You can report multiple metrics for a single model, but make sure that indicate a reason for which metrics you are using (and don't try to use all of them at once)
  * For a business audience, make sure you connect any metrics to real-world implications. You do not need to get into the details of how the model works.
  * For a data science audience, you don't need to explain what a metric is, but make sure you explain why you chose that particular one.
* **Limitations:** Identifying the limitations and/or uncertainty present in your analysis
  * Are there certain kinds of records where model performance is worse? If you used this model in production, what kinds of problems might that cause?
  * In general, this should be more in-depth for a data science audience and more surface-level for a business audience.
* **Recommendations:** Interpreting the model results and limitations in the context of the business problem
  * What should stakeholders _do_ with this information?

## Getting Started

Create a new repository for your project to get started. We recommend structuring your project repository similar to the structure in [the Phase 1 Project Template](https://github.com/learn-co-curriculum/dsc-project-template). You can do this either by creating a new fork of that repository to work in or by building a new repository from scratch that mimics that structure.

## Project Submission and Review

Review the "Project Submission & Review" page in the "Milestones Instructions" topic to learn how to submit your project and how it will be reviewed. Your project must pass review for you to progress to the next Phase.

## Summary

This project is an opportunity to expand your data science toolkit by evaluating, choosing, and working with new datasets. Spending time up front making sure you have a good dataset for a solvable problem will help avoid the major problems that can sometimes derail data science projects. You've got this!
