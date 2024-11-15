# Notes on Different Models and Datasets

## Datasets

- PIRM
  - 100 Images
  - Resolution ~400x600

| Name | n | Resolution |
| :-----| :----- | ----: |
| PIRM | 100 | ~400x600|
| T91 | 91 | ~150x200|

## Experiments with ResNet

### Models

| Name | # Resnet Blocks | Trainable Parameters |
| :-----| :----- | ----: |
| ResSR1 | 1 | 23.523 |
| ResSR2 | 2 | 97.315 |
| ResSR3 | 3 | 392.355 |

### Training

Dataset: PIRM, patches 224x224, 1046 patches, 4x upscaling, batch size 64

100 Epochs, no LR Scheduler


| Name | Set5 | Set14 |
| :-----| :----- | ----: |
| Model1 | 22.791 | 21.517 |
| Model2 |  21.460|  20.703|
| Model3 | 19.529 | 18.965 |