GAN Implementation on Fashion MNIST and MNIST Datasets


Overview
This project involves the implementation of a Generative Adversarial Network (GAN) on two popular datasets: Fashion MNIST and MNIST. The goal is to train a GAN to generate realistic images resembling the respective datasets.


Key Features
GAN Architecture:

The GAN architecture consists of a generator and a discriminator.
The generator creates synthetic images, while the discriminator evaluates the authenticity of the generated and real images.
The generator and discriminator are trained adversarially, resulting in improved image generation over time.


Dataset Handling:

Two datasets are utilized: Fashion MNIST, consisting of fashion item images, and MNIST, consisting of handwritten digit images.
Images are preprocessed and normalized for training.


Training Process:

The GAN is trained using a combination of Binary Cross-Entropy loss and adversarial training techniques.
The discriminator is trained to distinguish between real and generated images, while the generator is trained to deceive the discriminator by creating realistic images.


Callbacks and Training Monitoring:

Custom callbacks such as early stopping and model checkpointing are implemented to monitor and improve training.
Training progress and generated images are visualized to assess model performance.


Dependencies

TensorFlow 2.x

Matplotlib

NumPy
