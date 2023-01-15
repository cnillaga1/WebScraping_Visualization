Consider the following Wikipedia page, which contains the list of seasons played by the San Jose Sharks hockey team: [season link](https://en.wikipedia.org/wiki/List_of_San_Jose_Sharks_seasons)

# Webscraping

Your task is to scrape the “Year by Year” table on that page. You will produce a data frame called SJS that contains the following columns:

 - **Season**: The year of play. 

- **Reg_GF**: The number of “goals for”, i.e. goals scored by the Sharks that season.  

- **Reg_GA**: The number of “goals against”, i.e., goals scored by other teams against the Sharks that season.  

- **Finish**: The rank of the team in the regular season. (This should be a numeric variable.). 

- **Playoff_Wins**: The number of wins in the postseason that the sharks achieved. (Note: A “-” indicates that they did not make the playoffs, so this should count as 0 wins.). 

It is also fine if you have other variables in your dataset, as long as you have the five listed above.  

# Visualization 

Once you have created the dataset, make a gganimate plot showing how the Sharks have performed over time.  

![image](https://user-images.githubusercontent.com/102557726/212524959-679e3e24-d970-494e-a2f1-aa1596e500f5.png)
