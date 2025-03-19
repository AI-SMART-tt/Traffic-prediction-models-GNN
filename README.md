# Traffic-prediction-models-GNN
This work presents a comprehensive repository for classic and cutting-edge graph neural network (GNN)-based traffic flow prediction models. 

⚠️ **Note: The implementation of some models is currently being updated. We appreciate your patience.** ⚠️

---

## Introduction

Traffic flow prediction is a critical task in intelligent transportation systems, urban planning, and traffic management. Graph neural networks (GNNs) have emerged as a powerful tool for modeling spatial-temporal dependencies in traffic data. This repository collects and organizes implementations of classic and cutting-edge GNN-based traffic flow prediction models, making it easier for researchers and practitioners to explore, compare, and build upon existing work.

---

## Models Included

Below is a list of models currently included (or planned) in this repository. For each model, we provide links to the original paper and the authors' official source code (if available):

- **STGCN** (Spatio-Temporal Graph Convolutional Networks)  
  A pioneering model combining graph convolutions and temporal convolutions for traffic prediction.  
  - 📄 [Paper](https://arxiv.org/abs/1709.04875)  
  - 💻 [Source Code](https://github.com/VeritasYin/STGCN_IJCAI-18)  

- **DCRNN** (Diffusion Convolutional Recurrent Neural Network)  
  A model leveraging diffusion processes on graphs to capture spatial dependencies, integrated with recurrent neural networks for temporal modeling.  
  - 📄 [Paper](https://arxiv.org/abs/1707.01926)  
  - 💻 [Source Code](https://github.com/liyaguang/DCRNN)  

- **ASTGCN** (Attention-based Spatio-Temporal Graph Convolutional Networks)  
  A model incorporating spatial and temporal attention mechanisms to enhance prediction performance.  
  - 📄 [Paper](https://arxiv.org/abs/1806.01286)  
  - 💻 [Source Code](https://github.com/guoshnBJTU/ASTGCN-r-pytorch)  

- **GMAN** (Graph Multi-Attention Network)  
  A model utilizing multiple attention layers to capture complex spatio-temporal relationships in traffic data.  
  - 📄 [Paper](https://arxiv.org/abs/1910.03033)  
  - 💻 [Source Code](https://github.com/zhengchuanpan/GMAN)  

- **Graph-WaveNet**  
  A model combining graph convolutions with dilated causal convolutions to model long-term temporal dependencies.  
  - 📄 [Paper](https://arxiv.org/abs/1906.00121)  
  - 💻 [Source Code](https://github.com/nnzhan/Graph-WaveNet)  

- **T-GCN** (Temporal Graph Convolutional Network)  
  An early spatio-temporal GNN model combining GCN and GRU to capture spatial and temporal dependencies in traffic flow.  
  - 📄 [Paper](https://arxiv.org/abs/1811.05320)  
  - 💻 [Source Code](https://github.com/lehaifeng/T-GCN)  

- **AGCRN** (Adaptive Graph Convolutional Recurrent Network)  
  A model proposing an adaptive graph structure learning framework, combining GCN and RNN, suitable for dynamic traffic networks.  
  - 📄 [Paper](https://arxiv.org/abs/2007.02842)  
  - 💻 [Source Code](https://github.com/LeiBAI/AGCRN)  

### Planned Additions (Newer Models)
We are actively working on integrating more recent and advanced models, such as:

- **STSGCN** (Spatial-Temporal Synchronous Graph Convolutional Networks)  
  - 📄 [Paper](https://arxiv.org/abs/1906.06971)  
  - 💻 [Source Code](https://github.com/Davidham3/STSGCN)  

- **MTGNN** (Multivariate Time-series Graph Neural Networks)  
  - 📄 [Paper](https://arxiv.org/abs/2004.02038)  
  - 💻 [Source Code](https://github.com/nnzhan/MTGNN)  

- **DGCRN** (Dynamic Graph Convolutional Recurrent Network)  
  - 📄 [Paper](https://arxiv.org/abs/2104.14917)  
  - 💻 [Source Code](https://github.com/tsinghua-fib-lab/DGCRN)  

- **GTS** (Graph Traffic Speed Prediction)  
  A model utilizing GCN and attention mechanisms to capture complex spatio-temporal patterns in traffic speed prediction.  
  - 📄 [Paper](https://arxiv.org/abs/2001.06874)  
  - 💻 [Source Code](https://github.com/hkbu-libra/GTS)  

- **STGODE** (Spatio-Temporal Graph Ordinary Differential Equation)  
  A model leveraging graph ordinary differential equations (ODE) to model continuous spatio-temporal dynamics in traffic flow.  
  - 📄 [Paper](https://arxiv.org/abs/2108.04040)  
  - 💻 [Source Code](https://github.com/ZhuangWeilin/STGODE)  

- **STFGNN** (Spatio-Temporal Fusion Graph Neural Network)  
  A model fusing multi-scale spatio-temporal features for complex traffic flow prediction tasks.  
  - 📄 [Paper](https://arxiv.org/abs/2103.16160)  
  - 💻 [Source Code](https://github.com/KB5201314/STFGNN)  

- **PDFormer** (Patch-based Dual-Former)  
  A model combining Transformer and GCN, modeling spatio-temporal dependencies through patch-based techniques.  
  - 📄 [Paper](https://arxiv.org/abs/2205.13982)  
  - 💻 [Source Code](https://github.com/BUAABIGSCity/PDFormer)  

- ... and more!

If you have suggestions for additional models to include, feel free to open an issue or submit a pull request!

---

## Getting Started

### Prerequisites
To run the models in this repository, you will need the following dependencies:
- Python
- PyTorch/TensorFlow
- NumPy, Pandas, SciPy, etc. 

### Clone the repository:
   ```bash
   git clone https://github.com/AIcharon-stt/Traffic-prediction-models-GNN.git
   cd TrafficFlowGNNHub
---
---

---

## Models Included

Below is a list of models currently included (or planned) in this repository:

- **STGCN** (Spatio-Temporal Graph Convolutional Networks)  
  [Paper](https://arxiv.org/abs/1709.04875) | [Original Code](https://github.com/VeritasYin/STGCN_IJCAI-18)  
  A pioneering model combining graph convolutions and temporal convolutions for traffic prediction.
  
- **DCRNN** (Diffusion Convolutional Recurrent Neural Network)  
  [Paper](https://arxiv.org/abs/1707.01926) | [Original Code](https://github.com/liyaguang/DCRNN)  
  A model leveraging diffusion processes on graphs to capture spatial dependencies, integrated with recurrent neural networks for temporal modeling.
  
- **ASTGCN** (Attention-based Spatio-Temporal Graph Convolutional Networks)  
  [Paper](https://ojs.aaai.org/index.php/AAAI/article/view/3881) | [Original Code](https://github.com/Davidham3/ASTGCN)  
  A model incorporating spatial and temporal attention mechanisms to enhance prediction performance.
  
- **GMAN** (Graph Multi-Attention Network)  
  [Paper](https://aaai.org/papers/04942-gman-a-graph-multi-attention-network-for-traffic-prediction/) | [Original Code](https://github.com/zhengchuanpan/GMAN)  
  A model utilizing multiple attention layers to capture complex spatio-temporal relationships in traffic data.
  
- **Graph-WaveNet**  
  [Paper](https://arxiv.org/abs/1906.00121) | [Original Code](https://github.com/nnzhan/Graph-WaveNet)  
  A model combining graph convolutions with dilated causal convolutions to model long-term temporal dependencies.

- **AGCRN** (Adaptive Graph Convolutional Recurrent Network)  
  [Paper](https://arxiv.org/abs/2007.02842) | [Original Code](https://github.com/LeiBAI/AGCRN)  
  A model that simultaneously learns the graph structure and spatio-temporal dependencies with node-adaptive parameters.

- **MTGNN** (Multivariate Time Series Forecasting with Graph Neural Networks)  
  [Paper](https://arxiv.org/abs/2005.11650) | [Original Code](https://github.com/nnzhan/MTGNN)  
  A model that learns a graph structure adaptively while capturing temporal dependencies through dilated convolutions.

- **STSGCN** (Spatial-Temporal Synchronous Graph Convolutional Networks)  
  [Paper](https://aaai.org/papers/05354-spatial-temporal-synchronous-graph-convolutional-networks-a-new-framework-for-spatial-temporal-network-data-forecasting/) | [Original Code](https://github.com/Davidham3/STSGCN)  
  A framework that captures localized spatio-temporal correlations through synchronous modeling.

- **D2STGNN** (Decoupled Dynamic Spatial-Temporal Graph Neural Network)  
  [Paper](https://arxiv.org/abs/2206.09112) | [Original Code](https://github.com/zezhishao/D2STGNN)  
  A model that decouples spatial and temporal dependencies while considering dynamic spatial correlations.

- **STFGNN** (Spatial-Temporal Fusion Graph Neural Networks)  
  [Paper](https://arxiv.org/abs/2012.09641) | [Original Code](https://github.com/MengzhangLI/STFGNN)  
  A model that explicitly models the fusion of spatial and temporal relations through a novel graph structure.

### Planned Additions (Newer Models)
We are actively working on integrating more recent and advanced models, such as:

- **STGNCDE** (Spatio-Temporal Graph Neural Controlled Differential Equations)  
  [Paper](https://arxiv.org/abs/2106.10636) | [Original Code](https://github.com/jeongwhanchoi/STG-NCDE)  
  A continuous-time model based on neural controlled differential equations for irregular spatio-temporal data.

- **ST-GDN** (Spatial-Temporal Graph Diffusion Network)  
  [Paper](https://dl.acm.org/doi/10.1145/3503161.3548236) | [Original Code](https://github.com/zezhishao/STGDN)  
  A model employing graph diffusion processes to capture multi-scale spatial dependencies.

- **DSTAGNN** (Dynamic Spatio-Temporal Aware Graph Neural Network)  
  [Paper](https://ieeexplore.ieee.org/document/9746711) | [Original Code](https://github.com/StevenLOL/DSTAGNN)  
  A model that incorporates dynamic graph structures and temporal attention for improved prediction.

- **PDFormer** (Physical-informed Dual-graph Transformer)  
  [Paper](https://arxiv.org/abs/2303.09909) | [Original Code](https://github.com/BUAABIGSCity/PDFormer)  
  A physics-informed transformer architecture utilizing dual graph structures.

- **STEP** (Spatio-Temporal Graph Neural Networks with Particular Reference)  
  [Paper](https://arxiv.org/abs/2208.11876) | [Original Code](https://github.com/HKUDS/STEP)  
  A model that leverages particular reference mechanisms to enhance prediction accuracy.

- **STID** (Spatial-Temporal Identity)  
  [Paper](https://arxiv.org/abs/2306.08244) | [Original Code](https://github.com/zezhishao/STID)  
  A lightweight approach that emphasizes spatial and temporal identity embeddings.

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

If you believe any content in this repository infringes upon your copyright or intellectual property rights, please contact us immediately so we can address your concerns appropriately.

Happy coding, and enjoy exploring the world of GNN-based traffic flow prediction!

