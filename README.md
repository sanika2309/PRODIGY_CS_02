# PRODIGY_CS_02
# README
This project provides a Python script that demonstrates creating, encrypting, and decrypting images using the `Pillow` library and `NumPy`. The script allows you to generate a random image, encrypt it by inverting pixel values, and then decrypt it back to its original form.

## Features

- **Create a Sample Image**: Generates a 100x100 image with random pixel values and saves it as `input_image.png`.
- **Encrypt an Image**: Inverts pixel values of the image to create an encrypted version saved as `encrypted_image.png`.
- **Decrypt an Image**: Reverts the pixel values to recover the original image and saves it as `decrypted_image.png`.

## Prerequisites

Ensure you have the following Python packages installed:
- `Pillow` (PIL)
- `NumPy`

Install the required packages using pip:

```bash
pip install Pillow numpy
```

## Usage

1. **Create a Sample Image**: 
   Generates a 100x100 pixel image with random colors and saves it as `input_image.png`.
   ```python
   create_sample_image('input_image.png')
   ```

2. **Encrypt the Image**: 
   Encrypts `input_image.png` by inverting its pixel values and saves the result as `encrypted_image.png`.
   ```python
   encrypt_image('input_image.png', 'encrypted_image.png')
   ```

3. **Decrypt the Image**: 
   Decrypts `encrypted_image.png` by inverting the pixel values back to their original state and saves the result as `decrypted_image.png`.
   ```python
   decrypt_image('encrypted_image.png', 'decrypted_image.png')
   ```

## Example Workflow

By running the script, you will:
1. Generate a sample image (`input_image.png`).
2. Encrypt the generated image and save it as `encrypted_image.png`.
