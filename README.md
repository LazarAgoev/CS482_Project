# CS482_Project

The proposal for our project is that we are planning on using historical data from Spotify about the previous years' top songs in order to attempt to make an algorithm that can predict how popular a song will become, based off of measures such as decibel loudness, as well as the key and modality of the track. This problem is interesting because the world of music is a very unpredictable one, and record companies can only put out so many songs. This is a way for them, as well as independent music artists, to gain a predictive understanding on how popular they can expect one of their songs to become on a streaming service like Spotify. We will be using data from kaggle about the Top 50 songs on Spotify for various years in order to achieve the goal of this project. In terms of a learning algorithm, we are looking at gradient boosting as a baseline for how we want to train our data in order to try and get as high of an accuracy as we can. One of the things we'll have to improve on with this algorithm is to ensure that it can still be accurate even with the smaller amount of data that we have available. We will evaluate our data at first by looking at the accuracy of our training algorithm as we polish it, and then later by looking at some of the most popular songs from 2022 and plugging them into the algorithm with other more "mediocre" music, expecting the more popular songs to score a higher predicted popularity than the control tracks. We can also possibly make visual charts of how different aspects of a song impact its popularity, and draw conslusions from there.

Run the Google Colab section by section in order. Please be sure to utilize the 2021top.csv and SpotifySongsProject - Sheet1.csv files we provided in order to sucessfully run the Google Colab code. 
