# NBADataVisuals
data: https://www.kaggle.com/datasets/orkunaktas/nba-players-stats-2324/data

# NBA Player Statistics Dataset

This dataset contains comprehensive statistics for NBA players, capturing various performance metrics across different categories. The data is organized into several columns, each representing a specific aspect of the player's performance or background. Below is a detailed explanation of what each column stands for:

## Column Descriptions

- **Rk: Rank**  
  The player's rank in the dataset based on a particular criterion (e.g., alphabetical order, performance metrics, etc.).

- **Player: Player Name**  
  The full name of the NBA player.

- **Pos: Position**  
  The position the player typically plays on the court (e.g., PG for Point Guard, SG for Shooting Guard, SF for Small Forward, PF for Power Forward, C for Center).

- **Age: Age**  
  The player's age during the season.

- **Tm: Team**  
  The abbreviation of the team the player was a part of during the season.

- **G: Games Played**  
  The total number of games the player appeared in during the season.

- **GS: Games Started**  
  The number of games the player started in the season.

- **MP: Minutes Played**  
  The total number of minutes the player was on the court during the season.

### Shooting Statistics

- **FG: Field Goals**  
  The total number of field goals made by the player.

- **FGA: Field Goals Attempted**  
  The total number of field goals attempted by the player.

- **FG%: Field Goal Percentage**  
  The percentage of field goals made out of those attempted, calculated as `(FG/FGA) * 100`.

- **3P: 3-Point Field Goals**  
  The total number of 3-point field goals made by the player.

- **3PA: 3-Point Field Goals Attempted**  
  The total number of 3-point field goals attempted by the player.

- **3P%: 3-Point Field Goal Percentage**  
  The percentage of 3-point field goals made out of those attempted, calculated as `(3P/3PA) * 100`.

- **2P: 2-Point Field Goals**  
  The total number of 2-point field goals made by the player.

- **2PA: 2-Point Field Goals Attempted**  
  The total number of 2-point field goals attempted by the player.

- **2P%: 2-Point Field Goal Percentage**  
  The percentage of 2-point field goals made out of those attempted, calculated as `(2P/2PA) * 100`.

- **eFG%: Effective Field Goal Percentage**  
  A shooting percentage that adjusts for the fact that a 3-point field goal is worth one more point than a 2-point field goal, calculated as `((FG + 0.5 * 3P) / FGA) * 100`.

### Free Throw Statistics

- **FT: Free Throws**  
  The total number of free throws made by the player.

- **FTA: Free Throws Attempted**  
  The total number of free throws attempted by the player.

- **FT%: Free Throw Percentage**  
  The percentage of free throws made out of those attempted, calculated as `(FT/FTA) * 100`.

### Rebounding Statistics

- **ORB: Offensive Rebounds**  
  The total number of rebounds the player grabbed on the offensive end of the court.

- **DRB: Defensive Rebounds**  
  The total number of rebounds the player grabbed on the defensive end of the court.

- **TRB: Total Rebounds**  
  The combined total of offensive and defensive rebounds, calculated as `ORB + DRB`.

### Playmaking & Defense Statistics

- **AST: Assists**  
  The total number of assists made by the player.

- **STL: Steals**  
  The total number of times the player took the ball away from the opponent, causing a turnover.

- **BLK: Blocks**  
  The total number of times the player blocked an opponent's field goal attempt.

### Turnover & Fouling Statistics

- **TOV: Turnovers**  
  The total number of times the player lost possession of the ball to the opposing team.

- **PF: Personal Fouls**  
  The total number of personal fouls committed by the player.

### Scoring Statistics

- **PTS: Points**  
  The total number of points scored by the player during the season, including field goals and free throws.
