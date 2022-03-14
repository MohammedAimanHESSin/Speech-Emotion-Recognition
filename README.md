# Speech-Emotion-Recognition
We define speech emotion recognition (SER) systems as a collection of methodologies that
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
- 1D Model(ZCR): F1: 0.71   | Recall: 0.70 |   Precision: 0.70

- 2D Model(melspectrogram):  F1: 0.51     |   Recall 0.30  |   Precision:   0.28

### Confusion matrix
  ![This is an image](https://github.com/MohammedAimanHESSin/Speech-Emotion-Recognition/blob/main/results-pics/1d.PNG) 
  ![This is an image](https://github.com/MohammedAimanHESSin/Speech-Emotion-Recognition/blob/main/results-pics/2d.PNG) 

## Authors
- **[Moahmmed Aiman](https://github.com/MohammedAimanHESSin)**
- **[Osama Sherif](https://github.com/kevinwairi)**
- **[Abdulrahman Habib](https://github.com/habiib1999)**
- **[Ahmed Ashraf](https://github.com/habiib1999)**

---
_This README made with ❤️ by [Moahmmed Aiman](https://github.com/MohammedAimanHESSin)_
