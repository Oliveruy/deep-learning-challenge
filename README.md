# Applicant Success Prediction Analysis

## Overview of the Analysis

The purpose of this analysis is to assist a nonprofit organization in selecting applicants for funding with the best chance for success. This is achieved by using neural networks to predict whether applicants will be successful.

## Results

### Data Preprocessing

- **Target and Features**:
  - **Target variable**: Whether applicants will be successful (binary classification).
  - **Features**: Features used to predict success, which may include applicant characteristics, financial data, etc.
  - **Variables to remove**: Any variables that are not relevant to predicting success.

### Compiling, Training, and Evaluating the Model

- **Model Architecture**:
  - The model consists of 2 hidden layers with 80 and 30 neurons respectively, and an output layer with 1 neuron.
  - The activation functions used for each layer are not specified.
- **Model Performance**:
  - Model performance metrics such as accuracy, precision, and recall are not provided.

### Optimization

Three steps were used to try and optimize the model:

1. **Model 1: Adding More Neurons to a Hidden Layer**
   - Increased the number of neurons in the first hidden layer to 160.
   
2. **Model 2: Adding More Hidden Layers**
   - Added two additional hidden layers with 60 and 40 neurons respectively.

3. **Model 3: Using a Different Activation Function**
   - Changed the activation function from ReLU to hyperbolic tangent (tanh) in the hidden layers.

## Summary

- **Overall Results**:
  - The neural network model consists of 2 hidden layers and an output layer, with a total of 5981 trainable parameters.
- **Evaluation Interpretation**:
  - The model achieved a loss of 0.5554 and an accuracy of 72.94% on the evaluation dataset. A loss value closer to 0 indicates better performance, while an accuracy of 72.94% suggests that the model correctly predicts the outcome for approximately 73% of the applicants.
- **Recommendation**:
  - Based on the model architecture and performance, it appears that the neural network model is suitable for prediction. While the increase in accuracy from 72.7% to 72.9% after adding more hidden layers is a positive sign, further refining the model can be done over time to potentially improve the performance even more.