# FinalProjectDS105

**Team Name:** DS105 superstars

**Team Members:**
-   👨‍💻 Simon Deshayes
-   🦸‍♀️ Sijia He (Scarlett)
-   👩‍💻 Shuyu Cao (Cathy)
-   👸 Yinyue Wang (Cynthia)

NOTE! This repository only contains our source code for data analysis process. If you wanna check our final webpage, please see this repository instead: [FinalProjectWebsite](https://github.com/simondesh/FinalProjectWebsite)

## Motivation and Obejctives

Steam is a massive platform for gamers, developers, and publishers, offering access to thousands of games. Whenever Steam releases new games, they quickly become online sensations, attracting millions of players daily. As of September 2022, the number of games on Steam has reached an impressive 50,000. Not only do new releases dominate the scene, but timeless classics like CSGO have also made their mark in gaming history.

While some games gain immense popularity, others struggle to attract buyers. The game development industry is a lucrative field, as creating a hit game can bring substantial fortune to developers, driving more individuals to enter the market. Consequently, our team is intrigued by the factors that contribute to a game's success. We aim to offer suggestions to creators, investors, and publishers on how to craft a popular game, considering aspects such as genre, pricing, release year, and more.

## Data Sources
We used two API sources including Steam API and Steamspy API, here are the links to the corresponding API documentations we used in the project.
- Steam API: https://steamapi.xpaw.me/
- Steamspy API: https://steamspy.com/api.php

## How to use the repo

1. Clone the repository to your local machine
2. Set up the virtual env and install the dependencies:
```
$python3 -m venv env
$source env/bin/activate
(env)$pip install -r requirements.txt
```
3. Run the .ipynb files in the scr folder, including `data_gathering.ipynb`, `data-cleaning-steam.ipynb`, `data-cleaning-steamspy.ipynb`, `Exploratory Data Analysis.ipynb` and `XBG_modelling.ipynb`
   
## Issues
The data collection script (data_gathering.ipynb) may not produce identical results to our first extraction due to variations in the data obtained from the two APIs over time.

## Team Member Roles
|                                | Simon  |  Scarlett  |  Cathy  |  Cynthia  |
|--------------------------------|--------|------------|---------|-----------|
|Data Collection                 |√       |            |         |           |
|Data cleaning and <br> Wrangling|        |√           |         |           |
|Exploratory Data Analysis       |        |√           |         |√          |
|Topic Modelling                 |√       |            |√        |           |
|Documentation                   |√       |√           |√        |√          |
