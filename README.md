# 🥦 Cauliflower Classification with Deep Learning

This repository contains various deep learning models trained for the classification of cauliflower images. The project explores different convolutional neural network (CNN) architectures and Vision Transformers (ViT) to identify and categorize cauliflower based on its visual characteristics.

---

## 📁 Dataset

The models in this project are trained on a **custom cauliflower dataset**. This dataset is crucial for distinguishing between different states or types of cauliflower, which can be valuable for agricultural applications, quality control, or research.

📎 **Dataset Link**: [Custom Cauliflower Dataset on Kaggle](https://www.kaggle.com/datasets/paramjayeshkansagra/custom-cauliflower-dataset)

---

## 🧠 Models Explored

This project investigates the performance of several popular deep learning architectures for image classification:

- **VGG16** (`vgg16-cauli.ipynb`):  
  A deep convolutional network characterized by its use of very small (3×3) convolutional filters, emphasizing network depth for improved performance.

- **ResNet50** (`cauliflower-resnet50.ipynb`):  
  A 50-layer Residual Network that addresses the vanishing gradient problem using skip connections.

- **Base Vision Transformer** (`base-vit-cauliflower.ipynb`):  
  An implementation of the Vision Transformer (ViT), applying transformer models to image classification tasks.

- **Fine-tuned Vision Transformer** (`vision-transformer-finetune-cauliflower.ipynb`):  
  Demonstrates fine-tuning a pre-trained Vision Transformer on the cauliflower dataset using transfer learning for improved results.

Each notebook provides code for training, evaluating, and potentially deploying these models.

---

## 🗂️ Project Structure

```
.
├── base-vit-cauliflower.ipynb
├── cauliflower-resnet50.ipynb
├── vgg16-cauli.ipynb
├── vision-transformer-finetune-cauliflower.ipynb
└── README.md
```

---

## 🚀 Getting Started

### ✅ Prerequisites

- Python 3.x
- Jupyter Notebook or JupyterLab

### 📦 Required Python Libraries

Install via pip:

```bash
pip install tensorflow numpy pandas scikit-learn matplotlib Pillow opencv-python
pip install transformers datasets tensorflow-addons
```

---

## 🔧 Installation and Usage

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/your-repository-name.git
cd your-repository-name
```

### 2. Download the Dataset

Download the dataset from Kaggle:  
📥 [Custom Cauliflower Dataset](https://www.kaggle.com/datasets/paramjayeshkansagra/custom-cauliflower-dataset)

Unzip it and place the folder in your project directory.  
**Note**: You may need to modify the data paths in the notebooks accordingly.

### 3. Launch Jupyter Notebook

```bash
jupyter notebook
```

### 4. Run the Notebooks

Open any of the `.ipynb` files (e.g., `cauliflower-resnet50.ipynb`) and run the cells to train and evaluate models.

---

## 📊 Results

Each notebook provides training outputs and evaluation metrics such as accuracy, loss curves, and confusion matrices.  
You can compare the performance of models directly through these results.

📌 The **Fine-tuned Vision Transformer** and **ResNet50** are expected to perform the best due to their advanced architectures and use of transfer learning.

---

## 🤝 Contributing

Contributions are what make the open-source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

### How to Contribute

1. **Fork** the Project  
2. **Create your Feature Branch**  
   ```bash
   git checkout -b feature/AmazingFeature
   ```
3. **Commit your Changes**  
   ```bash
   git commit -m 'Add some AmazingFeature'
   ```
4. **Push to the Branch**  
   ```bash
   git push origin feature/AmazingFeature
   ```
5. **Open a Pull Request**

Also, feel free to open an issue with the tag `"enhancement"` for suggestions or bug reports.  
Don’t forget to ⭐ the project if you like it!

---

## 📜 License

Distributed under the **MIT License**.  
See the [LICENSE](LICENSE) file for more information.

---

## 📬 Contact

For any queries or feedback, feel free to reach out.

---
