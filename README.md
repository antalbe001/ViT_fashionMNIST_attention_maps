# ViT_fashionMNIST_pytorch

The aim of this project is to analyze the attention maps of a Vision Transformer (ViT). The model is a ViT implementation from scratch for image classification of FashionMNIST dataset. The model was trained first on the raw dataset, then with data augmentation using random geometric transformations and occlusions. The analysis focused on:
1) techniques for effective interpretability of attention maps and different heads visualization
2) how the maps change with data augmentation by applying transformation on trained and untrained model
3) how the maps change with small perturbation from adversarial training
4) how the maps vary across attention layers, to show where the model focuses at different layers

In _interpretability.ipynb_ the attention maps are displayed by:
1) averaging the attention maps for each head
2) taking minimum across heads
3) taking maximum across heads
4) using the rollout method as introduced in _https://arxiv.org/abs/2005.00928_.

Open _visualization.ipynb_ to show all the graphs.
