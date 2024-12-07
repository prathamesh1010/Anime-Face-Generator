Anime Face Generator Using DCGAN
This project demonstrates the use of Deep Convolutional Generative Adversarial Networks (DCGAN) to generate realistic anime-style faces. Built with Keras and TensorFlow, this model uses a GAN architecture to learn the distribution of anime faces and generate new, unseen images.

Overview
Deep Convolutional GAN (DCGAN) is an advanced GAN architecture that incorporates convolutional layers to improve image generation quality, making it suitable for generating high-quality images like anime faces.
This project leverages a dataset of anime faces to train the DCGAN model and generate realistic anime character faces from random noise vectors.
Features
Keras & TensorFlow: Utilizes Keras with TensorFlow backend to build and train the DCGAN model.
Anime Faces Dataset: Trained on a collection of anime character faces.
Image Generation: Generates high-quality anime faces through a GAN model.
Visualization: Includes tools for visualizing generated images during training to observe the model's progression.
Project Components
Generator: A neural network that learns to generate realistic anime faces from random noise.
Discriminator: A neural network that differentiates between real and fake anime images.
DCGAN Architecture: Combination of both networks, where the generator creates fake images and the discriminator evaluates them, with both networks being trained adversarially.
Training Process: The model is trained using the anime face dataset, refining the generator to create more realistic faces as training progresses.
Requirements
Python 3.x
TensorFlow
Keras
NumPy
Matplotlib (for visualization)
Pillow (for image manipulation)
