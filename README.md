# Speech-Emotion-Recognition
We definespeech emotion recognition (SER) systems as a collection of methodologies that
process and classify speech signals to detect the embedded emotions.

## Dataset
We will use CREMA dataset that is available at the following **[link](https://www.kaggle.com/dmitrybabko/speech-emotion-recognition-en)**.


## Feature Space
### We Created two feature spaces:
1. **[1D] Zero crossing rate:** 
  The rate of sign-changes of the signal during the duration of a particular frame.
  
2. **[2D] Mel Spectrogram:**
  Convert the audio waveform to mel spectrogram
 
 ## The Model | CNN Model
- For the **time domain** or **frequency domain** feature space, the feature space will be *1 Dimensional*, therefore in the architecture we will be using 1D convolutions.
- In **Mel-Spectogram** feature space, the audio is represented as **an image**, therefore we will be using **2D convolutions**
- Implemented everthing *from scratch*.

## Results

### F1 and Recall
- 1D Model(ZCR):

- 2D Model(melspectrogram):

### Confusion matrix
- 1D Model(ZCR):

- 2D Model(melspectrogram):
