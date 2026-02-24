# BMS Molecular Translation

This repository contains a deep learning pipeline designed to "translate" images of chemical compounds into their standard InChI textual notation.

🧪 Project Overview
The model treats the problem as an image-captioning task. It uses a Convolutional Neural Network (CNN) to extract visual features from molecular drawings and a Recurrent Neural Network (RNN) with an attention mechanism to generate the chemical identifier string.

🛠️ Technical Architecture
Encoder: EfficientNet-B2 (pretrained) used for robust feature extraction from diverse chemical structure drawings.
Decoder: An LSTM-based decoder featuring Top-K search to improve the accuracy of the generated InChI strings.
Frameworks: Built using Python and PyTorch.
