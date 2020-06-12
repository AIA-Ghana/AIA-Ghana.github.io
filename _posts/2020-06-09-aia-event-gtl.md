---
title: AIA Event GTL
date: 2020-01-04T02:07:29.708Z
background: /assets/img/blog/IMG-20200103-WA0014.jpg
categories:
  - events
comments: true
---
## AIA Meetup Ghana Tech Lab

This meetup featured very exciting presentations notably,

* Planning your data science projects
* Future of AI
* Health AI assessment framework
<p><strong>Some highlights from the first presentation below</strong></p>

### Planning your Data Science projects

Starting data science projects requires some form of planning, be it a personal project or a large scale industrial project. In the presentation, the workflow described is outlined below

* ### Business Understanding
<p>This is the beginning of the workflow, at this stage of the workflow, we seek to 
<ol>
<li>Set the objectives for the project</li>
<li>Describe a project plan</li>
<li>Set a success criteria</li>
</ol></p>
* ### Data Understanding
<p>At this stage, we try to answer questions from the business understanding phase. This involves activities from extracting data from the source, data wrangling, data visualization, finding relationships and correlation between attributes of the data. The dataset(s) involved is also cleaned and prepared for the task. Tools like pandas, Matplotlib, Apache spark, Tableau, Seaborn are used for these tasks. If business criteria or objective is met at this point we can end at this phase other wise we move to the next phase</p>
* ### Modeling
<p>At this phase we build models from the datasets provided from the previous stage, we select a modeling technique, build and assess the model using frameworks like [Scikit learn](https://scikit-learn.org/), [Tensorflow](https://www.tensorflow.org/) or [Pytorch](https://pytorch.org/)</p>
* ### Evaluation
<p>This stage involves evaluating model performance on two things, model metrics like accuracy, recall, precision and it's ability to solve the business objective and meet the success criteria. Models are evaluated on test data sets and A/B tested</p>
* ### Deployment and Monitoring
<p> This phase involves deploying the model to production and making it available to users, it's also monitored for performance decay to trigger continuous training pipelines to train model on fresh data. Monitoring is also important as it helps in planning infrastructure.</p>

