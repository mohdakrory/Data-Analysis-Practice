# Cricket-World-Cup-2023-Data-Analysis

Analyzing the performance of cricket teams and players in different scenarios and conditions using different metrics using Python, Pandas, and Matplotlib

## Domain knowledge (background)

To understand the terms and concepts of the cricket game watch this [video](https://www.youtube.com/watch?v=VwII4y5vpyU)

### Dataset header description 

<table border="1">
  <tr>
    <th>Header</th>
    <th>Explanation</th>
    <th>Data Type</th>
  </tr>
  <tr>
    <td>team</td>
    <td>The cricket team to which the player belongs.</td>
    <td>Categorical</td>
  </tr>
  <tr>
    <td>player</td>
    <td>The name of the player.</td>
    <td>Categorical</td>
  </tr>
  <tr>
    <td>bat_or_bowl</td>
    <td>Indicates whether the player is a batsman or a bowler.</td>
    <td>Categorical</td>
  </tr>
  <tr>
    <td>bb_bf</td>
    <td>Number of balls bowled or faced by the player.</td>
    <td>Numeric (discrete)</td>
  </tr>
  <tr>
    <td>runs</td>
    <td>Runs scored by the player.</td>
    <td>Numeric (discrete)</td>
  </tr>
  <tr>
    <td>wkts</td>
    <td>Number of wickets taken by the player.</td>
    <td>Numeric (discrete)</td>
  </tr>
  <tr>
    <td>wicketball_prob</td>
    <td>Probability of taking a wicket in a ball.</td>
    <td>Numeric</td>
  </tr>
  <tr>
    <td>runs_per_ball</td>
    <td>Average runs scored or conceded per ball.</td>
    <td>Numeric</td>
  </tr>
  <tr>
    <td>opposition</td>
    <td>The opposing team.</td>
    <td>Categorical</td>
  </tr>
  <tr>
    <td>ground</td>
    <td>The venue where the match is played.</td>
    <td>Categorical</td>
  </tr>
  <tr>
    <td>start_date</td>
    <td>The date when the match started.</td>
    <td>Date</td>
  </tr>
  <tr>
    <td>overs</td>
    <td>Number of overs bowled or faced.</td>
    <td>Numeric</td>
  </tr>
  <tr>
    <td>mdns</td>
    <td>Number of maidens bowled.</td>
    <td>Numeric (discrete)</td>
  </tr>
  <tr>
    <td>econ</td>
    <td>Economy rate (runs conceded per over).</td>
    <td>Numeric</td>
  </tr>
  <tr>
    <td>inns</td>
    <td>Number of innings played.</td>
    <td>Numeric (discrete)</td>
  </tr>
  <tr>
    <td>4s</td>
    <td>Number of fours scored.</td>
    <td>Numeric (discrete)</td>
  </tr>
  <tr>
    <td>6s</td>
    <td>Number of sixes scored.</td>
    <td>Numeric (discrete)</td>
  </tr>
  <tr>
    <td>sr</td>
    <td>Strike rate (for batting) or wicket strike rate (for bowling).</td>
    <td>Numeric</td>
  </tr>
  <tr>
    <td>not_out</td>
    <td>Indicates whether the player was not out (1) or not (0).</td>
    <td>Categorical</td>
  </tr>
  <tr>
    <td>mins</td>
    <td>Duration of the player's innings in minutes.</td>
    <td>Numeric</td>
  </tr>
</table>

## Required Analysis

**1. Team Performance Analysis:**
- Explore team-wise performance metrics.
- Analyze runs scored, wickets taken, and batting/bowling styles.
- Identify top-performing teams and their strengths.

**2. Player Performance Analysis:**
- Evaluate individual player statistics for both batting and bowling.
- Identify leading run-scorers and wicket-takers.
- Assess the impact of players on their team's performance.

**3. Opposition and Ground Analysis:**  
- Investigate how teams and players perform against different oppositions.
- Examine performance variations across different playing grounds.
- Identify if there are specific teams or players that excel in certain conditions.

**4. Temporal Analysis:**
- Study performance trends over time, considering start dates and overs played.
- Identify any temporal patterns or changes in team and player performance.

## Notebook Content 

You can find this notebook also on Kaggle [here](https://www.kaggle.com/code/mohamedeldakrory8/cricket-world-cup-2023-data-analysis#Temporal-analysis)

You can find the used dataset on Kaggle [here](https://www.kaggle.com/datasets/mohamedeldakrory8/world-cup-2023-data/data)

**The notebook contains the following topics**

### Dataset description
- Load data & preview
- Header description

### Exploring the data
- Checking for duplicates
- Checking for missing values, why is it normal to have missing values according to the cricket game rules
- Numeric features descriptive statistics
- Unique values count of each feature 

### Team performance analysis
- Team statistics
- Best performing team in each metric

### Player performance analysis
#### player statistics
- Lead run scorers - batting players
- Best performing batting player in each metric
- Lead wichet takers - bowling players
- Best performing bowling player in each metric
- Runs VS Wickets

### Ground and opposition analysis

#### Team performance against different oppositions
- Total runs of each team VS different oppositions
- Opposition against which each team scored its highest runs
- Total wickets of each team VS different oppositions
- Opposition against which each team scored its highest wickets

#### Player performance (batting/bowling) against different oppositions
- Top 10 run scorers' performance VS different oppositions
- Opposition against which each of the top 10 run scorers scored his highest runs
- Top 10 wicket takers' performance VS different oppositions
- Opposition against which each of the top 10 wicket takers scored his highest wickets

#### Team performance on each playground
- Total runs of each team in different playgrounds
- Playground on which each team scored the highest runs
- Total wickets of each team in different playgrounds
- Playground on which each team scored the highest wickets

#### Player Performance (batting/bowling) on each playground
- Top 10 run scorers performance in different playgrounds
- Playground on which each player (top 10) scored his highest runs
- Top 10 wicket takers performance in different playgrounds
- Playground on which each player (top 10) scored his highest wickets

### Temporal analysis 

#### Team performance over time
- Total overs for each team over time
- Total runs for each team over time
- Total wickets for each team over time

#### Player performance over time
- Total runs for each batting player (top 10) over time
- Total wickets for each bowling player (top 10) over time
