# Project: Data Modeling with Cassandra


### Overview

A startup called Sparkify wants to analyze the data they've been collecting on songs and user activity on their new music streaming app. The analysis team is particularly interested in understanding what songs users are listening to. Currently, there is no easy way to query the data to generate the results, since the data resides in a directory of CSV files on user activity on the app.

They'd like a data engineer to create an Apache Cassandra database which can create queries on song play data to answer the questions. My role is to create a database for this analysis. I'll be able to test the database by running queries given to me by the analytics team from Sparkify to create the results.

---

#### **Create queries to ask the following three questions of the data**

1. Give me the artist, song title and song's length in the music app history that was heard during sessionId = 338, and itemInSession = 4
2. Give me only the following: name of artist, song (sorted by itemInSession) and user (first and last name) for userid = 10, sessionid = 182
3. Give me every user name (first and last) in my music app history who listened to the song 'All Hands Against His Own'

---

#### Query Tables created

1. Query1: session_item_history table
2. Query2: artist_song_history
3. Query3: user_song_history

---

##### Python libraries used:
pandas
cassandra
re
os
glob
numpy
json
csv