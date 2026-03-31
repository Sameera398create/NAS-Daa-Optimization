# Neural Architecture Search — DAA Optimization

## Overview
Comparative study of 6 optimization algorithms applied to 
Neural Architecture Search (NAS) on CIFAR-10.

## Live Demo
[Try the live demo here](https://huggingface.co/spaces/SamAmmu2908/nas-cifar10-classifier)

## Algorithms Compared
| Algorithm | Type | Optimality |
|-----------|------|------------|
| Greedy | Deterministic | Local |
| Dynamic Programming | Deterministic | Global |
| Branch & Bound | Deterministic | Global |
| Random Search | Stochastic | None |
| Hill Climbing | Stochastic | Local |
| Genetic Algorithm | Evolutionary | Near-optimal |

## Best Result
- **Best Architecture:** conv3x3 → maxpool → maxpool → conv5x5 → conv5x5
- **Best Accuracy:** 49.50% on CIFAR-10
- **Found by:** (your best algorithm name here)

## Tech Stack
- Python, PyTorch, CIFAR-10
- Google Colab T4 GPU
- Gradio + Hugging Face Spaces

## How to Run
1. Open `NAS_DAA_Project.ipynb` in Google Colab
2. Runtime → Change runtime type → GPU
3. Run all cells in order
