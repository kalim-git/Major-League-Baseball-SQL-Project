# Major-League-Baseball-SQL-Project
<img width="1536" height="1024" alt="MLS baseball SQL project cover picture" src="https://github.com/user-attachments/assets/021d6fde-60ea-4209-aaad-64b88dc50cb2" />

This project uncovers meaningful trends in Major League Baseball (MLB) players data using the Sean Lahman Baseball Database.

## Dataset
The Dataset includes decades worth of data including player statistics like schools attended, salaries, teams played for, height and weight, and more.

 - <a href="https://github.com/kalim-git/Major-League-Baseball-SQL-Project/tree/main/Dataset%20SQL%20Scripts">SQL Scripts</a>
 - <a href="https://github.com/kalim-git/Major-League-Baseball-SQL-Project/tree/main/Dataset%20CSV%20Files">CSV Files</a>

## Goal
The goal of this project was to uncover meaningful trends in Major League Baseball (MLB) player data by analyzing their educational backgrounds, salaries, physical attributes, and career paths.

## Objectives
 1. What schools do MLB players attend?
 2. How much do teams spend on player salaries?
 3. What does each player’s career look like?
 4. How do player attributes compare?

## Task
Using advanced SQL querying techniques to track how player statistics have changed over time and across different teams in the league.

### PART I: SCHOOL ANALYSIS
  TASK 1: View the schools and school details tables
  TASK 2: In each decade, how many schools were there that produced players?
  TASK 3: What are the names of the top 5 schools that produced the most players?
  TASK 4: For each decade, what were the names of the top 3 schools that produced the most players?

  ### PART II: SALARY ANALYSIS
  TASK 1: View the salaries table
  TASK 2: Return the top 20% of teams in terms of average annual spending
  TASK 3: For each team, show the cumulative sum of spending over the years
  TASK 4: Return the first year that each team's cumulative spending surpassed 1 billion

  ### PART III: PLAYER CAREER ANALYSIS
  TASK 1: View the players table and find the number of players in the table
  TASK 2: For each player, calculate their age at their first (debut) game, their last game, and their career length (all in years). Sort from longest career to shortest career.
  TASK 3: What team did each player play on for their starting and ending years?
  TASK 4: How many players started and ended on the same team and also played for over a decade?

  ### PART IV: PLAYER COMPARISON ANALYSIS
  TASK 1: Which players have the same birthday? Hint: Look into GROUP_CONCAT / LISTAGG / STRING_AGG
  TASK 2: Create a summary table that shows for each team, what percent of players bat right, left and both
  TASK 3: How have average height and weight at debut game changed over the years, and what's the decade-over-decade difference?

## SQL Techniques
Using the Sean Lahman Baseball Database, I applied advanced SQL techniques to:

    Identify top player-producing schools across decades
    Track team salary trends and cumulative spending milestones
    Analyze career longevity and player-team loyalty
    Compare player attributes and spot changes over time

The SQL techniques are as follows:
- Numeric Functions
- Joins
- Window Functions
- Rolling Calculations
- Min / Max Value Filtering
- Datetime Functions
- String Functions
- Pivoting

## Give Heading
The findings were structured into clear, actionable insights using SQL queries, which allowed for uncovering long-term patterns and performance drivers across the league. This helped demonstrate how historical data can be leveraged to guide future recruitment, spending, and team-building strategies.

