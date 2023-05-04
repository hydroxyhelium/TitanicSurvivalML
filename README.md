## Titanic Survival Predictor - Machine Learning Model

This project is a machine learning model for predicting survival on the Titanic. The model is trained on the Titanic dataset, which contains passenger information such as age, gender, class, and fare, as well as whether or not each passenger survived.

### Requirements

- NumPy
- Pandas 
- Tensorflow 

### Usage
 
All the code for pre-processing, and the results are stored in ```Titanic_dataset.ipynb```. 

### To-Do 

- [x] Read in Train.csv into Pandas dataframe
- [x] Convert Sex, Embarkment to one-hot encoding
- [] Normalize Fares and Age values 
- [x] Design a Deep Nueral Network using Keras 
- [x] Convert train pandas dataframe to tensorflow tensor object  
- [] Use Keras API to convert tensor to batches, feed data through DNN to train the model 
- [] Do pre-processing on test.csv to make tensors
- [] Evaluate the model and Report final accuracy 
