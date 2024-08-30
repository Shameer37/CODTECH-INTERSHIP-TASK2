## CODTECH-INTERNSHIP-TASK2
- **Name**: NITTURU SHAMEER
- **Company**: CODTECH IT SOLUTIONS
- **ID**: CT08DS5957
- **Domain**: ARTIFICIAL INTELLIGENCE
- **Duration**: August to September 2024
- **Mentor**: MUZAMMIL AHMED

## Overview of the Project

### Project: GENERATIVIE ADVERSARIAL NETWORKS(GANS)

### Objective
The objective of the project is to  implementing and training a GAN model to generate realistic images.

### Key Activities
- **Dataset Loading and Preprocessing** : Load and preprocess the Fashion MNIST dataset for training.
- **Model Definition**  :  Build the generator and discriminator models with appropriate architectures and activation functions.
- **Training Functions** : Define functions to train the discriminator and generator, including gradient calculations and weight updates.
- **Visualization** : Generate and display images periodically to monitor the GAN's progress.
- **Training Loop** : Execute the training process, logging performance metrics and visualizing results.

### Technologies Used
- **TensorFlow** : TensorFlow is used as the primary deep learning framework.
- **NumPy** : For numerical operations and data manipulation.
- **Matplotlib** : For visualizing generated images and monitoring GAN progress.
- **TensorFlow Datasets** :  For loading and preprocessing the dataset.

### Functions Used
- **tf.keras.Sequential** : For building the GAN models (generator and discriminator).
- **tf.keras.layers** :  For defining various layers in the models (e.g., Dense, Conv2DTranspose, Conv2D, etc.).
- **tf.data.Dataset** : For creating and managing batches of data.
- **tf.keras.optimizers.Adam** : For optimizing the generator and discriminator.
- **tf.keras.losses.BinaryCrossentropy** : For calculating the loss during training.
- **tf.GradientTape** : For automatic differentiation and calculating gradients.

