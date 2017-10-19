
# NFL Draft Predictions - Capstone Project One Proposal

## Introduction

Professional sports are a lucrative and competitive industry. The National Football League (NFL) is the biggest sports league in the world. As is the norm in American professional sports, amateur players are selected via a league-wide draft, in this case the NFL Draft. A total of 256 selec- tions are made over 7 rounds. In the lead-up to this event, the NFL holds the NFL Scouting Combine (Combine): a long-running showcase where incoming players perform physical and mental tasks for NFL teams. Examples include the 40-yard dash, vertical jump, 3 cone drill, Wonderlic (intelligence test), and personal interviews. While this is only a portion of the draft scouting activity, it has tended to give lots of weight to the overall process. This analysis will attempt to tease out any predictive power that exists between the quantitative Combine results and draft round. Lots of resources are spent scouting players and determining draft rankings. This project can help a team provide a better draft grade for players and can also be used to estimate when a particular player may be drafted so that a draft trade can be used to target that specific player. Potential player college data and statistics will also be considered. 

## Approach

After obtaining the Combine data, it will need to be cleaned after some exploratory data analysis. It is already known there are missing variables, as not all players perform all tasks. Imputation will likely be used here, but there exists a possibility certain players may be removed. Potential en- hancement of the existing features will also be pursued: either as combinations or extractions of existing features. Other feature engineering cases will be considered as well. After this a simple linear model will be developed to ensure some predictive power exists. Depending on the other factors in the data and the analysis, other potential machine learning models may be pursued, such as Random Forest or Support Vector Machine.

## Client

The potential target audience are NFL teams. They would be given a prediction model where given a player, a probability of which round that player would be drafted in. They can incorporate this into their draft rankings and strategies. This can allow a team to target certain players with greater certainty given their own assigned draft picks or traded draft picks.

## Data

The main data source is Combine data hosted by [NFL Savant](http://www.nflsavant.com/). Additional statistics are also hosted by [Sports Reference](https://www.sports-reference.com/). The former is hosted as a simple [CSV file](http://www.nflsavant.com/dump/combine.csv?year=2015), which is readily readable. The latter is hosted in the form of [html tables](https://www.pro-football-reference.com/years/2017/draft.htm), which should also be relatively straightforward to read-in. The incoming players college career statistics may also be used in this project. The aforementioned Sports Reference will be the likely source for this data.

## Deliverables

The major result from this project for the client will be the player prediction model. The code will also be given. The slides and presentation of this project is the last component of the deliverable.

