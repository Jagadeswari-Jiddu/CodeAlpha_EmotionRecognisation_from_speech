Emotion recognisation from speech using deeplearning
Emotion recognition from speech, also known as speech emotion recognition (SER), is the process of automatically detecting and categorizing emotions expressed in human speech.
The primary goal of emotion recognition from speech is to develop computational models and algorithms that can accurately identify various emotional states conveyed through speech. 
These emotional states may include basic emotions such as happiness, sadness, anger, fear, disgust, surprise, neutral.

step1:downloading the data from kaggle datasets

Link: !kaggle datasets download -d ejlok1/toronto-emotional-speech-set-tess

Unzipping the dataset to a folder named dataset

code:!unzip /content/toronto-emotional-speech-set-tess.zip -d dataset

step2:Loading the data from the directorie using the library librosa .

step3:Extracting features from audio files using mfcc and normalizing the features.

step4: Exploratory analysis using waveplot

step5:Preprocessing the data

->reshaping the input data

->encoding the output data using LabelEncoder

step6:splitting the data using train_test_split

step7:Importing and building the model using deeplearning

model:sequential

layers:LSTM,Dense

step8:model evaluation and prediction

step9:evaluating accuracy score and classification report of the model

step10:Testing the model with new data and observing the output

step11:evaluating model accuracy and loss using matplotlib


