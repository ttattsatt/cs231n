# CS231n: Convolutional Neural Networks for Visual Recognition 

## Intent

My run of Stanford's CS231n and this repo is the working trace of that: notes, derivations, and assignment solutions.



## Course resources

- Lecture notes: [cs231n.github.io](https://cs231n.github.io/)
- Assignments: [cs231n.github.io/assignments](https://cs231n.github.io/assignments)
- Slides and videos: [cs231n.stanford.edu](http://cs231n.stanford.edu/)

## Repo structure

```
cs231n-self-study/
├── assignments/
│   ├── 2025/
│   │   ├── assignment1/   (kNN, SVM, Softmax, two-layer net)
│   │   ├── assignment2/   (FC nets, batchnorm, dropout, CNNs)
│   │   └── assignment3/   (RNNs, transformers, GANs, self-supervised)
│   └── 2026/
│       ├── assignment1/
│       ├── assignment2/
│       └── assignment3/
├── notes/                 (Obsidian-linked conceptual notes, derivations)
└── README.md
```

## Progress tracker

### Notes / lectures

| Topic | Status |
|---|---|
| Image Classification, kNN, k-NN, cross-validation | ✅ Done |
| Linear Classification (SVM loss, Softmax loss, regularization) | ✅ Done |
| Optimization 1 (gradient descent, numerical vs analytic gradient) | ✅ Done |
| Optimization 2 (Backpropagation, chain rule, staged computation) | ✅ Done |
| Neural Networks (architectures, activation functions) | ⬜ Not started |
| CNNs (convolution, pooling, architectures) | ⬜ Not started |
| Training Neural Networks (init, batchnorm, dropout, optimizers) | ⬜ Not started |
| CNN Architectures (AlexNet → ResNet) | ⬜ Not started |
| RNNs / Language Modeling | ⬜ Not started |
| Detection and Segmentation | ⬜ Not started |
| Generative Models | ⬜ Not started |
| Self-Supervised Learning | ⬜ Not started |

### Assignments

| Assignment | Status | Notes |
|---|---|---|
| A1 — kNN classifier (PyTorch, CIFAR-10) | 🔄 In progress | ~0.29 (L1), ~0.27 (L2) on subset |
| A1 — SVM | ⬜ Not started | |
| A1 — Softmax | ⬜ Not started | |
| A1 — Two-layer net | ⬜ Not started | |
| A2 — Fully connected nets | ⬜ Not started | |
| A2 — Batch normalization | ⬜ Not started | |
| A2 — CNNs | ⬜ Not started | |
| A3 — RNNs / Transformers | ⬜ Not started | |

> Status legend: ✅ Done · 🔄 In progress · ⬜ Not started

## Notes on scope

- PyTorch throughout, no other framework.
- Derivations done by hand before code; code checked against numerical gradient checks where applicable.
- Does **not** cover transformer internals, diffusion, or LLM training in depth — those live in the separate [CS336 repo](#). Where CS231n touches those areas (e.g. attention in vision), the connection is noted but not pursued deep here.