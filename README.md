### NBA 2017 data analysis with Phyton

Introduction In this project, we'll work with data from the 2017 NBA Season (a pretty exciting one) to perform Data Wrangling techniques, and then some analysis. We'll start by performing some Data Wrangling techniques to join the data from the season with that of players. We'll then perform different modifications and cleaning tasks to make sure our data is ready for analysis. Finally, we'll perform some analysis using Group By and Transform operations.

## 1 Merge s2017_df and players_df with a left join

Merge s2017_df and players_df using a left outer join, that means, we want to have all the stats information, but if there are missing values that can't be matched from players_df, we want to set those season values as null. Store the results from the merge in the variable df. 2 Are there misses (mismatches) in the resulting dataframe? As we performed a left outer join, if some values in from s2017_df couldn't be matched in players_df, the result will be null values (also referred as "misses" or "mismatches"). Are there any?

Yes No

3 How many rows couldn't be matched? Based on previous activities consider name column to find how many misses were there in the resulting frame?

4 Extract the names of the players that couldn't be matched Extract the names of the players from s2017_df that couldn't be matched with players_df in a list (it must be a list), under the variable name player_misses.

5 Modify players_df with the correct names to re-try a successful merge Now it's time to do some detective work... We can guarantee that the players missing in players_df do exist, but they just have different names. Now, you must find the players discrepancies and update the names in the players_df dataframe.

For example, if in s2017_df the player's name was "Michael J. Jordan", and in players_df it was just "Michael Jordan", the task is to modify players_df to make it now "Michael J. Jordan". Important: Modify the players_df dataframe in place! If you "break" something, you can always read the data again. ...

You can reach other part of NBA 2017 from DataWars https://app.datawars.io/project/b8efa63d-ac34-4e3c-8840-bece3e5ab75e?page=2
