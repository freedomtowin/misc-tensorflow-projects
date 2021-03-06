# ml-projects

## Kaggle Competition - M5 Forecasting Competition - Accuracy

#### [m5-lstm-model.ipynb (tensorflow v2)](https://github.com/freedomtowin/ml-projects/blob/master/Kaggle-M5-Forecasting-Accuracy/m5-lstm-model.ipynb)

#### [m5-pricing-agg-model.ipynb (tensorflow v2)](https://github.com/freedomtowin/ml-projects/blob/master/Kaggle-M5-Forecasting-Accuracy/m5-pricing-agg-model.ipynb)

The final resulted used an ensemble of two neural network models: 1) a pricing-based dense network for each deptarment and store 2) an pattern model using LSTMs for each time series cluster (time series were clustered on the correlation matrix)

The result was achieved with neural networks while light gradient boosted machines were the favorite among competitors in this competition. 

Private Score: Top 7%: 386/5558

## Kaggle Competition - Categorial Feature Encoding Challenge 2

#### [cat-dat-ii.ipynb (tensorflow v2)](https://github.com/freedomtowin/ml-projects/blob/master/Kaggle-Categorical-Feature-Encoding-Challenge-2/cat-data-ii.ipynb)

Machine learning workflow for Kaggle Competition: Categorical Feature Encoding Challenge II. The workflow explores using mean-value encoding, noise reduction techniques, and a categorical embedding layer with tensorflow. 

Private leaderboard score (AUC): 0.78685

Rank 1 private leaderboard score (AUC): 0.78820

[Competition Link](https://www.kaggle.com/c/cat-in-the-dat-ii/)

## Kaggle Competition - Predict Future Sales

#### [predict-future-sales.ipynb (tensorflow v2)](https://github.com/freedomtowin/ml-projects/blob/master/Kaggle-Predict-Future-Sales/predict-future-sales.ipynb)

Predict Future Sales: The final project for "How to win a data science competition" Coursera course, part 2 of the advanced machine learning specialization. The goal is to predict the monthly sales of items in each shop for the month of Novemeber. There are 33 months of daily item-shop data given in the training dataset.

The final solution effectively uses ID and categorical columns for feature creation, validation, and ensemble models. It combined results from boosted decision trees built on different categorical features.

Public Score: Top 1%: 79/8953

[Competition Link](https://www.kaggle.com/c/competitive-data-science-predict-future-sales)

## Serve a Pretrained TensorFlow Image Classifier with Docker (locally)

#### [Docker-TensorFlow-Serving (tensorflow v2)](https://github.com/freedomtowin/ml-projects/blob/master/Docker-TensorFlow-Serving)

Requirements: Docker, tensorflow/serving (image), python 3.8, tensorflow 2.3.0

This project loads in a pretrained model and saves it in a TF2.0 SavedModel format.

A docker image with tensorflow/serving is created. The SavedModel is copied to the image for serving.

A test image is downloaded and sent to the server for scoring using REST. The result is returned.

## Deep Autoregressive Models, Forecasting with TensorFlow 2.0

#### [deep-autoregressive-model-tensorflow.ipynb (tensorflow v2)](https://github.com/freedomtowin/ml-projects/blob/master/Deep-Autoregressive-Model/deep-autoregressive-model-v1.ipynb)

A formulation for deep autoregressive models was created using the 1st order approximation of the autoregressive function. A deep autoregressive model was created, in TensorFlow, to forecast temperature and rainfall in Melbourne AU. The forecasts were created by snowballing the predictions back into the model. The result showed that the model was capable of capturing small global trends and periodic patterns.

[Blog Post](https://freedomtowin.github.io/2020/05/12/Deep-Autoregressive-Models.html)

## 1-D Covolutional Network, Tensorflow 1.0

#### [1d-convolutional-network-AU-tempuratue-prediction.py (tensorflow v1)](https://github.com/freedomtowin/ml-projects/blob/master/1d-convolutional-network-AU-tempuratue-prediction.py) 

   1d-convolutional-network-AU-tempuratue-prediction.py includes a 1-d convolutional neural network forecasting model, built with TensorFlow v1.2. The model forecasts Australian    temperature using historical temperature/rainfall. 

## Particle Swarm Optimization on a GPU, Support Vector Machine 

#### [support_vector_machine_gpu_optimization.ipynb (cuda, kernelml)](https://github.com/freedomtowin/ml-projects/blob/master/Particle-Swarm-Optimization-On-GPU/support_vector_machine_gpu_optimization.ipynb)

This notebook shows the optimization of a multi-class, linear support vector machine using a simulation based optimizer. Any simulation based optimizer could be used with the cuda kernel in this notebook. I used KernelML, my custom optimizer, in this example. 

[Colab Link](https://colab.research.google.com/drive/1AptayjRoDITNLmyfCc0T7z_xKFBlg2l-#scrollTo=pa88P5JUvv_X)

[Blog Post](https://freedomtowin.github.io/2019/12/11/KernelML-SVM-GPU.html)

The runtime for this script should be set to use the GPU: Runtime->Change runtime type.

## Hierarchical Density Factorization

#### [kernelml-hierarchical-density-factorization.ipynb](https://github.com/freedomtowin/ml-projects/blob/master/Density-Factorization/kernelml-hierarchical-density-factorization.ipynb)

The goal is to approximate any multi-variate distribution using a weighted sum of kernels. Here, a kernel refers to a parameterized distribution. This method of using a decaying weighted sum of kernels to approximate a distribution is similar to a Taylor series where a function can be approximated, around a point, using the function’s derivatives. KernelML is a particle optimizer that uses parameter constraints and sampling methods to minimize a customizable loss function. The package uses a Cythonized backend and parallelizes operations across multiple cores with the Numba. KernelML is now available on the Anaconda cloud and PyPi (pip). Please see the KernelML extention on the documentation page.

[Blog Post](https://freedomtowin.github.io/2020/04/04/KernelML-Hierarchical-Density-Factorization.html)

## CapOne Challenge

