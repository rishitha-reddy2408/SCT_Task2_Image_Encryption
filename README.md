# Image Encryption Tool Using Pixel Manipulation

## SkillCraft Technology AI/ML Internship - Task 2

## Project Overview

This project focuses on developing a simple image encryption and decryption tool using pixel manipulation techniques.

Images are made up of pixels containing RGB values. This project encrypts images by modifying pixel values using mathematical operations and pixel swapping techniques.

The original image can be recovered through the decryption process.

---

## Technologies Used

- Python
- Google Colab
- NumPy
- Pillow (PIL)
- Matplotlib

---

## Features

- Image upload and processing
- Conversion of images into pixel arrays
- Pixel-level image manipulation
- Mathematical pixel encryption
- Image decryption
- RGB channel swapping
- Saving encrypted and decrypted images

---

## Working Principle

### Mathematical Pixel Encryption

A secret key value is added to each pixel value.

Formula:

Encrypted Pixel = (Original Pixel + Key) % 256

During decryption, the same key value is subtracted to recover the original image.

### Pixel Swapping

RGB channel values are swapped to modify pixel information and create an encrypted version of the image.

---

## Project Workflow

1. Upload input image
2. Convert image into pixel array
3. Apply mathematical encryption technique
4. Generate encrypted image
5. Decrypt encrypted image
6. Apply pixel swapping technique
7. Save output images

---

## Results

The project generates:

- Original Image
- Encrypted Image
- Decrypted Image
- Pixel Swapped Image

---

## Applications

- Basic image security
- Understanding image processing
- Learning pixel manipulation techniques
- Introduction to encryption concepts

---

## Future Enhancements

- Add password-based encryption
- Develop GUI application
- Implement advanced encryption algorithms
- Improve image security techniques

---

## Google Colab Notebook

You can view and run the project here:
https://colab.research.google.com/drive/1YjF20V2ZtfJO2S_NKqNyn0Kxu5ezET7d?usp=sharing

## Author

Pati Rishitha Reddy
