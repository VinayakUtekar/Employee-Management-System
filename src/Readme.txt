For GUI programming you need to install Tkinter inypur system
go to CMD and enter command pip install tkinter
and in code import tkinter to support GUI windows
Main window = TK
sub windows = Toplevel
for changing icon of the tkinter window we need to have proper icon image in ( .icon format)
which will replace the tkinter icon using the appropiate syntax
###########################################################################################################
For Sql Database Connectivity
we need to install SQLite3 or mysql in the system
https://sqlite.org/index.html
once dowloaded and installed from above link
open CMD in current project folder and create database
follow commands-
  1. sqlite3 databasename.db
  2. check if sqlite3 connected by just observing that next line has "sqlite3>"
  3. create table tablename(id int primary key, name text, salary float);
  4.once u enter u your database will be created
now in code import sql 
and use the database connectivity syntax to connect python and sql
refrence- https://docs.python.org/3/library/sqlite3.html
once database operations done close the connection to avoid lekage of data
###########################################################################################################
For Real time Location and Temperature
in CMD install requests
Follow command- pip install requests
in code Import requests to gain access to the location and temperature request
then for location we use IP info url which gives real time Location of user
and use Weather App website to display Real time Temperature of that Location
###########################################################################################################
