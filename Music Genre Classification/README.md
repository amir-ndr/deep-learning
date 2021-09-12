<h1> Context</h1><br />
Music. Experts have been trying for a long time to understand sound and what differenciates one song from another. How to visualize sound. What makes a tone different from another.<br />
This data hopefully can give the opportunity to do just that.<br /><br />

<h1> Content</h1><br />
genres original - A collection of 10 genres with 100 audio files each, all having a length of 30 seconds (the famous GTZAN dataset, the MNIST of sounds)
images original - A visual representation for each audio file. One way to classify data is through neural networks. Because NNs (like CNN, what we will be using today) usually take in some sort of image representation, the audio files were converted to Mel Spectrograms to make this possible.
2 CSV files - Containing features of the audio files. One file has for each song (30 seconds long) a mean and variance computed over multiple features that can be extracted from an audio file. The other file has the same structure, but the songs were split before into 3 seconds audio files (this way increasing 10 times the amount of data we fuel into our classification models). With data, more is always better.<br /><br />

the link of the dataset: https://www.kaggle.com/andradaolteanu/gtzan-dataset-music-genre-classification<br /><br />

<hr />
first we gained some information about the data set, then we loaded the songs, visualized and preprocessesed them using the librosa library.<br />
then we designed a model, compiled it with adam optimizer and fitted it based on mfcc of the songs.(so we recognize the genre of a song based on its mfcc matrix)<br />
so at the end we got 90% accuracy on the validation set.


