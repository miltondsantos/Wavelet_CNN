# Wavelet_CNN
This approach relate how to use the Wavelet Transform to create images to train the Convolutional Neural Network

## Abstract

Identifying the musical genre of a song is straightforward for humans but challenging to automate. This study uses the Wavelet Transform to represent music as time-frequency components, creating spectrograms. These spectrograms train a Convolutional Neural Network (CNN) to classify audio signals into 10 genres: Blues, Classical, Country, Disco, Hip Hop, Jazz, Metal, Pop, Reggae, and Rock. Only the first 15 seconds of each song are analyzed, with 6,075 tracks in the training set and 2,025 in the test set. The process was repeated 10 times with randomly selected data splits. Classification accuracy ranged from 70% to 94%, significantly outperforming the 10% expected by chance.

## Introduction and Justification
Convolutional Neural Networks (CNNs) are prominent in Computer Vision, excelling in tasks like image recognition and generation. They can also process images derived from time-series data, such as audio signals, and convert them into visual representations. However, training CNNs is challenging due to limitations in the quantity and quality of image datasets. Insufficient data can lead to overgeneralization, while low-quality images impair the network's ability to identify key features.
Audio processing significantly enhances signal analysis, especially with advanced machine learning and deep learning techniques. Feature extraction, crucial for model training, leverages time and frequency domain information to optimize signal representation.
This study investigates using CNNs to classify audio signals by converting Wavelet Transform coefficients into images. By focusing on Wavelet-based methods instead of traditional Fourier Transforms, the work aims to improve the accuracy of musical genre predictions, contributing novel approaches to audio classification.
