# dashtoon

RUN
“  If you want to run the code file first you have to download the images have have to put the respective path of “original_image_path” and “style_image_path “.

Neural Style Transfer with VGG-19
This repository implements Neural Style Transfer (NST) using the VGG-19 model, a fascinating optimization technique in deep learning. NST combines the content of one image with the style of another to generate unique, visually appealing images.

Requirements
Ensure you have the required libraries installed:
import torch
import torch.nn as nn
import torch.optim as optim
from PIL import Image
import torchvision.transforms as transforms
import torchvision.models as models
from torchvision.utils import save_image
import matplotlib.pyplot as plt
import numpy as np


Usage
1.	Load your content and style images by specifying their file paths.
2.	Execute the provided code to run the NST algorithm using the VGG-19 model.
3.	Adjust parameters such as total steps, learning rate, alpha, and beta to customize the output.
Example
Check the provided Jupyter notebook for a demonstration of NST using a content image and a style image.
Note
This code is designed for Google Colab; adjust file paths and configurations accordingly if using a different environment.
Feel free to experiment with different content and style images to create your own unique visual compositions. Enjoy exploring the world of Neural Style Transfer!

