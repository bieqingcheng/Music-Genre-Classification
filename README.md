# Music-Genre-Classification
Musical genres are categorical labels to characterize pieces of music. Here by using audio files we try and predict  genre's

In this project, we implement various machine learning algorithms such as Convolution Neural Network (CNN) and Random Forest to classify the following the music files in GTZAN dataset which has ten types of genres: country, classical, jazz, metal, pop, blues, rock, reggae, disco, hip-hop. 
We relied purely on Mel Frequency Cepstral Coefficients (MFCC) to characterize our data. We then applied the machine learning algorithms using the MFCCs as our features.

## DataSet

We have used the GTZAN Dataset from MARSYAS (Music Analysis, Retrieval and Synthesis for Audio Signals) Website.

The data consisted of 10 genres: (country, classical, jazz, metal, pop, blues, rock, reggae, disco, hip-hop), each containing 100 tracks. All the tracks are 30 seconds long, 22050Hz Mono 16-bit audio files in .au format. Thus, our total data set was 1000 songs, of which we used 80% for training and 20% for testing. 


