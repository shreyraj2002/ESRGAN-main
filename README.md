# Image Super Resolution using ESRGAN

## Overview

This repository contains the implementation of Image Super Resolution using Enhanced Super-Resolution Generative Adversarial Networks (ESRGAN). The project aims to enhance the resolution of low-resolution images, generating high-quality and realistic high-resolution images.

## Features

- Implementation of ESRGAN using Python and PyTorch
- Dataset curation and preprocessing for training and evaluation
- Model optimization and hyperparameter tuning
- Evaluation using metrics such as PSNR, SSIM, and LPIPS
- Documentation of project progress, methodology, and outcomes

## Requirements

- Python 3.x
- PyTorch
- NumPy
- OpenCV
- scikit-image
- NVIDIA GPU (optional for GPU acceleration)

## Installation

1. Clone the repository:

```bash
git clone https://github.com/yourusername/image-super-resolution-esrgan.git
```

2. Navigate to the project directory:

```bash
cd image-super-resolution-esrgan
```

3. Install the required packages:

```bash
pip install -r requirements.txt
```

## Usage

1. Download or prepare your low-resolution and corresponding high-resolution image datasets.
2. Update the dataset paths in the configuration files or scripts.
3. Run the preprocessing scripts to prepare the dataset for training.
4. Execute the training script to train the ESRGAN model.
5. Evaluate the model using the evaluation scripts and metrics.
6. Generate high-resolution images from new low-resolution inputs using the trained model.

## Documentation

For detailed documentation, including project methodology, implementation details, and evaluation results, please refer to the `docs/` directory.

## Contributing

Contributions to this project are welcome. Please read the [Contributing Guidelines](Contributing.md) for more information.

## Acknowledgments

- [ESRGAN: Enhanced Super-Resolution Generative Adversarial Networks](https://arxiv.org/abs/1809.00219)
- [PyTorch](https://pytorch.org/)
- [OpenCV](https://opencv.org/)
- [NumPy](https://numpy.org/)
- [scikit-image](https://scikit-image.org/)
