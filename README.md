# Image-to-PDF-using-Python-PLI
A simple Python program that converts images into PDF files using the Pillow (PIL) library.

This project provides an interactive command-line interface where you can choose whether you want to convert a **single image** or **multiple images** into a PDF.

## ✨ Features

* Convert a single image into a PDF.
* Convert multiple images into a single PDF.
* Uses the **Pillow (PIL)** library for image processing.
* Interactive command-line prompts.
* Accepts a local folder path from the user.
* Automatically saves the generated PDF in the same folder provided by the user.
* Simple and beginner-friendly Python project.

## 🛠️ Requirements

Make sure you have Python installed on your computer.

Install the required library using:

```bash
pip install Pillow
```

## 🚀 How to Use

Run the Python program:

```bash
python image_to_pdf.py
```

When the program starts, it will ask you to choose between two options:

```text
1. Single Image
2. Multiple Images
```

### Option 1 — Single Image

Select `1` if you want to convert a single image into a PDF.

The program will then ask you for the **local folder path** where the image is located.

For example:

```text
Enter the image folder path:
C:\Users\YourName\Pictures\MyImages
```

The program will find the image and convert it into a PDF.

The generated PDF will be saved in the **same folder** you provided.

### Option 2 — Multiple Images

Select `2` if you want to convert multiple images into one PDF.

The program will ask you for the **local folder path** containing your images.

For example:

```text
Enter the image folder path:
C:\Users\YourName\Pictures\MyImages
```

The program will process the images in that folder and combine them into a single PDF.

The generated PDF will be saved in the **same folder**.

## 📁 Example

Suppose your folder looks like this:

```text
MyImages/
├── image1.jpg
├── image2.jpg
├── image3.png
└── image_to_pdf.py
```

After running the program and selecting option `2`, the output could look like:

```text
MyImages/
├── image1.jpg
├── image2.jpg
├── image3.png
├── converted_images.pdf
└── image_to_pdf.py
```

## 🔧 Technologies Used

* **Python**
* **Pillow (PIL)**

## 📌 Purpose

This project was created as a simple utility for quickly converting images into PDF documents directly from a local computer without requiring an online image-to-PDF service.

@this program is completely made for personal use and is beyond the page limit, and the program is written by ChatGPT. 

This project is open source and available for personal and educational use.

