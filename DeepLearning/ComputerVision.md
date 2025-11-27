# 🖼️ Computer Vision  
*Modern Engineer Toolkit — Deep Learning / CV Track*

Computer Vision (CV) allows machines to understand images & video.  
This section builds on Deep Learning basics and covers **CNNs, detection, segmentation, Vision Transformers (basics only), and CV-specific engineering**.

📌 **Note:**  
Transformers for NLP, LLMs, and fine-tuning (LoRA/QLoRA) are covered in **Generative AI** → `../GenerativeAI/README.md`.

---

# 🧱 Prerequisites

Before starting Computer Vision, complete:

- **Deep Learning** → `./README.md`  
- **Machine Learning** → `../MachineLearning/README.md`  
- **Python + NumPy + Pandas** → `../Fundamentals/README.md`  
- **PyTorch basics** (tensors, autograd, training loops)

---

# 🎓 1. Computer Vision Courses (Beginner → Intermediate)

| Topic | Description | Link |
|-------|-------------|------|
| CNN Basics | Learn convolution, kernels, filters | ▶️ [Link](https://youtu.be/YRhxdVk_sIs) |
| Practical CV with PyTorch | Build CNNs, train on CIFAR/MNIST | ▶️ [Link](https://youtu.be/MfTkp9t2CeM) |
| Full Computer Vision Course | Image classification, detection, segmentation | ▶️ [Link](https://youtu.be/GMKXyESgg4k) |
| Vision Intuition | Visual breakdown of CNNs | ▶️ [Link](https://youtu.be/aircAruvnKk) |

---

# 🧠 2. Core Computer Vision Foundations

### 🔹 Why CNNs Work
- Local receptive fields  
- Parameter sharing  
- Translation invariance  

### 🔹 CNN Building Blocks
- Convolutions  
- Feature maps  
- Padding, stride  
- Pooling (max/avg)  
- Flattening  
- Fully connected heads  

---

# 🏗️ 3. CNN Architectures (Modern Overview)

| Architecture | Purpose | Notes |
|--------------|---------|-------|
| LeNet | First practical CNN | Historical importance |
| AlexNet | Breakthrough CNN | ReLU + dropout popularization |
| VGG | Deep + simple | 3×3 conv stacks |
| ResNet | Skip connections | Solves vanishing gradients |
| Inception | Multi-kernel conv paths | Efficient + scalable |
| MobileNet | For mobile devices | Depthwise separable convs |
| EfficientNet | Scaling CNNs optimally | State-of-the-art for years |

---

# 🎯 4. Image Classification

### Learn:
- Softmax output  
- Cross-entropy loss  
- Overfitting & augmentations  
- Transfer learning basics  

### Essential Techniques:
- Data augmentation  
- Early stopping  
- Batch normalization  

---

# 🛑 5. Object Detection

Classic + modern:

### 🔹 Single-shot detectors
- YOLO family (v3, v5, v7, v8)  
- SSD  

### 🔹 Two-stage detectors
- Faster R-CNN  
- Mask R-CNN (segmentation)

### Concepts:
- Bounding boxes  
- Anchor boxes  
- IoU (Intersection over Union)  
- Non-Max Suppression (NMS)

**Note:** YOLO fine-tuning tutorials belong in **projects**, not Deep Learning basics.

---

# 🎭 6. Image Segmentation

### Types:
- **Semantic segmentation** (class per pixel)  
- **Instance segmentation** (object-aware)  

### Popular architectures:
- UNet  
- DeepLabV3  
- Mask R-CNN  

Applications:
- Medical imaging  
- Self-driving  
- Robotics & automation  

---

# 🔄 7. Vision Transformers (ViT) — Fundamentals Only

📌 Detailed attention/Transformers/LLMs → `../GenerativeAI/README.md`

### Learn:
- Patch embedding  
- Linear projection  
- Self-attention over image patches  
- Positional embeddings  
- Classification head  

Used in:
- Modern classification (ViT/B16)  
- Detection (DETR)  
- Segmentation (Segmenter)

---

# 🧰 8. Computer Vision Tools & Libraries

| Category | Tools |
|----------|-------|
| DL Framework | PyTorch, TorchVision |
| Augmentation | Albumentations, imgaug |
| Detection Models | YOLOv8, Detectron2 |
| Segmentation | UNet frameworks, MMSegmentation |
| Datasets | COCO, Pascal VOC, ImageNet, CIFAR |

---

# 🧪 9. Computer Vision Projects (Beginner → Advanced)

### **Beginner**
- MNIST digit classifier  
- CIFAR-10 / CIFAR-100 classifier  
- Cats vs Dogs classifier  
- Basic image augmentation pipeline  

### **Intermediate**
- Helmet detection using YOLO  
- Face mask detection  
- UNet segmentation on medical images  
- Custom object detector on your dataset  

### **Advanced**
- Semantic segmentation for autonomous driving  
- OCR system (vision-only stack)  
- Object tracking (SORT / DeepSORT)  
- Vision transformer (ViT) training on custom data  

---

# 🧭 10. Learning Path (Recommended)

### **Phase 1 — CNN Basics**
- Convolutions  
- Kernels, feature maps  
- Basic classification  

### **Phase 2 — Architectures**
- VGG → ResNet → EfficientNet  

### **Phase 3 — Detection & Segmentation**
- YOLO / SSD  
- UNet / Mask R-CNN  

### **Phase 4 — Vision Transformers**
- Patch embeddings  
- Self-attention for images  

### **Phase 5 — Projects**
- Multiple end-to-end vision projects  

---

# 🔗 Cross-Links

- Deep Learning → `./README.md`  
- Generative AI (Transformers, NLP, LLMs) → `../GenerativeAI/README.md`  
- Robotics → `../Robotics/README.md`  

---

# ✔️ End of Computer Vision Module  
*Part of the Modern Engineer Toolkit*
