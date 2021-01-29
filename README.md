# Football Pool app
* **Author**: Ricardo Aguilar, github: [raguilar11](https://github.com/raguilar11)
* **Major**: Statistics
* **Year**: 2019

# Type of project
Shiny app.

# Purpose (including intended audience)
To provide mobile data entry and game tracking form for low-key football pools. 

# Explanation of files

* `webscrape.R` - Download seasonal game data from https://www.pro-football-reference.com and wrangle into long form. 
    - Variables: `Season`, `Week`, `Day`, `Date`, `Time`, `Winner`, `Loser`, `Location`
* `app.R` - Single file Shiny app 
    - Display Input: Dropdowns for season and week. 
    - Display Output: Schedule for the week
    - Data input: Button selector choice for user to select the team they think will win

# Completion status 
Not complete. Pending steps include: 

- [ ] Create a login (will need to create and connect to a password database)
- [ ] Update database with user choices (one time, and ongoing)
- [ ] Overall persistent database management
- [ ] Disable winner selection 1 hour before game starts

## Enhancements: 

- [ ] User performance graphs (% correct by week)
- [ ] Ranking among other pool members

# Can someone else work on this project? 
Yes

# Public Display/dissemination
None

# License
None
