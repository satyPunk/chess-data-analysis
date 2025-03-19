# Chess Data Analysis

## Overview
This project analyzes chess game data, cleans it, and visualizes key insights through various plots.

## Features
- Cleans and preprocesses chess game data
- Generates statistics and insights
- Visualizes trends with plots

## Installation
1. Clone the repository:
   ```sh
   git clone <repo_url>
   ```
2. Install dependencies:
   ```sh
   pip install pandas matplotlib seaborn
   ```
3. Run the script:
   ```sh
   python chess_analysis.py
   ```

## Data Fields
- **Game ID**: Unique identifier for each game
- **Rated**: Whether the game is rated or not
- **Start Time / End Time**: Timestamp of game start and end
- **Number of Turns**: Total moves in the game
- **Game Status**: How the game ended (checkmate, resignation, etc.)
- **Winner**: White, Black, or Draw
- **Time Increment**: Increment per move
- **White/Black Player ID & Rating**: Identifiers and ratings of players
- **All Moves in Standard Chess Notation**: List of moves played
- **Opening Eco**: Standardized opening code
- **Opening Name**: Name of the chess opening
- **Opening Ply**: Number of moves in the opening phase

## Visualizations
### 1. Rating Distribution
_This graph shows the distribution of player ratings._
![image](https://github.com/user-attachments/assets/54daa6d8-7943-43a8-a0ca-527ba7272ad1)

![Rating Distribution](#)

### 2. Game Length vs. Player Rating
_This scatter plot explores the relationship between game length and player ratings._
![image](https://github.com/user-attachments/assets/15f0c380-8c66-45db-806c-3faa67216800)

![Game Length vs. Rating](#)

### 3. Winner Distribution
_This chart shows how often White, Black, or a Draw occurs._

![Winner Distribution](#)

### 4. Popular Openings vs. Rating
_This box plot highlights how common openings are associated with different rating levels._
![image](https://github.com/user-attachments/assets/ed842700-fde3-4775-9fa1-1e5d4741fab6)

![Popular Openings](#)

### 5. Game Duration Distribution
_This histogram shows the distribution of game lengths in minutes._
![image](https://github.com/user-attachments/assets/ac2d9e31-9c91-45ff-9642-a275216d28bf)

![Game Duration](#)

## Contributing
Feel free to contribute by opening a pull request!

## License
This project is licensed under the MIT License.
