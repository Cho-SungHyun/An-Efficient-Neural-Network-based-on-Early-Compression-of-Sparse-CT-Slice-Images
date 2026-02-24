# An Efficient Neural Network based on Early Compression of Sparse CT Slice Images

This repository highlights the research and architectural design for efficient medical image processing, as published in **IEEE Access**.

### 🚀 Key Achievement: 3.5x Speedup
The core of this research is a computationally efficient CNN architecture optimized for CT image sequences. It is specifically designed for environments with limited computing power (e.g., mobile/embedded devices) without sacrificing prediction accuracy.

**Performance Metric:** Achieved **~3.5x actual speedup** over ShuffleNet-v2 on real-world CT datasets.

### 🛠 Technical Innovations
To achieve high-speed inference on serial CT image slices, the proposed model implements:
- **Pointwise Convolution & Depth-wise Separable Convolution:** To drastically reduce the number of parameters and floating-point operations.
- **Channel Shuffle Operations:** To maintain cross-channel information flow while minimizing computational overhead.
- **Optimized for Sparse Data:** Tailored to handle the unique characteristics of CT slice sequences efficiently.

### 🔗 Official Publication
The full methodology, experiments, and results are available via the official IEEE Xplore link:
**[Read the Full Paper on IEEE Xplore](https://ieeexplore.ieee.org/abstract/document/9680749)**

---
### Why this matters for Production ML:
This project demonstrates my ability to not only build accurate models but to **optimise for production constraints**. Whether it's medical imaging or high-throughput ad-tech requests, I focus on delivering state-of-the-art performance within strict latency and compute budgets.
