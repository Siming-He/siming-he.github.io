---
name: Are we really making much progress? Revisiting, benchmarking, and refining heterogeneous graph neural networks
tools: [Graph Neural Network, KDD 2021]
description: Qingsong Lv, Ming Ding, Qiang Liu, Yuxiang Chen, Wenzheng Feng, Siming He, Chang Zhou, Jianguo Jiang, Yuxiao Dong, Jie Tang
---

# Are we really making much progress? Revisiting, benchmarking, and refining heterogeneous graph neural networks

<a href="https://www.aminer.org/profile/qingsong-lv/542fe2c4dabfae3edd538e71" target="_blank">Qingsong Lv</a>, <a href="https://ming-ding.weebly.com/" target="_blank">Ming Ding</a>, Qiang Liu, Yuxiang Chen, Wenzheng Feng, <b>Siming He</b>, Chang Zhou, Jianguo Jiang, Yuxiao Dong, <a href="https://keg.cs.tsinghua.edu.cn/jietang/" target="_blank">Jie Tang</a><br>

{% include elements/button.html link="https://github.com/THUDM/HGB" text="Code" %}
{% include elements/button.html link="https://keg.cs.tsinghua.edu.cn/jietang/publications/KDD21-Lv-et-al-HeterGNN.pdf" text="Paper" %}

<b>Abstract: </b> Heterogeneous graph neural networks (HGNNs) have been blos-
soming in recent years, but the unique data processing and eval-
uation setups used by each work obstruct a full understanding of
their advancements. In this work, we present a systematical repro-
duction of 12 recent HGNNs by using their official codes, datasets,
settings, and hyperparameters, revealing surprising findings about
the progress of HGNNs. We find that the simple homogeneous
GNNs, e.g., GCN and GAT, are largely underestimated due to im-
proper settings. GAT with proper inputs can generally match or
outperform all existing HGNNs across various scenarios. To facil-
itate robust and reproducible HGNN research, we construct the
Heterogeneous Graph Benchmark (HGB), consisting of 11 diverse
datasets with three tasks. HGB standardizes the process of hetero-
geneous graph data splits, feature processing, and performance
evaluation. Finally, we introduce a simple but very strong baseline
Simple-HGN—which significantly outperforms all previous models
on HGB—to accelerate the advancement of HGNNs in the future.