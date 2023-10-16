# Cell segmentation using Mask R-CNN

### Note
- This project borrowed code from [cj-mills](https://github.com/cj-mills/pytorch-mask-rcnn-tutorial-code), thanks for his tutorial, it help me a lot!!!
- Using [GFP-GOWT1 mouse stem cells](http://celltrackingchallenge.net/2d-datasets/) dataset, if you download the training dataset, put it on `Fluo-N2DH-GOWT1\train` folder, the same with test dataset
- Using maskrcnn_resnet50_fpn_v2 from torchvision
- This project only for learning purpose so doesn't have any benchmark results
- checkpoint link [here](https://drive.google.com/file/d/1-71yJP0mDivh1qgbCkkUYTCKYc-PZjFZ/view?usp=drive_link), then put it on `checkpoints\2023-10-15_09-07-53` folder

### How to use this repo
- Just use [mask_rcnn_cell.ipynb](mask_rcnn_cell.ipynb)