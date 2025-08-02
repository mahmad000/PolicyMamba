# 🚀 PolicyMamba: Localized Policy Attention with State Space Model for Land Cover Classification

[IEEE TNNLS 2025](https://img.shields.io/badge/published-TNNLS--2025-blue.svg)(https://ieeexplore.ieee.org/document/11090003)

PolicyMamba introduces a **novel spatial–spectral state space model** designed for **hyperspectral image (HSI)** classification. It tackles the limitations of traditional self-attention models by leveraging **localized policy attention**, **sparsity constraints**, and a **hierarchical aggregation strategy** offering an efficient, scalable, and accurate solution for Land Cover Classification (LCC).

> 🔎 **Note:** This repository provides a simplified and resource-friendly version of PolicyMamba. The reported results may slightly vary from the paper due to:
> - Strict use of disjoint training, validation, and test splits.
> - Exclusion of overlapping windowing for reduced computational cost.
> - Compatibility with low-resource systems.

## 📸 Model Overview

### 🌈 Architecture Summary
![PolicyMamba Overview](https://github.com/user-attachments/assets/79f22b23-9c81-4394-b36a-7140ddac6919)

![Token Enhancement](https://github.com/user-attachments/assets/2a22713a-557a-4878-bd88-143b7513f497)
- **Spectral–Spatial Tokenization** with attention gates
- **Localized Policy Attention** with sparsity control
- **State Space Transition** for long-range modeling
- **Hierarchical Aggregation** for global coherence

---

### 🧠 Token Enhancement Module
![Attention Comparison](https://github.com/user-attachments/assets/f2127b3e-f265-4049-9d71-f53d782b7ef3)

---

### 🪟 Sliding Window
![Sliding Window](https://github.com/user-attachments/assets/36e0b5c0-5d80-42be-9437-3455bb72bc88)

---

### 📊 Experimental Results

- **Salinas**: 99.59% OA
- **Houston**: 98.72% OA
- **Pavia University**: 99.66% OA
- **WHU-Hi-LongKou**: 99.67% OA

> 📌 Accuracy will vary with the lightweight repo version—focused on practical usability over benchmark-level tuning.

---

### 🔍 Comparison of Attention Mechanisms
![Token Enhancement Impact](https://github.com/user-attachments/assets/5f2b746c-cfe2-4c21-8327-998679ce5b44)

---

## 📂 Dataset Structure

Public datasets:
- [University of Houston](https://www.ehu.eus/ccwintco/index.php/Hyperspectral_Remote_Sensing_Scenes)
- Pavia University
- Salinas
- WHU-Hi-LongKou (UAV)

**Expected directory layout:**
```
Datasets/
├── University of Houston/
│   ├── UH.mat
│   └── UH_gt.mat
├── Pavia University/
│   ├── PU.mat
│   └── PU_gt.mat
...
```

---

## 📜 Citation

If you use this work, please cite the original paper:

```bibtex
@ARTICLE{11090003,
  author={Ahmad, Muhammad and Mazzara, Manuel and Distefano, Salvatore and Mehmood Khan, Adil and Hassaan Farooq Butt, Muhammad and Hong, Danfeng},
  journal={IEEE Transactions on Neural Networks and Learning Systems}, 
  title={PolicyMamba: Localized Policy Attention With State Space Model for Land Cover Classification}, 
  year={2025},
  pages={1-12},
  doi={10.1109/TNNLS.2025.3586836}
}
```

---
## 📬 Contact

For inquiries or feedback, open an issue or contact [@mahmad00](mailto:mahmad00@gmail.com)


