# #Screenshots

![RC](/S1.png)
![RC](/S2.png)
![RC](/S3.png)
![RC](/S4.png)
![RC](/S5.png)
![RC](/S6.png)


# #Summary

<hr>

The goal of this project was create a map, following the specifications given by the game designer, for a hypothetical FPS game.
- To play the prototype click: [Download (150 Mb)](https://giusepperotondo.itch.io/project-v)
- To see more screenshots of the level [Art Station](https://www.artstation.com/artwork/rJPDP6) or scroll down to the bottom of this page

# #Specifications:

<hr>

- Make a big level by recycling a few assets
- The level must not be flat, players must be able to climb on roofs of buildings / rocks / other to gain height advantage and make the game more complete, dynamic and immersive
- Making it possible, in a single map, to be able to play both close-range rifles and long-range rifles, supporting the styles of both players
- Realize the Design using Graybox and tools provided by Unreal Engine, no complex textures
- For the map there must be elements that suggest to the player the height of the head of a standing enemy, this way the player always knows where to aim
- Level for a FPS with dynamic and fast movement
- Must be a map suitable for Search and Destroy, “Location”, Death Match, Free-for-All (FFA) and domination.
- Must include new mechanics unique to the level

# #Process

<hr>

I started by deciding right away the place and the events in which the level is set. After some research, I used [image references     ](/project_v_reference.png) and the story to build some game mechanics. The idea of the project is therefore:
- The map is set in Italy, Sicily, Temple of Agrigento.
- After some events in the world of FPS (xxx) gaming, two teams of players find themselves fighting in this temple under renovation. For this reason, there are:
- Ziplines and ladders that the player can use to climb
- Unstable columns that can fall / become an obstacle / be destroyed, has HP decided by the game designer.

Other requirements

- The way in which the player faces the enemies must not be linear, but the player must have the possibility to choose at least 2 directions to continue.
- The map must have a clear "central" place, where players can meet more easily
- Spawn - kill from long distances must be avoided, spawn points must be covered by props.
- Players can climb high buildings to get advantages, but their position doesn't have to be OP. Going up or staying for a long time carries a risk
- Bullets only pass through chests, not walls

# #Actors

<hr>

Actors used to create the prototype:

![RC](/project_v_chest.png)
This cube represents a chest/container left behind by workers. It can be pierced by blows and its end delimits the height of a player. They are scattered everywhere with the aim of helping the player to aim.

![RC](/project_v_co.png)
Column There are two columns, the blue ones and the normal ones. In the final level, the artist has to convey the difference through the use of textures and other methods. The blue pillar can fall / become an obstacle / be destroyed, it has HP decided by the game designer. The blue column can also be tied to a pulley which, if destroyed, drops the column.

![RC](/project_v_upv2.png)
Crane / zip line allows players to climb above the roof of the building.

![RC](/project_v_props.png)
Colonnade / Small temple / trees are for aesthetic purposes only.

![RC](/project_v_rock.png)
Rock This group of cubes represents rocks. It is used everywhere for this purpose.


# #Feedback and how I reacted:

<hr>

- It was too dark inside the main temple, so I took pieces off the roof and added lights inside. The new roof gives more sense to the storytelling of the map, improves visibility and creates reference points for interesting lineups useful for more experienced players (For throwing grenades, smoke bombs, blackberries…).
- The spawn area for search and destroy was really small. I greatly increased the coverage of spawned players, preventing them from being spawn killed.
- Other minor fixes, such as too empty zones

To download the first version of the game and see the iterations, feel free to ask me at: rotondo.giuseppe.03@gmail.com
