<img src="https://bit.ly/2VnXWr2" alt="Ironhack Logo" width="100"/>

# Hot Music Recommender
*Kim Desi*

*Ironhack | May 2021*

## Content
- [Project Description](#project-description)📙
- [Questions](#questions)❔
- [Dataset](#dataset)📄
- [Workflow](#workflow)🔧
- [Organization](#organization)📖
- [Links](#links)💫

## Project Description📙

The goal of this project was to create a music recommender based on the [billboard hot 100](https://www.billboard.com/charts/hot-100) using a machine learning model. In the first step the music recommender should ask the user for a song title as input and then check whether the user input is in the current hot 100 or not. 
- If it is, recommend another song that's currently in the top 100. 
- If it's not, use a model trained on songs audio features to recommend a song that is similar to the user input 

The recommendation is made by clustering the audio features of the dataset by similarity, using the K-means algorithm. 

## Questions❔

Starting this project I already had some questions, which only increased as soon as I started!  
- How can you recommend music based on the user inputs song?
- Which audio features are logical to use in the recommendation model and lead to good performance?
- How can I improve a machine learning model like this, which approaches are there?

## Dataset📄

To be able to check wheter the user input is part of the hot 100, a dataset of the current hot 100 song titles is needed. The data was obtained by web scraping the [hot 100](https://www.billboard.com/charts/hot-100) website and formatting it into a dataframe. To be able to recommend songs based on audio features, a dataset of songs and their audio features is needed. In this case I used Spotify's API to obtain data about songs and their adio features and stored them into a dataframe. 

## Workflow🔧

1. Set up project plan 
- think about what to do & research how to do it
- create different notebooks for different purposes
- set up folder structure in repository
- create OneNote for organization

2. Web scraping billboard hot 100
- scrape and format HTML of the website
- store data in dataframes & csv files

3. Spotify API
- reading documentation & setting up access
- obtain audio features of the hot 100
- obtain audio features of a playlist to create data for training the model
- store data in dataframes &csv files

4. Machine learning model
- prepare the data for the model to ensure optimal performance
- find optimal amount of clusters
- create new dataframes containing new information about which clusters songs belong to
- store data in dataframes/csv files and model using pickle
 
5. Hot music recommender
- create function including user input and recommendation 
- test the recommender!

6. Revisit & improve
- revisit project and add information/comments in code
- improve code

## Organization📖 

This project was organized using a OneNote notebook.

## Links💫

[Repository](https://github.com/Desikim/Project_3)  

 
