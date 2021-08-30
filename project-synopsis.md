# Project synopsis (draft)

## Project title
Audio decompression of speech data using Machine Learning

## Background
In order to save large amounts of bandwidth on phone lines, the audio sent through them is often times heavily compressed. This increases the amount of simultanious conversations the phone line supports, which saves phone companies a lot of money, but is at the cost of audio quality for the users.

As the compression used on the original audio signal is lossy, there is no way to restore the original audio algorithmically after it has been compressed. However an approximation focusing on enhancing human speech might be possible.

## Project statement
This project aims to train a Machine Learning model to recognize and enhance human speech from audio sent through compressed phone line connections and decompress the signal. Specifically my project should:

1. Present the theoretical foundation for how Short-Time Fourier Transform (STFT) works and can be used in regards to audio preprocessing
1. Account for and replicate the type of audio compression used in phone lines
1. Explain the concept of supervised learning
1. Create a dataset of pairs of compressed and uncompressed audio samples
1. Construct a simple baseline model to compare a more sophistcated machine learning model to
1. Explain the procces of training a machine learning model that estimates good quality audio clips from compressed clips 
1. Present a machine learning model architechture suitable for
1. Present results and a comparission to baseline model. (and maybe state-of-the-art?)
1. Discuss results and further improvements

