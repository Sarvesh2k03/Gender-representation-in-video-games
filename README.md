# Gender-representation-in-video-games

A statistical analysis of gender representation in video games using the language R on a data set (https://www.kaggle.com/datasets/br33sa/gender-representation-in-video-games).
We use statistical learning to uncover various ways in which the female and non-female characters (including male, non-binary and custom) are portrayed, identify prevalent stereotypes, and analyse how different gender identities are represented in video games

## Variables used


## Characters
| Predictor variable          |         Description                                                                                                        |
| -------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Gender                      | female, male, non-binary, custom                                                                                           |
| Age_range:                  | elderly, middle-aged, adult, young adult, teenager, child, infant, unknown                                                 |
| Playable:                   |  non-playable (0), playable (1)                                                                                            |
| Sexualization:              |  total number of misogynistic or sexualizing tropes present for a particular character (0-3)                               |
| Species:                    |  human, humanoid, animated object, animal, animated plant, creature, robot, humanoid animal, android robot, unknown        |
| Side:                       |  protagonist/neutral (P), antagonist (A), both sides (B)                                                                   |
| Relevance:                  |  protagonist (PA), deuteragonist (DA), sidekick (SK), main character (MC), secondary character (SC), main antagonist (MA)  |
| Romantic interest:          |  yes, no, optional                                                                                                         | 

## Games                                  
| Predictor variable          |         Description                                                                                                        |
| -------------------------------------------------------------------------------------------------------------------------------------------------------- |
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

## Sexualization                                                                                                                                        
| Predictor variable          |         Description                                                                                                        |
| -------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Sexualized clothing:        | True/False                                                                                                                 |
| Sexualized cutscenes:       | True/False                                                                                                                 |

