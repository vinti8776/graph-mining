---
layout: post
title: Encoder-decoder
---
In graph-based deep learning, low-dimensional vector representations of nodes in a graph are known as node embeddings. The goal of node embeddings is to project graph nodes from their original feature space into lower-dimensional space to reduce computational complexity while retaining the structural and relational information of nodes in the graph. A key idea in graph-based deep learning, or more precisely in graph representation learning, is to learn these node embeddings.
# 1. Encoder-decoder framework
In graph representation learning, we leverage the encoder-decoder framework to facilitate a comprehensive understanding of the graph structure. It is achieved in two crucial steps. Firstly, an encoder model is employed to map each node in the graph to a compact, low-dimensional vector, known as embedding. These embeddings are then passed as input to a decoder model that aims to reconstruct the local neighbourhood information for each node in the original graph. By doing so, we obtain a rich and structured graph representation conducive to further analysis. The encoder-decoder framework is depicted in Figure
