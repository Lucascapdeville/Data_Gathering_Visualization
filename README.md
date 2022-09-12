# CSGO - data gathering and visualization

# Intro
This project has the objective to gather and analyze the data from cs:go Highlighted S-Tier tournaments and player information from the year 2019,last year before pandemic hist, from liquipedia.net.

To find if there is any underserver market that might be a oportunity to invest after pandemic times.

## CS:GO
CS:GO is the latest successor of the counterstrike franchise developed by Valve and released in 2012.

The competitive scene has existed since the release of the game and has already payout more than 100M dollars in more than 6000 tournaments around the world.

In 2019 more than 24M dollars distributed in prizes in more than 300 tournaments.
## Liquipedia
Liquipedia is a wike style site that follows a multitude of games and has been cataloging gaming related content since the 2009.

## S-Tier tournaments
S-Tier Tournaments (formerly known as Premier Tournaments) offer an outstanding prize pool, are almost exclusively played offline,

and feature the best teams from all over the world. They are commonly held by well-established organizers and are considered especially prestigious amongst the community.

Highlighted tournaments are special CS:GO Major Championship ("CS:GO Championship" in 2013) events which feature a large prize pool and/or are sponsored by Valve.

# Project objective
Gather and clean tournaments and competitors information from S-Tier tournaments occurred in 2019

Create a Data visualization to better understand the data

## Methods
### API 
Liquipediaapy(https://github.com/c00kie17/liquipediapy)

Mediawiki(https://github.com/barrust/mediawiki)
### Technologies
pandas
regex


# Project Description
The data that we need to get to better understand the correlation between player nationalities and tournaments locations are presented in two pages from liquipedia

The first one is the player page that cotains information from all the player in the CS:GO competitive scene, and we can get with the liquipediaapy

The second one is located in the tournaments page from liquipedia and is posible to get from the liquipediapy

Both need some cleaning so we can better undestand the data before pandamic times(2019)

## Steps
The data gathering portion of this project started using the api to access the information from the tournaments and players pages from liquipedia.

The next step is filtering the data for the year of 2019 and selectingt the Highlithed tournaments list.

Using Mediawiki we find the url correspondig to the tournament page and get the players whom participated.

Then we cross reference those two informations to get the final data for these projects that contains:

The tournament list and location

The players and their country of origin 


# Conclusion
With the data gathered is easily that there is 2 major oportunities of tournament development.

The first one is Brazil with 31 players comming from this region is expected to have a huge pent up demand.

Another point that helps Brazil's case to receive a S-Tier tournament is the pent up demmand that the basilian community since there was never a S-Tier tournament in the CSGO era

The second one is a smaller oportunity but the oceanic region has a potential
