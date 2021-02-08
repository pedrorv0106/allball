# all ball 
> A playground for NBA statistics.

## What's In This Document
* [General Info](#general-info)
* [Technologies](#technologies)
* [Setup](#setup)

## General Info
all ball is a modern take on a classic sports statistics site. The app fetches data from https://www.balldontlie.io and displays it to the user in numerous ways.

Users are displayed both game results and the top players from the night prior. If no games were scheduled, users will be prompted to search for a date of their choosing.
!["home page"](src/assets/homePageScreenShot.png)

Users can click on a game card and be shown both a statistic log for each player and also an animated chart for team stats.
!["team game log"](src/assets/teamGameLogScreenshot.png)

!["team comparison"](src/assets/teamComparisonScreenshot.png)

Users can also search for players by name.
!["search results"](src/assets/searchResultsScreenShot.png)

## Technologies
all ball is created with:

* React
* React Hooks
* React-Router-Dom
* Styled-Components
* Recharts
* React-Flippy

## Setup
To run this project, install it locally using npm:
```
$ cd ../allball
$ npm install
$ npm start
```
