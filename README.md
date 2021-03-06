# Wireframes of apfelschuss.io

This repository includes wireframes (also known as page schematic or screen blueprint) of the [apfelschuss.io](https://apfelschuss.io/) web application frontend.

> Don't know what Apfelschuss is? Check out [apfelschuss main repo readme](https://github.com/Apfelschuss/apfelschuss/blob/master/README.rst) for more information about this project.

The source files of this project can be found in the [source](source) folder. All wireframes are created with [draw.io](https://www.draw.io/), which is a free online diagram software.

Export of source files (png, jpg, pdf, svg and so on) are stored in the [export](export) folder.

The base template is a 1920x1080 px browser window.

## Home

The homepage presents upcoming federal popular votes. Every vote includes following fields:
* Voting title
* Total numbers of voters
* Pie chart with proponent and opponent
* A detail button that leads to more information (description, movie, voters with their name and the areay where they live)

![home](export/home.png)


## Archive

The archive shows all past votings with official results in comparison to apfelschuss.io voters with a pie chart.
* Voting title
* Total numbers of voters
* Pie chart with proponent and opponent as well as official result
* A detail button that leads to more information (description, movie, voters with their name and the areay where they live)

![archive](export/archive.png)


## Voting example

Detailed view of a voting.
* Voting title
* Voters with profile picture, name, bio and residence
* The icon in the top right corner of every user profile is the [canton flag](https://en.wikipedia.org/wiki/Cantons_of_Switzerland#List)

![voting example](export/voting-example.png)


## Profile example

Detailed view of a user that shows its votings.
* Profile picture with name, bio and residence
* Past votings goupped in categories with thumb up or down

![profile](export/profile.png)


## Profile update

Detailed view of a user that shows its profile.
* Profile picture with name, bio and residence
* Residence according [this list](https://postleitzahlenschweiz.ch/tabelle/)

![profile update](export/profile-update.png)


## Login

Login as provided by Django.

![login](export/login.png)
