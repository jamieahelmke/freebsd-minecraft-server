# freebsd-minecraft-server

This repository provides a simple service script for a minecraft server.

To set up the server:
1. Install minecraft server software under `/opt/minecraft` (Available (here)[https://www.minecraft.net/en-us/download/server])
2. Install this script to `/etc/rc.d`
3. Create a user `minecraft` and give it full permissions to `/opt/minecraft`
4. Execute `service minecraft start` to start the server

Have fun!
