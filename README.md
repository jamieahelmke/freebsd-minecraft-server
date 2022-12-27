# freebsd-minecraft-server

This repository provides a simple service script for a minecraft server.

To set up the server:
1. Install a JRE ((Documentation)[https://www.freebsd.org/de/java/])
2. Install minecraft server software under `/opt/minecraft` (Available (here)[https://www.minecraft.net/en-us/download/server])
3. Run it once for test and accept the eula (`java -Xmx4096M -Xms1024M -jar /opt/minecraft/server.jar nogui`)
3. Install the `minecraft` script to `/etc/rc.d`
4. Create a user `minecraft` and give it full permissions to `/opt/minecraft`
5. Add line `minecraft_enable="YES"` in `/etc/rc.conf`
6. Execute `service minecraft start` to start the server

Have fun!
