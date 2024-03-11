# Chest X-ray Report Generator using Deep Learning

In this project, we introduce a deep learning model for automatically generating captions for Chest X-ray reports. Radiology reports play a crucial role in medical diagnosis and treatment planning, especially for lung diseases commonly diagnosed through Chest X-ray images. However, creating comprehensive and accurate reports can be time-consuming and relies heavily on expert knowledge. To streamline this process, we developed a deep learning-based system that automatically generates descriptive captions for Chest X-ray images.


## Overview

Our system utilizes DenseNet, a convolutional neural network (CNN) architecture, to analyze Chest X-ray images and extract relevant features. These features are then fed into a GRU (Gated Recurrent Unit) based network for caption generation. The generated captions aim to capture important details such as abnormalities, disease progression, and treatment options, providing a more efficient and cost-effective solution for healthcare professionals.

## Methodology

1. **Data Preprocessing**:
   - Preprocess the Chest X-ray images and corresponding reports.
   - Tokenize the text data for training the caption generator.

2. **Model Architecture**:
   - Utilize DenseNet as the image encoder to extract features from the images.
   - Implement a GRU-based decoder to generate captions based on the extracted features.

3. **Training**:
   - Train the model on a large dataset of Chest X-ray images and corresponding reports.
   - Fine-tune the model using a deep learning framework, optimizing for accuracy and coherence in generated captions.

4. **Evaluation**:
   - Evaluate the performance of the model using standard metrics such as BLEU score, ROUGE score, and human evaluation.
   - Validate the accuracy and coherence of the generated reports compared to ground truth reports.

## Dataset

- The model is trained on a large dataset of Chest X-ray images and corresponding reports.
- Dataset link: [Chest X-rays Indiana University](https://www.kaggle.com/datasets/raddar/chest-xrays-indiana-university)

## Usage

1. **Data Preparation**:
   - Ensure that the Chest X-ray images and corresponding reports are preprocessed and formatted correctly.

2. **Model Training**:
   - Train the model using the provided script or notebook.
   - Fine-tune the hyperparameters as necessary to optimize performance.

3. **Model Evaluation**:
   - Evaluate the generated captions using standard metrics and human evaluation.
   - Adjust the model architecture or training process based on evaluation results.

## Future Works

1. Explore the use of Attention models to further improve the accuracy and coherence of generated captions.

## Resources

- Kaggle notebook link: [Deep Learning Project](https://www.kaggle.com/code/shashankpandey2411/deep-learning-project)

