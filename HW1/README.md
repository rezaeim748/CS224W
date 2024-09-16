
# CS224W - Colab 1: Learning Node Embeddings

This notebook focuses on writing a full pipeline for **learning node embeddings**. The project explores multiple graph statistics, transforms graph structures for machine learning tasks, and implements a node embedding model using PyTorch.

## Key Components:
1. **Karate Club Network**:
   - A classic graph in network science is used as the primary dataset.
   - Basic graph statistics are explored to understand the network.

2. **Graph Structure Transformation**:
   - The notebook demonstrates how to transform a graph structure into a PyTorch tensor, enabling machine learning operations on the graph.

3. **Node Embedding Model**:
   - A simplified version of a node embedding model is implemented.
   - This model is written from scratch in PyTorch, providing hands-on experience in developing such algorithms.
   - The model differs from DeepWalk and node2vec but offers valuable insights into node embedding techniques.

## How to Use:
1. **Clone the Repository**:
   ```bash
   git clone https://github.com/rezaeim748/CS224W
   ```

2. **Install Dependencies**:
   The notebook requires the following Python packages:
   ```bash
   pip install networkx torch
   ```

3. **Run the Notebook**:
   Open the notebook in a Jupyter environment or Google Colab and follow the steps in sequence:
   - Load the Karate Club Network.
   - Explore graph statistics.
   - Convert the graph into a PyTorch tensor.
   - Implement and train the node embedding model.
