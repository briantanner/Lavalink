# Lavalink
Standalone audio sending node based on Lavaplayer and JDA-Audio.
Allows for sending audio without it ever reaching any of your shards.

Being used in production by FredBoat and Dyno.

## Features
* Powered by Lavaplayer
* Minimal CPU/memory footprint
* Twitch/YouTube stream support
* Event system
* Seeking
* Volume control
* REST API for resolving lavaplayer tracks (used for non-JVM clients)
* Statistics (good for load balancing)
* Basic authentication

## Client libraries:
* [JDA client](https://github.com/Frederikam/Lavalink/tree/master/LavalinkClient) (JDA, Java)
* [eris-lavalink](https://github.com/briantanner/eris-lavalink) (Eris, JavaScript)
* [lava-d.js](https://github.com/untocodes/lava-d.js) (discord.js, JavaScript)
* [discord.js-lavalink](https://github.com/MrJacz/discord.js-lavalink) (discord.js, JavaScript)
* Or [create your own](https://github.com/Frederikam/Lavalink/blob/master/IMPLEMENTATION.md)

## Server configuration
Download from [the CI server](https://ci.fredboat.com/viewLog.html?buildId=lastSuccessful&buildTypeId=Lavalink_Build&tab=artifacts&guest=1)

Put an `application.yml` file in your working directory. [Example](https://github.com/Frederikam/Lavalink/blob/master/LavalinkServer/application.yml.example)

Run with `java -jar Lavalink.jar`

# Acknowledgements
This project contains modified code from https://github.com/sedmelluq/jda-nas v1.0.5
