# Project synopsis

## Project title
Phase-aware decompression of speech data using deep learning

## Background
In order to save large amounts of bandwidth on phone lines, the audio sent through them is often times heavily compressed. This increases the amount of simultanious conversations the phone line supports, which saves phone companies a lot of money, but is at the loss of audio quality for the users.

As the compression used on the original audio signal is lossy, there is no way to fully restore the original audio signal algorithmically after it has been compressed. However an approximation focusing on enhancing human speech might be possible.

## Project statement
This project aims to tailor a deep learning model to enhance human speech from audio sent through compressed phone line connections and decompress the signal. 

In its essence the problem is to estimate the a true underlying signal from a set of coarse samples and it can therefore be viewed as a regression task. In recent years deep learning models have shown to perform well in regression tasks [1], motivating the reasoning behind the deep learning approach to solve the problem of decompressing speech data using deep learning. 

To achieve this the project aims to:

1. Create a dataset consisting of pairs of compressed and uncompressed speech samples based on existing speech datasets for the purpose of supervised learning. The compression used should match the compression used in phone lines connections. 

2. Tailor a supervised regressive deep learning model for estimating uncompressed speech samples from compressed speech samples. This includes experimenting with and choosing a fitting model architechture, set of hyperparameteres and loss function. Furthermore, a simple baseline model will be constructed in order to compare performance of the deep learning model to. 

3. Present experimental results of the tailored model, comparing them to existing methods and the contructed baseline model.

4. Discuss results and further improvements

## References
[1] Maybe reference some paper showing deep learning is suitable for regression tasks