# Symptom Driven Plant Diseases Classification

## Objective
Developed a multi-modal classification system that diagnoses plant diseases using both image-based analysis and textual symptom descriptions generated by a language model.

## Technologies Used
- Convolutional Neural Networks (VGG16, DenseNet, InceptionV3, Developed a Custom CNN)
- Multi-Modal Fusion
- Image Augmentation
- Gemini-Vision-Pro for symptom prediction

## Key Achievements
- Achieved **95.5% training accuracy** and **85% validation accuracy** with DenseNet model after 10 epochs.
- Integrated image and text features to enhance disease diagnosis, improving classification accuracy over traditional image-based methods.
- Designed a custom CNN architecture with six 2D-convolutional layers, max-pooling, and fully connected layers for effective feature extraction and disease classification.
- Applied **image augmentation techniques** (scaling, rotation, flipping) to enhance training data variety.
- Utilized **cosine similarity** to evaluate the alignment between generated symptoms and reference texts, achieving high similarity scores for various disease classes.

## Have a Peak at the Workflow
![Presentation1 pptx (1)](https://github.com/user-attachments/assets/6710e451-4f79-4da1-b1b0-8db6b0df188a)

## Results
- DenseNet performed the best among all models, achieving superior results in disease classification and symptom prediction.
