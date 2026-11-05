# Brain Tumor MRI Classification (Deep Learning)
Multi-class brain MRI image classification (Glioma, Meningioma, Pituitary, No Tumor) using Transfer Learning with **ResNet50**.
- **Tech Stack:** Python, TensorFlow, Keras, Scikit-learn, Matplotlib, Seaborn
- **Key Steps:** Image preprocessing & augmentation (`ImageDataGenerator`), frozen ResNet50 feature extraction with custom Dense/Dropout head, model training with `EarlyStopping`, and evaluation via Confusion Matrix & ROC/AUC curves.
