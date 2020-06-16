# CPSC 330: Applied Machine Learning

This is the course homepage for CPSC 330: Applied Machine Learning at the University of British Columbia. You are looking at the current version (Sep-Dec 2020). An earlier version from Jan-Apr 2020 can be found [here](https://github.com/UBC-CS/cpsc330/tree/1.0).

Instructor: [Mike Gelbart](https://www.mikegelbart.com/)


## Important links

* [course administrative info](docs/course_info.md)
* [other course documents](docs)
* [past exams](exams/)
* [Piazza](https://piazza.com/class/kb2e6nwu3uj23)
* [office hours calendar](http://www.cs.ubc.ca/~mgelbart/calendar.html)


## Lecture schedule

| #  | Date  | Topic | Related readings and links | vs. CPSC 340 |
|--- |-------|--------|---------------------------|--------------------|
| 1 | Sep 8 | [Course intro](lectures/01_syllabus-and-python.ipynb) ||   n/a
| 2 | Sep 10 | [Decision trees](lectures/03_decision-trees.ipynb) | **Assumed preparation**: [Decision tree video](https://youtu.be/WYDPYIe3RpQ?t=230) until 26:30, and then continue from 36:35 onwards. | less math
| 3 | Sep 15 | [The fundamental tradeoff of ML](lectures/04_fundamentals-of-learning.ipynb) (and the Golden Rule) | **Assumed preparation**: <ul><li>[Fundamentals of learning video](http.be/dPm-KTrJlFU?t=183) (47 min) <li>[part of the KNN video](https://youtu.be/JRF6oELLn0M?t=1248) **up to 29:00** on cross-validation (8 min)</ul> |
| 4 | Sep 17 | baselines, k-nearest neighbours, transforming numeric features (and the Golden Rule) | | 
| 5 | Sep 22 | Encoding categorical variables (and the Golden Rule) | | 
| 6 | Sep 24 | Pipelines (and the Golden Rule); hyperparameter optimization | |
| 7 | Sep 29 | [Model comparisons, EDA, missing data](lectures/07_census-data.ipynb) | [Meaningless comparisons lead to false optimism in medical machine learning](https://arxiv.org/pdf/1707.06289.pdf), [Damage Caused by Classification Accuracy and Other Discontinuous Improper Accuracy Scoring Rules](https://www.fharrell.com/post/class-damage/) | more depth
| 8 |  Oct 1 | [Logistic regression (binary and multi-class), `CountVectorizer`, `predict_proba`](lectures/05_countvec-and-logreg.ipynb) | no video | less depth on log reg, more on features
| 9 | Oct 6 | [Evaluation metrics for classification](lectures/08_classification-metrics-hyperopt.ipynb) | Optional watching: [video: precision and recall](https://youtu.be/3SD6fgNGZSo?t=214) (until 8:29), [video: ensembles](https://youtu.be/3SD6fgNGZSo?t=1386) (until 37:48), then continuing the same video until 46:33 for random forests; [Classification vs. Prediction](https://www.fharrell.com/post/classification/) | more depth
| 10 | Oct 8 | [Linear regression, feature importances](lectures/10_feature-importances.ipynb)  |  | more depth on feature importances, less on linear regression
| 11 | Oct 13 | [Evaluation metrics for regression](lectures/09_regression-housing-data.ipynb) | |  more depth on error metrics
| 12 | Oct 15 | [Ensembles](lectures/11_ensembles-review.ipynb) |  | n/a
|    | Oct 20 | MIDTERM | |
| 13 | Oct 22 | [Feature engineering, feature selection](lectures/12_feature-selection-pipelines.ipynb) | [Feature selection article](https://towardsdatascience.com/featuion-techniques-in-machine-learning-with-python-f24e7da3f36e) | feature engineering is new, less depth on feature selection
| 14 | Oct 27 | [Natural language processing](lectures/13_natural-language-processing.ipynb) |  |  new
| 15 | Oct 29 | [Neural networks & computer vision](lectures/14_neural-nets-computer-vision.ipynb) | [But what _is_ a Neural Network?](https://www.youtube.com/wrcAruvnKk&list=PLZHQObOWTQDNU6R1_67000Dx_ZCJB-3pi) | less depth
| 16 | Nov 3 | [Nearest neighbours for product similarity](lectures/15_nearest-neighbours.ipynb) | | less depth
| 17 | Nov 5 | [Time series data](lectures/16_time-series-data.ipynb) | Humour: [The Problem with Time & Timezones](https://www.youtube.com/watch?v=-5wpm-gesOY) | new 
| 18 | Nov 10 | [Survival analysis](lectures/17_survival-analysis.ipynb) | [Calling Bullshit video 4.1](https://www.youtube.com/watch?v=ITWQ5psx9Sw&list=D1Sje5jWxt-4CSZD7bUI4gSPS&index=19&t=0s), [Medium article](https://towardsdatascience.com/survisis-intuition-implementation-in-python-504fde4fcf8e) (contains some math) | new
| 19 | Nov 12 | [Clustering](lectures/18_clustering.ipynb) | | less depth
| 20 | Nov 17 | [Outliers](lectures/19_outliers.ipynb) |  | different angle
| 21 | Nov 19 | Model deployment (or move to Dec 1) | | new 
| 22 | Nov 24 | [Communicating your results](lectures/21_communication.ipynb) |  [Communication in Data Science](https://ubc-mds.github.io/2017-I-542-communication/) blog post; [Calling BS videos](https://www.youtube.com/playlist?list=PLPnZfvKID1Sje5jWxt-4CSZD7bUI4gSPS) Chapter 1 (5 video total) |  new
| 23 | Nov 26 | [Communicating your results, continued](lectures/22_communication-continued.ipynb) | [Calling BS videos](https://www.youtube.com/playlist?list=D1Sje5jWxt-4CSZD7bUI4gSPS) Chapter 6 (6 short videos, 47 min total) | new
| 24 | Dec 1 | [Ethics](lectures/23_ethics-conclusion.ipynb) | [Calling BS videos](https://www.youtube.com/playlist?list=PLPnZfvKID1Sje5jWxt-4CSZD7bUI4gSPS) Chapter 5 (6 short videos, 50 min total) | new
| 25 | Dec 3 | [Leftovers; Conclusion](https://github.com/UBC-CS/cpsc330/blob/master/lectures/20_miscellaneous-leftovers.ipynb) |   | 


## Attribution

Thank you to [Tomas Beuzen](https://tomasbeuzen.github.io/) and [Varada Kolhatkar](https://kvarada.github.io/) for significant contributions to the course materials.

## License

<a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-sa/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/">Creative Commons Attribution-ShareAlike 4.0 International License</a>.