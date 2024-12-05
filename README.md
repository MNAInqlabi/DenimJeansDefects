[![DOI](https://zenodo.org/badge/893384417.svg)](https://doi.org/10.5281/zenodo.14277159)

Dataset regarding BrokenStitches defect has been uploaded alongside the code

rest of the data can be accessed using the DOI given below

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.14279942.svg)](https://doi.org/10.5281/zenodo.14279942)



This code implements a Deep Convolutional GAN (DCGAN) using TensorFlow/Keras to generate high-resolution images (256x256). The model consists of:

Generator: Creates synthetic images from random noise.
Discriminator: Distinguishes real images from generated ones.
Both models are trained adversarially to improve the quality of generated images.

Prerequisites
Hardware: GPU recommended.
Libraries: Install the following:
bash
Copy code
pip install tensorflow keras numpy matplotlib tqdm pillow
Usage
Dataset: Place your images in the folder specified by image_path.
Run the Code: Train the model to generate synthetic images.
Outputs: View and save generated images after training.
Feel free to modify hyperparameters like LATENT_DIM and N_EPOCHS for your needs!
