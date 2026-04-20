# Experiments on LSTMs

This repository has been reorganized into a lightweight, task-oriented layout so notebooks, datasets, model exports, and benchmark outputs are easier to find.

## Repository layout

```text
.
├── notebooks/
│   ├── character_rnn/      # Character-level RNN/LSTM notebooks
│   ├── classification/     # CIFAR10, bidirectional, and codelab notebooks
│   └── experiments/        # Custom implementation and plotting notebooks
├── data/
│   └── text/               # Input text files
├── artifacts/
│   ├── metrics/            # CSV benchmark/metric outputs
│   └── models/             # Exported .tflite models
├── assets/
│   └── images/             # PNG images
└── README.md
```

## Notes

- If a notebook expects files from the old root path, update paths to the new directories above.
- A practical default is to open and run notebooks from the repository root.
