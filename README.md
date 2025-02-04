# Steam Game Purchases Analysis

This project analyzes user purchase behavior on **Steam**, one of the largest online gaming platforms. The dataset includes information about user purchases, game popularity, and overall engagement patterns.

## Project Overview

The goal of this project is to explore:

1. **How many different games are purchased by each user?**  
2. **What is the average number of games purchased per user?**  
3. **How many different users purchased each game?**  
4. **What are the top 10 most popular games?**  

Through this analysis, we aim to uncover insights into user behavior, game popularity, and broader engagement trends on the platform.

## Dataset

- **Source**: Steam purchase data (CSV format)
- **Columns**:
  - `UserID`: Unique identifier for each user
  - `GameName`: Name of the game purchased
  - `Action`: Type of action (filtered to only include purchases)

## Key Findings

- **Total Unique Users**: 12,390  
- **Total Unique Games**: 5,153  
- **Total Game Purchases**: 129,510  
- **Average Games Purchased Per User**: 10.4 games  
- **Top Games**: Dota 2, Team Fortress 2, Unturned, Counter-Strike Global Offensive

## Visualizations

The project includes a Power BI dashboard with the following visuals:

1. **KPI Cards**: Total Users, Total Games, and Total Purchases.
2. **Bar Chart**: Top 10 Most Popular Games.
3. **Line Chart**: Number of Games Purchased by Each User.
4. **Gauge Chart**: Average Games Purchased Per User.

## How to Run This Project

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/yourusername/steam-purchase-analysis.git
   ```
2. **Open the Power BI Dashboard:** Import the provided `.pbix` file into Power BI Desktop.

## Technologies Used

- **Python (Pandas)**: For initial data cleaning and preparation.
- **Power BI**: For data visualization and storytelling.

