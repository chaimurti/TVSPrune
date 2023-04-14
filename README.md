# TVSPrune

This is the pytorch implementation of our work **TVSPrune - Pruning Nondiscriminative Filters via Total Variation Separation of Intermediate Representations without fine tuning**. This work provides a new paradigm for pruning **without access to either the training set or the loss function**.
## Code for TVS Prune
### Installation

For this code, Python 3.6.9 is required. Instructions for a virtual environment are coming soon. 

At this time, pip functionality is unavailable. Please use
```
https://github.com/chaimurti/TVSPrune.git
```
to download required files. For CIFAR10/CIFAR100 experiments, the datasets and models will be downloaded automatically as well. Instructions coming soon for Imagenet experiments.


### Usage
At this time, this is an initial version of our code, where hyperparameters cannot be manually specified without editing the code. This functionality will be coming soon (before ICLR 2023).  Furthermore, please be aware that running this code is time consuming, and requires significant amounts of RAM (>8GB for CIFAR100 and **>100 GB for Imagenet**). A more cost effective variant is coming soon.

## Work Items
- [x] Initial uploads
- [ ] User-friendly version with hyperparameter selection 
- [ ] Imagenet code
- [ ] Virtual environment (Conda) setup 
- [ ] Memory-efficient version upload
- [ ] Detailed readme
- [ ] Discriminative filters without pruning
- [ ] Variants of TVSPrune
