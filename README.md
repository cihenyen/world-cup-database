# world-cup-database


## Project goal: 
Create a Bash script that enters information from World Cup games.csv file into PostgreSQL, then query the database for useful statistics.

Project made as part of the <b> FreeCodeCamp Relational Databases Beta Certificate course </b>


## Creating the database

Dataset:  gamestoadd.csv </a>

Created the database, 'worldcup', and the appropriate tables ('teams' and 'games') on PostgreSQL to visualise the data from games.csv.

## Automating data insertion and querying with SQL
Created a Bash script that reads the games.csv data and uses SQL query commands to insert the data automatically into the tables previously created.

Took constraints into consideration when creating the Bash script to insert all winner and opponent teams individually into 'teams' and then into 'games' based on the team_id created.

View:  insertdata.sh
  </a>
  
Finished by writing a Bash script that utilises SQL to query the database and obtain useful values.

View:  queries.sh
  </a>

Database dump (after inserting data):   worldcup.sql </a>
