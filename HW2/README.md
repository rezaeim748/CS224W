
# CS224W - Colab 2: Constructing Graph Neural Networks with PyTorch Geometric

In this Colab, you will build and train your own **Graph Neural Network (GNN)** using PyTorch Geometric (PyG) and apply the model to two tasks using datasets from the **Open Graph Benchmark (OGB)**. These tasks involve node property prediction and graph property prediction.

## Key Components:
1. **PyTorch Geometric (PyG)**:
   - The notebook introduces how PyTorch Geometric stores graph data as PyTorch tensors, enabling efficient machine learning on graphs.

2. **Open Graph Benchmark (OGB) Datasets**:
   - Two datasets from OGB are used to benchmark the performance of your GNN model.
   - **Node Property Prediction**: Predicting properties of individual nodes.
   - **Graph Property Prediction**: Predicting properties of entire graphs or subgraphs.
   - The `ogb` package is used to load datasets and evaluate models.

3. **Graph Neural Network Construction**:
   - You will construct a GNN model from scratch using PyTorch Geometric.
   - The model will be trained and evaluated on both node and graph property prediction tasks.

## Instructions:
1. **Set Hardware Accelerator to GPU**:
   - To speed up the process, ensure that the runtime is set to **GPU**.
   - Navigate to `Runtime` → `Change runtime type` → Set `Hardware Accelerator` to **GPU**.

2. **How to Run**:
   1. **Clone the Repository**:
      ```bash
      git clone <repository-url>
      ```

   2. **Install Dependencies**:
      Make sure the required libraries, such as PyTorch, PyTorch Geometric, and OGB, are installed:
      ```bash
      pip install torch torch-geometric ogb
      ```

   3. **Run the Notebook**:
      Follow the notebook step-by-step:
      - Set up the environment.
      - Load and inspect the OGB datasets.
      - Construct, train, and evaluate your GNN model on node and graph property prediction tasks.

## Notes:
- The Colab is expected to take around 2 hours, though debugging may extend the time.
- Make sure to sequentially run all cells so that intermediate variables and packages carry over properly.
