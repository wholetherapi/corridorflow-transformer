# corridorflow-transformer

Reference implementation for **"Windowed-Attention Transformers for Urban Corridor Travel-Time Forecasting"** (Transportation Research Part C: Emerging Technologies).

This repository contains the complete training and evaluation pipeline used in the
paper: dataset loaders, the model, the training loop, the evaluation script and the
released metrics.

## Contents

```
configs/
  default.yaml
src/
  __init__.py
  windowed_attention.py
train.py
eval.py
results/
  metrics.md
requirements.txt
```

## Quick start

```
pip install -r requirements.txt
python train.py --config configs/default.yaml
python eval.py --checkpoint checkpoints/best.pt
```

The released checkpoint reproduces the numbers in `results/metrics.md`.

## Citation

```bibtex
@inproceedings{corridorflow-transformer2026,
  title={Windowed-Attention Transformers for Urban Corridor Travel-Time Forecasting},
  booktitle={Transportation Research Part C: Emerging Technologies},
  year={2026}
  note={Under review at IEEE ITSC 2025},
}
```
