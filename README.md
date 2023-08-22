# YAMNet Audio Event Prediction and Cat-Dog Sound Classification

## About

Welcome to the YAMNet tutorial! In this guide, we'll explore the power of the YAMNet (Yet Another Multi-label Convolutional Neural Network) model – a versatile pre-trained deep neural network that predicts audio events across 521 classes, from laughter to sirens. But that's not all – we'll also take it a step further and leverage YAMNet's embeddings to build a custom model for classifying cat and dog sounds. Let's dive in!

## About YAMNet

YAMNet is a pre-trained neural network that employs the MobileNetV1 depthwise-separable convolution architecture. It can use an audio waveform as input and make independent predictions for each of the 521 audio events from the AudioSet corpus.

Internally, the model extracts "frames" from the audio signal and processes batches of these frames. This version of the model uses frames that are 0.96 second long and extracts one frame every 0.48 seconds .

## Building a Cat-Dog Sound Classification Model
Here's where the fun begins. The cat_dog_sound_classification.ipynb notebook will walk you through crafting a specialized model to distinguish between cat and dog sounds. The magic ingredient? YAMNet's embeddings as powerful features. Prepare to unravel data preprocessing, model architecture, training intricacies, and validation techniques.

## Evaluation and Model Export
No journey is complete without assessing achievements. Once your cat-dog sound classifier is trained, evaluate its prowess on a test dataset. The cat_dog_sound_classification.ipynb notebook will guide you. Furthermore, discover how to export your finely tuned model for future use in various applications.

## License

The code and content in this repository are shared under the Apache License, Version 2.0. Feel free to use them for your own learning and projects.

Happy Learning!

