# Research Project Website

Harmonize website

# Automated Singing Skills Evaluation Research Project

This repository contains the code and resources for an automated system to evaluate the singing skills of novice singers using machine learning techniques, specifically autoencoders for anomaly detection.

## Overview

The project aims to develop an objective and scalable framework for singing evaluation by leveraging the power of deep learning. Traditionally, assessing singing proficiency has relied on subjective evaluation by experts, which can be prone to bias and inconsistencies. By training an autoencoder model on a comprehensive dataset like the VocalSet, the system can learn patterns of proficient singing and detect anomalies (deviations) in new vocal performances.

The proposed solution involves the following key components:

1. **Data Preprocessing**: Cleansing the audio recordings by removing background noises and enhancing the audio quality.
2. **Model Training**: Training an autoencoder model on the labeled VocalSet dataset to learn patterns of proficient singing.
3. **Anomaly Detection**: Evaluating new recordings based on their reconstruction error, with higher errors indicating deviations from learned patterns.
4. **Error Localization**: A novel technique to pinpoint the precise temporal locations and magnitudes of detected anomalies, providing granular insights for targeted feedback.
5. **Result Visualization**: Presenting the evaluated results to the singer, highlighting mistakes at specific timeframes and providing overall scores.

## Research Objectives

- Cleanse the audio recording by removing background noises and enhancing the audio.
- Evaluate the audio recording in comparison to a reference track using machine learning approaches.
- Present the evaluated results to the singer, highlighting mistakes at specific timeframes and providing overall scores.

## Methodology

1. Conduct user research to understand user preferences and attitudes towards AI-based singing evaluation.
2. Clean and label the VocalSet dataset for training the autoencoder model.
3. Train the autoencoder model on the labeled dataset.
4. Develop a method to visually present the evaluation results to the user.

## Technologies Used

- **Front-end**: React Native
- **Back-end**: Python, TensorFlow, Firebase
- **Hosting**: Vercel
- **Other tools**: Google Colab, Librosa

## Milestones

- Completion of user research
- Dataset preparation and labeling
- Autoencoder model training
- Development of result visualization method
- Integration and deployment of the complete system

## Highlights

- Objective and scalable singing evaluation using deep learning
- Anomaly detection approach to identify deviations from proficient singing patterns
- Novel error localization technique for pinpointing specific mistakes
- Potential applications in music education, talent assessment, and vocal pedagogy research

## Documentation

The research is based on the following document:

- IT20654580 (1).pdf - Final report on "Evaluating Singing Skills Using Machine Learning Approaches"

## Contributions

Group Leader:
Wickramasinghe K.A.T.C.
Sri Lanka Institute Of Information Technology
Department: Software Engineering

Group Members:
Purnamal M.C.P.
Sri Lanka Institute Of Information Technology  
Department: Software Engineering

Wijesingha W.A.A.D.
Sri Lanka Institute Of Information Technology
Department: Software Engineering

Jayasekara S.S.C. 
Sri Lanka Institute Of Information Technology
Department: Software Engineering

## About Us

[Brief description of the research team or organization]

## Contact Us

[Contact information, including email, phone number, and address]
