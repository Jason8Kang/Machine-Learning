**1.算法简介**

        AP\(Affinity Propagation\)通常被翻译为近邻传播算法或者亲和力传播算法，是在2007年的Science杂志上提出的一种新的聚类算法。AP算法的基本思想是将全部数据点都当作潜在的聚类中心\(称之为exemplar\)，然后数据点两两之间连线构成一个网络\(相似度矩阵\)，再通过网络中各条边的消息\(responsibility和availability\)传递计算出各样本的聚类中心。
