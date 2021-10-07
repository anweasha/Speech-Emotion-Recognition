# Speech-Emotion-Recognition

Voice often reflects underlying emotion through tone and pitch. Based on this fact, Speech Emotion Recognition (SER) has been developed, which is the task of recognizing the emotional aspects of speech irrespective of the semantic contents. As such, in this python project I have tried building a model which will be able to recognize emotion from sound files.

> Dataset  
This dataset has 7356 files rated by 247 individuals 10 times on emotional validity, intensity, and genuineness.
[speech-emotion-recognition-ravdess-data](https://drive.google.com/file/d/1wWsrN2Ep7x6lWqOXfr4rpKGYrJhWc8z7/view)

> Some libraries used particularly for this project:  
- librosa
- pyaudio
- soundfile

> Steps  
- Loading the dataset
- Extracting features from it
- Splitting the it into train and test sets
- Initializing an MLPClassifier
- Training the model
- Calculating the accuracy of the model
