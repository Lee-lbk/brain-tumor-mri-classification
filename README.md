# Brain Tumor MRI Classification

##  Project Overview
A deep learning system that classifies brain MRI scans into four categories: Glioma, Meningioma, Pituitary Tumor, and No Tumor. This project uses computer vision to assist in medical image analysis.

##  Tech Stack
- **Frameworks:** Python, TensorFlow, Keras
- **Data Processing:** Scikit-learn
- **Visualization:** Matplotlib, Seaborn

##  Key Features
- **Data Augmentation:** Processed image data with rotation, shifting, and flipping using `ImageDataGenerator` to improve model generalization.
- **Transfer Learning:** Fine-tuned a pre-trained **ResNet50** backbone to extract visual features effectively.
- **Custom Classifier:** Built a classification head with Global Average Pooling and a Dense network (with Dropout) to prevent overfitting.
- **Automated Training:** Monitored validation loss using `EarlyStopping` to save the best model weights automatically.

##  Evaluation & Results
The model was tested on a separate dataset of 1,600 images (400 per class) to ensure balanced performance.
- **Overall Accuracy:** 67.31%
- **Performance Highlights:** 
  - Achieved High AUC for No Tumor (0.940) and Pituitary (0.946).
  - Identified classification challenges between Glioma and Meningioma, reflecting real-world clinical difficulty.
- **Visuals:** 
*(Add your confusion matrix or ROC curve screenshot here. Example: `![Confusion Matrix](confusion_matrix.png)`)*

##  How to Run Locally
1. Clone the repository:
   ```bash
   git clone [https://github.com/yourusername/brain-tumor-mri-classification.git](https://github.com/yourusername/brain-tumor-mri-classification.git)
