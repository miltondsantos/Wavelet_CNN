# Wavelet_CNN
This approach relate how to use the Wavelet Transform to create images to train the Convolutional Neural Network

## Abstract

Identifying the musical genre of a song is straightforward for humans but challenging to automate. This study uses the Wavelet Transform to represent music as time-frequency components, creating spectrograms. These spectrograms train a Convolutional Neural Network (CNN) to classify audio signals into 10 genres: Blues, Classical, Country, Disco, Hip Hop, Jazz, Metal, Pop, Reggae, and Rock. Only the first 15 seconds of each song are analyzed, with 6,075 tracks in the training set and 2,025 in the test set. The process was repeated 10 times with randomly selected data splits. Classification accuracy ranged from 70% to 94%, significantly outperforming the 10% expected by chance.
