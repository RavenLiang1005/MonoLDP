# MonoLDP
An official pytorch implemention of MonoLDP
## Introduction
MonoLDP is a two-stage network consists of a depth prediction module and a relative pose estimation module. 
![network_final_v1](https://github.com/user-attachments/assets/b2feea0a-ecbc-426c-87ec-c18254bb8911)

## Depth Prediction
### Preparation
1. Pytorch and conda environment
create conda environment
```
conda conda create -n monoldp_depth python=3.8
conda activate monoldp_depth
conda install pytorch=1.7.0 torchvision=0.8.0  cudatoolkit=11.0 -c pytorch
```
2. Requirements
```
cd MonoLDP/Depth_Estimation
pip install -r requirements.txt
```
3. Dataset
We have the processed dataset here 
