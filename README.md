# SNPE-Setup_env_and_convert
The Snapdragon Neural Processing Engine (SNPE) is a Qualcomm Snapdragon software accelerated runtime for the execution of deep neural networks. In this link after experimenting, will discuss the exact environment setup and version to convert models trained in Tensorflow to .dat format

### 1. SNPE Setup
Setting up Environment for SNPE for converting model to .dat format (SNPE Format)
Installing all the packages and versions in Virtualenv
1. Creating virtualenv with Python 3.5 version
```
 $ virtualenv env_name --system-site-packages --python=python3.5
 
```
2. Entering inside the virtualenv
```
(env_name) source env_1.21/bin/activate
 
```
3. Install Tensorflow 1.11 wheel version, with other versions may led to errors
```
(env_name) wget https://storage.googleapis.com/tensorflow/linux/cpu/tensorflow-1.11.0-cp27-none-linux_x86_64.whl
 
```
