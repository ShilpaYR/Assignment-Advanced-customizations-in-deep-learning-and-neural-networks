
# Advanced Customizations in Deep Learning and Neural Networks

This repository contains a structured set of Google Colab notebooks demonstrating advanced concepts in deep learning using both **TensorFlow/Keras** and **PyTorch**.

---

# Repository Structure

## Part 1 — Data Augmentation and Generalization

| Notebook | Description |
|--------|-------------|
| Notebook 1 | TensorFlow: Regularization techniques (L1, L2, Dropout, EarlyStopping, MC Dropout, BatchNorm, Initialization, Callbacks, TensorBoard, Keras Tuner) |
| Notebook 2 | PyTorch: Equivalent regularization techniques and comparisons |
| Notebook 3 | Image augmentation and classification (TensorFlow + KerasCV) |
| Notebook 4 | Multi-modal augmentation (image, text, time series, tabular, speech, document, video) |

---

## Part 1 Mapping to Requirements

| Requirement | Notebook |
|------------|---------|
| L1 / L2 regularization | Notebook 1, 2 |
| Dropout / MC Dropout | Notebook 1, 2 |
| Early stopping | Notebook 1 |
| Initialization strategies | Notebook 1 |
| Batch normalization | Notebook 1 |
| Custom dropout / regularization | Notebook 1 |
| TensorBoard & callbacks | Notebook 1 |
| Keras tuner | Notebook 1 |
| Image augmentation | Notebook 3 |
| Multi-modal augmentation | Notebook 4 |

---

## Part 2 — Advanced Deep Learning Constructs

| Notebook | Description |
|--------|-------------|
| Notebook 5 | TensorFlow custom components (loss, metric, activation, initializer, regularizer, constraint) |
| Notebook 6 | Advanced TensorFlow models (custom layers, scheduler, TensorBoard, residual models) |
| Notebook 7 | Custom optimizer, training loop, and Weights & Biases |
| Notebook 8 | Advanced PyTorch concepts (custom model, loss, loop, scheduler, W&B, TensorBoard) |

---

## Part 2 Mapping to Requirements

| Requirement | Notebook(s) |
|------------|-------------|
| Custom learning rate scheduler | 6, 8 |
| Custom dropout | 6 |
| Custom normalization | 6 |
| TensorBoard | 6, 7, 8 |
| Custom loss function | 5, 8 |
| Custom activation / initializer / regularizer / constraint | 5 |
| Custom metric | 5, 8 |
| Custom layers | 6, 8 |
| Custom model | 6, 8 |
| Custom optimizer | 7, 8 |
| Custom training loop | 7, 8 |
| Weights & Biases | 7, 8 |

---

# Key Highlights

- Clear A/B comparisons between baseline and advanced techniques
- Consistent structure across notebooks
- Lightweight datasets for fast execution in Colab
- Coverage of both TensorFlow and PyTorch ecosystems
- Includes visualization, logging, and experiment tracking

---

# How to Run

1. Open each notebook in Google Colab
2. Run cells sequentially
3. Enable GPU if desired
4. For W&B:
   - Default mode is offline
   - Switch to online mode for full tracking

---

# Summary

- Part 1 focuses on **generalization and augmentation**
- Part 2 focuses on **custom deep learning internals**
- Combined, the notebooks demonstrate both **practical usage** and **low-level understanding** of deep learning systems

---

# End of README
