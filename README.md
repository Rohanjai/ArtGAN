# ArtGAN

This repository contains the code for training and generating art using a Generative Adversarial Network (GAN).

## Overview

Generative Adversarial Networks (GANs) are a class of artificial intelligence algorithms used in unsupervised machine learning, implemented by a system of two neural networks contesting with each other in a zero-sum game framework. This repository implements an ArtGAN, which is specifically trained on art images to generate new pieces of art.

## Files

- `gan-art.ipynb`: Jupyter notebook containing code for training and building the GAN model using art images.
- `Generateimage.ipynb`: Jupyter notebook for generating art using the trained GAN model.
- `data/`: Add the dataset here.
- `images/`: Directory to store the generated art images.
- `model-weights/`: Included Trained GAN model weights.

## Usage

1. **Training the GAN Model**:
   - Open and run `gan-art.ipynb` in a Jupyter notebook environment. Make sure to specify the path to your art dataset.
   - Train the GAN model using the provided code. You may adjust hyperparameters and architecture as needed.

2. **Generating Art**:
   - Once the GAN model is trained, open and run `Generate_image.ipynb`.
   - Use the trained model to generate new art images. You may experiment with different input parameters to produce various styles of art.

3. **Customization**:
   - Feel free to modify the code, experiment with different architectures, or use different datasets to train the GAN model on different styles of art.

## Dependencies

- Python 3.x
- Pytorch
- NumPy
- Matplotlib
- Jupyter notebook


## License

This project is licensed under the [MIT License](LICENSE).
