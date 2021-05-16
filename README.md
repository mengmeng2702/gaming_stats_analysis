# gaming_stats_analysis

## Project Overview
**Selected Topic**: 

Twitch Viewership Analysis Based on Game Reviews/Genre/Year

**Reasoning on Choosing the Topic**:

Gaming industry has been blooming with the rapid increase of audience. Live streaming, among all the other entertaining forms of activities in the gaming industry, is incredibly popular and is a growing industry. Twitch GVC revenue generated were 1.6 USD billions in the year of 2018, 1.5 USD billions in 2019, and 2 USD billions in 2020, which has supassed YouTube revenue in those consecutive years from 2018 - 2020 with 1.2, 1.4 and 1.7 USD billions revenue (IQBAL, 2021).

This project aims to provide analysis and make predictions on whether the cumulative reviews of games, associated genre, and release year correlate to the total watched hours on Twitch (Twitch Viewership). Twitch is a video game streaming platform where users live stream themselves watching/playing games.


**Description of Source Data**

The team has carefully chosen new datasets (CSV files from Kaggle website) from the original ones after performing data cleaning and table merging using Python Pandas. In order to have a wider range of games that's existing in the market, we have chosen the following datasets as our source data:

*Metacritic Video Game Comments* - Video Game Comments from Metacritic's Best of All Times, <a href="https://www.kaggle.com/dahlia25/metacritic-video-game-comments">click here for the link to the dataset</a>

*Steam Store Games (Clean dataset) *- Combined data of 27,000 games scraped from Steam and SteamSpy APIs, <a href="https://www.kaggle.com/nikdavis/steam-store-games">click here for the link to the dataset</a>

*Top games on Twitch 2016 - 2021* - Monthly top 200 games on the platform, <a href="https://www.kaggle.com/rankirsh/evolution-of-top-games-on-twitch">click here for the link to the dataset</a>

*Steam Reviews Dataset* - Rating data from 6M unique users, with 15M reviews over 8,183 games, <a href="https://www.kaggle.com/forgemaster/steam-reviews-dataset">click here for the link to the dataset</a>

**Objectives**
* Objective 1: Perform feature importance analysis on the selected dataset(s) to see the statistical correlation between different features and twitch viewership. Twitch viewership furthermore breaks down to peak reviews, and hours watched.

* Objective 2: The second objective we hope to accomplish is from a user experience perspective. We wish to help new twitch users to be able to make decisions on the options of games they can start with based on their needs (reaching the optimal hours watched by viewers within a preferred time period).

## Communication protocal
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
* Feature Importance analysis and Random Forest Model
* SHAP values

The idea is to perform feature importance analysis on the Objective 1 to conclude the features that do cast an impact on the Twitch Viewership. Then we will use SHAP values to interpret the impact of certain value for a given feature compared to the baseline values. 

## Provisional Database
* PostgresSQL will be used to store our table(s) from the datasets after data clearning.


## References:

IQBAL, M. (2021, March 29). *Twitch Revenue and Usage Statistics (2021).* Business of Apps. https://www.businessofapps.com/data/twitch-statistics/#4
