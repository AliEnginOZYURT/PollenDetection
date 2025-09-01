# Pollen Family Classification

This is one of my personal projects where I worked on **classifying pollen images by family**.  
The goal was to combine **image processing and deep learning** and apply it to a real dataset.

---

## What I Did
- Implemented an automatic segmentation pipeline in OpenCV to crop pollen grains from microscopy images.  
- Cleaned and balanced the dataset so that each family has enough samples.  
- Built a custom PyTorch dataset class for family-level labels.  
- Trained a ResNet18 model (transfer learning from ImageNet) to classify pollen families.  
- Evaluated the model with accuracy, confusion matrices, and classification reports.  

---

## How to Run
Clone the repo and install dependencies:
```bash
git clone https://github.com/yourusername/pollen-family-classification.git
cd pollen-family-classification
pip install -r requirements.txt
```

Run the training:
```bash
python pollen_v5.py
```

---

## Results
- The model reached good accuracy on the test set.  
- Confusion matrices helped identify which pollen families were most often misclassified.  
- Learned that preprocessing quality has a strong impact on classification performance.  

---

## Tech Stack
- PyTorch + Torchvision  
- OpenCV  
- NumPy / Matplotlib / Seaborn  
- scikit-learn  

---

## Next Steps
- Experiment with deeper models (ResNet50, EfficientNet).  
- Improve segmentation for overlapping pollen.  
- Extend classification to genus/species level in the future.  

---

## About
This project helped me practice:  
- Computer Vision  
- Deep Learning  
- Data preprocessing and cleaning  
- Building end-to-end ML pipelines  
