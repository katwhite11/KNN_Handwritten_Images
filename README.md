# K Nearest Neighbors (KNN) Classifier for Handwritten Digits Recognition

This is a K Nearest Neighbors (KNN) educational project for recognizing handwritten digits using the Scikit-learn library. In this project, I have implemented a KNN algorithm to make predictions on digits from the famous UCI ML Handwritten Digits Dataset.

## Overview

The K Nearest Neighbors algorithm is a simple and effective classification algorithm that classifies data points based on their similarity to neighboring data points. 


![Untitled](https://github.com/katwhite11/KNN_Handwritten_Images/assets/119902118/97fcfe76-0c97-41d0-a52d-a0fcb5814c77)
![1 v6Nn_zj8W0qsnk9Cc6Di_g](https://github.com/katwhite11/KNN_Handwritten_Images/assets/119902118/71a2df4e-4c5b-4d6b-bcb6-c6440a960364)



## Dataset

The dataset we will be using is the UCI ML Handwritten Digits Dataset, which contains a collection of 8x8 pixel grayscale images of handwritten digits (0 to 9). Each image is labeled with the corresponding digit it represents.

__Dataset Source:__ [UCI ML Handwritten Digits](https://archive.ics.uci.edu/dataset/80/optical+recognition+of+handwritten+digits)


## Project Structure

- __KNN.ipynb:__ Jupyter Notebook containing the project code.
- __knn.py:__ Python script of project.
-  __KNN Handwritten Digits Classification Algorithm.pdf__ The written report on the algorithm, dataset, and specific findings. 

## Notebook Contents

- Loading and Exploring Data: Load the UCI ML dataset, visualize some sample digits, and explore the dataset's structure.

- Data Preprocessing: Prepare the data for training shuffling the dataset and splitting into training and testing sets.

- K Nearest Neighbors: Create functions for calculating euclidean distance and the KNN algorithm from scratch.

- Model Evaluation: Train the KNN model, make predictions, and evaluate its performance using accuracy.

- Visualization: Visualize some of the predictions made by the KNN classifier.

Results

The KNN classifier achieves an accuracy of around 96.30%, classifying handwritten digits from the UCI ML dataset.

## Conclusion

In this project, we successfully created a KNN algorithm from scratch to recognize handwritten digits from the UCI ML dataset. The accuracy achieved showcases the effectiveness of the KNN algorithm for this task. Feel free to experiment with different values of K and explore other classification algorithms to improve the results.

## License

This project is licensed under the MIT License. Feel free to use the code and notebook for educational purposes.
