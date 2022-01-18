# RNN-LSTM-Chatbot
Chat bot model built on RNN LSTM Deep learning model with DEEP NLP

Seq2seq model implementation of chatbot based on Artificial Intelligence (Generative rasedt
Implementation of seq2seq model in Chatbot (AI Chatbot) Here we have used Tensorflow version 1.0.0 Python = 3.5
We can run the command from console or IDE.
This Project is under Training so we do not have weight file.

However to train model I will recommend to use Goggle Collaboratory with GPU runtime it will train the model way faster in comparision to CPU . To run on GPU use the following commands:

step 1: 
from google.colab import drive drive.mount('/content/gdrive')

step 2: 
path = "gdrive/My Drive/Project"

step 3: 
import os

os.chdir(path)

step 4:

!pip3 install tensorflow==1.0.0

step 5:

!apt-get remove cuda !apt-get autoremove cuda !apt-get purge cuda !apt-key del /var/cuda-repo-9-2-local/*.pub !rm -rf /var/cuda-repo-8-0-local-ga2/

step 6:

!sudo wget https://developer.nvidia.com/compute/cuda/8.0/Prod2/local_installers/cuda-repo-ubuntu1604-8-0-local-ga2_8.0.61- 1_amd64-deb !sudo dpkg -i cuda-repo-ubuntu1604-8-0-local-ga2_8.0.61-1_amd64-deb !sudo apt-get update !sudo apt-get -y install cuda-8-0

step 7:

!pip install tensorflow-gpu==1.0

TO CHECK THE VERSION OF GPU, TENSORFLOW AND CUDA RUN THE FOLLOWING COMMAND:

import tensorflow as tf tf.test.gpu_device_name()

tf.version

!nvcc --version
