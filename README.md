# SentiChallenge

A Russian Sentiment analysis BERT model, fine-tuned for SA task from 
[RuBert-cased-conversational](https://huggingface.co/DeepPavlov/rubert-base-cased-conversational) 
with Sequence classification head, trained on [GoEmotions](https://ai.googleblog.com/2021/10/goemotions-dataset-for-fine-grained.html)
dataset which was translated to russian with help of Yandex Cloud Translate API.

Model is able to recognise un-emotional speech and [27 categories of emotions](https://github.com/stas1f1/SentiChallenge/blob/main/emotion_dict.csv)

Pre-trained model weights available [here](
https://drive.google.com/drive/folders/1-09VNNqAQ0uuwEZz6so6eiL85cVNzDAy?usp=sharing)

Examples:
---

<p align="center">
  <img src="https://github.com/stas1f1/SentiChallenge/blob/main/example1.png" width="500" title="hover text">
  <img src="https://github.com/stas1f1/SentiChallenge/blob/main/example2.png" width="485" title="hover text">
</p>

Class recognition success rates:
---

<p align="center">
  <img src="https://github.com/stas1f1/SentiChallenge/blob/main/ClassSuccess.png" width="1000" title="hover text">
</p>
