# SIADS 696 Milestone 2 Spring/Summer 2024 Team 5

**Overview**
ReliefWeb is an informational service provided by the United Nations (UN) that receives humanitarian reports and content from over 4000 sources including international agencies, local governments, research institutions, and media. The editorial team at ReliefWeb manually classifies reports into one of 20 ‘UN Themes’, such as agriculture and climate change, which is very tedious and time-consuming. We applied supervised learning (text classification) to automate labeling reports with predefined themes and unsupervised learning (topic modeling) to extract topics from reports related to one theme, specifically climate change.

**Summary**
We created a multiclass text classification model using logistic regression to predict the theme label of a ReliefWeb report which assigns one of ten possible theme labels to a new report with an average F1-score of 0.86. We also generated two topic models to identify climate change subtopics. With Latent Dirichlet Allocation, we identified two topics related to (1) community support and development and (2) oil spills from the report summaries tagged to Climate Change and Environment, while with non-negative matrix factorization, we identified at least 4 distinct subtopics (project, flood, forest, oil).

