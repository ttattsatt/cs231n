# CS231n — Convolutional Neural Networks for Visual Recognition

My personal notes, assignments, and experiments while going through Stanford's [CS231n](http://cs231n.stanford.edu/) course.

## What's here

| Folder | File | Description |
|--------|------|-------------|
| `lectures/lecture1/` | `imageclassifier.py` | kNN classifier (L1 & L2 distance) on CIFAR-10 |

## Progress

- [x] Lecture 2 — Image Classification, kNN, L1/L2 distances
- [ ] Lecture 3 — Loss functions, Regularization, Gradient Descent
- [ ] Assignment 1

## Setup

```bash
pip install torch torchvision numpy
python lectures/lecture1/imageclassifier.py
```

CIFAR-10 (~170 MB) is downloaded automatically to `./data/` on first run (not tracked by git).
