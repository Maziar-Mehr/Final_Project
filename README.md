# Lyric-based Song Recommendation Using Universal Sentence Encoder Embeddings and Spotify’s API

by [Maziar Mehr](https://github.com/Maziar-Mehr), December 2021
## Understanding song lyrics using natural language processing.
[Presentation](https://slides.com/d/yCJDfAs/live)

![Record-shop](https://user-images.githubusercontent.com/88034001/148057551-f9046147-d8dc-47dd-aa0e-f75e289dc65e.jpg)



## Table of contents
- [Project Brief](https://github.com/Maziar-Mehr/Final_Project#project-brief)
- [Data & Visualization](https://github.com/Maziar-Mehr/Final_Project#data--visualization)
- [Tools](https://github.com/Maziar-Mehr/Final_Project#Tools)



## Project Brief
Boundaries that divide music genres are fuzzy and the passing of time augments this even more. Hip-hop is a very lyric-heavy genre and many of the key descriptive metrics that describe lyric count for hip-hop are different from all other genres. Accordingly, hip hop genre is a great fit for this project but this method can be used for any other music genre that contains lyrics.
 
**Description :**
In this venture, I dived into how natural langue processing can be applied to build a lyrics-based song recommender. First, I automated the Spotify app with python to find the lyrics of the current song playing using Spotify API and BeautifulSoup. Besides, I created the lyrics data frame using web scraping from a couple of different online sources. Finally, after Embedding the lyrics by using Universal Sentence Encoder I clustered them using the K-means method. 
 ![P - Final](https://user-images.githubusercontent.com/88034001/146432587-72907535-6436-4146-9b20-fdbbc727e7ce.png)


**Challenge:**
Automate Spotify with Python (Spotify API) and Text Embedding and Clustering. 

**Advanced Analysis & Data Scientist Techniques :**
- Data Visualisation to show or interactively explore trends, patterns, relationships
- Scraping data or utilising APIs to collect data, which will need cleaning, wrangling
- NLP: unstructured data, text and sentiment analysis


## Data & Visualization
The raw [data](https://github.com/Maziar-Mehr/Final_Project/tree/main/Data) contains the lyrics of 274 songs from 12 different Hip-Hop artists. The 
dashboard below shows the frequency of the words in this data set. 
![Visual](https://user-images.githubusercontent.com/88034001/146430671-b7d62695-a3f0-4879-b06e-abc1d701f53d.png)


For further information you can find the Tableau worksheets [here.](https://github.com/Maziar-Mehr/Final_Project/tree/main/Tableau)

## Tools
I used the following tools to achieve the objective.

- **Tableau:** You can find the Tableau worksheets [here](https://public.tableau.com/app/profile/maziar7848/viz/Hip-Hopgenreanalysis/MostCommonWordsTop20?publish=yes).
- **Python:**  You can find here the [NoteBooks](https://github.com/Maziar-Mehr/Final_Project/tree/main/Python) 
- [Universal Sentence Encoder](https://tfhub.dev/google/universal-sentence-encoder/1) 


