# Lung Nodule Detection

A deep learning model for detecting and segmenting lung nodules in CT images using a U-Net architecture.

## Features
- Processes 2D CT images from .npy files
- Trains on a dataset of lung images with nodule annotations
- Provides visualizations with DSC score overlays
- Includes weighted loss function to better detect small nodules

## Usage
1. Install requirements: `pip install -r requirements.txt`
2. Run training: `python train.py`
3. Run inference: `python predict.py --image_path /path/to/image.npy`

## Dataset
The model was trained on 512x512 lung CT images with corresponding nodule masks.
