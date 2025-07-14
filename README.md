# FIFA-World-cup-EDA
# FIFA World Cup Data Analysis

This notebook performs an exploratory data analysis on a dataset containing FIFA World Cup match information. The analysis covers several key aspects of World Cup history and performance.

## Questions Answered:

1.  **How has the average number of goals per match changed over time?**
    - We analyzed the trend of average goals scored per match across different World Cup tournaments.
    - The analysis involved converting match dates, calculating total goals per match, grouping by year, and visualizing the average goals over time.
    - The World Cup with the highest average goals was identified as 1954, and the lowest was 1990.

2.  **Which countries have been the most successful in terms of match wins, titles, and goal difference?**
    - We determined the total number of wins for each country.
    - We identified the winners of each tournament and counted the number of titles won by each country.
    - We calculated the total goal difference (goals scored minus goals conceded) for each country.
    - These metrics were combined and countries were ranked to identify the most successful nations overall.

3.  **Which teams have the best attacking and defensive records?**
    - We calculated the total goals scored by each team (attacking record).
    - We calculated the total goals conceded by each team (defensive record).
    - Teams were ranked based on their total goals scored (best attacking) and total goals conceded (best defensive).

4.  **Does the host nation have a performance advantage?**
    - We identified the host nation for each World Cup tournament.
    - We filtered matches where the host nation was playing and analyzed their performance metrics (wins, goals scored, goals conceded) in home vs. away matches.
    - We compared the host nation's performance to the average performance of all teams to assess if there is a host nation advantage.
    - A visualization was created to illustrate the comparison of average goals scored and conceded.

5.  **Which stadiums and cities hosted the most matches?**
    - We counted the number of matches hosted by each stadium to identify the most frequently used venues.
    - We counted the number of matches hosted by each city to identify the cities that have been central to the World Cup.

6.  **What are the top head-to-head rivalries in the World Cup?**
    - We identified matches played between the same two teams to define head-to-head rivalries.
    - We counted the number of times each rivalry occurred.
    - We explored ways to incorporate rivalry significance (e.g., knockout stage matches, closeness of results) into the ranking of rivalries.
    - The top rivalries were presented based on match count and a consideration of significance.

7.  **Which confederations (UEFA, CONMEBOL, etc.) perform best overall?**
    - We loaded or created a mapping of countries to their respective football confederations.
    - We merged the confederation data with the match data.
    - We analyzed performance metrics (wins, goals, titles) for each confederation.
    - Confederations were ranked based on their overall performance to determine which ones have historically performed best.
