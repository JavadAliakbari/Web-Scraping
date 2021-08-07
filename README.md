# Welcome to GitHub Desktop!

This Python project extract "Top 250 Movies" and "Top 1000 Actors and Actresses" information from https://www.imdb.com/ and save them as a CSV file. This file is then analyzed with pandas library and we insert them into the MySQL database.

The code has been implemented by Jupyter notebook and it has 3 parts. the first part is named Top250_movies.ipnnb which is extracts the top 250 IMDB movies and save them as a CSV file. The same procedure applied to top1000Actor.ipynb. The CSV files have been read by the InsertTablesMySQL.ipynb file and have been inserted into a MySQL Database.

You should add your user and pass for SQL Database in the user_pass.txt file so it can be read by the InsertTablesMySQl.ipynb file.

Javad Aliakbari