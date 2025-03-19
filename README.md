# Traffic-prediction-models-GNN
This work presents a comprehensive repository for classic and cutting-edge graph neural network (GNN)-based traffic flow prediction models. 

⚠️ **Note: The implementation of some models is currently being updated. We appreciate your patience.** ⚠️

---

## Introduction

Traffic flow prediction is a critical task in intelligent transportation systems, urban planning, and traffic management. Graph neural networks (GNNs) have emerged as a powerful tool for modeling spatial-temporal dependencies in traffic data. This repository collects and organizes implementations of classic and cutting-edge GNN-based traffic flow prediction models, making it easier for researchers and practitioners to explore, compare, and build upon existing work.

---

## Models Included

Below is a list of models currently included (or planned) in this repository:

- **STGCN** (Spatio-Temporal Graph Convolutional Networks)  
  A pioneering model combining graph convolutions and temporal convolutions for traffic prediction.
  
- **DCRNN** (Diffusion Convolutional Recurrent Neural Network)  
  A model leveraging diffusion processes on graphs to capture spatial dependencies, integrated with recurrent neural networks for temporal modeling.
  
- **ASTGCN** (Attention-based Spatio-Temporal Graph Convolutional Networks)  
  A model incorporating spatial and temporal attention mechanisms to enhance prediction performance.
  
- **GMAN** (Graph Multi-Attention Network)  
  A model utilizing multiple attention layers to capture complex spatio-temporal relationships in traffic data.
  
- **Graph-WaveNet**  
  A model combining graph convolutions with dilated causal convolutions to model long-term temporal dependencies.

### Planned Additions (Newer Models)
We are actively working on integrating more recent and advanced models, such as:
- **STSGCN** (Spatial-Temporal Synchronous Graph Convolutional Networks)  
- **MTGNN** (Multivariate Time-series Graph Neural Networks)  
- **DGCRN** (Dynamic Graph Convolutional Recurrent Network)  
- ... and more!

If you have suggestions for additional models to include, feel free to open an issue or submit a pull request!

---

## Getting Started

### Prerequisites
To run the models in this repository, you will need the following dependencies:
- Python
- PyTorch/Tensorflow
- NumPy, Pandas, SciPy, etc. 

### Clone the repository:
   ```bash
   git clone https://github.com/AIcharon-stt/Traffic-prediction-models-GNN.git
   cd TrafficFlowGNNHub
   ```

### Usage
Detailed instructions for running each model, including dataset preparation, training, and evaluation, will be provided in the respective model directories. Stay tuned for updates!

---

## Repository Structure

```
TrafficFlowGNNHub/
│
├── datasets/             # Sample datasets and data preprocessing scripts
├── models/               # Model implementations
│   ├── STGCN/            # STGCN model code
│   ├── DCRNN/            # DCRNN model code
│   ├── ASTGCN/           # ASTGCN model code
│   ├── GMAN/             # GMAN model code
│   ├── Graph-WaveNet/    # Graph-WaveNet model code
│   ├── Bi-TSENet/    # Bi-TSENet model code
│   └── ...               # More models to be added
├── utils/                # Utility functions (e.g., data loaders, evaluation metrics)
├── docs/                 # Additional documentation
├── requirements.txt      # List of dependencies
└── README.md             # This file
```

## License

This project is licensed under the MIT License - see the LICENSE file for details.

---

## Contact

For questions, suggestions, collaborations, or any copyright-related concerns, please feel free to reach out via email at ttshi3514@163.com or open an issue on GitHub.

Happy coding, and enjoy exploring the world of GNN-based traffic flow prediction!
```

---

