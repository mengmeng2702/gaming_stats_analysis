# gaming_stats_analysis

## Project Overview
**Selected Topic**: 

Twitch Viewership Analysis Based on Game Reviews/Genre/Year

**Reasoning on Choosing the Topic**:

The gaming industry has been growing recently with a rapid increase in audience size. Live streaming, among all the other entertainment forms of activities, is incredibly popular and is a growing industry. Twitch GVC revenue generated was 1.6 USD billions in year 2018, 1.5 USD billions in 2019, and 2 USD billions in 2020, which has surpassed YouTube revenue in those consecutive years from 2018 - 2020, with 1.2, 1.4, and 1.7 USD billions revenue respectively(IQBAL, 2021).

This project aims to provide analysis and make predictions on whether the cumulative reviews of games, associated genre, and release year correlate to the total hours watched on Twitch (Twitch Viewership).

**Description of Source Data**

The team has carefully chosen new datasets (CSV files from Kaggle website) from the original ones after performing data cleaning and table merging using Python Pandas. To include a wider range of games that we have currently in the market, we have chosen the following datasets as our source data:

*Metacritic Video Game Comments* - Video Game Comments from Metacritic's Best of All Times, <a href="https://www.kaggle.com/dahlia25/metacritic-video-game-comments">click here for the link to the dataset</a>

*Steam Store Games (Clean dataset)*- Combined data of 27,000 games scraped from Steam and SteamSpy APIs, <a href="https://www.kaggle.com/nikdavis/steam-store-games">click here for the link to the dataset</a>

*Top games on Twitch 2016 - 2021* - Monthly top 200 games on the platform, <a href="https://www.kaggle.com/rankirsh/evolution-of-top-games-on-twitch">click here for the link to the dataset</a>

*Steam Reviews Dataset* - Rating data from 6M unique users, with 15M reviews over 8,183 games, <a href="https://www.kaggle.com/forgemaster/steam-reviews-dataset">click here for the link to the dataset</a>

**Objectives**
* Objective 1: Perform feature importance analysis on the selected dataset(s) to see the statistical correlation between different features and twitch viewership. Twitch viewership furthermore breaks down to peak views, and hours watched.

* Objective 2: The second objective we hope to accomplish is from a user experience perspective. We wish to help new Twitch users to be able to make decisions on the options of games they can start with based on their needs (reaching the optimal hours watched by viewers within a preferred period).

## Team and Communication
**Team Members**
- Sasha Manohar
- Anthony Hendrickson
- Boyang Yu
- Mengdi Liu

**Communication**
- Communication media: Slack
- Collaboration tools: Slack & Github & Google shared drive
- How often do we meet: Monday & Wednesday, touchpoint Google Meet on request

**Values**
- Responsiveness
- Honesty
- Transparency
- Meeting rubric expectations
- Punctuality
- Respect/friendliness


## Provisional Machine Learning Model
* Feature Importance analysis and Random Forest Model/ Deep Learning Model
* SHAP values

The candidates of input variables are features potentially related to a game's viewership, such as the genre of the game, number of monthly reviews on steam, etc. The output of the model would be predictions on proxies of viewership, i.e., hours watched per month, average number of viewers per channel.

The idea is to perform feature importance analysis on the Objective 1 to conclude the features that do cast an impact on the Twitch Viewership. Then we will use SHAP values to interpret the impact of certain values for a given feature compared to the baseline values. 

## Provisional Database

For the purposes of achieving Objective 1, a database connection will not be used; instead, available CSV files will be loaded into memory for the purposes of cleaning.

Once cleaned, all data will be loaded to memory simultaneously in order to run a comprehensive feature importance analysis with accounts for majority of features included in our reviews dataset.

Objective 2's scope, which is yet to be finalized, will likely use some form of PostgreSQL to store and stage the entire dataset to allow for querying select portions of data to account for user-generated insights.

# Technologies Used
## Data Cleaning and Analysis
Pandas will be used to import the two .csv files and the the .json file, explore and clean, and ultimately merge them all into a single dataframe in pandas. We are also considering using sqlalchemy to push the data into postgresql.

## Database Storage
Our primary project objective may not require database storage. If the storage is necessary, we will use postgresql.

## Machine Learning
*Please see machine learning section*

## Dashboard
We will be using Tableau for our Dashboards.


## References:

IQBAL, M. (2021, March 29). *Twitch Revenue and Usage Statistics (2021).* Business of Apps. https://www.businessofapps.com/data/twitch-statistics/#4