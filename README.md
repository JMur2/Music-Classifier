# Music-Classifier
My final project for Introduction to Intelligent Systems.  This project is meant to classify the genres of songs with an artificial neural network.  

There are 2 files included, one dedicated to creating the spectrograms, and one dedicated to training/testing the model with the data.  The first file is closely based on a similar project from desposisj, a link to that repository is here:
https://github.com/despoisj/DeepAudioClassification

I used this repository to help me transform the songs in their raw format into the spectrogram images.  The work on my model file is my own based on the work we did in class for convolution.

The Data directory has 3 sub directories, Raw, Slices, and Spectrograms.  The raw directory is where songs need to go to convert them.  Note that the genre of the song must be in the properties if the .mp3 file in order for it to work as intended. The slices anf spectrograms file will populate as the create dataset file is ran.  Make sure to empty these before recreating the dataset to avoid duplicated and replacements.
