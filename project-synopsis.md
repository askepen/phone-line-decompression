# Project synopsis

## Project title
Phase-aware decompression of speech data using deep learning

## Background
In order to save large amounts of bandwidth on phone lines, the audio sent through them is often times heavily compressed using lossy compression techniques. This allows for increasing the number of simultaneous conversations the phone line supports, which saves phone companies a lot of money, but is at the loss of audio quality for the users. As the compression used on the original audio signal is lossy, there is no way to fully restore the original audio signal algorithmically after it has been compressed. However, the quality of restored audio signal might be enhanced using recovery methods that leverage the characteristics of the underlying human speech.

## Project statement
This project aims to tailor a deep learning model to enhance human speech from audio sent through compressed phone line connections and decompress the signal. In its essence, the problem is to estimate the true underlying signal from a set of coarse samples and it can therefore be viewed as a regression task. In recent years, fully data-driven deep learning models have proven very successful in a plethora of regression tasks arising in various fields ranging from engineering and economics to forestry (see, e.g., [1]), motivating the reasoning behind the deep learning approach to solving the problem of decompressing speech data. Furthermore, in order to increase the likelihood of capturing the underlying patterns of human speech, this project aims to make the deep learning model phase-aware, as phase-awareness and phase processing has shown to be an important factor in speech enhancement when using deep learning (see, e.g., [2]).

To achieve this, the project aims to:

1. Create a dataset consisting of pairs of compressed and uncompressed speech samples based on existing speech datasets for the purpose of supervised learning. The compression used should match the compression used in phone lines connections.

2. Tailor a supervised deep regression model for estimating uncompressed speech samples from compressed speech samples. This step involves choosing the most relevant deep learning architecture considering the nature of input data and fine tuning that in a data-driven manner (e.g., determining the configuration, the set of hyper-parameters, and the loss function). Furthermore, a simple baseline model will be constructed in order to compare performance of the deep learning model to. 

3. Present experimental results of the tailored model, comparing them to existing methods and the constructed baseline model.

4. Discuss the experimental results, identify limitations of the tailored model and discuss further improvements.

## References
[1] Reichstein, Markus, et al. "Deep learning and process understanding for data-driven Earth system science." Nature 566.7743 (2019): 195-204.

[2] Zheng, Naijun, and Xiao-Lei Zhang. "Phase-aware speech enhancement based on deep neural networks." IEEE/ACM Transactions on Audio, Speech, and Language Processing 27.1 (2018): 63-76.



