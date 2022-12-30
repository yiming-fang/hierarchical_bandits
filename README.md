# Hierarchical Bandits for Music Recommendation
Final Project for Data-driven Decision Modeling (ORCS 4200) @ Columbia University

Multi-armed bandits (MABs) are a framework for sequential decision-making and are often used for building recommendation systems. However, in applications such as music recommendation, it is often the case that the dataset contains thousands of items to choose from; if each item is modeled as an individual arm, the learning process would become extremely inefficient or even infeasible.

In this project, we propose a novel recommendation scheme called hierarchical bandits, and apply the technique to a real-world music dataset. Hierarchical bandits alleviate the problem of large sample spaces by partitioning the sample space in a hierarchical way and breaking up the decision-making process into a group of decision-making choices with different levels of granularity. By doing so, we can ensure that each sub-sample space contains a reasonable number of choices, such that well-known algorithms such as ε-decreasing can be applied effectively.

For more information, please read https://github.com/yiming-fang/hierarchical_bandits/blob/main/Project_Report.pdf
