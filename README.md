# Chappie-vs-Tracy-ANN-Showdown-on-MNIST
Train and compare two hand-coded Artificial Neural Networks (ANNs) — Chappie and Tracy — on the full MNIST dataset (10 classes), from scratch using NumPy.
🧠 Dataset: MNIST (0–9 digits) Input size: 784 (28x28 flattened)

Output: 10 classes → one-hot encoded targets

Normalize pixel values (0–255 → 0–1)

Use train/test split from sklearn or keras.datasets

To make learning Artificial Neural Networks (ANNs) exciting, we introduce two digital warriors: Chappie and Tracy — each representing a different neural network architecture.

Chappie
Architecture: 1 hidden layer (784 → 64 → 10)

Personality: Fast, lightweight, and efficient.

Strengths:

Simpler structure

Trains quickly

Easier to visualize and debug

Weaknesses:

May struggle with complex patterns

Limited capacity to learn deep features

Tracy
Architecture: 2 hidden layers (784 → 128 → 64 → 10)

Personality: Smart, analytical, and detail-oriented.

Strengths:

Learns more abstract features

Can model complex relationships

Higher flexibility and power

Weaknesses:

Takes longer to train

Slightly harder to tune

In this notebook, Tracy and Chappie go head-to-head on the MNIST battlefield! Let’s see who classifies handwritten digits better!
