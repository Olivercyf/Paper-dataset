# Dataset
It is used to store some datasets based on my published papers.

## 1. [2017-2022 Nobel laurates in Physics.xlsx](https://github.com/Olivercyf/Paper-dataset/blob/main/2017-2022%20Nobel%20laurates%20in%20Physics.xlsx)
Li et al. (2019) ([Li et al.'s dataset](https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/6NJ5RN), [Li et al.'s paper](https://www.nature.com/articles/s41597-019-0033-6)) created a dataset about Nobel laureates. The dataset contains 193 Nobel laureates in Physics from 1902 to 2016, including the laureate’s name, award time, laureate’s paper title, paper publication time, Prize-winning paper label and other data. Here we supplemented the paper data of totally 18 laureates from 2017–2022 from Web of Science and Scopus, and identified these laureates’ Prize-winning papers according to the evaluation criteria proposed by Li et al. (2019).

**In the 2017-2022 Nobel laurates in Physics.xlsx:**
| Column name | Description |
|---|---|
|Laureate_ID|the laureate ID (according to the “Laureate ID” in Li et al.’s dataset)|
|Laureate_name|the name of the laureate|
|author_h|the h-index of the laureate (from the Scope)|
|Prize_year|the year when the laureate wins the prize|
|Prize_paper_year|the year when the Prize-winning paper is published|
|Title|the title of the paper|
|Pub_year|the publication year of the paper|
|Is_prize_winning_paper|yes or no|
|content|the abstract and citation of the paper|
|authors|the author name of the paper|

As the representative of prominent scientists, understanding the Nobel laureates’ research patterns throughout their careers are helpful to promote the science development. In our paper([Exploitation and exploration: An analysis of the research pattern of Nobel laureates in Physics](https://www.sciencedirect.com/science/article/pii/S1751157723000536?dgcid=coauthor)), we use the BERT model to vectorize the laureates’ papers and calculate the similarity matrices among them, and detect the research topics of each laureate by Affinity Propagation clustering. We further propose relevant indexes based on Kuhn's ‘essential tension’ hypothesis and divide the laureates’ research topics into the Prize-winning topic, the topic semantically closest to the Prize-winning topic, and other non-Prize-winning topics. The empirical analysis of 117 Nobel laureates in Physics shows that they have a similar research pattern, that is, they tend to explore 2 to 3 topics alternately in different periods, but they usually identify the core research topics early and mainly focus on exploiting them throughout their careers, and other non-Prize-winning topics they explore are often related in some way to the Prize-winning ones.

## 2. 多源数据特征级融合方法相关论文收集与人工分类结果.xlsx
特征级融合是将从大量原始数据中提取的描述同一研究对象的多个特征进行融合的一系列方法技术，其目的是得到比单一特征更全面、综合的结果。由于特征级融合方法广泛运用于不同学科，但彼此间研究差异较大，对具体学科进行系统综述从而提出有针对性的发展路径将更有意义，以2011-2022年图书情报领域多源数据特征级融合方法的相关文章为研究对象，中文数据来源为CNKI “图书情报与数字图书馆”学科分类下期刊，检索式为篇名or关键词or摘要 =（多源数据+数据融合+信息融合+关系融合+多维融合+特征融合+特征级融合+特征整合）；英文数据来源为Web of Science中“INFORMATION SCIENCE & LIBRARY SCIENCE”学科分类下期刊，检索式为篇名or关键词or摘要 =（multi*source* OR data fus* OR informat* fus* OR relation* fus* OR multidimens* fus* OR feature* fus* OR feature* integrat*）。在文献阅读过程中，根据文献引用关系不断扩展文献范围，总共获得107篇相关文献 。



