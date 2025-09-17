<<<<<<< HEAD
# UPER
UPER: A Unified Polyhedral Representation for Universal Multi-dimensional Diffusion MRI Image Modeling

### Necessary Packages and Versions
```
pytorch=1.7.1=py3.8_cuda10.1.243_cudnn7.6.3_0
torchvision=0.8.2=py38_cu101
monai-weekly==0.9.dev2152
nibabel==3.2.1
omegaconf==2.1.1
timm==0.4.12
```

### Stage 1: MAE Training
The run scripts are in directory scripts
```
python main.py \
        configs/mae3d_dmri_1gpu.yaml \
        --mask_ratio=0.125 \
        --run_name='mae3d'
```
