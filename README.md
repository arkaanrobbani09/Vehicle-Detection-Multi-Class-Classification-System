# Multi-Class Vehicle Detection & Classification System

An end-to-end Deep Learning computer vision pipeline designed for vehicle detection and multi-class classification using the **Faster R-CNN** architecture paired with a **ResNet50-FPN** backbone, trained on the OpenImages Vehicles Dataset.

## 📌 Key Highlights
- **Multi-Class Classification:** Accurately detects and classifies 5 vehicle types: Ambulance, Bus, Car, Motorcycle, and Truck.
- **Robust Architecture:** Faster R-CNN with ResNet50-FPN backbone (~41 Million trainable parameters).
- **Strong Model Convergence:** Reached a best validation loss of **0.3370** at epoch 9 (24.3% total loss reduction).
- **Custom Annotation Pipeline:** Efficient parsing of complex Pascal VOC annotation formats for 1,254 images (2,388 annotated object instances).

## 📊 Technical Specifications

| Component | Specification |
| :--- | :--- |
| **Model Architecture** | Faster R-CNN (ResNet50-FPN Backbone) |
| **Input Resolution** | 416 × 416 pixels |
| **Target Classes** | Ambulance, Bus, Car, Motorcycle, Truck |
| **Trainable Parameters** | 41,097,261 |
| **Best Validation Loss** | 0.3370 (Epoch 9/10) |
| **Training Execution** | ~30 minutes (CPU) |

## 🛠️ Tech Stack
- **Deep Learning Framework:** PyTorch, Torchvision
- **Computer Vision & Processing:** OpenCV, PIL, Pascal VOC Parser
- **Data Analytics & Plotting:** Matplotlib, Seaborn, NumPy, Pandas
- **Development Environment:** Google Colab / Jupyter Notebook

## 🚀 Future Roadmap
- [ ] Real-time inference acceleration via TensorRT / ONNX Runtime
- [ ] Multi-vehicle tracking integration using DeepSORT / ByteTrack
- [ ] Edge hardware deployment on embedded platforms (NVIDIA Jetson / Raspberry Pi)
