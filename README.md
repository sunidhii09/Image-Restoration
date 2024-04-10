# Image Restoration using GFPGAN

This project aims to restore and colorize images using the Generative Face Aging with Progressive Gradient Consistency (GFPGAN) model. GFPGAN is a deep learning model designed for facial attribute manipulation tasks, including aging, rejuvenation, and colorization.

## Prerequisites

Before running this project, make sure you have the following dependencies installed:

- Python (>= 3.6)
- PyTorch (>= 1.4.0)
- OpenCV
- Numpy

You can install these dependencies using pip:

```
pip install torch opencv-python numpy
```

## Getting Started

1. Clone this repository to your local machine:

```
git clone https://github.com/sunidhii09/Image-Restoration.git
cd image-restoration
```

2. Download the pre-trained Gfpgan model weights. You can find them [here]([https://example.com/gfpgan_weights.pth](https://github.com/TencentARC/GFPGAN)), then place the weights file inside the `path/` directory.

3. Run the script `index.py` to restore and colorize images.
Replace the path with the path to the image you want to restore and colorize, and the output path with the desired path to save the output image.
