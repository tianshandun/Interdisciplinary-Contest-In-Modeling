# Interdisciplinary-Contest-In-Modeling
 All files include:
 1. The official discription of problem E
 2. The whole PDF solution
 3. The certificate of achievement of Meritorious Winner
# The summary overview
Forest carbon sequestration plays an important role in mitigating the effects of climate change.
There are two types of forest carbon sequestration: plant carbon sequestration and forest products
carbon sequestration. For forest managers, it becomes a challenge to develop optimal forest
management plans based on these two aspects. This report aims at developing a model to calculate
the carbon sequestration of forests and forest products over time and assessing the integrated level
of forests. We are expected to consider the benefits derived from forests in as many ways as possible
and provide forest managers with the best forest management plan for certain forest.

For problem 1, we are primarily concerned with two aspects. The first is the dynamic
calculation of carbon sequestration of plants and their products.And the second is the impact of
harvesting management on the dynamic calculation. We use a logistic regression model. In
model 1: Dynamic Carbon Sequestration Model, we set time as the independent variable and
carbon sequestration as the dependent variable to solve the problem of carbon sequestration. After
that, we design a reasonable harvesting management and calculate the time distribution of carbon
sequestration in forests and their products. Our model can provide forest managers with optimized
harvesting density and rotation.

For question 2, we need to further consider various ways of realizing forest value based on forest
carbon sequestration, and then evaluate the comprehensive forest value. In model 2: SEE model,we
first determine the evaluation indexes, then calculate their weights by AHP and EWM and then
combine the data with expert opinions to establish the scoring system of decision variable matrix.
Next, according to the indicators we determined, we carry out multi-objective programming with a
total of three indicators ,including ecological , economic and social benefits as decision variables
and carbon sequestration as the objective function .After solving Pareto Optimality,the final optimal
forest management plan is obtained.

In the case study, we investigate forest carbon sequestration in the Mohe forest area in northern
Greater Khingan Mountains, China. According to model 1, based on the forestry data of Greater
Khingan Mountains, we calculate the carbon sequestration in Mohe forest area of Greater Khingan
Mountains in the next 100 years using matlab. According to model 2, we designe a reasonable and
optimized forest management plan. Finally, we extended the 10-year rotation period and explored
the timeline transition strategy.

At the end of the article, we perform a sensitivity analysis, analyze the strengths and weaknesses
of the model, and consider directions for further improving.
