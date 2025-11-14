# Deep CNN Autoencoder for Image Denoising

This project builds a deep convolutional autoencoder that removes noise from images. You feed it a noisy image, it works its magic, and out comes a cleaner version. Think of it as a digital washing machine for pixels.

## What this project does

* Loads a dataset of images
* Adds random noise to them
* Builds an encoder that compresses the image
* Builds a decoder that reconstructs a cleaner version
* Trains the full autoencoder to map noisy inputs to clean outputs
* Shows denoising results for testing images

## How it works

1. **Noisy image in**
2. **Encoder compresses it**
3. **Decoder tries to rebuild it**
4. **Output looks much cleaner if everything goes well**

## Project structure

* Notebook: `Deep_CNN_Autoencoder_Denoising_Image_(1).ipynb`
* Sections inside:

  * What an autoencoder is
  * How the flow works
  * Importing modules
  * Loading dataset
  * Adding noise
  * Building encoder
  * Building decoder
  * Training
  * Visualization

## Requirements

Install the basics:

```
tensorflow
keras
numpy
matplotlib
```

If your environment is dusty, a good old `pip install tensorflow numpy matplotlib` should fix it.

## How to run it

1. Open the notebook in Jupyter or VS Code
2. Run the cells in order
3. Watch the model train
4. Check out the before and after images
5. Admire how your computer now knows how to clean dirty pictures
   (in a safe way, calm down)

## Key features

* Uses deep CNN layers for better spatial feature extraction
* Supports noisy image generation on the fly
* Easy to extend for other image cleaning tasks
* Good for beginners trying to learn autoencoders

## Output

You will see:

* Original clean images
* Noisy versions
* Reconstructed clean predictions

If the reconstruction looks ugly, blame the dataset, not me.

## Future improvements

* Try different noise types
* Add skip connections like U Net
* Train on more data
* Use GPU if you enjoy not waiting forever

## License

Free to use. Free to modify.