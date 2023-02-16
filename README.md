# Fantasy Basketball Analysis
## Using probability and statistics to turn fantasy into science
## Author: William Lusty, Georgia Tech School of Math
### 1. Intro (in progress)
Fantasy sports are a popular form of entertainment globally.
### 2. Sleeper and Lock-in Mode
Sleeper is a fantasy sports app that is relatively new to the market. They offer a simple to use platform that is particuarly popular for fantasy basketball. In October 2022, Sleeper announced a new fantasy basketball mode called "Lock-In Mode" which revolutionizes the way the game is played. 

The prevalent game mode previously had users pick a single game per week that would be counted for the team's total score. This would typically be done at the start of every week before the games had been played. For example, if Lebron James was playing Phoenix, Boston, and Portland this upcoming week and I had him on my team, if I predicted that Lebron would be able to score many points against Portland's defense, I might pick to count the Lebron's Portland game to count for my team this week. 

Lock-in Mode, however, has users choose after every game that a player plays whether or not they would like for that game to count for their team every week. For example, suppose that Luka Doncic is on my team and plays Houston, San Antonio, and Miami this week. Let's say that Luka generates 51 fantasy points against Houston in the first game of the week. I know have a decision, either lock in those 51 fantasy points to count for my team this week or to leave the points unlocked, risking the sure points on the chance that he will produce more in one of the next two games.

Lock-in mode has several different advantages over the old methods of playing fantasy basketball. Firstly, as a user, many more games each week have implications on the success of my team. With the old "pick" mode, only one game per player per week has an affect on the success of my team. With lock-in mode, every game of every player on my team that doesn't have their points locked in yet could give be a chance for a player to produce. Secondly, Lock-in Mode generates a much higher usage rate for the Sleeper app than traditional pick mode. With pick mode, players effectively "set it and forget it", since they can pick their games at the start of the week and there are no more decisions to be made. With lock-in mode, however, users who wish to maximize their team's points must check the app every day to see if any of their players had high-production games that should be locked in. Finally, a team's bench players can be utilized a lot more in lock-in mode. If one of my starters is not playing on a given night (and their points haven't been locked in yet), there is no reason why I shouldn't temporarily put them on the bench in favor of someone who is playing tonight on the chance that the bench player will have a highly productive game that could be locked in.

This discussion of lock-in mode versus the old game picking modes leads us to the motivation of this project. 

### 3. Motivation
Lock-in mode has made fantasy basketball more fun and exciting this season for the reasons discussed above. Although the new game mode was easy to understand, some of the subleties of the new game mode created opportunities for players to explore different strategies for playing the game. At the start of the season, players in our league were playing like it was still in pick mode and being punished by other players who had adapted their strategies faster. For example, in pick mode, many players would be happy if their non stars, their rotation players, could reliable create 20-25 fantasy points. This led some players this year to lock in games at these levels without realizing the probability that some other player on the bench will probably beat those numbers with some patience and smart daily rotations.  This means that games are much higher scoring with this mode because players are supposed to choose high outlier games. 

It has been fun for me, as a student of probability and statistics, to mentally study the effects that this new game mode has had on the league this season. It has also led me to adjust some of my strategies for drafting and picking up players to my team. For example, I have convinced myself that lock-in mode rewards more highly variable players over consistent production players. This is because a more highly variable player is more likely to have some high outlier game this week that I will be able to lock in if I am patient. Another example has been my mental "baseline" for a "good" fantasy game has shifted upward from about 20-25 fantasy points per game to about 30-35 points per game. 

However, most of this modeling has been done mentally through trial and error. The goal of this project is to model Sleeper Fantasy Basketball Lock-in Mode using probability and statistics and see what insights and new strategies can be developed. I also aim to constantly compare and contrast lock-in mode and the traditional "pick" mode to see what kinds of strategies work for one versus the other (under certain mathematical assumptions). Finally, as an avid fantasy basketball user myself, I would like to develop methods of assessing and scoring players under the assumptions of my model so that I can make more intelligent decisions about who to trade for, draft, and acquire in free agency. Finally, I would like to develop heuristics to decide if and when to lock in a player's game in the middle of a matchup. 

### 4. Model
We will be using probability and statistical theory extensively in this investigation. The fundamental unit of a fantasy team is the player, so our investigation will begin there. 


```python

```
