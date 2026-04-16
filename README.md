# Fandango's Rating Conspiracy : Can you really trust online movie reviews?
 
> *"The best movie ticket is an informed one."*
 
Uncovering Fandango's 2015 rating scandal — were movie scores quietly inflated to sell more tickets? This data analysis digs into the bias behind online ratings, compares Fandango against rival platforms, and asks the question every moviegoer should: **can you actually trust what you see online?**
 
---
 
## The Backstory
 
In 2015, data journalist **Walt Hickey** at FiveThirtyEight noticed something suspicious. Fandango — a platform that *both reviews movies AND sells tickets for them* — seemed to be rating films unusually high. Almost suspiciously high.
 
His investigation revealed a glaring pattern: the star ratings displayed on Fandango's website were consistently **rounded up**, not to the nearest half-star, but always in Fandango's favor. A movie with a true rating of 4.1 stars would display as 4.5. A 4.5 would show as 5.
 
The conflict of interest was obvious. Fandango profits when you buy tickets. Higher ratings = more ticket sales. So... were they cooking the books?
 
This project sets out to answer that very question — with data.
 
---
 
## Project Objective
 
> **If you are planning on going out to see a movie, how well can you trust online reviews and ratings? Do they have a bias towards rating movies higher than they should be rated?**
 
To answer this, I have analyzed Fandango's ratings head-to-head against other major review platforms and look for statistically significant signs of inflation.
 
---
 
## What's Inside
 
-  **Exploratory Data Analysis (EDA)** — Getting familiar with the data, distributions, and anomalies
-  **Fandango vs. The Competition** — Comparing ratings across Rotten Tomatoes, Metacritic, and IMDB
-  **Rating Distribution Analysis** — Are Fandango's scores skewed higher than everyone else?
-  **Normalization & Scaling** — Putting all platforms on the same scale for a fair fight
-  **Visual Storytelling** — Clear, compelling charts that make the bias impossible to ignore

## Dataset
 
The dataset used in this project was originally compiled by **Walt Hickey / FiveThirtyEight** and contains:
 
- fandango_scrape.csv - Fandango star ratings and vote counts for popular films
- all_sites_scores.csv - Ratings from Rotten Tomatoes (critics + audience), Metacritic, and IMDB

*Made with curiosity, Python, and a healthy distrust of suspiciously round numbers.*
