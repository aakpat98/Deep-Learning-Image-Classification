# 🐾 Deep Learning Cats vs Dogs Classifier

This project builds and optimizes a deep learning model to classify images of cats and dogs using CNN architectures and transfer learning. It is based on the [Kaggle Dogs vs. Cats dataset](https://www.kaggle.com/c/dogs-vs-cats-redux-kernels-edition/overview) and includes end-to-end steps: from preprocessing and augmentation to model training, evaluation, and scalable inference.

---

## 📌 Goals

- Build a robust image classification pipeline with deep learning
- Compare performance across CNN, VGG16, ResNet50, and ResNet50V2
- Optimize accuracy through fine-tuning, data augmentation, and callbacks
- Deploy a memory-efficient prediction method for production-scale inference

---

## 🧠 Key Features

- **Transfer Learning:** Pretrained ResNet50 and ResNet50V2 models
- **Advanced Augmentation:** Improves generalization and prevents overfitting
- **Model Comparison:** Plots and metrics for validation across architectures
- **Scalable Inference:** Uses Keras `Sequence` for batch-wise prediction on large datasets
- **Performance:** Final model achieves >95% validation accuracy

---

## 📂 Files

- `Deep_Learning_Image_Classification.ipynb`: Full Jupyter notebook with code and results
- `Image-Classification-Report.pdf`: Summary report with model insights and visualizations

---

## 🧪 Technologies

- Python, TensorFlow/Keras, NumPy, Pandas, Matplotlib, Seaborn
- Jupyter Notebooks
- Scikit-learn for data splitting and evaluation

---

## 📝 Results

The best-performing model, **ResNet50V2**, achieved:
- ✅ **95%+ validation accuracy**
- ✅ Efficient test-time inference using memory-safe sequences
- ✅ ~10–15% performance gain over baseline CNN

---

## 📈 Potential Extensions

- Ensemble modeling (ResNet + VGG)
- Threshold optimization for log loss
- Deployment via Flask/FastAPI or TensorFlow Serving

---

## 🚀 Author

Developed as part of a deep learning exploration project focused on image classification and model interpretability.

