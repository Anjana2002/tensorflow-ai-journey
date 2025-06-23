
# TensorFlow AI Journey 🚀

Welcome to my TensorFlow AI Journey!

This repository documents my learning and experiments with TensorFlow, covering foundational concepts in deep learning through hands-on notebooks.

## 📁 Folder: `Intro to tensorflow`

### 1. Predicting with a Single Neuron
A minimal neural network model using one neuron.

- Uses **Stochastic Gradient Descent (SGD)** as the optimizer.  
- Employs **Mean Squared Error (MSE)** as the loss function.  
- **Goal**: Learn a linear relationship through gradient descent.

---

### 2. `housing_prices.ipynb`
A practical example of supervised learning.

- **Problem**: Predict house prices based on the number of bedrooms.  
- **Base cost**: \$50,000  
- **Each bedroom adds**: \$50,000  
- **Goal**: Train a model to accurately predict prices  
  (e.g., a 7-bedroom house ≈ \$400,000).

---

### 3. `computer_vison`
An introductory example in **computer vision**.

- Explores image-based classification using TensorFlow/Keras.

---

### 4. `callback`
Demonstrates the use of the **Callbacks API** in TensorFlow.

- Automatically stops training once a target accuracy or loss is achieved.  
- Helps prevent overfitting and saves time/resources.  

---

### 5. Improving Computer Vision Accuracy using Convolutions
Introduces **Convolutional Neural Networks (CNNs)**.

- Enhances image classification performance with:
  - **Convolution layers**
  - **MaxPooling layers**

---

### 6. `exploring convolution`
Further exploration of **convolutional layers**.

- Experiments with different configurations to understand their effect on accuracy and performance.  

---

    - The input should be a tf.keras.Input with a shape that matches 
    that of every image in the training set (including the color dimension)
    
    - A good layer (after the Input) would be a Conv2D layer
    
    - The model will work best with 3 convolutional layers
    
    - There should be a Flatten layer in between convolutional and dense layers
    
    - The final layer should be a Dense layer with the number of units and 
    activation function that supports binary classification.

    - Adam is a good optimizer in this case.

    - About loss functions:

        - SparseCategoricalCrossentropy will require label_mode to be 'int' or 'binary' 
        and the last layer should have two units with a 'softmax' activation function.

        - BinaryCrossentropy will require label_mode to be 'int' or 'binary' 
        and the last layer should have only one unit with an activation function such as 'sigmoid'.

        - CategoricalCrossentropy will require label_mode to be 'categorical'
        and the last layer should have two units with a 'softmax' activation function.

## 🧠 Technologies Used

- Python  
- TensorFlow / Keras  
- Google Colab / Jupyter Notebooks



