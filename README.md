# Assessing Recommender System Architectures: A Comparative Study of Collaborative Filtering, Graph-Based, and Hypergraph-Based Models

## Overview

This repository contains the implementation and analysis for the project "Assessing Recommender System Architectures: A Comparative Study of Collaborative Filtering, Graph-Based, and Hypergraph-Based Models." The study evaluates the performance of different recommender system architectures using the MovieLens 100k dataset. The architectures compared include collaborative filtering algorithms, graph-based models, and hypergraph-based models.

## Table of Contents

- [Overview](#overview)
- [Introduction](#introduction)
- [Research Questions](#research-questions)
- [Algorithms Implemented](#algorithms-implemented)
  - [Collaborative Filtering](#collaborative-filtering)
  - [Graph-Based Models](#graph-based-models)
  - [Hypergraph-Based Models](#hypergraph-based-models)
- [Results](#results)
- [Conclusion](#conclusion)
- [Future Work](#future-work)
- [Contributing](#contributing)


## Introduction

In recent years, recommender systems have become integral to enhancing user experiences across various digital platforms, especially in the entertainment industry. This project evaluates the efficacy of different recommender system architectures by leveraging the MovieLens 100k dataset. The study aims to provide a comprehensive exploration of the strengths and limitations of collaborative filtering, graph-based, and hypergraph-based models.

## Research Questions

1. Which recommender system architecture—collaborative filtering, graph-based, or hypergraph-based—delivers the most accurate and relevant movie recommendations?
2. How effectively does each model address the cold-start problem with new users?
3. Which model delivers the most reliable recommendations when faced with sparse data environments?

## Algorithms Implemented

### Collaborative Filtering

- **KNNBasic**: Implemented with Pearson similarity, this algorithm is effective in user-based collaborative filtering.
- **SVD**: A matrix factorization approach known for its accuracy and robustness in recommendation tasks.
- **CoClustering**: Clustered users and items simultaneously into co-clusters, leveraging the similarities within and across these clusters to make recommendations.

### Graph-Based Models

- **LightGCN**: Leverages graph convolutional networks to improve recommendation accuracy.
- **Graph Attentiion Network (GAT)**: Utilizes attention mechanisms to weigh the importance of different neighboring nodes, enhancing the quality of node embeddings for recommendation.
- **GraphSAGE**: Generates node embeddings by sampling and aggregating features from a node's local neighborhood.

### Hypergraph-Based Models

- **HyperGCN**: Captures higher-order relationships in the data through hypergraph structures.
- **Node2Vec**: Generates node embeddings through biased random walks, capturing diverse network features.

## Results

The results section contains a detailed analysis of each algorithm's performance based on metrics such as RMSE, MAE, Precision@10, and Recall@10. Please refer to the [results] directory for the full analysis.

## Conclusion

This study highlights that while each model has its strengths, the choice of recommender system architecture should consider specific application contexts, such as accuracy, running time, and suitability for real-time applications.

## Future Work

Future research can explore several avenues:

1. Further tuning hyperparameters for graph-based and hypergraph-based models.
2. Investigating the scalability of these models with larger datasets and real-world applications.
3. Developing a design space framework for recommender systems to suggest the most suitable algorithms based on dataset characteristics.


## Contributing

Contributions are welcome! Please open an issue or submit a pull request for any improvements or new features.

