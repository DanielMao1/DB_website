
+++
date = "2020-05-22T14:45:00+02:00"
title = "大规模相似性检索"
picture = "projects/similarity_search/main.jpg"
short_description="相似性检索是指对于一个给定的查询，在包含众多物品的数据集中，找出与其最相似物品的任务"
+++
相似性检索是指对于一个给定的查询，在包含众多物品的数据集中，找出与其最相似物品的任务。相似性检索是数据处理中最常见的操作之一，有着包括推荐、图片检索、文件检索和实体识别在内的众多应用。由于其广泛的应用，包括Google, Microsoft 和Facebook在内的众多公司都在开展相似性检索研究。但高效相似性检索面临着诸多挑战——数据集的规模很大，可以包含上亿个高维向量；检索对处理时延和结果质量的要求都很高，例如在10ms内召回率达到0.9. 在这个课题下，我们将从以下方面开展研究：
- 设计针对不同相似性度量的检索算法，包括欧氏距离，内积，编辑距离等；
- 利用先进硬件进行相似性检索，例如GPU, SSD 和NVM；
- 横跨多台服务器的分布式相似性检索；
- 用机器学习技术改善相似性检索算法。 
