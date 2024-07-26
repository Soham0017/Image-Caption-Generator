# Image Caption Generator

## Overview
This project involves developing an image caption generator inspired by the book "Deep Learning for Natural Language Processing" by Jason Brownlee. The model generates descriptive captions for images using deep learning techniques.

## Dataset
The model was trained using the Flickr8k dataset, which contains over 8000 images with corresponding captions. The dataset can be found [here](https://github.com/jbrownlee/Datasets/releases/download/Flickr8k/Flickr8k_Dataset.zip).

## Model Architecture
- **Base Model**: Fine-tuned VGG16 for feature extraction from images.
- **Captioning Model**: Implemented a merge model that combines image features with text input to generate captions.
- **Performance**: Achieved a BLEU score of 0.4235.

## Technologies Used
- Python
- Keras
- TensorFlow
- VGG16
- Deep Learning
- Computer Vision
- Natural Language Processing (NLP)
