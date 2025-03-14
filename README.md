# Deep Belief Networks (DBNs) & Unsupervised Pretraining

## 📌 Project Overview
This project focuses on **training Restricted Boltzmann Machines (RBMs) and Deep Belief Networks (DBNs)** for **image recognition and generative modeling**. The study evaluates **unsupervised pretraining using contrastive divergence (CD-1)** and its impact on **stability, classification accuracy, and feature learning**.

## 🛠️ Technologies & Tools Used
- **Programming Language**: Python
- **Libraries**: NumPy, Matplotlib
- **Dataset**: MNIST Handwritten Digits
- **Training Method**: Contrastive Divergence (CD-1)
- **Evaluation Metrics**: Reconstruction Loss, Hidden Unit Activation Patterns, Classification Accuracy

## 🔍 Key Features
### **🔄 Restricted Boltzmann Machines (RBMs)**
- **Monitored stability** using reconstruction loss and weight/bias update norms.
- **Analyzed hidden unit activations** to understand feature learning.
- **Tested different hidden unit sizes (200-500 nodes)** to compare performance.

### **📈 Deep Belief Network (DBN) Pretraining**
- **Implemented greedy layer-wise pretraining** to build hierarchical feature representations.
- **Measured classification accuracy** on MNIST (**Train: 84.28%, Test: 84.21%**).
- **Examined generative capabilities** using different **probabilistic vs. binary sampling strategies**.

### **🖼️ Image Reconstruction & Generation**
- Evaluated **reconstruction loss trends** across different DBN layers.
- **Generated images** using probabilistic and binary sampling, highlighting trade-offs in convergence and pattern clarity.

## 📊 Results
✔️ **Higher hidden unit counts improve reconstruction accuracy**, reducing loss significantly.  
✔️ **Greedy layer-wise pretraining stabilizes DBN training**, achieving **84.21% classification accuracy**.  
✔️ **Probabilistic sampling aids convergence** but can **trap the model in spurious patterns**.  
✔️ **Binary sampling introduces randomness**, improving robustness but slowing convergence.  

