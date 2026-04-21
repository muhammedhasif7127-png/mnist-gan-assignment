# MNIST GAN Assignment

## 📌 Objective
Implement and train a simple Generative Adversarial Network (GAN) using TensorFlow/Keras to generate handwritten digit images resembling the MNIST dataset.  
This assignment strengthens understanding of adversarial learning and generative modeling.

---

## 🛠 Features
- Generator and Discriminator implemented with Keras Sequential API
- MNIST dataset preprocessing (normalized to [-1, 1])
- Binary Cross-Entropy loss
- Adam optimizer (lr=0.0002, β1 = 0.5)
- Training loop for 20 epochs
- Visualization of generated digits every epoch
- Loss curve plotting for generator and discriminator
- Short report included: [report.pdf](report.pdf)

---

## 📂 Project Structure
```text
mnist_gan_assignment/
│
├── gan_mnist.ipynb   # Jupyter Notebook implementation
├── gan_mnist.py      # Python script version
├── report.pdf        # 2–3 page write-up
├── README.md         # Project documentation
└── results/          # Generated outputs
    ├── epoch_20.png
    └── loss_curve.png
```

---

## ⚙️ Requirements
- Python 3.8+
- TensorFlow 2.x
- NumPy
- Matplotlib

Install dependencies:
```bash
pip install tensorflow numpy matplotlib
```
