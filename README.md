# Spotify Project Proposal
Group Project 1


## Project Title: 
The Spotify API Analysis 

## Team Members: 
Molly Bruns, Sydney Cohen, Maite Rivas,  B Slone

## Project Description/Outline: 
Analyze various audio features of publicly available spotify top charts for the week of June 2nd 2022 to see how a given audio feature is represented in top songs 

## Research Questions to answer: 
* Does tempo significantly impact the danceability of global top songs?
* Is there any significant relationship between the danceability and energy of global top songs?
* Does energy help us predict the valence of top songs? 
* Is there any significant relationship between a top song’s duration and its other audio audio features?

## Datasets to Be Used:
* Publicly available spotify top charts found at [charts.spotify.com](https://charts.spotify.com/charts/view/regional-global-weekly/latest)
* [Spotify API](https://developer.spotify.com/documentation/web-api/reference/#/operations/get-several-audio-features) data based on song ID for songs of interest 

## Rough Breakdown of Tasks: 
* Create dataframe of top songs of interest for given investigation
* Clean up raw csv from publicly available top charts 
* Loop through spotify API to pull variable of interest 
* Basic visualizations and statistical analysis to determine interesting correlations and trends based on question
* Choose and create useful visualizations and explain inferences 
</br>
---
## Findings
**Does tempo significantly impact the danceability of global top songs?**</br>


**Is there any significant relationship between the danceability and energy of global top songs?**</br>


**Does energy help us predict the valence of top songs?**</br> 


**Is there any significant relationship between a top song’s duration and its other audio audio features?**</br>
There were very weak or no correlations between a song's duration and the following audio features: 
- Tempo: ![Song Duration by Tempo - Global Top Songs 5/27/2022 - 6/2/2022](https://github.com/mbruns13/project_1_spotify/blob/main/images/duration_tempo.png?raw=true)
- Energy: ![Song Duration by Energy - Global Top Songs 5/27/2022 - 6/2/2022](https://github.com/mbruns13/project_1_spotify/blob/main/images/duration_energy.png?raw=true)
- Danceability: ![Song Duration by Danceability - Global Top Songs 5/27/2022 - 6/2/2022](https://github.com/mbruns13/project_1_spotify/blob/main/images/duration_danceability.png?raw=true) 
- Weeks on Chart: ![Song Duration by Weeks on Chart - Global Top Songs 5/27/2022 - 6/2/2022](https://github.com/mbruns13/project_1_spotify/blob/main/images/duration_weeks-on-chart.png?raw=true)
- Rank: ![Rank by Song Duration - Global Top Songs 5/27/2022 - 6/2/2022](https://github.com/mbruns13/project_1_spotify/blob/main/images/rank_duration.png?raw=true)
- Number of Streams: ![Song Duration by Number of Streams - Global Top Songs 5/27/2022 - 6/2/2022](https://github.com/mbruns13/project_1_spotify/blob/main/images/duration_streams.png?raw=true)

Most songs in the Global Top Songs Chart between 5/27/22 and 6/2/22 were between 2.91 and 3.85 minutes long, with the average duration equal to 3.43. The songs from the same time period on the US chart were similar, with most songs lasting between 2.90 and 3.94 minutes long, with the average duration equal to 3.49.

</br>

Slide presentation can be found [here](https://docs.google.com/presentation/d/1emqUlGtQ6cZXMqo08uc2ZbHmale3IQClO9j39Cb1cxk/)