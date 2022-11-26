# Speech-Emotion-Recognition


## Introduction
The Speech Emotion Recognition system is builded to detect the emotion from a speech file, developed from a Multilayer Perceptron neural network (MLP) model. The advanced MLP model consists of three fully connected layers: an input layer, a hidden layer that extracts discriminative features, and an output layer. Regarding the result, it has reached 91.67% validation accuracy in training the RAVDESS dataset among angry, neutral, and happy emotions. 


## Feature Engineering
An additional class is used to explore and extract features from a speech file, including Short-Time Fourier Transform (stft), Zero-Crossing Rate (zcr), Root Mean Square (rms), Mel-Frequency Cepstral Coefficients (mfcc), chroma_shift, melspectrogram.
![image](https://user-images.githubusercontent.com/64537025/204066334-8c91d7aa-8636-4b41-bee7-2462b97a695a.png)


## Dataset
The database I used in speech emotion recognition is the Ryerson Audio-Visual Database of Emotional Speech and Song (RAVDESS) which is available to download on Kaggle. The portion of the RAVDESS I used contains in total of 1440 audio files, by 12 actors and 12 actresses with 60 audio files for each professional actor, speaking two linguistically matched sentences in North American English. This database comprises seven sets of emotions, calm, happy, sad, angry, fearful, surprise, and disgust expressions, plus a neutral emotion.
![image](https://user-images.githubusercontent.com/64537025/204066281-0180c24b-fb68-4a78-8003-5634b7e9716b.png)
https://www.kaggle.com/datasets/uwrfkaggler/ravdess-emotional-speech-audio 


## Python Library
1. LibROSA 0.9: which adds the building blocks essential to produce music information retrieval systems for music and audio analysis
2. seaborn 0.11: which is a library for creating statistical graphics, builds on the top of matplotlib and merges closely with pandas data structure 
3. Sklearn: a set of python modules for machine learning and data mining that supports both supervised and unsupervised learning, model selection and evaluation and so on; it has an in-built neural network model by using the supervised learning, known as multilayer perceptron
4. pydub: which manipulates audio with a simple and easy high-level interface
5. pandas
6. numpy
7. glob
8. soundfile
9. os
10. sys
11. matplotlib


## Training Model
![image](https://user-images.githubusercontent.com/64537025/204066133-46ad9bb8-3516-4e0d-a490-87875e78b1e0.png)


## Results
![image](https://user-images.githubusercontent.com/64537025/204066190-e1682f28-2216-4d2f-91bd-187825de66e1.png)







