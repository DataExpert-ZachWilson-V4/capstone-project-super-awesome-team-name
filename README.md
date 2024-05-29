Problem: 

Researching and picking a weekly pick for PGA one and done leagues is time consuming. 


*What is One and Done?* 
In PGA betting / gaming, The One and Done format is growing in popularity. It has several noticeable similarities to NFL Survivor pools, with the main difference being entries are not eliminated with a bad week. Players pick one golfer per week and earn points based on their selected golfer's prize money for that tournament


*Why is it time consuming?* 
The "expert analysis", in addition to being formulaic, is typically hidden behind SEO bloat and paywalls. Moreover, it's hard to find any single dataset with the expected prize pools of each tournament in a single place.  

*What information is helpful to know when researching picks?* 
 - Expected Prize Pools for the season by tourney: You want to know when to use the best available players to maximize your $ winnings.
 - A golfers season form: How are they performing in the season?
 - A golfers historical form: How are they trending over years? 
 - A golfers past performance at each course
 - A golfers past performance at courses similar to each other



Scope the project and figure out what datasets you're using.
 - Expected Prize Pools..I've yet to find a data set that aggregates this. I will need to scrape and create a dataset.
 - Past performance of golfer by tournament, course and year. I can use datagolf's api https://datagolf.com/api-access#historical-raw-data
 - Historical form / rankings. I can use datagolf's api https://datagolf.com/api-access#historical-raw-data
 - User input. User can remove players they've already used to see updated rankings for the rest of season.
 - Betting Odds. Pull in tournament specific betting odds from datagolf or BetsAPI

   
Output 
- A web app where a user can manage and research their weekly pick in a single dashboard that can be grokked in under 5 minutes. 
