# Dataset
It is used to store some datasets based on my published papers.

## 1. 2017-2022 Nobel laurates in Physics.xlsx
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
