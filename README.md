# Automated-Image-Captioning

## Overview
Automated Image Captioning is a deep learning project implemented entirely in a Jupyter Notebook. The project generates descriptive captions for images using Convolutional Neural Networks (CNNs) for feature extraction and Recurrent Neural Networks (RNNs) with Bahdanau attention for sequence generation. The model is trained on the Flickr8k dataset to produce meaningful captions.

## Features
- Extracts image features using a pre-trained CNN model (e.g., InceptionV3).
 Implements RNN with Bahdanau attention for generating context-aware captions.
- Trained on the Flickr8k dataset for caption generation.
- Built as a single Jupyter Notebook for simplicity and ease of execution.

## Tech Stack
- **Programming Language:** Python
- **Deep Learning Framework:** TensorFlow/Keras
- **Dataset:** Flickr8k
- **Notebook Environment:** Jupyter Notebook

## Prerequisites
Ensure the following software and libraries are installed on your system:
- Python 3.8+
- Jupyter Notebook
- TensorFlow >= 2.5
- NumPy >= 1.20
- Pandas >= 1.3
- Matplotlib >= 3.4
-NLTK >= 3.6
Install dependencies using:
```bash
   pip install -r requirements.txt
```

## Installation and Usage
**1. Clone the Repository**
```bash
    git clone https://github.com/SaiKiranNaik03/Automated-Image-Captioning.git
    cd automated-image-captioning
```
**2. Download the Dataset**
- Download the Flickr8k Dataset.
- Place the dataset in the data/ directory or update the path in the notebook accordingly.

**3. Run the Jupyter Notebook**
- Start the Jupyter Notebook server:
```bash
    jupyter notebook
```
- Open and run the imageCaption.ipynb file step-by-step to execute the project.

  **4. Caption Generation**
  The notebook includes steps to:
- Preprocess the dataset.
- Train the model.
- Generate captions for input images.
- Evaluate the model using BLEU scores.

 ## Results
Sample Input:
![Result1](https://github.com/user-attachments/assets/c68e078d-6eca-41b1-8aee-2dced58c2430)

## Future Enhancements
- Expand support to larger datasets such as Flickr30k or MS COCO.
- Upgrade the architecture to include Transformer-based models for better performance.
- Add multilingual support for caption generation.

## Acknowledgments
- **Dataset:** Flickr8k dataset by the University of Illinois at Urbana-Champaign.
- **Frameworks & Tools:** TensorFlow/Keras, NLTK, and Jupyter Notebook.

## Contact
For queries, reach out at saikirannaik03@gmail.com or connect on [LinkedIn](https://www.linkedin.com/in/k-sai-kiran-naik-5b6019257/)

