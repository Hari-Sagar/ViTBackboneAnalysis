# Analysis of Pretrained ViT Backbones in Classification for Social Impacts
Hari Sagar, David Bombara

## Installation
1. Machine should have an NVIDIA gpu with cuda drivers
2. git clone --recurse-submodules https://github.com/Hari-Sagar/ViTBackboneAnalysis.git

## Datasets
1. Download these three datasets
   * DeFungi - https://archive.ics.uci.edu/dataset/773/defungi
   * RealWaste - https://archive.ics.uci.edu/dataset/908/realwaste
   * fMoW - Follow instructions from https://github.com/fMoW/dataset
2. Unzip data files
3. Update download paths in cell 1 of each notebook

## Running Notebooks
1. For the ibot model, create a conda environment
   * conda create --name ibot python=3.8
   * conda activate ibot
2. cd ibot
3. pip install -r requirement.txt
4. jupyter server
5. Run the three notebooks (DeFungi.ipynb, RealWaste.ipynb, fMoW.ipynb)
6. Repeat for dinov2 and mae
