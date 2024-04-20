

# Low-Light Image Enhancement using Deep Convolutional Encoder

## Introduction
Briefly introduce the project, its purpose, and what problem it aims to solve. Mention that it's a Python implementation for enhancing low-light images using Deep Convolutional Encoder (DCE) networks.

## Installation
Provide instructions on how to install the required dependencies and set up the environment. Include any specific versions of libraries that are necessary.

## Usage
Explain how users can use the provided code. Include sample code snippets or a step-by-step guide on how to use the `ZeroDCE` model for enhancing low-light images.

### Example Usage:
```python
# Sample code to use the ZeroDCE model for image enhancement
from PIL import Image

# Load the original low-light image
original_image = Image.open("low_light_image.png")

# Enhance the image using the ZeroDCE model
enhanced_image = infer(original_image)

# Display the original and enhanced images
plot_results(
    [original_image, ImageOps.autocontrast(original_image), enhanced_image],
    ["Original", "PIL Autocontrast", "Enhanced"],
    (20, 12),
)
```

## Model Architecture
Provide an overview of the architecture of the Deep Convolutional Encoder (DCE) network used in the Zero-DCE model. Include diagrams or visual representations if possible.

## Loss Functions
Explain the various loss functions used in the training process, such as color constancy loss, exposure loss, illumination smoothness loss, and spatial consistency loss. Include mathematical formulations and their significance.

## Training
Detail the training procedure, including how to load and preprocess the training data, model compilation, defining custom loss functions, and training the Zero-DCE model. Provide code snippets and explanations.

## Evaluation
Discuss how the model performance is evaluated, including metrics used and how to interpret the results. Provide instructions on how users can evaluate the model on their own datasets.

## Results
Showcase some results of the enhanced images obtained using the Zero-DCE model. Include comparisons between original and enhanced images, highlighting improvements in image quality.
<img src="result_1.png"/>
<img src="result_2.png"/>


## Acknowledgments
Acknowledge any individuals, organizations, or projects that contributed to the development of the Zero-DCE model or the implementation.


