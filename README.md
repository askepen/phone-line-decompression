# Leveraging Machine Learning to enhance human speech in audio compressed through phone line connections
In order to save large amounts of bandwidth on phone lines, the audio sent through them is often times heavily compressed. This increases the amount of simultanious conversations the phone line supports, which saves phone companies a lot of money, but is at the cost of audio quality for the users.  

As the compression used on the original audio signal is lossy, there is no way to restore the original audio algorithmically after it has been compressed. However an approximation focusing on enhancing human speech might be possible. This project aims to train a Machine Learning model to recognize and enhance human speech from audio sent through compressed phone line connections and decompress the signal.


## Data
I imaging traning a model using supervised learning, with a dataset consisting of pairs of compressed and uncompressed audio samples of human conversations. There already exists [large datasets of humans speech](https://github.com/jim-schwoebel/voice_datasets) publically available. We will need to generate the compressed audio samples by running the original audio samples through a compression algorithm in order to simulate a phoneline. The exact compression algorithm to use, I am unsure of as of now. 

Alternatively, we might be able to literally play the audio through a real world phone connection in order to obtain samples. This approach might be more expensive, but may also generate more accurate data.

## Application
A practical application of this could be to integrate the machine learning model into an app or a phone OS. This way a person would be able to decrompress the live incoming audio of phone conversations and have a natural sounding conversation. 
