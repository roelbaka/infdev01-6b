php Json local file storage
=====================

#Twitch
If you want twitch data from multiple users, the twitch server will take a while before all results come back.

This script Saves the info from multiple users of twitch locally.in a Json Array

This way the results can be accessed directly.


#Reddit
Used the same Library to get latest subreddit messages.

- Tip cronjob this script every 5 minutes to check which users are online on twitch.

#Usage 
~~~
use composer to install dependencies.

Chmod save folder 777
with your browser call generate.php?password=Your Password Here to generate local .json files  with all the requested data

Results will be saved in:
Saves/TwitchStreamers.json
Saves/RedditFeed.json
~~~
