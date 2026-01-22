# computer_vision
 the file related to the field of computer vision tasks and projects 
# 📦 Accurate Object Detection & Geometric Transformations using YOLOv8

A complete **computer vision pipeline** using **YOLOv8** for accurate object detection and **geometric image transformations**, fully compatible with **Google Colab**.

This project detects real-world objects such as **fruits, cups, books, bottles, and household items**, extracts them individually, applies **8 geometric transformations**, and exports organized results for academic, research, and learning purposes.

---

## 🚀 Features

- ✅ YOLOv8 object detection (COCO pre-trained)
- 🎯 Targeted detection of:
  - Fruits (apple, banana, orange, etc.)
  - Cup, bottle, bowl
  - Book and daily objects
- 🖼️ Automatic object cropping with padding
- 🔄 8 geometric transformations applied to each object:
  1. Original  
  2. Translation  
  3. Rotation  
  4. Scaling  
  5. Shearing  
  6. Rigid (Euclidean)  
  7. Similarity  
  8. Affine
- 📊 Visualization grids for every detected object
- 🗂️ Clean, well-organized output folders
- 📝 Auto-generated summary report
- 📦 ZIP archive export

---

## 🧠 Model Details

- **YOLOv8 Nano (`yolov8n.pt`)**
- Pre-trained on the **COCO dataset**
- Optimized for:
  - Fast inference
  - Low resource usage
  - Accurate detection of common objects

> You can switch to `yolov8s.pt` or `yolov8m.pt` for higher accuracy.

---

## 🛠️ Tech Stack

- **Python**
- **Ultralytics YOLOv8**
- **OpenCV**
- **NumPy**
- **Matplotlib**
- **Pillow (PIL)**
- **Google Colab**

---

## 🔄 Project Workflow

1. Install required libraries  
2. Upload an image (or use a sample image)  
3. Detect objects using YOLOv8  
4. Filter target classes  
5. Draw bounding boxes with confidence scores  
6. Crop detected objects  
7. Apply geometric transformations  
8. Save visualizations and reports  
9. Export all outputs as a ZIP file  

---

## 📁 Output Structure

