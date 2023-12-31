# Anemia Detection from Conjunctiva Images
This repository contains a project focused on classifying anemia using conjunctiva images. The goal of the project is to develop a machine learning model that can accurately detect the presence of anemia based on images of the conjunctiva.

## Table of Contents

- Project Overview
- Dataset
- Model Development
- Usage
- Contributing
- License
- Project Overview
  
Anemia is a common blood disorder that can often be visually identified by changes in the conjunctiva of the eye. This project aims to leverage machine learning techniques to automate the detection of anemia by analyzing conjunctiva images. The repository contains code and resources related to data preprocessing, model training, and evaluation.

Dataset
We used a curated dataset of conjunctiva images collected from various sources. The dataset consists of images categorized into two classes: 'Anemic' and 'Non-Anemic'. The images have been preprocessed and augmented to ensure diversity and enhance the model's robustness.

Model Development
Our approach involves training a deep learning model using state-of-the-art architectures such as Convolutional Neural Networks (CNNs). The model is trained on the preprocessed dataset and fine-tuned to achieve optimal performance in classifying anemia from conjunctiva images.

## Usage
Clone the repository:

```
git clone https://github.com/shashankkapoor/Anemia-Detection-From-Conjunctiva.git
```
Navigate to the project directory:
```
cd Anemia-Detection-From-Conjunctiva
```
To work with this code you need to first know the path on your system where you saved this colab and dataset.

```
import pickle
dataset = pickle.load(open('/path/to/dataset/x_final_conjunctiva.pkl', 'rb'))
labels = pickle.load(open('/path/to/label/y_final_conjunctiva.pkl', 'rb'))
```

Contributing
Contributions are welcome! If you'd like to contribute to this project, please follow these steps:

Fork the repository.
Create a new branch for your feature or bug fix.
Make your changes and commit them.
Submit a pull request explaining your changes and their benefits.
Peace!!  
