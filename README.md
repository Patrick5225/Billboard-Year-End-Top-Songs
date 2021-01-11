# Billboard Year-End Charts Analysis
The [Billboard Year-End chart](https://www.billboard.com/charts/year-end/2020/hot-100-songs) is a chart published by Billboard each year that displays yearly rankings of the top 100 songs, as determined by the Billboard company themself. According to Billboard, rankings are determined based on factors such as sales, amount of streams on music streaming services such as Spotify, and how frequently songs are played on radio stations. Each billboard chart year starts and ends around the month of December.

But does Billboard really rank their charts based on measures such as popularity, as they claim? In this project, I collected data of every song that has appeared on the Billboard Year-End charts from years 1960-2020, along with measures such as popularity and other audio features of each song, to answer this question. I also used the collected data to observe if there were any common characteristics among songs that appeared on Billboard charts, if there were any relationships among variables such as the audio features of songs and the year it was ranked on the charts, and to explore which artists/songs appeared most often.

## Project Overview
- Scraped over 6000 songs, artists, and rankings from Wikipedia using python libraries requests and beautifulsoup4
- Retrieved more data for each song such as its popularity and audio features using Spotify's Web API
- Cleaned data using python and Excel to add and remove columns, fix data values, and remove or fill null values

## Resources Used

**Website where data is scraped**: https://en.wikipedia.org/wiki/Billboard_Year-End</br>
**Spotify API Article**: https://towardsdatascience.com/what-makes-a-song-great-part-2-e82a44be659c</br>
**Spotify Web API Documentation**: https://developer.spotify.com/documentation/web-api/

## Main Files in this Repository
`Billboard Year-End Analysis.ipynb` Contains exploratory data analysis with visuals, tables, and charts</br>
`wikipedia_scraper.ipynb` Code used to scrape data</br>
`Spotify Id Extraction.ipynb` Uses Spotify's API to find Spotify Id for each song in data</br>
`Spotify Audio Features Extraction.ipynb` Uses Spotify's API to extract audio features of each song</br>
`spotify_complete.csv` Contains all the completed, cleaned data
