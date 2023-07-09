# Emotion-Recognition-from-audio-and-video :smile: :fearful:
©Riccardo Paolini ©Davide Femia ©Alessandro D’Amico ©Sfarzo El Husseini

The purpose of this project is to provide guidelines for implementing a multimodal model that includes textual and audio features. Specifically, our focus is on the differences between small and large language models: we compare them in terms of size, performance, resource usage and degree of explainability for a **Sentiment Analysis** task (Emotion Recognition on the IEMOCAP dataset). 

In order to highlight the advantages and disadvantages of each approach and to give a meaningful evidence of the differences between the two types of models, we implement and benchmark one model for each kind (small, large) and modality (text, audio).

## Models
In this project we tried to join the following models:
- CNN-BiLSTM + BiLSTM
- CNN-BiLSTM + Albert
- Wav2Vec + BiLSTM

In the following table we reported the weighted F1-Score achieved by the models on the different emotions:

<table class="tg">
<thead>
  <tr>
    <th class="tg-cly1" rowspan="2">Model</th>
    <th class="tg-cly1">Neutral</th>
    <th class="tg-cly1">Anger</th>
    <th class="tg-cly1">Happiness</th>
    <th class="tg-cly1">Sadness</th>
    <th class="tg-cly1">Frustration</th>
    <th class="tg-cly1">Excited</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td class="tg-cly1">CNN-BiLSTM + BiLSTM</td>
    <td class="tg-cly1">xxx</td>
    <td class="tg-cly1">xxx</td>
    <td class="tg-cly1">xxx</td>
    <td class="tg-cly1">xxx</td>
    <td class="tg-cly1">xxx</td>
    <td class="tg-cly1">xxx</td>
  </tr>
  <tr>
    <td class="tg-cly1">CNN-BiLSTM + Albert</td>
    <td class="tg-cly1">xxx</td>
    <td class="tg-cly1">xxx</td>
    <td class="tg-cly1">xxx</td>
    <td class="tg-cly1">xxx</td>
    <td class="tg-cly1">xxx</td>
    <td class="tg-cly1">xxx</td>
  </tr>
  <tr>
    <td class="tg-cly1">Wav2Vec + BiLSTM</td>
    <td class="tg-cly1">xxx</td>
    <td class="tg-cly1">xxx</td>
    <td class="tg-cly1">xxx</td>
    <td class="tg-cly1">xxx</td>
    <td class="tg-cly1">xxx</td>
    <td class="tg-cly1">xxx</td>
  </tr>
</tbody>
</table>
