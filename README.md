# Brain-Tumor-Detection-CNN-VGG-16-
Brain Tumor Detection v1.0 using **CNN** and **VGG-16**. This project classifies brain MRI scans into two categories: **Tumor** and **No Tumor**. Built with deep learning and transfer learning techniques, it provides a foundation for medical image analysis and research. Dataset sourced from Kaggle.

# Brain Tumor Detection v1.0

This project implements **Brain Tumor Detection** using deep learning models, specifically **Convolutional Neural Networks (CNN)** and **VGG-16**. The system is trained to classify MRI brain images into two categories: **Tumor** and **No Tumor**.

---

## 📌 Features

* Binary classification of brain MRI scans.
* Implemented with both **custom CNN architecture** and **VGG-16 transfer learning**.
* Trained and validated on a structured dataset with MRI images.
* Provides a foundation for further research in medical imaging and disease detection.

---

## 📂 Dataset

The dataset used is available on Kaggle:
[`Brain MRI Images for Brain Tumor Detection`](https://www.kaggle.com/datasets)

**Path Structure:**

```
/kaggle/input/brain-mri-images-for-brain-tumor-detection
    ├── train/images
    └── valid/images
```

**Classes:**

* `Tumor`
* `No Tumor`

---

## 🧠 Models

1. **Custom CNN**

   * Designed with multiple convolutional, pooling, and dense layers.
   * Trained from scratch for binary classification.

2. **VGG-16 Transfer Learning**

   * Pre-trained VGG-16 model fine-tuned on brain MRI dataset.
   * Better generalization due to pre-trained ImageNet weights.

---

## ⚙️ Requirements

Install the dependencies before running the project:

```bash
pip install tensorflow keras matplotlib numpy pandas scikit-learn
```

---

## 🚀 Usage

1. Clone the repository:

   ```bash
   git clone https://github.com/yourusername/Brain-Tumor-Detection.git
   cd Brain-Tumor-Detection
   ```
2. Run the training script:

   ```bash
   python train.py
   ```
3. Evaluate the model on validation data:

   ```bash
   python evaluate.py
   ```
4. Predict a single image:

   ```bash
   python predict.py --image path_to_image.jpg
   ```

---

## 📊 Results

* The **CNN model** provides baseline accuracy.
* The **VGG-16 model** outperforms CNN due to transfer learning capabilities.
* Performance metrics: Accuracy, Precision, Recall, and F1-score are logged during training.

<img width="600" height="190" alt="Screenshot 2025-09-27 145242" src="https://github.com/user-attachments/assets/cb57cdcc-4f1e-4b40-af8b-098e6c072157" />
<img width="245" height="256" alt="Screenshot 2025-09-27 145320" src="https://github.com/user-attachments/assets/1ca18a4a-94f6-4ad2-ba99-28a8aa3a42eb" />
<img width="246" height="251" alt="Screenshot 2025-09-27 145336" src="https://github.com/user-attachments/assets/eeeb3f73-a91f-4108-9abc-fa2c95248c1b" />
<img width="124" height="305" alt="Screenshot 2025-09-27 145356" src="https://github.com/user-attachments/assets/48cf0355-e51c-45ef-a8e2-c0d0a1fe0521" />


---

## 📌 Future Improvements

* Extend dataset with more MRI images for robustness.
* Experiment with other architectures (ResNet, EfficientNet, DenseNet).
* Apply Grad-CAM for explainability of tumor detection.

---

## 📜 License

This project is open-source and available under the MIT License.

---

## 👨‍💻 Author

Developed by **Preh-Keerio**
For research and educational purposes.
