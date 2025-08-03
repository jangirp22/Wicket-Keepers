# Wicket-Keepers
This project presents an IPL Query Optimization System that enables users to query IPL data from 2008 to 2024. The system provides a menu-driven interface to execute analytical queries. It supports operations like player statistics, team head-to-head analysis, venue-based performance metrics, and seasonal award predictions. 

The raw IPL data from Kaggle, comprising ball-by-ball.csv and matches.csv, is first cleaned and
preprocessed. Functional dependencies are identified to decompose the data into BCNF-compliant relational
tables with clearly defined primary and foreign keys. A terminal-based interface is built to support dynamic
query execution, enabling users to retrieve match-wise, player-wise, and team-wise statistics efficiently.
Query performance is enhanced through indexing and query optimization techniques.
