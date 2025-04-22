# CS009A-Overwatch-2-Project
Collaborated with a classmate to do a hitrate analysis on an Overwatch 2 dataset using Python (matplotlib). (June 2024)

-> Chandrahaas Mariserla, Ryan Chiang

Our Dataset concerns player data from Overwatch 2, Season 1.

![image alt](https://github.com/CMariserla/CS009A-Overwatch-2-Project/blob/4cd17e4c3a0e38d7e6b337246e16de70fc45c7d4/Captzsdfure.PNG)

## Which heroes had the highest average pick rate across all ranks? 
The top 3 heroes with the highest average pick rate are: Ana, Moira, Genji - in order from least to greatest. This indicates that out of 36 unique heroes in the data file, the 3 heroes most likely to be chosen for play are Ana, Moira, and Genji. The top two are in the support role in the game. This is not necessarily surprising since from experience support has been a more popular role to play ingame. What was surprising was that Genji, a damage hero, was in the top 3 of most popular characters.

## Which Hero did players prefer - hit scan or projectile? 
In FPS games, there are two main systems to register when something is hit. These are hitscan, and projectile. In game, hitscan is where the game checks where you are aiming as you fire and sees if there is a target. Projectile has a travel time before it can register the hit. Overwatch is unique in that it has both hitscan characters and projectile characters. To calculate if each was more used, we took the average of the average pick rate for each projectile hero and compared it to the average of the average pick rate for each hitscan hero. Players picked hitscan heroes at an average rate of 3.05% Players picked projectile heroes at an average rate of 2.74%. There is a slightly higher rate of players choosing hitscan characters, however the difference is close enough that there could not be a statistically significant difference.

## What characters are more successful in low rank lobbies(Bronze) and high rank lobbies? 
Examining the difference in win rates between the highest rank and the lowest rank can show which characters are more dominant in low rank lobbies and high rank lobbies. It can show us which characters are more easy to learn and do well versus which ones are harder to master. For example, the hero Wrecking Ball is known to be extremely hard to learn. This is confirmed with low rank lobbies having a win rate of 29.86% and with high ranks at a rate of 35.36%.

## Which heroes have the highest average elimination rate /10 min (10 minute measured playtime)? 
The top 3 characters with the highest average elimination rate are D.Va, Pharah, and Symmetra. This indicates players are most able to confirm kills with these characters. D.Va has high mobility in game and is able to chase, and focus on enemy players. Pharah is a flying character and as a result can be hard to deal with by the enemy team. Symmetra being in the third position was very interesting. The way she does damage is that as her ranged beam is aimed on a target, her damage increases over time, using 3 levels of damage. But, because her first damage level is very weak, this results in her being a type of glass cannon. She has to get very close and it can take a significant amount of time to charge to the highest level, As a result she can be quickly eliminated.
