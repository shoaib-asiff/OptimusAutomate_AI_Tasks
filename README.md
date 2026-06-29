# OptimusAutomate_AI_Tasks
# OptimusAutomate Artificial Intelligence Internship Projects

This repository contains my completed Artificial Intelligence internship tasks for the OptimusAutomate Virtual Internship Program.

## Completed Tasks

1. **Task 1: Image Classification with CNN**
2. **Task 4: Recommendation System**

Both projects are implemented in Python using Jupyter Notebook / Google Colab.

---

## Project Files

```text
.
├── Image_Classification_OptimusAutomate.ipynb
├── Movie_Recommendation_System_OptimusAutomate.ipynb
└── README.md
```

---

# Task 1: Image Classification with CNN

## Overview

In this task, I built a Convolutional Neural Network (CNN) to classify images into different categories. The project uses the CIFAR-10 dataset, which contains small colored images from 10 classes.

## Dataset

**Dataset Used:** CIFAR-10

CIFAR-10 contains 60,000 images divided into 10 classes:

* Airplane
* Automobile
* Bird
* Cat
* Deer
* Dog
* Frog
* Horse
* Ship
* Truck

The dataset is loaded directly using TensorFlow/Keras.

## Technologies Used

* Python
* TensorFlow / Keras
* NumPy
* Matplotlib
* Scikit-learn

## Result

The model achieved a test accuracy of around **64%** on the CIFAR-10 test dataset.

This result is realistic because CIFAR-10 is more challenging than simpler datasets like MNIST due to colored images, object variation, and background differences.

---

# Task 4: Movie Recommendation System

## Overview

In this task, I built a movie recommendation system using the MovieLens dataset. The system recommends movies based on similarity between movie genres and user rating patterns.

## Dataset

**Dataset Used:** MovieLens Latest Small

The dataset contains:

* 9,742 movies
* 610 users
* 100,836 ratings

## Recommendation Methods Used

### 1. Content-Based Filtering

Content-based filtering recommends movies based on movie features. In this project, movie genres are used as features.

The genres are converted into numerical vectors using `CountVectorizer`, and then cosine similarity is used to find movies with similar genre patterns.

### 2. Collaborative Filtering

Collaborative filtering recommends movies based on user rating behavior.

In this project, Pearson correlation is used to find movies that were rated similarly by users.

## Example Output

For the movie **Toy Story (1995)**, the system recommends movies such as:

* Toy Story 2 (1999)
* Antz (1998)
* Monsters, Inc. (2001)
* Finding Nemo (2003)
* Aladdin (1992)

The recommendations are shown with similarity scores, average ratings, rating counts, and explanations.

---

# How to Run the Projects

## Option 1: Run on Google Colab

1. Open Google Colab.
2. Upload the notebook file.
3. Click on **Runtime**.
4. Select **Change runtime type**.
5. Select **GPU** for the CNN project if available.
6. Run all cells one by one.

## Option 2: Run Locally

Install the required libraries:

```bash
pip install numpy pandas matplotlib scikit-learn tensorflow
```

Then open the notebooks using Jupyter Notebook:

```bash
jupyter notebook
```

---

# Key Learnings

Through these tasks, I learned:

* How CNNs are used for image classification.
* How data augmentation and dropout help reduce overfitting.
* How confusion matrices and accuracy plots are used for model evaluation.
* How recommendation systems work.
* The difference between content-based filtering and collaborative filtering.
* How cosine similarity and Pearson correlation are used in recommendation engines.

---

# Conclusion

This repository contains two AI-based projects completed as part of the OptimusAutomate Artificial Intelligence Internship.

The first project focuses on computer vision using CNNs, while the second project focuses on recommendation systems using similarity metrics.

Both projects are beginner-friendly, practical, and demonstrate important concepts in artificial intelligence and machine learning.
::: 
