# 👗 Fashion GAN – Generative Adversarial Network for Fashion

---

The Fashion GAN is a deep learning model that generates realistic images of fashion items. It leverages GANs (Generative Adversarial Networks) to create new fashion images that resemble real-world clothing items. This project primarily uses the Fashion MNIST dataset, which contains grayscale images of 28x28 pixels representing clothing categories such as T-shirts, pants, shoes, dresses, and more.

---

## 📂 Dataset

Dataset: Fashion MNIST – Kaggle

Dataset contains 60,000 training images and 10,000 test images.

Each image is 28x28 pixels grayscale, labeled into 10 categories.

Why Fashion MNIST?

Standard benchmark for image generation and classification tasks.

Small size allows for faster experimentation.

Suitable for GANs to generate realistic fashion images.

---

## 🔥 Features

✅ Generates realistic fashion images using a GAN architecture.
✅ Uses Fashion MNIST dataset for training and validation.
✅ Demonstrates the concept of adversarial training (Generator vs Discriminator).
✅ Can be extended for colorization, higher-resolution generation, or style transfer.
✅ Helps in understanding deep learning fundamentals for generative modeling.

---

## 🛠️ Installation

Clone the repository:

git clone https://github.com/Hariprasadkurra/Fashion_GAN/
cd Fashion-GAN

---

### Install dependencies:

pip install -r requirements.txt

---

### Suggested Dependencies:

tensorflow>=2.9
keras
numpy
matplotlib
pandas
scikit-learn
tqdm

---

### 🎮 How to Use

Open the Jupyter Notebook:

jupyter notebook main.ipynb

---

Run the cells sequentially:

Data loading & preprocessing

Build the GAN architecture (Generator + Discriminator)

Training the GAN

Generate new fashion images

Visualize generated images at each training step to monitor progress.

---

## 📊 Project Structure
.
├── main.ipynb            # Notebook with GAN training and generation
├── requirements.txt      # Python dependencies
├── datasets/             # Folder containing Fashion MNIST dataset
├── outputs/              # Folder for generated fashion images
├── models/               # Saved GAN model weights
└── README.md             # Project documentation

---

🧠 Key Concepts Learned

Generative Adversarial Networks (GANs)

Training stability techniques for GANs

Image preprocessing and normalization

Loss functions for generator and discriminator

Visualization of generated data during training

---

### 🚀 About Me

GitHub: https://github.com/Hariprasadkurra
