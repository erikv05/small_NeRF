# NeRF PyTorch Breakdown

```
conda env create -f environment.yml
```

or

```
pip install torch numpy tqdm matplotlib tensorboard imageio
```

1. Begins at run_nerf.py train() function
2. load_data.py has dataloader that fills in values