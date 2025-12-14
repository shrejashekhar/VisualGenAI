# VisualGenAI

**Overview**

GenAI Image Generation using GANs is a Generative AI project focused on creating CIFAR-10–like images using Generative Adversarial Networks (GANs).

The project implements a custom GAN architecture consisting of a Generator and a Discriminator. These two neural networks compete with each other during training—the Generator learns to create realistic images, while the Discriminator learns to distinguish between real images and generated ones. Over time, this adversarial process results in the generation of visually meaningful and diverse images.

This project is designed to be beginner-friendly and is ideal for students exploring deep learning, generative models, and image synthesis.


**
**
   Key Features****

Trains a custom GAN model on the CIFAR-10 dataset

Generates synthetic images that resemble CIFAR-10 categories

Produces unique image variations through random latent vectors

Supports execution using Jupyter Notebooks and Google Colab

Beginner-friendly implementation with clear training workflow

**Use Cases**

Data Augmentation
Generate synthetic images to enhance small or imbalanced datasets.

Learning & Concept Exploration
Understand how GANs work internally through hands-on experimentation.

Prototyping & Experimentation
Create mock images for testing computer vision pipelines or UI concepts.

Generative Art & Creativity
Explore creative patterns and variations through latent space manipulation.
**
Usage**
**Setup**


Ensure the required dependencies are installed:

Python 3.x

TensorFlow

Keras

NumPy

Matplotlib

(Optional) Open the notebook directly in Google Colab for GPU support.


**Training the GAN**

Open the provided Jupyter Notebook locally or upload it to Google Colab.

Run the cells step by step to:

Load the CIFAR-10 dataset

Initialize the Generator and Discriminator

Train the GAN using adversarial loss

GPU acceleration is recommended for faster training, especially on Colab.


**Image Generation**

After training is complete, use the trained Generator model to produce new images.

Experiment with different latent space vectors to observe diverse image outputs.

Save or visualize generated images directly from the notebook.
