Feature comparison between [Aternos](http://aternos.org/) and [exaroton](http://exaroton.com/) 

## Table of Contents

- [Quick Comparison Table](#quick-comparison-table)
- [Aternos vs exaroton - Feature Comparison with Explanation](#aternos-vs-exaroton---feature-comparison-with-explanation)
- [What Makes exaroton Different](#what-makes-exaroton-different)
- [Current Downsides of exaroton](#current-downsides-of-exaroton)


# Quick Comparison Table

| # | Feature | Aternos | exaroton |
|---|--------|---------|----------|
| [1](#public-api) | Public API | Doesn't provide a public API | Provides a public API |
| [2](#custom-startup-arguments) | Custom startup arguments | Not possible | Supported |
| [3](#performance) | Performance | Lower performance | Better performance |
| [4](#server-loading--saving-speed) | Loading / saving speed | Slower | Faster |
| [5](#ads) | Ads | Funded by ads; many ads on the website | Paid service; ad-free |
| [6](#startup-queue) | Startup queue | May be lined up in a queue when starting the server | No queue |
| [7](#ram-allocation) | RAM | Less than 3 GB without Medal boosts | Up to 16 GB |
| [8](#world-upload-size-limit) | World upload size limit | 1 GB | 3 GB |
| [9](#server-storage-limit-compressed) | Server storage limit (compressed) | 4 GB | 10 GB |
| [10](#discord-bot) | Discord bot | No public Discord bot | Public Discord bot available|
| [11](#autostart) | Autostart | Not available | Available |
| [12](#autostop) | Autostop | Always enabled to save resources | Configurable; can be enabled to save credits |
| [13](#custom-plugins--mods) | Custom plugins / mods | Not possible as some allow automatic shutdown circumvention | Any plugins / mods allowed |
| [14](#paid-plugins--mods) | Paid plugins / mods | Not possible | Allowed |
| [15](#file-downloads) | File downloads | Only certain files (worlds, configs, Bedrock addons, etc.) | Most files |
| [16](#server-creation-limit-per-account) | Servers per account | Create up to 3 servers | Create up to 10 servers |
| [17](#server-regions) | Server regions | Central Europe only | Central Europe & North America |
| [18](#server-networks) | Server networks | Not supported | Supported |
| [19](#custom-server-software) | Custom server software | Not supported | Supported |
| [20](#modpacks) | Modpacks | Preloaded modpacks only | Custom modpacks can be uploaded |
| [21](#preloaded-modpacks) | Preloaded modpacks | Fewer | More |
| [22](#modification-of-preloaded-modpacks) | Preloaded modpack modification | Cannot modify mod collection or configs | Possible with modpack overrides |
| [23](#modpack-versions) | Modpack versions | Latest only | Can use specific versions by uploading |
| [24](#monetization) | Monetization | Not allowed | Allowed |
| [25](#offline-waiting-lobby) | Offline waiting lobby | Forced | Configurable |
| [26](#player-idle-timeout-afk-kick) | Player idle timeout | Limited; cannot be disabled | Not limited |
| [27](#server-render--view-distance) | Render / view distance | Limited | Not limited |
| [28](#simulation-distance) | Simulation distance | Limited | Not limited |
| [29](#247-online) | 24/7 always online | Not allowed | Possible but not recommended |
| [30](#addons-for-mods--plugins) | Addons for mods / plugins | Only some allowed | Most / All allowed |
| [31](#server-advertising) | Advertising | Aternos Discord only | Aternos and exaroton Discord |




# Aternos vs exaroton - Feature Comparison with Explanation

## Public API
   - Aternos does **not** provide a public API.
   - exaroton does, see [the official guide](https://support.exaroton.com/hc/en-us/articles/360019857878).

## Custom Startup Arguments
   - Aternos does **not** support custom startup arguments (e.g. Aikar’s flags).
   - exaroton supports them, see [the official guide](https://support.exaroton.com/hc/en-us/articles/4403786325137).

## Performance
   - exaroton generally offers better performance than Aternos. Read more on allocated resources and hardware [here](https://support.exaroton.com/hc/en-us/articles/360019687757).

## Server Loading / Saving Speed
   - exaroton has faster server loading and saving times compared to Aternos, given the same server size.

## Ads
   - Aternos is funded by ads and displays many ads on its website.
   - exaroton is a paid service and completely ad-free.

## Startup Queue
   - Aternos servers may be placed in a queue when starting.
   - exaroton has no startup queue.

## RAM Allocation
   - Aternos servers are limited to less than 3 GB of RAM without boosts from [Aternos-Medal partnership](https://aternos.medal.tv/) (varies by software and version).
   - exaroton allows up to 16 GB of RAM (16 GB is more than enough for most servers). See [the official guide](https://support.exaroton.com/hc/en-us/articles/360019687757).

## World Upload Size Limit
   - Aternos: 1 GB
   - exaroton: 3 GB

## Server Storage Limit (compressed)
   - Aternos: 4 GB
   - exaroton: 10 GB

If you reach this limit, you can no longer start your server. Contact support for help on reducing server size.

## Discord Bot
   - Aternos does not offer a public Discord bot, as users must visit the website to start servers due to ad-based funding.
   - exaroton provides a public Discord bot to start, stop, restart, manage your servers and more from your own Discord server. See [the official guide](https://support.exaroton.com/hc/en-us/articles/360019687777).

## Autostart
   - Aternos does not offer this feature.
   - exaroton supports Autostart, allowing servers to start automatically when a player tries to join. See [the official guide](https://support.exaroton.com/hc/en-us/articles/15338752897181).

## Autostop
   - Aternos always enforces Autostop to conserve limited resources.
   - exaroton allows Autostop to be disabled, or enabled to save credits when the server is empty. See [the official guide](https://support.exaroton.com/hc/en-us/articles/360019687297).

## Custom Plugins / Mods
   - Aternos restricts custom uploads for plugins and mods because some can prevent automatic shutdown. Only those in the [plugins/mods section](https://aternos.org/addons) are usable, there are over 42,000 plugins/mods available.
   - exaroton allows uploading any plugins and mods (drag and drop works). See [the official guide](https://support.exaroton.com/hc/en-us/articles/360019687677).

## Paid Plugins / Mods
   - Paid plugins/mods are not possible on Aternos.
   - exaroton allows the use of any plugins/mods, including paid ones.

## File Downloads
   - Aternos only allows downloading specific files (e.g., worlds, configs, Bedrock addons).
   - exaroton allows downloading most server files (use `Ctrl + A` to select all files).

## Server Creation Limit per Account
   - Aternos: up to 3 servers
   - exaroton: up to 10 servers

## Server Regions
   - Aternos: Central Europe only
   - exaroton: Central Europe and North America (See [the official guide](https://support.exaroton.com/hc/en-us/articles/21659706549789-Server-region))

## Server Networks
   - It's not possible to create a proxy server on Aternos.
   - exaroton supports server networks, see [the official guide](https://support.exaroton.com/hc/en-us/articles/4404724229137).  

## Custom Server Software
   - exaroton allows uploading and running custom server software, not just prelisted options. See [the official guide](https://support.exaroton.com/hc/en-us/articles/360019687717).
   - This is not possible on Aternos.

## Modpacks
   - Aternos only allows using [preloaded modpacks](http://aternos.org/software/modpacks/) or creating a custom modpack by manually [installing mods](https://support.aternos.org/hc/en-us/articles/360027235871) one by one in [the mods section](https://aternos.org/addons).
   - Instead of using one of the preloaded modpacks or creating a custom modpack, exaroton also allows uploading custom modpacks. See [the official guide](https://support.exaroton.com/hc/en-us/articles/360019687717-Uploading-custom-server-software-and-modpacks#:~:text=server%2Dlaunch.jar.-,Modpacks,-Since%20modpacks%20are).

## Preloaded Modpacks
   - exaroton offers more [preloaded modpacks](http://exaroton.com/software/modpacks) for quick setup and instant play. See [the official guide](https://support.exaroton.com/hc/en-us/articles/4415404404625).

## Modification of Preloaded Modpacks
   - Aternos does not allow modifying the mods or configs of preloaded modpacks.
   - exaroton supports [modpack overrides](https://support.exaroton.com/hc/en-us/articles/32500934647709).

## Modpack Versions
   - Aternos only provides the latest version of preloaded modpacks. Preloaded modpacks get updated automatically when a new version is out.
   - exaroton allows using specific modpack versions by uploading them as custom server software. See [the official guide](https://support.exaroton.com/hc/en-us/articles/360019687717-Uploading-custom-server-software-and-modpacks#:~:text=server%2Dlaunch.jar.-,Modpacks,-Since%20modpacks%20are).

## Monetization
   - Since Aternos is free, earning real money from its servers is not allowed and may result in permanent suspension of your Aternos account.
   - exaroton allows server monetization.

## Offline Waiting Lobby
   - The offline waiting lobby cannot be disabled on Aternos.
   - exaroton allows enabling or disabling the offline waiting lobby. See [the official guide](https://support.exaroton.com/hc/en-us/articles/31506159658397).

## Player Idle Timeout (AFK kick)
Idle (AFK) players are kicked from the server after a certain time. This is a feature of Vanilla Minecraft.
   - On Aternos, the idle timeout is 10 minutes by default and cannot be disabled. On Java Edition, this can be increased via `/setidletimeout` command but the maximum value is limited to 30 minutes. Trying to circumvent the idle timeout by any way is a violation of [Aternos' terms of service](https://aternos.org/tos) and will result in permanent suspension of your Aternos account(servers).
   - exaroton does not limit this. It can be configured on [the options page](https://exaroton.com/options) or using the `/setidletimeout <minutes>` command on Java Edition. If set to `0`, the idle timeout is disabled.

## Server Render / View Distance
The amount of world data the server sends the client, measured in chunks in each direction of the player (radius, not diameter). In the Minecraft client, this option is called "Render distance" and can be set to a lower value than the server's view distance to improve the client performance and FPS. However, it is not possible to set it to a higher value than the server's view distance to load more chunks. Setting it higher won't change anything.

Java Edition players can use a client sided mod like [Bobby](https://modrinth.com/mod/bobby) or [Distant Horizons](https://modrinth.com/mod/distanthorizons) to achieve a greater render distance than the server's.
   - On Aternos, the maximum value of server view distance is limited to 15 on Paper/Purpur/Bedrock and 10 on other software for performance optimization. [Read more here](https://support.aternos.org/hc/en-us/articles/360032974492).
   - exaroton does not limit this. It can be configured in the [`server.properties`](http://exaroton.com/files/server.properties) file. It is not recommended to set the server view distance higher than 10.

## Simulation Distance
The maximum distance from players that living entities may be located in order to be updated by the server, measured in chunks in each direction of the player (radius, not diameter). If entities are outside of this radius, then they are not ticked by the server and they are not visible to players.
   - On Aternos, the maximum value of simulation distance is limited to 5 for performance optimization.
   - exaroton does not limit this. It can be configured in the [`server.properties`](http://exaroton.com/files/server.properties) file. It is not recommended to set the simulation distance higher than 10.

## 24/7 Online
#### Aternos
   - Running your server 24/7 is **not** possible on Aternos because it is a 100% free service. Aternos has limited resources and wants to ensure they are used by active players.
   - Trying to circumvent this is a violation of [Aternos’ terms](https://aternos.org/tos) and will result in your Aternos account(servers) being suspended permanently. [Read more here](https://support.aternos.org/hc/en-us/articles/31771896948253).
#### exaroton
   - On exaroton, it is possible to run your server 24/7. However, this is **not** the intended use case for exaroton and will be more expensive than other hosting providers. It is recommended to enable [Autostart](https://support.exaroton.com/hc/en-us/articles/15338752897181) and [Autostop](https://support.exaroton.com/hc/en-us/articles/360019687297) to only run your server when there are active players.
   - If you run a large public server that almost always has players online, a traditional monthly subscription-based hosting provider might be cheaper. However, if you only play a few hours per day with your friends, you can save a lot of money by only running your server when you actively use it with exaroton.

## Addons for Mods / Plugins
#### Aternos
   - On Aternos, whether addons for specific mods or plugins are allowed always depends on how those addons are implemented in the mod/plugin in question. If a mod/plugin implements their addon system in a safe way, Aternos generally allows addons to be uploaded. For example, content packs for the Immersive Railroading mod are supported.
   - If the way a mod/plugin implements their addon system or the addon itself might allow circumventing [Aternos' restrictions](https://aternos.org/tos), such as bypassing the automatic shutdown, then such addons cannot be used on Aternos. For example, gunpacks for the TaCZ mod, addons for the Fisk's Superheroes mod, addons for the Lucraft: Core mod, content packs for the Flan's Mod, addons for the Skript plugin are **not** supported.
#### exaroton
- On exaroton, most, if not all, addons for mods and plugins are supported.

## Server Advertising
   - Aternos server advertisements are only allowed in the [Aternos Discord](https://discord.gg/aternos)'s **servers** channel.
   - exaroton server advertisements are allowed in both the [Aternos Discord](https://discord.gg/aternos)'s **servers** channel and the [exaroton Discord](http://discord.gg/exaroton)'s **servers** channel.

---

# What Makes exaroton Different

1. Unlike the traditional hosting providers with a fixed monthly plan, exaroton is **pay-as-you-go**! You are only charged for the time you **actually use** your server. [Read about pricing here](https://support.exaroton.com/hc/en-us/articles/360019687657).
2. exaroton is not meant for running your server 24/7. After all, most servers don’t have players online all the time. Just enable **[Autostart](https://support.exaroton.com/hc/en-us/articles/15338752897181)** and **[Autostop](https://support.exaroton.com/hc/en-us/articles/360019687297)** so players can join and play anytime while saving your money.
3. There's **no subscription**; you don't need to worry about getting a bill charged automatically. You only pay when you choose to buy credits.
4. Share payments for your server with your friends in a safe way with **[credit pools](https://support.exaroton.com/hc/en-us/articles/11567970055581)**!
5. You can change your server's allocated RAM at any time whenever needed.
6. exaroton servers are **fully DDoS protected** to keep you safe from DDoS attacks.
7. exaroton provides an **easy-to-use user interface**, making server management simple and intuitive.
8. Want to create a **Java-Bedrock crossplay** server? exaroton makes this effortless, eliminating the need for manual setup. See [the official guide](https://support.exaroton.com/hc/en-us/articles/360019857918).
9. [Import your Aternos servers](https://support.exaroton.com/hc/en-us/articles/360019857978) to exaroton instantly with just a few clicks!
10. Unlike many other hosting providers, exaroton offers **[unlimited free backups](https://support.exaroton.com/hc/en-us/articles/360019857278)**! Backups stay even after server deletion. Just enable automatic backups and you are worry-free!
11. Tired of the default `exaroton.me` address? Use a **[custom domain name](https://support.exaroton.com/hc/en-us/articles/360019687257)**!
12. exaroton is made by a company with **12+ years** of server hosting experience, continuously adding **new features**!
   
---

# Current Downsides of exaroton

1. Certain plugins/mods may not work, such as voting or backup plugins/mods, as well as web map plugins/mods (e.g., Dynmap, BlueMap).  
2. exaroton only provides **one port per server**, so it’s not possible to use both GeyserMC and a voice chat plugin/mod simultaneously.  
3. Although planned, there are currently no servers in the Asia region.
4. Renaming files on the website is unfortunately currently not possible due to the way exaroton's storage system is implemented. exaroton is planning to fix this in the future but it requires a major overhaul of some core systems.
5. Only the latest server log file is stored.
6. FTP is not supported on exaroton.
7. exaroton does not provide static IP addresses, due to the dynamic pricing model.
8. The `/restart` command added by Spigot is not supported on exaroton. (Note that you should never use `/reload` or `/bukkit:reload` on Bukkit-based software like Spigot/Paper/Purpur. Use `/minecraft:reload` instead for reloading datapacks.) 

---

<p align="center">
Made with ❤️ by Adriel
</p>


