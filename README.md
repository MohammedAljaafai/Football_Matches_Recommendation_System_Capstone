# Football_Matches_Recommendation_System_Capstone
### **Introduction:**
This system receives inputs from the user, and these inputs are the today's date and gives a list of the matches in that date from the following leagues, the English, German, Spanish, Italic, French, Portuguese, Dutch , and Saudi leagues. The other input the prefered game for the user from this list. The output will be football mathces that are arrnged based on distance (Similarity) from the prefered game. (A capstone project).
The Recommender system will recommend 6 games with an order from the closest distance the the furthest distance.
## **Football Mathces Datasets**

### **Data Description:**
- These datasets include the football matches results of the last 10 seasons (Starting from 2012 and Ending with 2021) plus the current season(Until February). 
- These results are for the English, German, Spanish, Italic, French, Portuguese, Dutch, and Saudi leagues

### **Data Dictionary:**
The English, German, Spanish, Italic, French, Portuguese, And Dutch leagues shares these 10 columns

Key to results data:
- League = Referese to the country's league
- Wk = The week of the game during the season
- Day= The Day of the game during the season
- Date = The Date of the football game
- Time = The Timing of the football game
- Home = Home team
- Home = Away team
- Score = Game Score (Number of goals for each team)
- Attendance = Total attendance of the game
- Venue = Stadium Name
- Referee = Referee Name
- Match Report = A report for the match (If there are important information. For examplem a team forfeit from a game)
- Notes = Notes
### **Results:**
The results are shown in the Knn-Recomender file.

### **Data Source:**
All of the datasets were collected from this website:
https://fbref.com/en/comps/70/Saudi-Professional-League-Stats
### **Other Resurces:**
https://towardsdatascience.com/introduction-to-recommender-systems-1-971bd274f421
https://scikit-learn.org/stable/modules/neighbors.html#nearest-neighbor-algorithms
https://towardsdatascience.com/introduction-to-recommender-systems-6c66cf15ada
