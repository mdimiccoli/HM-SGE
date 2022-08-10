# HM-SGE
Learning grounded word meaning representations on similarity graphs (EMNLP 2021)

The repository contains our results and PyTorch code for the proposed algorithm described in our Learning grounded word meaning representations on similarity graphs EMNLP 2021 [paper](https://aclanthology.org/2021.emnlp-main.391.pdf).

## <sub> Abstract </sub>
This paper introduces a novel approach to learn visually grounded meaning representations of words as low-dimensional node embeddings on an underlying graph hierar-
chy. The lower level of the hierarchy models modality-specific word representations through dedicated but communicating graphs, while the higher level puts these representa-
tions together on a single graph to learn a representation jointly from both modalities. The topology of each graph models similarity relations among words, and is estimated jointly
with the graph embedding. The assumption underlying this model is that words sharing similar meaning correspond to communities in an underlying similarity graph in a low-
dimensional space. We named this model Hierarchical Multi-Modal Similarity Graph Embedding (HM-SGE). Experimental results validate the ability of HM-SGE to simulate human
similarity judgements and concept categorization, outperforming the state of the art. 
#



## <sub> code TBA soon </sub>

![diagram-1](https://github.com/mdimiccoli/HM-SGE/blob/7d3a1d877af6eb02247030500390376182546442/diagram-1.png)

## Citation

```js
@InProceedings{Dimiccoli_2021_EMNLP,
author = {Dimiccoli, Mariella and Wendt, Herwig and Battle, Pau},
title = {Learning grounded word meaning representations on similarity graphs},
booktitle = {The 2021 Conference on Empirical Methods in Natural Language Processing (EMNLP)},
month = {November},
year = {2021}
}
```
