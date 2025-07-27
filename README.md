# 🏏 IPL Data Visualization Using Python
This project performs data analysis and visualization on Indian Premier League (IPL) match data. Using Python libraries like Pandas, Matplotlib, and Seaborn, we explore match trends, team performance, player impact, and decision patterns.

## 📌 Project Overview
This analysis focuses on:

Seasonal trends of IPL matches

Toss decision strategies

Match results (wins, ties, no results)

Team performance across seasons

Player of the match trends

## 📁 Dataset Information
File Name: IPL.csv

Source: Kaggle or similar cricket datasets

Key Columns Used:

season

winner

toss_decision

win_by_runs, win_by_wickets

player_of_match

Note: The column umpire3 was dropped and null values were removed from key features for clean analysis.

## 🧹 Data Cleaning Steps
Removed the umpire3 column

Dropped rows with missing values in:

city, player_of_match, winner, toss_winner, toss_decision, result, season, umpire1, umpire2

## 📊 Visualizations Included
1. Matches Played Per Year
Bar chart showing how many IPL matches were played in each season
📌 matchesperyear.png

## 2. Toss Decision Distribution
Pie chart showing how often teams choose to bat or field after the toss
📌 tossdecision.png

## 3. Match Result Types
Pie chart of match result types: normal wins, ties, or no result
📌 result.png

## 4. Wins by Run Margin
Histogram of matches won by various run margins
📌 winbyruns.png

## 5. Wins by Wicket Margin
Histogram of matches won with different numbers of wickets remaining
📌 winbywickets.png

## 6. Top 10 Players of the Match
Horizontal bar chart of players with the most "Player of the Match" awards
📌 players.png

## 7. Matches Won by Teams
Scatter plot showing how many matches each team has won
📌 Matches.png

## 🛠️ Technologies Used
Python

Pandas

Matplotlib

Seaborn

Jupyter Notebook / VS Code
