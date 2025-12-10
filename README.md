# Personal Minecraft server
Saving memory with my friend, and my server experiment for open Minecraft server in some day.

## Guide if you want to open the server yourself

1. pick your server (VM mostly) and choose about 4 to 8 Gbs Ram server

3. set up network security by adding port 25565 (Minecraft server default port)

2. remote to the VM and install java SDK 17

3. clone this repo

4. change the directory to the repo and run the command "java -jar purpur.jar --nogui."

5. give public IPv4 to your friend and let's play!!

my personal recommendation is Azure Virtual machine 8 Gbs and picks the nearest region of your (I choose Singapore)

Now it on 1.21.10 Purpur server launcher

## To run the minecraft server

`java -Xms4G -Xmx4G -jar purpur.jar --nogui`

## check out more purpur command [here](https://purpurmc.org/docs/Commands/)
