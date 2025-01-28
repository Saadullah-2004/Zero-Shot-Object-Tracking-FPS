# Zero-Shot Object Tracking in First-Person Gaming

## Team Members
- Tanish Roy
- Dev Shah
- Saadullah Shazad
- Inaam Azeezur-Rahman

## Project Overview
This project focuses on developing a **zero-shot object tracking system** optimized for **first-person gaming environments**. By leveraging **pre-trained models and semantic embeddings**, we aim to enable tracking of dynamic objects **without the need for extensive labeled training data**.

## Machine-Vision Problem
We are addressing the problem of **tracking objects in first-person gaming environments** with **zero-shot learning**. This is challenging due to:
- **Generalization to unseen objects** during inference.
- **Fast-changing perspectives** in FPS games.
- **Real-time performance requirements** for practical applications.

## Dataset
- **Dataset Name**: Doom-FPS Dataset  
- **Source**: [Doom Gameplay Dataset](https://github.com/thavlik/doom-gameplay-dataset)  
- **Description**: The dataset includes **170+ hours** of gameplay footage from **Doom 1 & Doom 2**, making it suitable for **object tracking, unsupervised learning, and video processing**.

## Motivation for This Project
This project is significant for several reasons:
- **Practical Applications**:
  - Real-time analytics for **e-sports and game streaming**.
  - Automated **game testing and debugging** for developers.
- **Technical Challenges**:
  - Requires **zero-shot learning** models to generalize effectively.
  - Must handle **motion blur, occlusions, and fast viewpoint changes**.
- **Skill Development**:
  - Hands-on experience with **transformer-based architectures**.
  - Understanding **object tracking in dynamic environments**.
- **Novel Contribution**:
  - Enhances **gaming-specific tracking models**.
  - Benchmarks **zero-shot learning for fast-moving objects**.

## Team Responsibilities
| Team Member         | Responsibility |
|---------------------|---------------|
| **Tanish Roy**     | Research object tracking architectures, select base models (CLIP, SAM), implement tracking algorithm |
| **Dev Shah**       | Conduct experiments, tune hyperparameters, optimize zero-shot framework |
| **Saadullah Shazad** | Handle dataset integration, preprocessing, and evaluation metrics |
| **Inaam Azeezur-Rahman** | Develop visualizations, document system design, and contribute to validation |

## Repository Setup
- **GitHub Repository**: [Zero-Shot-Object-Tracking-FPS](https://github.com/Saadullah-2004/Zero-Shot-Object-Tracking-FPS)
- **Who set it up?**: Saadullah Shazad
- **Dataset Access**: Downloaded and preprocessed by Saadullah Shazad

## Next Steps
1. Implement **object tracking pipeline**.
2. Fine-tune **pre-trained models** for gaming environments.
3. Validate and benchmark the **zero-shot tracking performance**.

## References
1. Vaswani, A., et al. *Attention Is All You Need.* NeurIPS, 2017. [Paper](https://arxiv.org/abs/1706.03762)
2. Radford, A., et al. *Learning Transferable Visual Models from Natural Language Supervision.* ICML, 2021. [Paper](https://arxiv.org/abs/2103.00020)
3. Doom Gameplay Dataset. [Repository](https://github.com/thavlik/doom-gameplay-dataset)

---
