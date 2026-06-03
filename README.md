# TEINF_Project01
Teinf Project including Node-red,discord and minecraft

Introduction
This project combines the use of discord, node-red and a minecraft server. It consists out of 2 subprojects.

1st Subproject
In this one discord and node-red with its dashboard palette is used. On the dashboard we have a timer where the user gives a time in seconds and has a start button to start the timer. Then there's a diagramm to show the usage percentage of the cpu over the last 5 minutes. As last a discord reads from a discord channel if a picture was posted and if so it posts it also on the diagramm. It doesn't store the picture if the server shutdown or a new picture in discord is posted.

2nd Subproject
Here I combine node-red, discord and a minecraft server. We use also this palette (https://flows.nodered.org/node/@tomsith/node-red-contrib-minecraft). The palette is used for different commands in minecraft. The commands are written in a discord channel where a bot reads it and in node-red the actions are forwarded to the minecraft server. We can set the weather, reset all the players to a hardcoded coordinate (0 100 0) and get the server status which includes Minecraft Version and how many players are online. Another thing I made is a sort of challenge. It consists of the player getting an item in a given time and bring it back to a chest. The challenge is initiated in another discord channel via the command !start {item that should be found}|time for it in minutes|. The command creates then a chest where the item should be delivered. 
