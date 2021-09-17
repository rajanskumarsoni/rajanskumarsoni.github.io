---
<!-- layout: archive -->
title: "Research"
permalink: /research/
author_profile: true
---
## <center>Abstract</center>
Hidden Markov models (HMMs) belong to the class of double embedded stochastic models which were originally leveraged for speech recognition and synthesis. HMMs subsequently became a generic sequence model across multiple domains like NLP, bio-informatics and thermodynamics to name a few. Literature has several heuristic metrics to compare two HMMs by factoring in their structure and emission probability distributions in HMM nodes. However, typical structure-based metrics overlook the similarity between HMMs having different structures yet similar behavior. Generally behavior-based metrics rely on the nature of the set of reference sequences used for assessing the similarity in behavior. Further, little exploration has taken place in leveraging the recent advancements in deep graph neural networks for learning effective representations for HMMs.\\
In this thesis, we propose two novel deep neural network based approaches to learn embeddings for HMMs and evaluate the validity of the embeddings based on subsequent clustering and classification tasks. Our proposed approaches use a Graph variational Autoencoder and diffpooling based Graph neural network (GNN) to learn embeddings for HMMs. The graph autoencoder infers latent low-dimensional flat embeddings for HMMs in a task-agnostic manner; whereas the diffpooling based graph neural network learns class-label aware embeddings by inferring and aggregating a hierarchical set of clusters and sub-clusters of graph nodes. Empirical results reveal that the HMM embeddings learnt through the Graph variational autoencoders and diffpooling based GNN outperform the popular heuristics as measured by the cluster quality metrics and the classification accuracy in downstream tasks.\\
## Research Publications
1. Rajan Kumar Soni, Karthick Seshadri, Balaraman Ravindran, *Metric Learning for comparison of HMMs using Graph Neural Networks*, **Published in ACML 2021**.
2. Rajan Kumar Soni, Karthick Seshadri, Balaraman Ravindran, *Exploring graph neural nets for representation learning: A case study in ergodic HMMs*, **Submitted to Graph Embedding and Mining workshop, ECML-PKDD 2021**.
       


