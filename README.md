# Hay-Simulator

This is some simple code I wrote using Roblox Lua; my friends and I wanted to try out making a game where you can pick up hay, earn points, and then use it to get new items, and so on. Here's just a small part of it, the scripts for picking up hay, using Roblox's DataStore service to store the hay count on the server, and having the hay transition when hit. 

Here's the testing game if you'd like to check it out yourself: https://www.roblox.com/games/5656817598/Hay-Simulator-Datastore-Test

Screenshots:



Structure of "Hay" objects/parts in game: 
![2021-04-17 16_01_52-Window](https://user-images.githubusercontent.com/65698531/115128971-77dfd280-9f96-11eb-8b65-b4f87c419eed.png)

Placement of server-side scripts in ServerScriptService: 
![image](https://user-images.githubusercontent.com/65698531/115128979-8e862980-9f96-11eb-93af-1a19e99c6789.png)

HayGUI script placement in the TextLabel to display the amount of hay collected: 
![image](https://user-images.githubusercontent.com/65698531/115128988-980f9180-9f96-11eb-8c44-536814cfa852.png)

In-Game perspective: 

Before collecting hay: 
![image](https://user-images.githubusercontent.com/65698531/115129001-d311c500-9f96-11eb-89ce-52a9f0881e60.png)

After collecting some hay: 
![image](https://user-images.githubusercontent.com/65698531/115129020-f50b4780-9f96-11eb-9722-80d6afcab3fd.png)
