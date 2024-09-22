# Capstone-Project-SECS-UNet
## Final project: Braude - College of Engineering in Karmiel

The code for this project was developed using Python and the Keras API within TensorFlow, implemented on the Kaggle platform. The datasets used for training and testing include RAVDESS_8K, which provides clean speech data, and UrbanSound8K, containing a variety of environmental noise samples, both dataset samples are in 8 kHz. Data preprocessing involved downsampling the audio files to 8 kHz, if they are different. As well as augmenting the clean speech data with different levels of noise, according to two types of factors, urban_noise_factor and white_noisy_factor, that determine the intensity of the noise that will be added to the clean speech from RAVDESS dataset.

Please cite this notebook if you want to use it properly: [Link to the Notebook](https://www.kaggle.com/code/hadadavihay/speech-enhancement-unet-capstone-project)


Based on: [Link to the article](https://www.mdpi.com/2076-3417/12/9/4161)
