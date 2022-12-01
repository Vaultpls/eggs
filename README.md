# Parkers Pterodactyl eggs repo

I am working on adding a large collection of public eggs for the Pterodactyl community.

With that I am also accepting PR's for new services and also updates to the current ones.

If you are submitting PR's try and keep names and titles the same.

## How to import an egg

If you are reading this it looks like you are looking to add an egg to your server.

1. Download any of the json files located in the folders below.
   1. It's easiest to right click the `raw` button and save as.
2. In your panel go to the `Nests` section in the admin part of the panel
3. Click the green `Import Egg` button
4. Browse to the json file you saved earlier
5. Select what nest you want to put the egg in.
   1. If you want a new nest you need to create it before importing the egg.

## You must restart your daemon after importing an egg if you are using 0.7. This is not required on 1.X

## Please read the CONTRIBUTING.md before submitting PRs

## [Bots](/bots)

[Discord](/bots/discord)

**Note:** these are actual Discord bot eggs, NOT language eggs. The old language eggs (discord-js-generic, discord-py-generic, etc) have been moved to the [generic languages section](#generic-languages).

* [ATL Bot](/bots/discord/atlbot) Node JS
* [Bastion](/bots/discord/bastion) Node JS
* [CorpBot](/bots/discord/corpbot) Python
* [Dynamica](/bots/discord/dynamica) Node JS
* [fragbot](/bots/discord/fragbot) Golang
* [JMusicBot](/bots/discord/jmusicbot) Java
* [parkertron](/bots/discord/parkertron) Golang
* [pixel-bot](/bots/discord/pixelbot) Python
* [Redbot](/bots/discord/redbot) Python
* [SinusBot](/bots/discord/sinusbot)

[Other](/bots/other)

* [Big Brother Bot](/bots/other/bigbrotherbot)

[Twitch](/bots/twitch)

* [PhantomBot](/bots/twitch/phantombot)
* [SogeBot](/bots/twitch/sogebot)

[TeamSpeak3](bots/teamspeak3)

* [JTS3ServerMod](/bots/teamspeak3/jts3servermod)

## [Generic Languages](/generic)

* [dart](/generic/dart/)
* [deno](/generic/deno/)
* [golang](/generic/golang/)
* [java](/generic/java/)
* [lua](/generic/lua/)
* [nodejs](/generic/nodejs/)
* [nodemon](/generic/nodemon/)
* [python](/generic/python/)
* [rust](/generic/rust/)

## [Database](/database)

### In-Memory Databases

[Redis](/database/redis)

* [Redis 5](/database/redis/redis-5)
* [Redis 6](/database/redis/redis-6)
* [Redis 7](/database/redis/redis-7)

### noSQL

* [MongoDB](/database/nosql/mongodb)
* [rethinkdb](/database/nosql/rethinkdb)

### SQL Databases

* [MariaDB](/database/sql/mariadb)
* [PostgreSQL](/database/sql/postgres)

## [Voice Servers](/voice_servers)

* [Lavalink](/voice_servers/lavalink)
* [Teamspeak_ARM64](/voice_servers/teamspeak_ARM64)
* [TeaSpeak](/voice_servers/teaspeak)
* [TS3-Manager](/voice_servers/ts3_manager)

## [Game Eggs](/game_eggs)

[Among Us](game_eggs/among_us)

* [BetterCrewLink Server](game_eggs/among_us/bettercrewlink_server)
* [CrewLink Server](game_eggs/among_us/crewlink_server)
* [Impostor Server](game_eggs/among_us/impostor_server)

[BeamNG.drive](game_eggs/beamng)

* [BeamMP Server](game_eggs/beamng/beammp)
* [KissMP](game_eggs/beamng/kissmp)

[ClassiCube](game_eggs/classicube)

* [MCGalaxy](game_eggs/classicube/mcgalaxy)

[Call of Duty 4X](game_eggs/cod/cod4x)

[ET Legacy](game_eggs/enemy_territory/etlegacy)

[FTL: Tachyon](game_eggs/ftl/tachyon)

[Factorio](game_eggs/factorio)

* [Vanilla](game_eggs/factorio/factorio)
* [ModUpdate](game_eggs/factorio/factorio-modupdate)
* [Clusterio](game_eggs/factorio/clusterio)

[Grand Theft Auto](game_eggs/gta)

* GTA V
  * [FiveM](game_eggs/gta/fivem)
  * [ragecoop](game_eggs/gta/ragecoop)  
  * [RageMP](game_eggs/gta/ragemp)
  * [alt:V](game_eggs/gta/altv)

* GTA SA
  * [Multi Theft Auto](game_eggs/gta/mtasa)
  * [SA-MP](game_eggs/gta/samp)

* GTA
  * [GTAC](game_eggs/gta/gtac)

[League Sandbox](game_eggs/leaguesandbox)

[Los Angeles Crimes](game_eggs/losangelescrimes)

[Mindustry](game_eggs/mindustry)

* [Mindustry](game_eggs/mindustry/mindustry)

[Minetest](game_eggs/minetest) (including MTG)

* [Minetest](game_eggs/minetest/minetest)

[Minecraft](game_eggs/minecraft)

* [Bedrock](game_eggs/minecraft/bedrock) Servers for Bedrock Minecraft (Windows 10, mobile, console)
  * [Bedrock](game_eggs/minecraft/bedrock/bedrock)
  * [gomint](game_eggs/minecraft/bedrock/gomint)
  * [Nukkit](game_eggs/minecraft/bedrock/nukkit)
  * [PocketMine MP](game_eggs/minecraft/bedrock/pocketmine_mp)

* [Java](game_eggs/minecraft/java) Servers for Java Minecraft
  * [Cuberite](game_eggs/minecraft/java/cuberite)
  * [Fabric](game_eggs/minecraft/java/fabric)
  * [Feather](game_eggs/minecraft/java/feather)
  * [Feed The Beast](game_eggs/minecraft/java/ftb)
  * [Forge](game_eggs/minecraft/java/forge)
  * [Glowstone](game_eggs/minecraft/java/glowstone)
  * [Magma](game_eggs/minecraft/java/magma)
  * [Mohist](game_eggs/minecraft/java/mohist)
  * [NanoLimbo](/game_eggs/minecraft/java/nanolimbo)
  * [Paper](game_eggs/minecraft/java/paper)
  * [Purpur](game_eggs/minecraft/java/purpur)
  * [Spigot](game_eggs/minecraft/java/spigot)
  * [SpongeForge](game_eggs/minecraft/java/spongeforge)
  * [SpongeVanilla](game_eggs/minecraft/java/spongevanilla)
  * [Technic](game_eggs/minecraft/java/technic)
  * [VanillaCord](game_eggs/minecraft/java/vanillacord)

* [Crossplay](game_eggs/minecraft/crossplay/) servers for crossplay between Bedrock and Java edition
  * [Purpur-GeyserMC-Floodgate](game_eggs/minecraft/crossplay/purpur-geysermc-floodgate/)

* [Proxies](game_eggs/minecraft/proxy) Minecraft Server Proxies
  * [Java](game_eggs/minecraft/proxy/java)
    * [FlameCord](game_eggs/minecraft/proxy/java/flamecord)
    * [Travertine](game_eggs/minecraft/proxy/java/travertine)
    * [Velocity](game_eggs/minecraft/proxy/java/velocity)
    * [Waterfall](game_eggs/minecraft/proxy/java/waterfall)
  * [Bedrock](game_eggs/minecraft/proxy/bedrock)
    * [Waterdog PE](game_eggs/minecraft/proxy/bedrock/waterdog_pe)
  * [Cross Platform](game_eggs/minecraft/proxy/cross_platform)
    * [GeyserMC](game_eggs/minecraft/proxy/cross_platform/geyser)
    * [Waterdog](game_eggs/minecraft/proxy/cross_platform/waterdog)

[OpenArena](game_eggs/openarena)

* [openarena](game_eggs/openarena/openarena)

[OpenRA](game_eggs/openra)

* [OpenRA Dune2000](game_eggs/openra/openra_dune2000)
* [OpenRA Red Alert](game_eggs/openra/openra_red_alert)
* [OpenRA Tiberian Dawn](game_eggs/openra/openra_tiberian_dawn)

[Red Dead Redemption](game_eggs/rdr)

* [RedM](game_eggs/rdr/redm)

[Rimworld](game_eggs/rimworld)

* [Open World](game_eggs/rimworld/open_world)

[SteamCMD Servers](game_eggs/steamcmd_servers) These eggs use SteamCMD to install

* [7 Days to Die](game_eggs/steamcmd_servers/7_days_to_die)
* [ARK: Survival Evolved](game_eggs/steamcmd_servers/ark_survival_evolved)
* [Arma](game_eggs/steamcmd_servers/arma)
  * [Arma 3](game_eggs/steamcmd_servers/arma/arma3)
  * [Arma Reforger](game_eggs/steamcmd_servers/arma/arma_reforger)
* [Assetto Corsa](game_eggs/steamcmd_servers/assetto_corsa)
* [Avorion](game_eggs/steamcmd_servers/avorion)
* [Barotrauma](game_eggs/steamcmd_servers/barotrauma)
* [Black Mesa](game_eggs/steamcmd_servers/black_mesa)
* [Citadel: Forged with Fire](game_eggs/steamcmd_servers/citadel)
* [Conan Exiles](game_eggs/steamcmd_servers/conan_exiles)
* [Craftopia](game_eggs/steamcmd_servers/craftopia)
* [Cryofall](game_eggs/steamcmd_servers/cryofall)
* [DayZ (Experimental)](game_eggs/steamcmd_servers/dayz-experimental)
* [Don't Starve Together](game_eggs/steamcmd_servers/dont_starve)
* [ECO](game_eggs/steamcmd_servers/eco)
* [Fistful of Frags](game_eggs/steamcmd_servers/fof)
* [HLDS Server](game_eggs/steamcmd_servers/hlds_server)
  * [HLDS Vanilla](game_eggs/steamcmd_servers/hlds_server/vanilla)
  * [ReHLDS](game_eggs/steamcmd_servers/hlds_server/rehlds)
* [Holdfast: Nations At War](game_eggs/steamcmd_servers/holdfast)
* [Hurtworld](game_eggs/steamcmd_servers/hurtworld)
* [Insurgency: Sandstorm](game_eggs/steamcmd_servers/insurgency_sandstorm)
* [Killing Floor 2](game_eggs/steamcmd_servers/killing_floor_2)
* [Left 4 Dead](game_eggs/steamcmd_servers/left4dead)
* [Left 4 Dead 2](game_eggs/steamcmd_servers/left4dead_2)
* [Modiverse](game_eggs/steamcmd_servers/modiverse)
* [Mordhau](game_eggs/steamcmd_servers/mordhau)
* [No More Room in Hell](game_eggs/steamcmd_servers/nmrih)
* [Onset](game_eggs/steamcmd_servers/onset)
* [Open Fortress](game_eggs/steamcmd_servers/open_fortress)
* [Pavlov VR](game_eggs/steamcmd_servers/pavlov_vr)
* [PixARK](game_eggs/steamcmd_servers/pixark)
* [Post Scriptum](game_eggs/steamcmd_servers/post_scriptum)
* [Project Zomboid](game_eggs/steamcmd_servers/project_zomboid)
* [Quake Live](game_eggs/steamcmd_servers/quake_live)
* [Rising World](game_eggs/steamcmd_servers/rising_world)
* [Risk Of Rain 2](game_eggs/steamcmd_servers/risk_of_rain_2)
* [Rust](game_eggs/steamcmd_servers/rust)
  * [Autowipe](game_eggs/steamcmd_servers/rust/rust_autowipe)
  * [Staging](game_eggs/steamcmd_servers/rust/rust_staging)
* [Satisfactory](game_eggs/steamcmd_servers/satisfactory)
* [Solace Crafting](game_eggs/steamcmd_servers/solace_crafting)
* [SCP: Secret Laboratory](game_eggs/steamcmd_servers/scpsl)
  * [dedicated](game_eggs/steamcmd_servers/scpsl/dedicated)
  * [exiled](game_eggs/steamcmd_servers/scpsl/exiled)
  * [multiadmin](game_eggs/steamcmd_servers/scpsl/multiadmin)
* [Soldat](game_eggs/steamcmd_servers/soldat)
* [Space Engineers](game_eggs/steamcmd_servers/space_engineers)
  * [default](game_eggs/steamcmd_servers/space_engineers/default)
  * [torch](game_eggs/steamcmd_servers/space_engineers/torch)
* [Squad](game_eggs/steamcmd_servers/squad)
* [Starbound](game_eggs/steamcmd_servers/starbound)
* [Stationeers](game_eggs/steamcmd_servers/stationeers)
* [Stormworks: Build and Rescue](game_eggs/steamcmd_servers/stormworks)
* [Subnautica: Nitrox Mod](game_eggs/steamcmd_servers/subnautica_nitrox_mod)
* [Sven Co-op](game_eggs/steamcmd_servers/svencoop)
* [The Forest](game_eggs/steamcmd_servers/the_forest)
* [The Isle](game_eggs/steamcmd_servers/the_isle)
  * [Evrima](game_eggs/steamcmd_servers/the_isle/evrima)
* [Team Fortress 2 Classic](game_eggs/steamcmd_servers/team_fortress_2_classic)
* [Tower Unite](game_eggs/steamcmd_servers/tower_unite)
* [Unturned](game_eggs/steamcmd_servers/unturned)
* [V Rising](game_eggs/steamcmd_servers/v_rising)
* [Valheim](game_eggs/steamcmd_servers/valheim)
  * [Valheim Vanilla](game_eggs/steamcmd_servers/valheim/valheim_vanilla)
  * [Valheim Plus Mod](game_eggs/steamcmd_servers/valheim/valheim_plus)

[Teeworlds](game_eggs/teeworlds)

* [Teeworlds](game_eggs/teeworlds/teeworlds)

[Terraria](game_eggs/terraria)

* [Vanilla](game_eggs/terraria/vanilla)
* [tModLoader](game_eggs/terraria/tmodloader)
* [TShock](game_eggs/terraria/tshock)

[Tycoon Games](game_eggs/tycoon_games)

* [OpenRCT2](game_eggs/tycoon_games/openrct2)
* [OpenTTD](game_eggs/tycoon_games/openttd)

[Veloren](game_eggs/veloren)

[Vintage Story](game_eggs/vintage_story)

[Wine Generic](game_eggs/wine/generic)

[Xonotic](game_eggs/xonotic/xonotic)

[FoundryVTT](game_eggs/FoundryVTT)

## [Monitoring](/monitoring/)

### Loki

* [Loki](/monitoring/loki)

### Prometheus

* [Prometheus](/monitoring/prometheus)

## [Storage](/storage/)

### S3 Storage

* [minio](/storage/minio)

## [Software](/software/)

### Code Server

* [Code-Server](/software/code-server)

### Elasticsearch

* [Elasticsearch](/software/elasticsearch)

### Gitea

* [Gitea](/software/gitea)

### Grafana

* [Grafana](/software/grafana)

### haste-server

* [haste-server](/software/haste-server)

### LanguageTool

* [languagetool](/software/languagetool)

### Owncast

* [owncast](/software/owncast)

### RabbitMQ

* [rabbitmq](/software/rabbitmq)

### Reposilite

* [Reposilite](/software/reposilite)

### Yarr

* [yarr](/software/yarr)

### 5e Tools

* [5e Tools](/software/5e-tools)
