# EmoTone
 By combining the realms of artificial intelligence and signal processing, we dive deep into the patterns and nuances of human emotions expressed through speech

Emotion Identification and Speaker Age Classification in Speech
I conducted a comprehensive study on emotion identification and speaker age classification given an audio sample using advanced speech and audio processing techniques. Emotion recognition, which involves automatically detecting and classifying a speaker's emotional state, and speaker age classification, which focuses on predicting the age group of a speaker based on their speech characteristics, are critical areas of research in the field of speech processing.

Dataset
To conduct this study, I utilized the widely used Toronto emotional speech set (TESS) Collection, which comprises a diverse collection of audio recordings of two actors (YAF & OAF) portraying various emotions, including neutral, disgust, fear, pleasant surprise, happiness, anger, and sadness. The dataset contains a total of 2800 samples, with each sample having an average duration of 2 seconds. The TESS Collection provides a balanced distribution of samples for each emotion category and offers a representative set of emotional speech data, making it suitable for training and evaluating emotion recognition and speech processing models.

In addition to the TESS Collection, I also conducted a recording using an iPhone 14 Pro, mimicking the same prompt as provided in the TESS dataset, to capture the emotional expression of happiness using a voice tone like that of a young adult female (YAF) speaker. This recording aimed to simulate a real-world scenario and served as a valuable addition to the study.

Notebooks
This repository contains two notebooks that showcase the implementation of emotion identification and speaker age classification models:

CNN-based Emotion Identification.ipynb: This notebook demonstrates the use of Convolutional Neural Networks (CNN) for emotion identification in speech. It includes data preprocessing steps, model architecture, training, and evaluation. The notebook provides insights into how CNNs can be leveraged to accurately classify emotional states in speech samples.

LSTM-based Speaker Age Classification.ipynb: This notebook showcases the utilization of Long Short-Term Memory (LSTM) networks for speaker age classification. It covers data preprocessing, LSTM model creation, training, and performance evaluation. The notebook provides an understanding of how LSTM networks can be employed to predict the age group of a speaker based on their speech characteristics.

Feel free to explore these notebooks to gain insights into the implemented models, experiment with different parameters, and build upon the research presented.

Conclusion
Through this study, I aimed to contribute to the advancement of emotion recognition and speaker age classification in speech processing. By utilizing the TESS Collection and a recorded sample, the notebooks in this repository demonstrate the potential of CNNs and LSTMs in accurately identifying emotions and predicting age groups based on speech characteristics.

Please refer to the respective notebook files for more details on the implementation and methodology.
