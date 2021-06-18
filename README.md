
# Hot Music Recommender

*Ironhack Data Analytics bootcamp Project 3*

#### Project Description

Creating an algorithm that compares audio features of an input song to 2 databases with clusters containing different audio feature groups.

#### Workflow

1. Create dataframe hot 100 songs 
  -Scrape website of hottest 100 music (link)
  -Restructure HTML into dataframe with hot 100 songs and artists
  -Get the audio features of the hot 100 songs and add to dataframe
     
2. Create dataframe out of huge playlist(s) using spotipy
  -Gather information in dataframe
  -Get the audio features of the spotify playlist and add to dataframe
     
3. Train a model (algorithm) 
  -Using clustering method of audio feats
  -Calculating optimal number of clusters (k)
  -Using model to suggest songs in step 4
 
4. Create function to check if user input = hot 100
  -If yes, suggest another song of hot 100 with similar audio feat
  -If not, suggest another song with similar audio feat by any artist & popularity
     
   
 
