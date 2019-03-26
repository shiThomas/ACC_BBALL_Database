# ACC_BBALL_Database

In this project, I created a PostgreSQL data base relating to ACC basketball teams, and allow queries to discover information
about things like player statistics, team attributes, etc. The database will have 4 tables, specified
as follows (an underlined attribute indicates the primary key for the table):
PLAYER (PLAYER_ID, TEAM_ID, UNIFORM_NUM, FIRST_NAME, LAST_NAME, MPG, PPG,
RPG, APG, SPG, BPG)
TEAM (TEAM_ID, NAME, STATE_ID, COLOR_ID, WINS, LOSSES)
STATE (STATE_ID, NAME)
COLOR (COLOR_ID, NAME)
