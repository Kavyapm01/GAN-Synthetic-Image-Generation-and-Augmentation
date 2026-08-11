# GAN for Synthetic Image Generation and Augmentation

## 📌 Project Overview

This project focuses on Generative Adversarial Networks (GANs) for synthetic image generation and image augmentation. The project explores different GAN architectures and their applications in generating and transforming images.

## 📊 Dataset

This project uses the **Chest X-Ray Pneumonia** dataset obtained from Kaggle.

### Dataset Details

- **Dataset Name:** Chest X-Ray Pneumonia
- **Source:** Kaggle
- **Dataset Provider:** Paul Timothy Mooney
- **Data Type:** Chest X-ray images
- **Task:** Pneumonia image classification and synthetic image generation
- **Classes:** Normal and Pneumonia

### Dataset Usage

The dataset is used as the source data for training the GAN models in this project:

- **DCGAN:** Generates synthetic chest X-ray images.
- **CGAN:** Generates synthetic images conditioned on class information.
- **CycleGAN:** Performs image-to-image translation between image domains.

### Preprocessing

Before training, the images are prepared for the GAN models by:

- Resizing images to the required input dimensions.
- Converting images to the required image format.
- Normalizing pixel values.
- Organizing images according to their classes where required.

### Dataset Source

The original dataset is available on Kaggle:

[Chest X-Ray Pneumonia Dataset](https://www.kaggle.com/datasets/paultimothymooney/chest-xray-pneumonia)

## 🎯 Objectives

- Generate realistic synthetic images using GANs.
- Explore different GAN architectures.
- Perform image-to-image translation.
- Use synthetic images for data augmentation.
- Study the performance and capabilities of different GAN models.

## 🤖 GAN Architectures

### 1. DCGAN
Deep Convolutional Generative Adversarial Network (DCGAN) uses convolutional neural networks to generate synthetic images.

### 2. CycleGAN
CycleGAN performs unpaired image-to-image translation between two different image domains without requiring paired images.

### 3. StyleGAN
StyleGAN is used for high-quality synthetic image generation with control over different image features.

## 🛠️ Technologies Used

- Python
- PyTorch
- TensorFlow
- NumPy
- Matplotlib
- Google Colab
- Deep Learning

## 📂 Project Files

- `gan.ipynb` – GAN/DCGAN implementation
- `cgan.ipynb` – CycleGAN implementation
- `stylegan.ipynb` – StyleGAN implementation

## 📊 Results

The trained GAN models successfully produced synthetic chest X-ray images and demonstrated the capabilities of generative deep learning for medical image synthesis and augmentation.

### Model Results

- **DCGAN:** Generated synthetic chest X-ray images from random noise.
- **CGAN:** Generated class-conditioned synthetic images based on the specified class.
- **CycleGAN:** Performed image-to-image translation without requiring paired images.

The generated samples are provided in the corresponding model folders inside the `results/` directory. These results can be used to visually compare the outputs and understand the differences between the GAN architectures.

### Observations

The experiments demonstrate that GAN-based models can generate visually meaningful synthetic images and can potentially be used to increase the diversity of image datasets for machine-learning applications.


## 🚀 How to Run

1. Download or clone this repository.
2. Open the required `.ipynb` notebook in Google Colab.
3. Upload or connect the required dataset.
4. Run the notebook cells sequentially.

## 👩‍💻 Project

**GAN for Synthetic Image Generation and Augmentation**
