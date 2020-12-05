# F2020-SDSProject (12/8)

* Things in BoxNote has been copied to `Outline`.

* Check `Projects` tab to overview the progress.

## Guideline

Submit one .pdf (or .html) file and one .R (or .Rmd) file: 5-pages max (including relevant figures to be included at a reasonable size) with the following structure: 

* Introduction: describe the data that you chose and the goals (scientific questions) that you want answer with your analysis. If you use multiple data sources for your analysis, highlight this here. 

- [ ] Describe the data
- [ ] Research goals

* Preprocessing and descriptives: show some descriptive statistics (this can be numeric summaries, boxplots/scatterplots, correlation plots, anything you think is relevant) that give a first hint to the relationships that the data has. In case you transform some variables or create new variables using the existing ones (feature engineering), highlight this here.

- [ ] Descriptive statistics: Table and Histogram


* Methods: describe what method you use to accomplish your goals and the motivation for choosing such method. Detail how you choose potential tuning parameters of the model. Hint: you can analyze your data using a single model (in this case the choice of your model should be carefully justified in light of your overarching goals), or compare the performance of two/three (max) different models on your data (in this case highlight pros and cons of each one of these models).

* Results: show the results (include tables, graphs) that support your initial goal.
 

## Grading rubric

* (4pt) overall clarity of the exposition: how clearly is the analysis explained?

* (4pt) overall correctness of the approach: does the analysis answer the goals that you had?

* (2pt) preprocessing and descriptives: are the descriptive plots relevant to the analysis?

* (3pt) justification of the approach: for example, why do you choose to use a Lasso regression? How do you pick values of the tuning parameters? In case you compare several methods, what are the pros and cons of each one of them?

* (2 pt) conclusions: how do you interpret your results?

* (3pt) correctness of the code: does the code replicate the correct results of your analysis?

* (2pt) legibility of the code: remove redundant code, write code legibly.
