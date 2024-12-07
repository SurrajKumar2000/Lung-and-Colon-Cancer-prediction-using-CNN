# Colon Cancer Prediction using CNN

## Introduction
Colon cancer is one of the most prevalent and deadly forms of cancer worldwide. Early detection is crucial for improving patient outcomes. This project aims to develop a deep learning model based on Convolutional Neural Networks (CNN) to accurately predict lung cancer from chest X-ray images.

## Dataset
The dataset used in this project consists of chest X-ray images labeled as either "normal" or "lung cancer". The dataset is publicly available and can be downloaded from https://www.cancer.gov/types/lung

## Dependencies
pyparsing                                         3.2.0
python-dateutil                                   2.9.0.post0
python3-openid                                    3.2.0
pyttsx3                                           2.98
pytz                                              2024.2
requests                                          2.32.3
requests-oauthlib                                 2.0.0
rsa                                               4.9
scikit-learn                                      1.5.2
scipy                                             1.13.1
seaborn                                           0.13.2
setuptools                                        75.1.0
six                                               1.17.0
social-auth-app-django                            5.4.2
social-auth-core                                  4.5.4
sqlparse                                          0.5.2
tensorboard                                       2.15.2
tensorboard-data-server                           0.7.2
tensorflow                                        2.15.0
tensorflow-estimator                              2.15.0
tensorflow-io-gcs-filesystem                      0.37.1
tensorflow-macos                                  2.15.0
termcolor                                         2.5.0
threadpoolctl                                     3.5.0
typing_extensions                                 4.12.2
tzdata                                            2024.2
urllib3                                           2.2.3
Werkzeug                                          3.1.3
wheel                                             0.44.0
wrapt                                             1.14.1
zipp                                              3.21.0


## Usage
1. Clone the repository:
```bash
https://github.com/SurrajKumar2000/Lung-and-Colon-Cancer-prediction-using-CNN.git
```
2.Install the required dependencies:
```bash
pip install -r requirements.txt
```

##
## Preprocess the dataset:
Split the dataset into training, validation, and test sets.
Normalize the pixel values of the images.
Augment the dataset to increase the diversity of the training samples.

## Train the CNN model:
Define the CNN architecture.
Compile the model with appropriate loss function and optimizer.
Train the model using the training and validation sets.
Evaluate the model:
Use the test set to evaluate the model's performance.
Calculate metrics such as accuracy, precision, recall, and F1-score.

## Make predictions:
Use the trained model to predict lung and colon cancer on new chest X-ray images.
Visualize the predictions and compare them with the ground truth labels.
