# Avalanche-an-end-to-end-library-for-continual-learning
## Continual Learning Evaluation with Avalanche Library
### Introduction
**This repository explores the evaluation of continual learning strategies using the Avalanche library. Continual learning is crucial for AI systems to retain knowledge from sequential data streams without catastrophic forgetting. The project evaluates three strategies—Naive, Replay, and GDumb—across benchmark datasets: MNIST, FashionMNIST, and CIFAR-100.**

### Key Features
Continual Learning Strategies: Implemented Naive, Replay, and GDumb strategies.
Datasets: Evaluated on MNIST, FashionMNIST, and CIFAR-100 datasets.
Avalanche Library: Utilized Avalanche for evaluation and benchmarking.
Evaluation Metrics: Analyzed accuracy over time, consistency across classes, and training dynamics.
### Installation
Clone the repository:
git clone (https://github.com/Usamaahmad06/Avalanche-an-end-to-end-library-for-continual-learning)

#### Install dependencies:
pip install -r requirement.txt

### Project Structure
train.py: Main script for training and evaluating continual learning strategies.
utils.py: Utility functions for data preprocessing and model evaluation.
results/: Directory containing results and plots of accuracy over time.
docs/: Documentation files, including the technical report and research paper.

**Results and Analysis**
The project evaluates the performance of continual learning strategies based on the following criteria:

_Accuracy Over Time_: Monitored how accuracy changes with each new task or dataset increment.

_Consistency Across Classes_: Analyzed whether strategies perform consistently across different classes within datasets.

_Variability in Performance:_ Investigated how strategies adapt to different datasets (MNIST, FashionMNIST, CIFAR-100).

_Training Dynamics:_ Explored the learning curves and convergence behavior of strategies.

### Conclusion
The project provides insights into the effectiveness of Naive, Replay, and GDumb strategies for continual learning tasks. By leveraging the Avalanche library, we demonstrate their applicability across various datasets and discuss potential improvements and future research directions.

**References**

**Avalanche Library:** https://avalanche.continualai.org/

**PyTorch Documentation:** https://pytorch.org/docs/stable/index.html

**Technical Report:** file:///C:/Users/Usama%20Ahmad/Downloads/datasets/Technical%20Report.pdf

**Research Paper:** (https://arxiv.org/pdf/2104.00405)
