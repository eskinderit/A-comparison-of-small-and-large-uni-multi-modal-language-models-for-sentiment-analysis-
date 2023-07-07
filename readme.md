# Emotion-Detection-from-audio-and-video :smile: :fearful:
©Riccardo Paolini ©Davide Femia ©Alessandro D’Amico ©Sfarzo El Husseini

Sentiment analysis is the study of extracting emotions and opinions from text data. The recent popularity of sentiment analysis is due to its applications such as monitoring social media, managing brand reputation, and improving customer service. From machine learning to deep learning, sentiment analysis can categorize text as positive, negative or neutral, and identify emotions such as happiness or anger. 

Bimodal sentiment analysis uses both text and audio to better understand emotions. By combining text and audio, models can capture both wording and tone of voice to improve accuracy. The key challenge is effectively merging multimodal data to create robust and precise representations for predicting emotions. Bimodal models analyze and integrate text and audio. They typically have separate parts for processing each modality before combining them through fusion techniques. 

Fusion is classified into early, late and hybrid. Early fusion mixes features from each modality before inputting them into a shared classifier. Late fusion trains separate classifiers for each modality and combines their outputs. Hybrid fusion combines early and late fusion, often with deep learning to learn complex hierarchical representations. The choice of fusion technique depends on the application, dataset, and performance needs.

## Models
In this project we tried to join the following models:
- CNN-BiLSTM + BiLSTM
- CNN-BiLSTM + Albert
- Wav2Vec + BiLSTM
