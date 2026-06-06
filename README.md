# MNIST-with-MLP
# Digit Recognizer — Kaggle Competition

My first deep learning project from scratch, built while learning PyTorch step by step.

## What is this?

A model that recognizes handwritten digits (0-9) from the [Kaggle Digit Recognizer](https://www.kaggle.com/competitions/digit-recognizer) competition. The dataset contains 42,000 labeled 28×28 grayscale images.

## What I built

An MLP (Multi-Layer Perceptron) trained on the MNIST-style data:

```
Input (784) → Linear(784→128) → ReLU → Linear(128→64) → ReLU → Linear(64→10)
```

**Validation accuracy: ~97%**

## What's covered in the notebook

- Loading and exploring the data (EDA)
- Normalization (pixel values scaled to 0–1)
- Building a custom PyTorch `Dataset` and `DataLoader`
- Train/validation split (80/20)
- MLP model definition with `nn.Module`
- Training loop with backpropagation
- Validation loop with accuracy tracking

## Stack

- Python
- PyTorch
- Pandas / NumPy
- Matplotlib

## Next steps

- [ ] CNN (Convolutional Neural Network) — better accuracy by preserving spatial structure
- [ ] Data augmentation
- [ ] Submission to Kaggle
