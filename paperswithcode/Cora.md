# source
* Cora, Citeseer, PubMed: [Collective Classification in Network Data](https://xueshu.baidu.com/usercenter/paper/show?paperid=11a790b0c5ea7aba0f952d8d958f2245&site=xueshu_se)
# description
>* **Citation Networks.** In the citation network datasets Cora, Citeseer and Pubmed nodes represent
documents and edges represent citation links. The networks contain bag-of-words feature vectors for
each document. We treat the citation links as (undirected) edges. For training, we use 20 labels per
class.
>* **Social Network Datasets.** COLLAB is derived from three public scientific collaboration datasets.
Each graph corresponds to an ego-network of different researchers from each field with the task to
label each graph to the field the corresponding researcher belongs to. IMDB-BINARY is a movie
collaboration dataset where each graph corresponds to an ego-network of actors/actresses. An edge
is drawn between two actors/actresses if they appear in the same movie. The task is to infer the genre
of the graph. REDDIT-BINARY is an online discussion dataset where each graph corresponds to a
thread. An edge is drawn between two users if one of them responded to another’s comment. The
task is to label each graph to the community/subreddit it belongs to.
>* **Bioinformatic Datasets.** MUTAG is a dataset consisting of mutagenetic aromatic and heteroaromatic nitro compounds. PROTEINS holds a set of proteins represented by graphs. Nodes represent
secondary structure elements (SSEs) which are connected whenever there are neighbors either in the
amino acid sequence or in 3D space.
>* **3D Object Datasets.** ModelNet10 is an orientation-aligned dataset of CAD models. Each model
corresponds to exactly one out of 10 object categories. Categories were chosen based on a list of the
most common object categories in the world.
# statistics
![image](https://user-images.githubusercontent.com/51369075/97122626-3e09de00-1762-11eb-9b28-fa8b30b09a74.png)
# example
* [Cora, Citeseer, Pubmed](https://blog.csdn.net/qwezhaohaihong/article/details/106037641?utm_medium=distribute.pc_aggpage_search_result.none-task-blog-2~all~first_rank_v2~rank_v25-1-106037641.nonecase&utm_term=citeseer%E6%95%B0%E6%8D%AE%E9%9B%86%E6%8F%8F%E8%BF%B0&spm=1000.2123.3001.4430)
* please refer to the Internet for more details
# referenced by
[Fast Graph Representation Learning with PyTorch Geometric](https://arxiv.org/pdf/1903.02428v3.pdf)
