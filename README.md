# MarvelCharacterRecognitionUsingGANs
A python implementation of a Deep Convolutional Generative Adversarial Neural Network which tries to generate marvel characters.

The code tries to learn the probability distribution of Marvel Characters from the dataset.

The Gan model consists of two neural networks-<br>
1. A convolutional network, which acts as discriminator D.
2. A deconvolutional network, which acts as a generator G.

The generator takes a random input, sometimes called noise vector to produce a fake image.

The discriminator takes input a image from real dataset and generated output by the discriminator.

The discriminator learns to diffrentiate between real and fake images, while the discriminator tries to learn to produce images which are more real like to fool the discriminator.

The model tries to minimize the Wasserstein Loss.

Gans are very hard to converge and need immense computational power to produce novel results.

16 images for each epoch is generated

There are total 1500 epochs.


The photos generated to learn looks meaningless at first instance but if we take a closer look a the examples we can clearly see
the model has learned to make some edges and form comic book like patterns.

The data set is not provided due to privacy reasons.
