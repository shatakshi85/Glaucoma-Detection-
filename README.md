# Glaucoma-Detection-
Glaucoma Detection using a hybrid CNN–RNN + XGBoost model. CNN extracts spatial features from retinal fundus images, RNN captures feature dependencies, and XGBoost performs final classification. The system enables accurate, automated glaucoma screening to support early diagnosis.

Glaucoma Detection Using CNN–RNN and XGBoost
This repository presents a hybrid deep learning and machine learning approach for automatic glaucoma detection using retinal fundus images. The system combines Convolutional Neural Networks (CNNs), Recurrent Neural Networks (RNNs), and XGBoost to achieve high accuracy and robust classification performance.

- Project Overview
Glaucoma is a progressive eye disease that causes irreversible vision loss if not detected early. Traditional diagnosis relies on expert examination and manual assessment, which can be time-consuming and subjective. This project proposes an AI-assisted diagnostic framework that extracts spatial and sequential features from retinal images and uses a powerful ensemble classifier for final prediction.

 - Methodology
CNN is used for automatic spatial feature extraction from retinal fundus images (optic disc and cup patterns).
RNN captures sequential and contextual dependencies from CNN-extracted feature maps.
XGBoost acts as the final classifier, leveraging learned deep features to improve classification accuracy and generalization.
This hybrid architecture effectively handles both complex spatial patterns and feature dependencies, outperforming standalone models.

- Technologies Used
Python
TensorFlow / Keras
XGBoost
NumPy, Pandas
OpenCV
Matplotlib / Seaborn
Jupyter Notebook

- Workflow
Dataset loading and preprocessing
Feature extraction using CNN
Sequential modeling using RNN
Feature flattening and handoff to XGBoost
Training, validation, and evaluation

 - Results
The proposed CNN–RNN + XGBoost model achieves high classification accuracy in distinguishing glaucomatous and normal eyes, demonstrating the effectiveness of hybrid deep learning approaches for medical image analysis.
