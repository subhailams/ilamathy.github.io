---
layout: page
title: Multimodal Image Recommendation using GNN
description: Graph Neural Network for Pinterest image recommendation with text, graph, and image embeddings
img: assets/img/pinterest-gnn.jpg
importance: 5
category: work
github: https://github.com/subha-ilamathy/Pinterest-Multimodal-Image-Retrieval-using-GNN
---

## Problem
Graph-only link prediction based solely on structural properties fails to capture the semantic complexity of Pinterest's visual ecosystem. Images need semantic understanding beyond graph structure.

## Solution
This project tackles the link prediction challenge for Pinterest by combining text, graph, and image embeddings to recommend images. By integrating multimodal data, the system understands both visual content and user behavior patterns.

## Key Features
- **Multimodal Embeddings**: Text (CLIP), Image (ResNet/CLIP), and Graph (Node2Vec)
- **Graph Neural Networks**: GCN and GraphSAGE for link prediction
- **Semantic Understanding**: CLIP for vision-language alignment
- **Scalable Architecture**: Handles large-scale Pinterest data

## Technical Implementation
- **Tech Stack**: PyTorch Geometric, CLIP, GNN, Graph Neural Networks, Machine Learning, Transformers
- **Data Processing**: Pinterest dataset with image-text pairs
- **Model Training**: Multi-task learning with embedding fusion
- **Evaluation**: Link prediction accuracy and recommendation quality

## Results
- Improved recommendation accuracy over graph-only approaches
- Better handling of cold-start problems
- Captured semantic relationships between images

**Type**: Master's Project  
**Repository**: [GitHub](https://github.com/subha-ilamathy/Pinterest-Multimodal-Image-Retrieval-using-GNN)
