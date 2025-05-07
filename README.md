# SVD Image Compression

This project demonstrates how **Singular Value Decomposition (SVD)** can be used for **image compression** in Python. It shows how reducing the rank of the image matrix can compress the image while preserving its essential features.

## 📌 What It Does

- Loads a grayscale (or RGBA) image.
- Converts the image to grayscale (if needed).
- Applies SVD to decompose the image matrix.
- Reconstructs compressed images using only the top-k singular values.
- Plots the original and compressed images side-by-side.

## 📷 Example Output

| Rank | Compressed Output |
|------|--------------------|
| 5    | Very low detail, high compression |
| 20   | Moderate detail |
| 50   | Good balance |
| 100  | Nearly original |

## 🛠️ Requirements

- Python 3.x
- numpy
- matplotlib
- scikit-image

Install dependencies using:

```bash
pip install numpy matplotlib scikit-image
