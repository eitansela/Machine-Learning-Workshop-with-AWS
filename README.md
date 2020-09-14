# Machine Learning Workshop with AWS

## Examples

### SageMaker Built-in Algorithms
- [Targeted Direct Marketing](01_sagemaker_built_in_algorithms) predicts potential customers that are most likely to convert based on customer and aggregate level metrics, using Amazon SageMaker's implementation of [XGBoost](https://github.com/dmlc/xgboost).

### SageMaker Script Mode
- [Train and Host a Keras Model with Horovod on Amazon SageMaker](02_sagemaker_script_mode) This example demonstrates how we train and host a [Keras Sequential model](https://keras.io/getting-started/sequential-model-guide) on SageMaker. The model used for this notebook is a simple deep convolutional neural network (CNN) that was extracted from [the Keras examples](https://github.com/keras-team/keras/blob/master/examples/cifar10_cnn.py).

### SageMaker Bring Your Own Container
- [Bring Your Own scikit Algorithm](03_sagemaker_bring_your_own_container) provides a detailed walkthrough on how to package a scikit learn algorithm for training and production-ready hosting.
