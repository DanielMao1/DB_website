+++
date = "2020-05-22T14:45:00+02:00"
title = "Query Optimization on Big Data System"
picture = "projects/system/system.png"
short_description="When the scale of data is very large, companies usually introduce distributed big data systems to analyze or process the data."
+++
When the scale of data is very large, companies usually introduce distributed big data systems to analyze or process the data. In order to facilitate the interaction of developers, there are usually some SQL-based systems like Hive and Flink. In this scenario, query processing time is an important metric for judging the quality of a system. In order to improve development and production efficiency and reduce operation and maintenance costs, optimizing these systems has become an important issue. We will conduct research from the following aspects

  * Optimize the components of the query optimizer, such as cardinality estimation, to make the optimizer's estimate of the query cost more accurate, so as to achieve a smaller cost query plan.
  * Introduce new hardware such as GPU into the big data system to improve the speed of physical query.