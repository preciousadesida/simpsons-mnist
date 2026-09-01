CSC2042S Assignment — Multi-Class Perceptron on Simpsons-MNIST

Description
This project implements a multi-class perceptron (one-vs-rest, using 10 binary perceptrons) from scratch in NumPy, trained and evaluated on the Simpsons-MNIST dataset. It covers data loading, the perceptron implementation, training with two stopping criteria, hyperparameter tuning (learning rate and normalisation), evaluation with standard classification metrics and confusion matrices, and a data augmentation study (brightness jitter and rotation) on the RGB model.

Files submitted
Assign1.ipynb - main notebook containing all code for the assignment: data loading (Task 1), the BinaryPerceptron and MultiClassPerceptron classes (Task 2), the training loop and stopping criteria comparison (Task 3), hyperparameter grid search (Task 4), evaluation with confusion matrices (Task 5), RGB vs. grayscale analysis (Task 6), and the data augmentation experiment (Task 7).
ADSPRE001 - written report.pdf — the written report describing the OOP design, hyperparameter tuning process, and key results/insights.
README.md — this file.

Setup instructions
Requirements:
Python 3.x
numpy
Pillow (PIL)
scikit-learn
matplotlib

Install dependencies with:
pip install numpy pillow scikit-learn matplotlib

Dataset: This repository does not include the dataset. Download the Simpsons-MNIST dataset (grayscale and RGB versions) and place it in a folder named dataset/ in the same directory as Assign1.ipynb, with the following structure:
dataset/
The dataset folder should contain grayscale/ and rgb/ subfolders, each with
train/ and test/ folders inside, and each of those containing the 10 character
folders (bart_simpson, charles_montgomery_burns, etc.).

Running the code: Open Assign1.ipynb and run the cells in order from top to bottom. The notebook is divided into sections corresponding to each task (Task 1 through Task 7), marked with headings/comments in the code.