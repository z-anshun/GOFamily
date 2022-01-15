# 贪心算法
贪心算法的核心是 每次局部的最优解都可以是最终解的最优解。

贪心算法的应用场景较少，跟dp比简直就是弟弟。

dp的话核心就是记录每次的选择，然后综合起来选择一个真的全局最优。

分治法是指将问题划分成一些独立的子问题，递归的求解各子问题，然后合并子问题的解而得到原问题的解。与此不同，动态规划适用于子问题独立且重叠的情况，也就是各子问题包含公共的子子问题。在这种情况下，若用分治法则会做许多不必要的工作，即重复地求解公共的子问题。动态规划算法对每个子子问题只求解一次，将其结果保存在一张表中，从而避免每次遇到各个子问题时重新计算答案。

所以其实分治的颗粒度更大一些，它只不过要求我们分而治之，并没有太多的限制。然而dp或者贪心，他们的核心思想都是最优解的问题。尤其是动态规划它是要求各个问题相对独立又相对重叠，独立是指各个子问题不会对上个问题又影响，重叠是说，每一个子问题，都相对整个问题是相同类型的问题。分治法 —— 各子问题独立；动态规划 —— 各子问题重叠。