# 🍎 Apple Leaf Disease Detection using Vision Transformer (ViT)

A deep learning project to classify apple leaf diseases using the Vision Transformer (ViT) model. The aim is to assist in early detection of plant diseases to help farmers and agronomists take timely action.

---

## 🎯 Objective

- Detect whether an apple leaf is **healthy** or **diseased**.
- Classify leaf diseases like **Black Rot**, **Scab**, and **Cedar Apple Rust**.
- Utilize modern transformer-based models for better accuracy over CNNs.

---

## 🧠 Model Details

- **Architecture**: ViT (`vit-base-patch16-224-in21k`)
- **Frameworks**: PyTorch & Hugging Face Transformers
- **Approach**: Transfer learning and fine-tuning
- **Techniques**: Data augmentation, class balancing, custom preprocessing

---

## 📁 Dataset

The model is trained on a **custom-curated dataset** of apple leaf images with four categories:

- `Apple___Black_rot`
- `Apple___Scab`
- `Apple___Cedar_apple_rust`
- `Apple___Healthy`

📂 **Download Dataset**  
📎 [Custom Apple Leaf Dataset on Google Drive](https://drive.google.com/drive/folders/1-74VT_9iPxE7E1H8WTt6FY-JGf99dvg4?usp=sharing)

---

## 🧰 Libraries & Tools

- `torch`, `torchvision`
- `transformers` (Hugging Face)
- `sklearn` (metrics)
- `matplotlib`, `seaborn`
- `PIL`, `numpy`, `pandas`

---

## 🚀 Getting Started

### 🔧 Setup Instructions

1. **Clone the Repository**
```bash
git clone https://github.com/Muku2003-code/apple-leaf-vit.git
cd apple-leaf-vit
