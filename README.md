# Facial Expression Recognition

This project on Colab uses the FER 2013 dataset from Kaggle (FER+ is WIP).

## Getting Started
1. Open the `facial_expression_recognition.ipynb` file on Colab or your computer.
2. Follow the Kaggle API authentication instructions to obtain a `kaggle.json` file and place it in the root directory of the project.
3. Run the code to download and extract the datasets. The datasets will be stored in a local `fer2013` folder.

## Data Description
The FER 2013 dataset consists of images of faces and the corresponding labels indicating the facial expression in each image. The labels are integers in the range 0-6, where each integer corresponds to a specific facial expression as follows:

- (0) Angry
- (1) Disgust
- (2) Fear
- (3) Happy
- (4) Sad
- (5) Surprise
- (6) Neutral

Each image is represented in the datasets as a string of grayscale pixels (integers in the range 0-255). The size of the images is 48x48.

## Acknowledgements
- The Kaggle dataset was created by the "Challenges in Representation Learning: Facial Expression Recognition Challenge" competition organizers.
- The FER+ dataset was created by Microsoft.

## Further Reading
- The Kaggle competition webpage for the FER 2013 dataset: https://www.kaggle.com/c/challenges-in-representation-learning-facial-expression-recognition-challenge
- The GitHub repository for the FER+ dataset: https://github.com/microsoft/FERPlus
- A review of existing facial expression recognition datasets: https://arxiv.org/ftp/arxiv/papers/2105/2105.03588.pdf
