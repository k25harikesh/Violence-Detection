# Violence Detector using VGG19 Pre-trained Model (CNN+LSTM)

## Overview
This project implements a violence detector using a VGG19 pre-trained model combined with a Long Short-Term Memory (LSTM) network. The VGG19 model is used for feature extraction from video frames, and the LSTM network is used to analyze temporal sequences of features to detect violence in videos.

## Features
- Utilizes transfer learning with VGG19 pre-trained model for feature extraction.
- Implements a Long Short-Term Memory (LSTM) network for analyzing temporal sequences of features.
- Trained on custom data to detect violence in videos.
- Provides specific results for violence detection in videos.


## Dependencies
- Python 3.x
- PyTorch
- OpenCV
- NumPy

## References
- [VGG19 Paper](https://arxiv.org/abs/1409.1556)
- [LSTM Paper](https://www.bioinf.jku.at/publications/older/2604.pdf)

## License
This project is licensed under the [MIT License](LICENSE).
