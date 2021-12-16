# Song Recommender Based on Lyrics 

by [Maziar Mehrbakhsh](https://github.com/Maziar-Mehr), December 2021
## Analyzing lyrics from the Hip-hop genre and song recommendations based on lyrics



![Cover 2](https://user-images.githubusercontent.com/88034001/146410874-e194aabb-2f94-48a2-b566-f47d458066c3.jpg)

## Table of content
- [Project Brief](https://github.com/vonate5/midterm_regression_project#project-brief)
- [Data](https://github.com/vonate5/midterm_regression_project#data)
- [Process & tools](https://github.com/vonate5/midterm_regression_project#process--tools)
- [Visualization](https://github.com/vonate5/midterm_regression_project#visualization)
- [Results](https://github.com/vonate5/midterm_regression_project#results)


## Project Brief
**Why Hip-Hop?**
 Boundaries that divide genres are fuzzy and the passing of time augments this even more. Hip-hop is a very lyric-heavy genre and many of the key descriptive metrics that describe lyric count for hip-hop are different from all other genres. Accordingly, hip hop genre is a great fit for this project.
 
**Description :**
The first step of this project was to automate the Spotify app with python to use the Spotify API and then get the lyrics of the song that is currently playing on the Spotify App by scrapping. On the other hand, I created a lyrics data frame by scrapping several sources online (Genius and Musixmatch ...). One of the main challenges in this project is encoding and clustering the lyrics. There are so many methods available out there for text encoding and clustering but I used the Universal sentence encoder because is suitable for large texts. 
 

**Challenge:**
Automate Spotify with Python (Spotify API) and Text Embedding and Clustering. 

**Advanced Analysis & Data Scientist Techniques :**
- Data Visualisation to show or interactively explore trends, patterns, relationships
- Scraping data or utilising APIs to collect data, which will need cleaning, wrangling
- NLP: unstructured data, text and sentiment analysis

Further project details such as deliverables can be found [here](https://github.com/vonate5/midterm_regression_project/tree/main/project_details)

## Data
Leveraging on the [data](https://github.com/vonate5/midterm_regression_project/tree/main/data) we were provided with, we used Tableau's data visualisation tools to explore the relationships between features. 
To find out more about the distribution of the important features I highlighted, you can have a look on our Tableau dashboard below:<br/> <br/>
<img width="1059" alt="tableau_visualization" src="https://user-images.githubusercontent.com/88034001/142411325-114de632-cc82-4ecd-859d-f8c11bbfe4c4.png">


For further information you may find the Tableau worksheets and dashboard [here](https://github.com/vonate5/midterm_regression_project/tree/main/tableau)

## Process & tools
We use the following tools to achieve the objective.

<img width="302" alt="process tools (1)" src="https://user-images.githubusercontent.com/88034001/142411294-c85a20ce-3d40-4bdf-92b8-6cd18d3fc295.png">


- **MySQL:** we use MySQL to complete the SQL [questions](https://github.com/vonate5/midterm_regression_project/blob/main/project_details/sql_questions_regression.md). You can find the answers [here](https://github.com/vonate5/midterm_regression_project/tree/main/sql).
- **Trello:** set up our Trello board to help us organized and complete the daily tasks.
- **Tableau:** here you can find the Tableau [questions](https://github.com/vonate5/midterm_regression_project/blob/main/project_details/tableau_regression.md).You can find the Tableau worksheets and dashboard [here](https://github.com/vonate5/midterm_regression_project/tree/main/tableau).
- **Python:** programming language we use to build the Machine Learning model that give us the 84% accuracy of the price prediction. You can find here the [code](https://github.com/vonate5/midterm_regression_project/tree/main/code) and the final model [here](https://github.com/vonate5/midterm_project/blob/main/code/Midterm_project_regression_final.ipynb).
- **Machine Learning:** we use the Linear Regression model, being the final accuracy **84.4%**. 

## Visualization
You can see the full visualization we've done in [Tableau 📊](https://github.com/vonate5/midterm_regression_project/tree/main/tableau) or the [Presentation](https://slides.com/virgilioonate/case-s)

## Results

#### Our model can predict the price of a house based on features with the accuracy of 84.4%.

#
**Thanks for reading,**

If you have any question please reach out to us,<br/><br/>
Team MadRan
