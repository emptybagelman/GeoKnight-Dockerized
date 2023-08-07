# GeoKnight -Dockerized

### The World Is Fracturing! Will *you* take up the sword and piece it back together?

*This is the dockerized version of GeoKnight, composing of both client AND server resources.*

Welcome to **_EdVenturers'_** group project, GeoKnight. 
The school system failed, and it's up to you with your wealth of geographic knowledge to fend off the hordes to protect the world!

**GeoKnight** is a round-based game, where the user has to answer questions to boost their stats to fight off the enemy invaders. Stats can be boosted by choosing one of three categories in which, if answered correctly, grants you an increase to that respective stat.
You can also store your score at the end of each game!

Want to see it for yourself?

## Cloning The Repo

Install **Docker** from here: https://www.docker.com/
Open **GitBash** on your system, or install it if you don't. Link for Git here: https://git-scm.com/downloads

Create and move to a directory folder. Do this by running:
```
mkdir <directory_name>
cd <directory_name>
```

Clone this repo into your new directory:
```
git clone git@github.com:emptybagelman/GeoKnight-Dockerized.git
```

From the directory you made, in **GitBash**, run:
```
docker compose up
```

To view **_GeoKnight_**, open your browser of choice, and in the search bar type: ```localhost:8080```

Or, to view the backend .json, type: ```localhost:3000```, if you're feeling frisky :)