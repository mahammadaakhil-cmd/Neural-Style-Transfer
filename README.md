# Neural Style Transfer using TensorFlow

## 📌 Project Overview

This project implements **Neural Style Transfer (NST)** using a pre-trained TensorFlow Hub model. The goal is to combine the **content of one image** with the **artistic style of another image** to generate a unique stylized output.

This project was completed as part of the **Prodigy InfoTech AI Internship – Task 05**.

---

## 🎯 Objective

Develop a Neural Style Transfer application that applies the artistic style of one image to the content of another image using deep learning techniques.

---

## 🛠️ Technologies Used

* Python
* TensorFlow
* TensorFlow Hub
* Matplotlib
* NumPy
* Google Colab

---

## 📂 Project Workflow

1. Upload a content image.
2. Upload a style image.
3. Preprocess both images.
4. Load the pre-trained Neural Style Transfer model from TensorFlow Hub.
5. Generate the stylized image.
6. Display and save the output.

---

## 🚀 Features

* Transfers artistic styles to ordinary images
* Uses a pre-trained deep learning model
* Easy to run in Google Colab
* Produces high-quality stylized outputs
* Supports custom content and style images

---

## 📁 Project Structure

```
Neural-Style-Transfer/
│
├── content.jpg
├── style.jpg
├── output.jpg
├── neural_style_transfer.ipynb
├── README.md
└── requirements.txt
```

---

## 📦 Installation

Install the required packages:

```bash
pip install tensorflow tensorflow-hub matplotlib numpy
```

---

## ▶️ How to Run

1. Open the notebook in Google Colab.
2. Install the required libraries.
3. Upload:

   * `content.jpg`
   * `style.jpg`
4. Run all notebook cells.
5. Wait for the model to generate the stylized image.
6. Download the generated `output.jpg`.

---

## 📸 Example

### Input

* **Content Image:** A normal photograph
* **Style Image:** An artwork or painting

### Output

A new image that preserves the original content while adopting the artistic style of the selected painting.

---

## 📊 Sample Workflow

```
Content Image
        │
        ▼
Neural Style Transfer Model
        ▲
        │
Style Image
        │
        ▼
Stylized Output Image
```

---

## 📚 References

* TensorFlow Hub Neural Style Transfer Model:
  https://tfhub.dev/google/magenta/arbitrary-image-stylization-v1-256/2

* TensorFlow Documentation:
  https://www.tensorflow.org/tutorials/generative/style_transfer

* Neural Style Transfer Research Paper:
  https://arxiv.org/abs/1508.06576

---

## 👨‍💻 Internship

**Prodigy InfoTech – AI Internship**

**Task 05:** Neural Style Transfer

---

## 📄 License

This project is developed for educational and internship purposes only.
