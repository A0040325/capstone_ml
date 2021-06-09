# capstone_ml
A repository containing the entire source code for the ML portion of our caption projects : Indoor Domestic Violence Detection
# Machine Learning Deployment on Google App Engine for Violence Detection API

---

Author:
* Hafizh Fauzan (M0040321)
* Charles Chang (M0040323)
* Rhennata (C1391685)
* Rosyita Ayu Sulistyo (C1391689)
* Aufa Nabil Amiri (A0040325)
* Iqbal Firmansyah (A1391686)

---

## System Overview
Making a Machine Learning model using 3D Convolutional Neural Network

---

## Machine Learning

### Step 1. Download the dataset from Kaggle
Real Life Violence Dataset : https://www.kaggle.com/mohamedmustafa/real-life-violence-situations-dataset

### Step 2. Install the required dependencies
This is the requirements that is needed:

```
tensorflow == 2.1.0
sklearn
matplotlib
theano
keras
opencv
imageio
imageaug
```

### Step 3. Training and Testing Process
Training and Testing Process is done by executing the lines in the jupyter notebook. We used 1200 out of the existing 2000 images, you may try to add the remaining images if you have a strong enough hardware

## Things to Improve

* TensorFlow usage is outdated, resulting in an error on newer versions
* Performance, there's still room to increase the model's accuracy
* Tried CONV2DLSTM with 3D CNN, although it needs more tuning to increase the performance of the model
