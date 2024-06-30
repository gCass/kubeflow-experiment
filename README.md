# kubeflow-experiment
The aim of the project is to have an experimental version of a ML workflow using Kubeflow.
Using the mnist dataset we want to build a binary classificator.
The main architectural elements of the pipeline are divided through a development pipeline and a production pipeline.
The development pipeline is composed of:
- reading the dataset from a source (local)
- split the dataset into training and test
- preprocess the training set
- preprocess the test set
- train the model over the training set
- store the model
- score the model over the test set
- store the model performances in a dashboard
