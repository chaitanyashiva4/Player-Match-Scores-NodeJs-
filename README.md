# Player-Match-Scores-NodeJs-
Player Match Scores
Player Match Scores
Given two files app.js and a database file cricketMatchDetails.db consisting of three tables player_details, match_details and player_match_score.

Write APIs to perform operations on the tables player_details, match_details and player_match_score containing the following columns,

Player Details Table

Column	Type
player_id	INTEGER
player_name	TEXT
Match Details Table

Column	Type
match_id	INTEGER
match	TEXT
year	INTEGER
Player Match Score Table

Column	Type
player_match_id	INTEGER
player_id	INTEGER
match_id	INTEGER
score	INTEGER
fours	INTEGER
sixes	INTEGER
API 1
Path: /players/
Method: GET
Description:
Returns a list of all the players in the player table

Response
API 2
Path: /players/:playerId/
Method: GET
Description:
Returns a specific player based on the player ID

Response
API 3
Path: /players/:playerId/
Method: PUT
Description:
Updates the details of a specific player based on the player ID

Request
Response
API 4
Path: /matches/:matchId/
Method: GET
Description:
Returns the match details of a specific match

Response
API 5
Path: /players/:playerId/matches
Method: GET
Description:
Returns a list of all the matches of a player

Response
API 6
Path: /matches/:matchId/players
Method: GET
Description:
Returns a list of players of a specific match

Response
API 7
Path: /players/:playerId/playerScores
Method: GET
Description:
Returns the statistics of the total score, fours, sixes of a specific player based on the player ID

Response

Use npm install to install the packages.

Export the express instance using the default export syntax.

Use Common JS module syntax.
