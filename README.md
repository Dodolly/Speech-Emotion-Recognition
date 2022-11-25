# Speech-Emotion-Recognition


## Introduction
The Speech Emotion Recognition system is builded to detect the emotion from a speech file, developed from a Multilayer Perceptron neural network (MLP) model. The advanced MLP model consists of three fully connected layers: an input layer, a hidden layer that extracts discriminative features, and an output layer. Regarding the result, it has reached 91.67% validation accuracy in training the RAVDESS dataset among angry, neutral, and happy emotions. 


## Feature Engineering
An additional class is used to explore and extract features from a speech file, including Short-Time Fourier Transform (stft), Zero-Crossing Rate (zcr), Root Mean Square (rms), Mel-Frequency Cepstral Coefficients (mfcc), chroma_shift, melspectrogram.
