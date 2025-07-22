# Data Security in Medical Images Using Watermarking Technique

This project presents an approach for enhancing **data security** in medical images using a **digital watermarking technique**. Medical images are highly sensitive and need secure storage and transmission. Watermarking helps protect the integrity and authenticity of these images by embedding imperceptible, yet robust, information directly into the image.

## 📁 Project Files

- `minor_max_.ipynb` – Main Jupyter Notebook implementing the watermarking technique on medical images.

## 💡 Objective

The objective of this project is to:
- Protect patient data embedded within medical images.
- Prevent unauthorized tampering or distribution.
- Use watermarking to ensure integrity and authentication of images.

## ⚙️ Techniques Used

- **Digital Image Processing**
- **Discrete Wavelet Transform (DWT)** or **DCT-based watermarking**
- **Medical image dataset (e.g., MRI, CT scans)**
- **Python libraries**: OpenCV, NumPy, Matplotlib, etc.

## 🔐 Watermarking Process Overview

1. **Input**: Original medical image and patient information.
2. **Preprocessing**: Resize and normalize image.
3. **Watermark Embedding**: Embed patient info as watermark using DWT/DCT or spatial domain.
4. **Output**: Watermarked image.
5. **Verification**: Extract watermark and compare with original data.

## 🧪 Requirements

Install the following Python libraries:

```bash
pip install opencv-python numpy matplotlib
