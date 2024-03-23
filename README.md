This script uses the Python Imaging Library (PIL) to manipulate images. Here's how the code works:

encrypt_image function takes an image path and an encryption key as input. It loads the image, creates a new image of the same size for the encrypted image, and then iterates over each pixel of the original image. For each pixel, it applies the encryption operation by adding the encryption key to each color channel value (R, G, B). The result is then set as the pixel value in the encrypted image.

decrypt_image function takes an encrypted image path and the same encryption key used for encryption. It performs the reverse operation by subtracting the encryption key from each color channel value of the encrypted pixels to retrieve the original pixel values. The decrypted image is then saved.
