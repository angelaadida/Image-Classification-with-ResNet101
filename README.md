# 🖼️ Image Classification Web App — ResNet101

A **Streamlit web application** that classifies images into 1,000 categories using **ResNet101** — a deep convolutional neural network pretrained on ImageNet.

---

## 🚀 How It Works

1. Upload an image (JPG, JPEG, or PNG)
2. App resizes image to **224×224** pixels
3. Preprocesses with ResNet101 normalization
4. Model predicts **Top 3 most likely categories** with confidence scores

---

## 🧠 Model: ResNet101

- **Architecture**: Residual Network with **101 layers**
- **Pretrained on**: ImageNet (1,000 object categories)
- **Input size**: 224×224 pixels
- **Output**: Top-3 predictions with confidence scores

### Why ResNet101?
ResNet101 has **twice as many layers** as ResNet50, capturing more complex features and improving accuracy — at the cost of increased computation time.

---

## 🛠️ Tech Stack

| Category | Tools |
|----------|-------|
| Web Framework | Streamlit |
| Deep Learning | TensorFlow, Keras |
| Model | ResNet101 (pretrained ImageNet) |
| Image Processing | PIL, NumPy |
| Language | Python |

---

## 📁 Project Structure

```
Image-Classification-with-ResNet101/
│
├── resnet101.py       # Main Streamlit app
├── results_resnet101.png  # Sample output screenshot
└── README.md
```

---

## 🚀 How to Run

```bash
pip install streamlit tensorflow pillow numpy
streamlit run resnet101.py
```

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).
