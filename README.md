# ImgProcessing_Spring2019
## Project for Image Processing Spring 2019 SKKU

## Prerequisites
 - Python 3
 - CPU or NVIDIA GPU + CUDA CuDNN (better).
 - List packages:
 ```
 opencv-python
 numpy
 torch 1.1
 torchvision
 matplotlib
 tqdm
 PIL
 ```
 
## Prepare data
 - Create a folder 'data' and download fundus data into this folder.

## Preprocessing
 - Change `INPUT_DIR`, `OUTPUT_DIR_CROP`, `OUTPUT_DIR_COLOR` to the correspoding path.
 - Run this notebook `image_processing_class.ipynb` for cropping, resize and applying high-pass filer.

## Training
 - Change the `TRAIN_DATA_PATH`, `TRAIN_DATA_PATH_COLOR`, `TEST_DATA_PATH`, `TEST_DATA_PATH_COLOR` to the correspoding path.
 - Run these notebooks for each methods `project_classifier_original.ipynb`, `project_classifier_crop.ipynb`, `project_classifier_final.ipynb`

## Results
 - The loss curve:

![Loss](https://github.com/QuangBK/ImgProcessing_Spring2019/blob/master/loss.png)
 - The accuracy curve:

![Acc](https://github.com/QuangBK/ImgProcessing_Spring2019/blob/master/acc.png)
