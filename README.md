# SoccerPlayer_Evaluation
This repo is for soccerplayer value market evaluation. 


# Player Attributes Dataset
Dataset source is from [STATHead FBref](https://stathead.com/fbref/). See here and free to join!

You can download the complete dataset used for the analysis from the link below:
[Download the 3years_statistics1.xlsx file]([path/to/3years_statistics1.xlsx](https://docs.google.com/spreadsheets/d/1p4p690VWMjMB_3mkBzbgOi3ZfvBowVF3/edit?usp=drive_link&ouid=109629826928896722483&rtpof=true&sd=true))


# Player Attributes

### 1. General Information
| Attribute | Description |
|-----------|-------------|
| **Rk** | Rank - The player's rank in the list. |
| **Player** | Name of the player. |
| **xG** | Expected Goals - A metric that estimates the quality of goalscoring chances and the likelihood of them being scored. |
| **Season** | The season in which the data was collected. |
| **Age** | The player's age. |
| **Nation** | The player's nationality. |
| **Team** | The team the player was part of during the season. |
| **Comp** | Competition - The league or competition in which the player played. |
| **Pos** | Position - The player's position on the field. |
| **id** | An identifier for the player. |

### 2. Playing Time
| Attribute | Description |
|-----------|-------------|
| **MP** | Matches Played - The number of matches the player appeared in. |
| **Min** | Minutes Played - The total minutes the player was on the field. |
| **90s** | Number of 90-minute intervals played (used to normalize statistics per 90 minutes). |
| **Starts** | Number of matches started. |
| **Subs** | Number of times substituted on. |
| **unSub** | Number of matches played without being substituted. |

### 3. Expected Goals and Assists
| Attribute | Description |
|-----------|-------------|
| **xG.1** | Expected Goals (another representation or specific scenario). |
| **npxG** | Non-Penalty Expected Goals - xG excluding penalty kicks. |
| **xAG** | Expected Assists - A metric that estimates the quality of passing chances created. |
| **xG+xAG** | Total of Expected Goals and Expected Assists. |
| **xA** | Expected Assists (same as xAG). |
| **npxG+xAG** | Non-Penalty Expected Goals plus Expected Assists. |
| **G-xG** | Goals minus Expected Goals - Difference between actual goals scored and xG. |
| **np:G-xG** | Non-Penalty Goals minus Expected Goals - Difference between non-penalty goals and npxG. |
| **A-xAG** | Assists minus Expected Assists - Difference between actual assists and xAG. |
| **npxG/Sh** | Non-Penalty xG per Shot - Quality of shots excluding penalties. |

### 4. Shooting
| Attribute | Description |
|-----------|-------------|
| **Sh** | Shots - Total number of shots taken. |
| **G/Sh** | Goals per Shot. |
| **G/SoT** | Goals per Shot on Target. |
| **SoT** | Shots on Target - Total number of shots on target. |
| **SoT%** | Shots on Target Percentage. |
| **Dist** | Average shot distance. |
| **FK** | Number of free kicks taken. |

### 5. Performance
| Attribute | Description |
|-----------|-------------|
| **Gls** | Goals - Total goals scored. |
| **Ast** | Assists - Total assists. |
| **G+A** | Goals plus Assists. |
| **G-PK** | Non-Penalty Goals. |
| **PK** | Penalties - Total penalties scored. |
| **PKatt** | Penalty Attempts - Total penalty attempts. |
| **PKm** | Penalty Misses. |

### 6. Touches
| Attribute | Description |
|-----------|-------------|
| **Touches** | Total number of touches. |
| **Def Pen** | Touches in Defensive Penalty Area. |
| **Def 3rd** | Touches in Defensive Third. |
| **Mid 3rd** | Touches in Middle Third. |
| **Att 3rd** | Touches in Attacking Third. |
| **Att Pen** | Touches in Attacking Penalty Area. |
| **Live** | Touches in open play (excluding set-pieces). |

### 7. Carries
| Attribute | Description |
|-----------|-------------|
| **Carries** | Total carries (dribbling). |
| **TotDist_x** | Total Carry Distance - Total distance covered while carrying the ball. |
| **PrgDist_x** | Progressive Carry Distance - Distance covered toward the opponent’s goal. |
| **PrgC** | Progressive Carries - Carries that advance the ball significantly towards the opponent’s goal. |
| **1/3_x** | Carries into the final third. |
| **CPA** | Carries into the Penalty Area. |
| **Mis** | Miscontrols - Times the player lost control of the ball. |
| **Dis** | Dispossessed - Times the player was dispossessed by an opponent. |

### 8. Receiving
| Attribute | Description |
|-----------|-------------|
| **Rec** | Total receptions of the ball. |
| **PrgR** | Progressive Receptions - Receptions of the ball that advance the ball significantly towards the opponent’s goal. |

### 9. Passing
| Attribute | Description |
|-----------|-------------|
| **Cmp** | Completed Passes. |
| **Att** | Pass Attempts. |
| **Cmp%** | Pass Completion Percentage. |
| **KP** | Key Passes - Passes leading to a shot. |
| **1/3_y** | Passes into the final third. |
| **PPA** | Passes into the Penalty Area. |
| **CrsPA** | Crosses into the Penalty Area. |
| **PrgP** | Progressive Passes - Passes that advance the ball significantly towards the opponent’s goal. |
| **TotDist_y** | Total Pass Distance. |
| **PrgDist_y** | Progressive Pass Distance. |



