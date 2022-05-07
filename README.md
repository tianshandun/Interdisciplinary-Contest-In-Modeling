# Interdisciplinary-Contest-In-Modeling
 All files include:
 1. The official description of problem E
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

> 森林碳汇在缓解气候变化的影响方面发挥着重要作用。森林碳汇有两种类型：植物碳汇和林产品碳汇。
> 对于森林管理者来说，如何根据这两个方面制定最佳的森林管理计划已经成为一个挑战。
> 本报告旨在开发一个模型来计算森林和林产品在一段时间内的碳固存量，并评估森林的综合水平。
> 希望我们能尽可能多地考虑森林带来的效益并为森林管理者提供针对某些森林的最佳森林管理计划。

For problem 1, we are primarily concerned with two aspects. The first is the dynamic
calculation of carbon sequestration of plants and their products.And the second is the impact of
harvesting management on the dynamic calculation. We use a logistic regression model. In
model 1: Dynamic Carbon Sequestration Model, we set time as the independent variable and
carbon sequestration as the dependent variable to solve the problem of carbon sequestration. After
that, we design a reasonable harvesting management and calculate the time distribution of carbon
sequestration in forests and their products. Our model can provide forest managers with optimized
harvesting density and rotation.

> 对于问题1，我们主要关注两个方面。第一个方面是动态计算植物及其产品的碳封存。
> 第二个方面是采伐管理对动态计算的影响。我们使用逻辑回归模型。在
> 模型1动态碳封存模型中，我们将时间设为自变量，将碳封存设为因变量。
> 之后，我们设计了一个合理的采伐管理，并计算了森林及其产品的碳封存时间分布。我们的模型可以为森林管理者提供优化的
> 采伐密度和轮伐。

For question 2, we need to further consider various ways of realizing forest value based on forest
carbon sequestration, and then evaluate the comprehensive forest value. In model 2: SEE model,we
first determine the evaluation indexes, then calculate their weights by AHP and EWM and then
combine the data with expert opinions to establish the scoring system of decision variable matrix.
Next, according to the indicators we determined, we carry out multi-objective programming with a
total of three indicators ,including ecological , economic and social benefits as decision variables
and carbon sequestration as the objective function .After solving Pareto Optimality,the final optimal
forest management plan is obtained.

> 对于问题2，我们需要进一步考虑基于森林碳汇的各种森林价值实现方式，然后评估综合森林价值。在模型2SEE模型中，我们
首先确定评价指标，然后通过AHP和EWM计算其权重，再结合数据和专家意见建立决策变量矩阵的评分体系。
接下来，根据我们确定的指标，我们进行了多目标编程，共有3个指标，包括生态、环境和经济。
总共有三个指标，包括生态、经济和社会效益作为决策变量。
在解决了帕累托最优后，得到了最终的最优森林经营方案。

In the case study, we investigate forest carbon sequestration in the Mohe forest area in northern
Greater Khingan Mountains, China. According to model 1, based on the forestry data of Greater
Khingan Mountains, we calculate the carbon sequestration in Mohe forest area of Greater Khingan
Mountains in the next 100 years using matlab. According to model 2, we designe a reasonable and
optimized forest management plan. Finally, we extended the 10-year rotation period and explored
the timeline transition strategy.

> 在该案例研究中，我们调查了中国大兴安岭北部漠河林区的森林碳汇情况。
根据模型1，基于大兴安岭的林业数据，我们用matlab计算了大兴安岭漠河林区在未来100年的固碳量。
根据模型2，我们设计了一个合理和优化的森林管理计划。
最后，我们延长了10年的轮伐期并探讨了时间线过渡策略。

At the end of the article, we perform a sensitivity analysis, analyze the strengths and weaknesses
of the model, and consider directions for further improving.

> 在文章的最后，我们进行了灵敏度分析，并且分析了模型的优点和缺点，并考虑进一步改进的方向。
