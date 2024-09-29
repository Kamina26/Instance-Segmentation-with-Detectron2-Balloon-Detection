# Instance Segmentation with Detectron2: Balloon Detection

This project showcases how to use [Detectron2](https://github.com/facebookresearch/detectron2) for instance segmentation tasks. The objective is to detect and segment balloons using a custom dataset. This implementation is based on the Mask R-CNN model pre-trained on the COCO dataset.

- **Framework**: Detectron2
- **Task**: Instance Segmentation
- **Model**: Mask R-CNN with ResNet-50 backbone and Feature Pyramid Network (FPN)
- **Dataset**: Balloon dataset from [Matterport Mask R-CNN](https://github.com/matterport/Mask_RCNN/releases/download/v2.1/balloon_dataset.zip)
- **Objective**: Detect and segment balloons from images.

## Features

- Pre-trained Mask R-CNN (COCO) used for transfer learning.
- Custom dataset loading, including handling annotations in COCO format.
- Visualization of instance segmentation results.
- Training and inference with Detectron2's Mask R-CNN architecture.
- Runs in Google Colab with CUDA support for fast training and inference.

 Install dependencies:
   !pip install pyyaml
   !pip install torch==1.8.0+cu101 torchvision==0.9.0+cu101 -f https://download.pytorch.org/whl/torch_stable.html
   !pip install detectron2 -f https://dl.fbaipublicfiles.com/detectron2/wheels/cu101/torch1.8/index.html

pixellib:
https://github.com/ayoolaolafenwa/PixelLib

Mask R-CNN:
https://github.com/matterport/Mask_RCNN
https://github.com/ahmedfgad/Mask-RCNN-TF2
