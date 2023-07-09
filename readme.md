# Emotion-Recognition-from-audio-and-video :smile: :fearful:
©Riccardo Paolini ©Davide Femia ©Alessandro D’Amico ©Sfarzo El Husseini

The purpose of this project is to provide guidelines for implementing a multimodal model that includes textual and audio features. Specifically, our focus is on the differences between small and large language models: we compare them in terms of size, performance, resource usage and degree of explainability for a **Sentiment Analysis** task (Emotion Recognition on the IEMOCAP dataset). 

In order to highlight the advantages and disadvantages of each approach and to give a meaningful evidence of the differences between the two types of models, we implement and benchmark one model for each kind (small, large) and modality (text, audio).

## Models
In this project we tried to join the following models:
- CNN-BiLSTM + BiLSTM
- CNN-BiLSTM + Albert
- Wav2Vec + BiLSTM

The results of each model are reported in the following table.

<table class="tg">
<thead>
  <tr>
    <th class="tg-cly1" rowspan="2">Model</th>
    
    <th class="tg-cly1">Neutral</td>
    <th class="tg-cly1">Anger</td>
    <th class="tg-cly1">Happiness</td>
    <th class="tg-cly1">Sadness</td>
    <th class="tg-cly1">Frustration</td>
    <th class="tg-cly1">Excited</td>
  </tr>
</thead>
<tbody>
  <tr>
    <td class="tg-cly1">Model 1</td>
    <td class="tg-cly1">xxx</td>
    <td class="tg-cly1">xxx</td>
    <td class="tg-cly1">xxx</td>
    <td class="tg-cly1">xxx</td>
    <td class="tg-cly1">xxx</td>
    <td class="tg-cly1">xxx</td>
  </tr>
  <tr>
    <td class="tg-cly1">Model 2</td>
    <td class="tg-cly1">xxx</td>
    <td class="tg-cly1">xxx</td>
    <td class="tg-cly1">xxx</td>
    <td class="tg-cly1">xxx</td>
    <td class="tg-cly1">xxx</td>
    <td class="tg-cly1">xxx</td>
  </tr>
  <tr>
    <td class="tg-cly1">Model 3</td>
    <td class="tg-cly1">xxx</td>
    <td class="tg-cly1">xxx</td>
    <td class="tg-cly1">xxx</td>
    <td class="tg-cly1">xxx</td>
    <td class="tg-cly1">xxx</td>
    <td class="tg-cly1">xxx</td>
  </tr>
</tbody>
</table>
