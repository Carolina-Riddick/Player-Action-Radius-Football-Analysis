# Player-Action-Radius-Football-Analysis

## Player Action Radius / Radios de Accion por Jugador

This notebook performs a visual analysis of a football player's activity during a match by generating an action-radius plot and a heatmap based on event coordinates.

### What the notebook does

1. Loads the event data from a CSV file.
2. Filters the dataset to keep only the events of a specific team or player (using teamId or playerId).
3. Selects specific event types, such as passes, to focus the analysis.
4. Cleans the data by removing extreme outliers in the x and y coordinates using Z-score filtering.
5. Converts the coordinate columns into NumPy arrays for use in plotting functions.
6. Draws a StatsBomb-style pitch and adjusts colours, orientation and layout.
7. Generates a KDE heatmap to visualise where the player interacted most on the pitch.
8. Prepares the setup for further analysis, such as passing maps or convex hull action areas.

### Purpose of the analysis

- The goal is to visually understand the areas of influence of a player during the match, identify where they participated most, and create tools for analysing passes, shots or any other event type present in the dataset.

<p align="center">
<a href="https://www.kaggle.com/code/carolinariddick/player-action-radius-football-analysis/edit">
<img width="480" height="332" alt="Captura de pantalla 2025-11-18 a las 16 22 11" src="https://github.com/user-attachments/assets/53632d60-bb35-4b0f-a723-4d794e54c733" />
</a>
</p>

<p align="center">
<a href="https://www.kaggle.com/code/carolinariddick/player-action-radius-football-analysis/edit">
  <img width="491" height="340" alt="Captura de pantalla 2025-11-18 a las 16 21 49" src="https://github.com/user-attachments/assets/b58d7ec4-ef38-4091-a8c6-75fa238f1a1a" />
</a>
</p>
