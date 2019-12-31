# Emotion Recognition Challenge 2019
This is a very first challenge that I participated in Deep Learning, because I've just been studying in this field for 3 months...

</p>
<a href="https://colab.research.google.com/github/nhatsmrt/erc/blob/master/ERC.ipynb">
  <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/>
</a>

## Final Result: 
- 11th place in the 1st Round.
- 4th place in Final Round - Honourable Mention ( ***Exceeding our expectations O.O*** )

## Dataset:
Train: https://drive.google.com/drive/folders/1TeguARxkKENBuEbBsZup1ZPt7Z-rBoeQ

Test: https://drive.google.com/drive/folders/1UU1H3dwPKS6CjviROqoW9RXpGo6hms6Z

## Our Solution:
* First and foremost, we generated 3 types of sound signal to image for training this problem - *STFT*, *Mel-spectrogram-RGB*, *Mel-spectrogram-GreyScale*. 
* Besides that, essembling 3 models, including RNN and CNN models with their precision point based on class *(Turning Point)* maked our result better . 
* In addition, we tried to use mel spectrogram images in <span style="background-color: #FFFF00">*tranposed form*</span> due to operating principle of CNN - sliding frame in horizontal-order
<br />

## References:
[1] https://haythamfayek.com/2016/04/21/speech-processing-for-machine-learning.html
<br />
[2] https://www.kaggle.com/ejlok1/audio-emotion-part-6-2d-cnn-66-accuracy
<br />
