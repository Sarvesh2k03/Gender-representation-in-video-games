# Gender-representation-in-video-games

A statistical analysis of gender representation in video games using the language R on a data set (https://www.kaggle.com/datasets/br33sa/gender-representation-in-video-games).


Languages and tools used :

<p>
<img alt="R" src="https://img.shields.io/badge/R-276DC3?style=for-the-badge&logo=r&logoColor=white">
<img alt="Colab" src="https://img.shields.io/badge/Colab-F9AB00.svg?style=for-the-badge&logo=googlecolab&color=525252">
</p>

We use statistical analysis to uncover various ways in which the female and non-female characters (including male, non-binary and custom) are portrayed, identify prevalent stereotypes, and analyse how different gender identities are represented in video games. 

Here we try to find an answer to the following questions:
> 1) Which of the female or non-female characters are majorly associated with protagonists? 
> 2) Is there any noticeable correlation between the sexualization of female characters and their "side"?
> 3) How does the representation of women characters vary across the different countries games are developed in and the platforms the game is released on?
> 4) Are there any discernible patterns in the reception and representation of women characters based on "Avg_Reviews" and "Country" or "Platform"?
> 5) What genres of video games tend to prioritise or feature a higher percentage of female characters?
> 6) What is the relationship between the percentage of women on the team and sexualization of female characters?
> 7) How has the representation of women characters in video games evolved over different release years?
> 8) Are there noticeable trends in the portrayal of women characters, and how do these trends align with changes in average reviews over time?




## Datasets Variables used


### Characters:
| Predictor variable          |         Description                                                                                                        |
| ----------------------------|--------------------------------------------------------------------------------------------------------------------------- |
| Gender                      | female, male, non-binary, custom                                                                                           |
| Age_range:                  | elderly, middle-aged, adult, young adult, teenager, child, infant, unknown                                                 |
| Playable:                   |  non-playable (0), playable (1)                                                                                            |
| Sexualization:              |  total number of misogynistic or sexualizing tropes present for a particular character (0-3)                               |
| Species:                    |  human, humanoid, animated object, animal, animated plant, creature, robot, humanoid animal, android robot, unknown        |
| Side:                       |  protagonist/neutral (P), antagonist (A), both sides (B)                                                                   |
| Relevance:                  |  protagonist (PA), deuteragonist (DA), sidekick (SK), main character (MC), secondary character (SC), main antagonist (MA)  |
| Romantic interest:          |  yes, no, optional                                                                                                         | 

### Games:                                  
| Predictor variable          |         Description                                                                                                        |
| ----------------------------|--------------------------------------------------------------------------------------------------------------------------- |
| Release:                    |  Years 2012-2022                                                                                                           |
| Genre:                      |  Action adventure, role playing game (RPG), action, adventure, simulation, interactive story                               |
| Publisher:                  |  Game publishers                                                                                                           |
| Country:                    |  Game developer’s country                                                                                                  |  
| Platform:                   |  The platform the game was released on (PS4, Wii U, etc)                                                                   |
| Protagonist:                |  Number of protagonists (1-3)                                                                                              |
| Protagonist_non_male:       |  Number of female, non-binary, and custom protagonists (0-17)                                                              |
| Relevant_males:             | Number of males in the game (0-17)                                                                                         |
| Relevant_non_male:          |  Number of female, non-binary and custom characters in the game (0-14)                                                     |
| Percentage_non_male:        | Percent of total characters that are non-male                                                                              |
| Avg_reviews:                |  Average of the ratings from Metacritic, Destructoid, IGN, and Gamestop                                                    |

### Sexualization:                                                                                                                                        
| Predictor variable          |         Description                                                                                                        |
| ----------------------------|--------------------------------------------------------------------------------------------------------------------------- |
| Sexualized clothing:        | True/False                                                                                                                 |
| Sexualized cutscenes:       | True/False                                                                                                                 |


## Conclusion:
Through this statistical analysis we can come to the conclusion -
While there is some progress made towards gender diversity and sexualization reduction, there are still some disparities that need some attention and some efforts are needed to break some stereotypes, and be more inclusive and varied when it comes to representations of characters in video games.

