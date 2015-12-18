# Zappy

This project is done in a month for our last C second year project at Epitech. We were a team of 6 people.

## Principle

The game is to manage a universe and its inhabitants. This world, called Trantor, is geographically made up of plains and does not include any other terrain. The game board represents the entire area of the world, such as a world map. Food and mineral resources are randomly generated on the ground.

The Trantorien is peaceful. It is neither violent nor aggressive. He cheerfully wanders in search of stones and feeds the way. It easily crosses his fellows on the same field unit and sees as far as his visual abilities permit, and the food he collects allows him to live for a certain period of time.

The goal of the players is to move up the hierarchy trantorienne. This "increase", which enhances their physical and mental abilities must be performed in a particular rite. It must indeed meet on the same field unit:
- A combination of stones
- A number of players of the same level.

A player begins the incantation and thus starts the process of elevation. It is not necessary that the participants are on the same team. Only matter their level. All players of the group performing the incantation reach the next level.

To complicate the task of AI, the field of view of the players is limited. At each elevation, vision increases by a measuring unit in front and one on each side of the new row. Trantorien also a way to detect the presence of his comrades by emitting a wave-radar indicating the direction to take her to join them.

The game is played by team. The winning team is the one with six players have reached the maximum elevation.

## How to Launch the game

Make the project first.
```
make
```
You can make the each binary apart if you want with the objects name :
````
make zappy_server
make zappy_ai
make zappy_gui
````

### Server

To launch a basic Server, just precise the Port [-p] and the Teams names [-n].
```
./zappy_server [-p port [-x size_x] [-y size_y] [-c max_clients] [-t speed] -n team_1 team_2 ...
```

### GUI

To launch the GUI, you have update your LD_LIBRARY_PATH environment variable. At the root of the project, just enter this
```
`cat link`
```

And then launch the gui pricising the IP and port of the server
```
./zappy_gui [ip] [port]
```

### IA

To launch Ias
```
./client [-n teamname] [-p port] (([-h machine name]))
```

Enjoy it !
