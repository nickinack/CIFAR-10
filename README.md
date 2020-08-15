# CIFAR-10
A CIFAR-10 image classifier made using Keras and Tensorflow and trained with a TPU-v3. Datasets have been imported from the Keras CIFAR 10 Library.

## About
This mini-project is a CIFAR-10 Image classifier. The CNN-architecture has been adding dropout regularization, data augmentation and batch normalization. The CIFAR-10 dataset (Canadian Institute For Advanced Research) is a collection of images that are commonly used to train machine learning and computer vision algorithms. It is one of the most widely used datasets for machine learning research.

## CNN-Architecture 
The layers in the CNN-Model are as follows:

```python
<tensorflow.python.keras.layers.convolutional.Conv2D at 0x7f5624058cd0>,
 <tensorflow.python.keras.layers.normalization_v2.BatchNormalization at 0x7f55e879b410>,
 <tensorflow.python.keras.layers.convolutional.Conv2D at 0x7f55e879b950>,
 <tensorflow.python.keras.layers.normalization_v2.BatchNormalization at 0x7f55e86d7e90>,
 <tensorflow.python.keras.layers.pooling.MaxPooling2D at 0x7f55e86f4990>,
 <tensorflow.python.keras.layers.core.Dropout at 0x7f55e8646d10>,
 <tensorflow.python.keras.layers.convolutional.Conv2D at 0x7f55e8656fd0>,
 <tensorflow.python.keras.layers.normalization_v2.BatchNormalization at 0x7f55e8665a10>,
 <tensorflow.python.keras.layers.convolutional.Conv2D at 0x7f55e8664c10>,
 <tensorflow.python.keras.layers.normalization_v2.BatchNormalization at 0x7f55e865d850>,
 <tensorflow.python.keras.layers.pooling.MaxPooling2D at 0x7f55e85dbb50>,
 <tensorflow.python.keras.layers.core.Dropout at 0x7f55e85aff50>,
 <tensorflow.python.keras.layers.convolutional.Conv2D at 0x7f55e85cb2d0>,
 <tensorflow.python.keras.layers.normalization_v2.BatchNormalization at 0x7f55e85cb450>,
 <tensorflow.python.keras.layers.convolutional.Conv2D at 0x7f55e8548290>,
 <tensorflow.python.keras.layers.normalization_v2.BatchNormalization at 0x7f55e85329d0>,
 <tensorflow.python.keras.layers.pooling.MaxPooling2D at 0x7f55e8490510>,
 <tensorflow.python.keras.layers.core.Dropout at 0x7f55e8496c50>,
 <tensorflow.python.keras.layers.core.Flatten at 0x7f55e8553450>,
 <tensorflow.python.keras.layers.core.Dense at 0x7f55e84ba090>,
 <tensorflow.python.keras.layers.normalization_v2.BatchNormalization at 0x7f55e8545dd0>,
 <tensorflow.python.keras.layers.core.Dropout at 0x7f5628dbb110>,
 <tensorflow.python.keras.layers.core.Dense at 0x7f56291bb210>
 ```
 
 ## Progress
 
 - Try1: The first try was training the data set using normal sequential CNN. The accuracy achieved was 64.385%
 - Try2: The second try involved adding Dropout regularization (dropout rate: 0.25). The accuracy was 79.72%.
 - Try3: The third try involved adding Batch Normalization and data augmentation after converting the training datasets into tensors. The accuracy was 85.26%.
 - Try4: The final try involved varying dropout rates for each layers. The accuracy was 87.75%.
 
 ## Accuracy
 
 The accuracy for the overall Model turns out to be 87.75%. This can be compared to the following Architectures:
 - DCNN
 - MDCNN
 - RRELU
 - Stochastic Pooler
 
 ## Usage
 
To execute and run these files, download and open them in your Jupyter lab/ Jupyter notebook

If you do not have jupyter notebook/lab, download them using the following code :
```bash
pip install jupyterlab
```
```bash
pip install notebook
```

 #### After installing , you may open your notebooks using the following command:

```bash
jupyter lab
```
```bash
jupyter notebook
```

Run all the cells in order.

## Contributors
<a href="https://github.com/nickinack">Karthik Viswanathan</a>
 
