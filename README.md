# Variational Autoencoder (VAE) for Medical Image Reconstruction

This script implements a Variational Autoencoder (VAE) for medical image reconstruction using TensorFlow and Keras. The VAE model is trained on a dataset of medical images to reconstruct masked versions of the input images.

## Dependencies

- Python 3.x
- NumPy
- TensorFlow
- Keras
- OpenCV (cv2)
- Matplotlib

You can install the dependencies using pip:

```bash
pip install numpy tensorflow opencv-python matplotlib


## Usage

1. **Prepare your dataset**: Organize your medical images into a directory. The script assumes the images are in either PNG, JPG, or JPEG format.

2. **Update data_path variable**: Update the `data_path` variable in the script to point to the directory containing your medical images.

3. **Adjust input shape and latent dimension**: Update the `input_shape` variable to match the dimensions of your images. Also, adjust the `latent_dim` variable based on your desired latent space dimension.

4. **Run the script**: Execute the script in your Python environment.

```bash
python vae_medical_image.py

