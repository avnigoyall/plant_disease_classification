# Plant Disease Classification
This project is aimed to classify plant disease from leaf images.

## Project Overview
Phase 1:
* Train a CNN on the PlantVillage dataset to detect diseases in leaf images
* Evaluate performance using metrics like accuracy and confusion matrix
Phase 2 (Planned):
* Fine-tune the model on crops native to California (e.g., grapes, citrus)
* Integrate a large language model (LLM) to provide treatment advice based on disease class, region, and crop type

## Features
* Loads and preprocesses images from the PlantVillage dataset publicly available on Kaggle
* Trains a CNN with multiple convolutional and pooling layers
* Evaluates & plots the model accuracy on validation data

## Results
Initial model performance:
* Accuracy: ~50% (baseline)
* Goal: Improve through augmentation, tuning, and fine-tuning for local crops

