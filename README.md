# poll-voting-system
voting system
INTRODUCTION 

In this project I'm going to create polls, implement a voting system, delete polls, and view the list of created polls. 

Each poll created can have an unlimited amount of answers we can add to it, these answers will be voted by our visitors/users and then they can view the results once voted, each vote a user makes will be updated in our database. 

 

FILE STRUCTURE 

\-- phppoll 
  |-- functions.php 
  |-- index.php 
  |-- create.php 
  |-- vote.php 
  |-- result.php 
  |-- delete.php 
  |-- style.css 

Each file will contain the following: 

functions.php — The functions file will contain the template and database connection functions. 

index.php — The index page will contain the list of polls created and the navigation buttons. 

 

create.php — The create page will contain input fields (HTML5) so we can create new polls. 

 

vote.php — The vote page will show the list of answers for the specified poll, each answer will contain a radio button so the user can select an answer and vote. 

 

result.php — The result page will show the results for the specified poll, each answer will show the number of votes and the percentage bar. 

 

style.css — The stylesheet (CSS3) for our poll and voting system. 

A visual representation of the "phppoll" database: 

 

Description of each table and the columns in those tables: 

polls table — This table will contain information about the polls we create (title and description). 

id — The unique ID for the poll, this will be auto incremented. 

title — The title of the poll, this could be a question, etc. 

desc — The description of the poll, this is optional, you do not need to provide a description. 

poll_answers table — This table will contain all the answers for our created polls. 

id — Unique ID, this will be auto incremented. 

poll_id — The poll ID, this will be the id column in the polls table, this how we can relate both tables. 

title — The title of the poll answer. 

votes — The number of votes the answer has. 

 

CONCLIUSION 

With our polling system we are able to create polls from the admin and users are able to vote and view the results of the leading polls. 
