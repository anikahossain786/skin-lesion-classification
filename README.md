
##  Project Overview: Skin Lesion Classification Using CNN & RetNet Ensemble

### Introduction

This project presents a deep learning-based approach for the **automatic classification of skin lesions** using an ensemble of two neural network architectures: **Convolutional Neural Networks (CNN)** and **RetNet (Multi-head Attention-based Network)**. The goal is to improve the early detection of skin cancer by classifying lesion images into multiple diagnostic categories.

### Objective

To develop a robust, accurate, and efficient classification system that can:

* Process dermoscopic images of skin lesions.
* Leverage both convolutional features and attention mechanisms.
* Improve diagnostic accuracy using model ensembling.

### Methodology

1. **CNN Model**

   * Extracts local and spatial features using convolutional layers.
   * Achieves high baseline accuracy and precision.

2. **RetNet Model**

   * Uses a Reshape + Multi-head Attention mechanism to capture contextual relationships.
   * Complements the CNN by focusing on non-local dependencies.

3. **Ensemble Model**

   * Combines predictions from both models using average pooling.
   * Improves performance through model diversity.

### Results

| Model        | Accuracy   | Precision  | Recall     | F1 Score   |
| ------------ | ---------- | ---------- | ---------- | ---------- |
| CNN          | 96.07%     | 96.25%     | 96.03%     | 96.01%     |
| RetNet       | 79.99%     | 80.10%     | 80.00%     | 79.87%     |
| **Ensemble** | **95.63%** | **95.78%** | **95.59%** | **95.52%** |

The ensemble approach balances the strengths of both models and delivers a more stable and accurate classification result.

### Implementation

* Built and trained entirely in **Google Colab**.
* Implemented using **TensorFlow / Keras**.
* Final model and evaluation metrics are available in the notebook.

🔗 **Notebook Link**:
[Skin Lesion Classification - Colab](https://colab.research.google.com/drive/16kqPlAJC-RXuhF0T0TsV0CLUZ_fmz5JE?usp=sharing)

### Conclusion

The project successfully demonstrates the benefit of combining CNN and attention-based architectures for medical image classification. The ensemble model shows strong performance and can serve as a foundational tool for AI-assisted dermatological diagnostics.

