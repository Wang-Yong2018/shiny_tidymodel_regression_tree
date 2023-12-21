# shiny_tidymodel_regression_tree
Interfactively tidymodel regression tree  using shiny

The Problem:
How to clearly explain the target variable changed(quantitatively) was lead by which predictors ?  And how often(hours, days)?
The Answer are 3 toolboxs:
1. time plot : Show the target and time relation. Super easy to understand, Super easy to explain.
2. KPI Number: Show the mean value, standard deviation value as well as how many data observered. Those basic statistics figures help to now the sample scale.
3. Fancy rpart.plot: Show the target values was splited by different predictor variables and values. The fancy part is the line width can change based on how often it happened. In this way, we know which path should be focused.

My story: 
During several of my digital transformation project, the multiregression is used to show the how target is influenced by predictors. but it is difficult to explain to customer as well as get them trust the model. For example, a power plants electricty MWH to power grid was influenced not only by the fuel burned by also by the power plant internal power usage as well as dozens of reasons. Those predictors are measured by hundres of sensors. The customer has strong industry backgroud knowledge and season experience. Though working on digital transformation as well, the common lanauage is visulization and interfactive modeling, they can use such tool to find the root cause and get result by themself instead of tell them final result.

Let's why I want to share the shiny tidymodel based regress tree with you. 

Best Regards,
WY


