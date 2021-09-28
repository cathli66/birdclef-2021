# birdclef-2021
Using Machine Learning to classify bird species from birdcalls. Done with Emily Song in 2021.

Generates spectrogram images of provided birdcall recordings and using librosa. 
Creates data augmentation samples and generates more spectrogram images to improve robustness of the model. 
The CNN model built with tensorflow trains on spectrograms plus data augmentation samples to get about 80% accuracy for first 100 bird species with most high quality soundscapes.
