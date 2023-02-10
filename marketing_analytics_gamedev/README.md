# Marketing analytics of the mobile game "Space Brothers"

NOTE: The information inside notebook is in Russian but you can assess the code at least. The translation is in process.

## The purpose

The new mobile game "Space Brothers" has been launched. In this game users build their own space program and try to colonize The Galaxy.
One of the monetization model is to show some ads on the screen of building cards.

The research purpose is to study of the players behavior depending on the acquisition source.

## The results

1. The users behavior has been analysed.

The users are divided into 2 types depending on the strategy they use to finish first level: builders and fighters. The number of fighters are almost twice more than builders. However, fighters are building objects too, but 20% less than builders.
The monetization with buildings cards is suitable for both strategies.

2. The time for finishing level has been estimated depending on players strategy.

The following hypothesis has been tested: "The time for finishing first level differs depending on players strategy."

It is statistically reliable that time for finishing level differs depending on player strategy. Builders spend almost 20% more time than fighters.

3. The dependence of chosen strategy to acquisition source has been assessed.

The following hypothesis has been tested: "The chosen strategy depends on acquisition source."

There is no statistical significant difference between acquisition sources for the proportion of builders, therefore, chosen strategy doesn't depend on acqusition source.

4. Acquisition costs have been analyzed.

Yandex.Direct brings more users than others.
The most expensive source is Facebook.
Less money spend on YouTube but this source bring the cheapest users.

Recommendations:

- redirect the flow of funds to Yandex.Direct
- redirect the flow of funds to YouTube
- think over ways to encourage players to choose builder strategy

## Data

The following data are available:

**1. Game events data:**

- event time
- event name
- building type
- user id
- type of finished project

**2. Ads costs data:**

- click date
- traffic source
- click costs

**3. Users data:**

- user id
- acqusition source

## Python libraries

- pandas
- matplotlib.pyplot
- seaborn
- plotly
- numpy
- scipy
- math

