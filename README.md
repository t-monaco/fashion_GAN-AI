# Generative Adversarial Network - (GAN)

## Description

Build a GAN that is capable of creating replicas of fashion clothes with tha data provided by `tensorflow_datasets.load('fashion_mnist')`.

**How we achieved this?**
Basically, we create two different neural network. The `generator`, responsible of creating fake images and the `discriminator`, responsible of spotting which of those are fake or not based on the data provided.

> **DISCLAIMER:**
> Training these types of GAN might require decent amount of GPU resources and might take several hours.
