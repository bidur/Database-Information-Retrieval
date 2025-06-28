
1. Open an empty gitpod workspace using http://gitpod.new/ 
-> first create an account in gitpod ->

2. Install sqlite and sqlite web using

sudo apt install sqlite

(add sudo if encounter system priviledge issues) pip install sqlite-web

3. Use command prompt of sqlite to create your first database with filename 'testsqlite.db'.

5. Lanuch sqlite-web with the 'testsqlite.db'. And show that you are able to visit the sqlite-web portal from your mobile phone.

6. Create a table and import the dataset (https://www.dropbox.com/scl/fi/55em2zos95atrukf4hy59/flights-export.csv?rlkey=s8qxhgy6mrzjylc4bxvbahdp2&dl=0 to an external site.) into testsqlite.db using sqlite-web.

7. In sqlite-web use SQL statement to finish the following queries.

a) Calculate the total and average number of passengers per year, given that Net Income (Fin. Position) > 0. 

b) Calculate the total and average number of passengers per year, given that Net Income (Fin. Position) < 0.

c) Calculate the total and average number of passengers per year.

8. Use sqlite command prompt to redo one of the queries in 7.



