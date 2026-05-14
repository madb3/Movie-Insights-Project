# Exploring Movie Trends
A class project exploring trends in the film industry using a variety of metrics
## Project Overview
- Built a simple recommendation system based on movie data like genre and popularity
- Looked at how genres changed over time, specifically revenue and popularity
- Used data visualization methods to find trends and understand why certain movies are recommended

## Data Sources
#### Letterboxd Movie Dataset: https://www.kaggle.com/datasets/kutayahin/letterboxd-movies-dataset
#### Horror Movies Dataset: https://www.kaggle.com/datasets/sujaykapadnis/horror-movies-dataset
#### Movie history and context:
https://dl.acm.org/doi/10.1145/2827872 \
https://onebeon.com/film-genres/how-film-genres-have-changed-over-the-decades/ \
https://trail.pugetsound.edu/?p=18998

## Recommendation System
- Tuned features like genres, ratings, and popularity into numerical values to compare movies.
- Visualized similarity results using bar chart showing match percentages
- System accurately recommended movies with similar values
#### Example Output:

<img width="373" height="316" alt="5b648f6dca3eea35ec854b045189efe8" src="https://github.com/user-attachments/assets/7f297056-4b4c-4292-805a-bc89a2ace2c7" />


## Film Industry Insights
### How have movie genres trended over time?
Using data visualization techniques, I was able to create a line graph comparing movie popularity and decade to find any patterns. I found that there was a large spike in horror movie production in the 80s and 2000s. There is a notable decline in the 2020s, with a major decline in ticket sales following the pandemic and the rise of streaming services.

<img width="575" height="390" alt="genres over time" src="https://github.com/user-attachments/assets/ef56a3bb-4d5b-49d9-848d-2a4b0797188b" />

### What caused the increase in horror movie production in the 80s?
* I noticed a huge uptick in horror movie production in the 80s from my previous graph and wanted to explore the cause. Since social and cultural influences are difficult to quantify directly, I focused on more measurable factors like production value and budget.
* To do this, I sourced a horror movie dataset containing budget and revenue information and merged it with my Letterboxd dataset. This allowed me to enrich overlapping titles with financial data on production cost and box office performance.
* I then created a scatterplot comparing horror films to other genres in terms of budget versus revenue. The results showed that horror movies were typically low-budget but generated relatively high returns at the box office.

<img width="633" height="469" alt="budget revenue over time" src="https://github.com/user-attachments/assets/0f6b5dad-2df1-4d6d-9e2b-7b176d43bda8" />

#### I concluded that the 3 major causes of the spike in popularity were:
- __Cultural factors:__ As cold war tensions died down in 1980s, there was an opportunity to capitalize on emerging anxieties rooted in suburban life and the "Satanic Panic".
- __Industry improvements:__ Better special effects technology made for a more immersive and believable horror movie experience.
- __Low risk, high reward:__ On average, horror movies were cheap to produce but yielded strong box office returns, making them a good investment for production studios.














