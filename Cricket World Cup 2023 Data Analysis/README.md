# Cricket-World-Cup-2023-Data-Analysis

Analyzing the performance of cricket teams and players in different scenarios and conditions using different metrics using Python, Pandas, and Matplotlib

## Domain knowledge (background)

To understand the terms and concepts of the cricket game watch this [video](https://www.youtube.com/watch?v=VwII4y5vpyU)

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
