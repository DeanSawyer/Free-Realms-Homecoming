<p align="center">
  <img src="res/OSFR.png" alt="Open Source Free Realms logo">
</p>

# Free Realms Homecoming

Free Realms Homecoming is a community fork of [Open Source Free Realms](https://github.com/Open-Source-Free-Realms/OpenSourceFreeRealms), an experimental server emulator for the original **Free Realms PC client**.

## Current status

This repository contains an early walking emulator. It is a starting point for restoring more of the game, but it is not a complete or ready-to-play Free Realms server.

This is a separate project from the PS3 bootstrap and the newer Sanctuary server.

## What's in this repository

- `ofrserver/Server.sln` — Visual Studio solution
- `ofrserver/Gateway/` — login, player, chat, map, and NPC code
- `ofrserver/Customize/` — character and item definitions
- `ofrserver/Packets/` — archived packet captures for research
- `res/` — project artwork

## Building from source

The server projects target **.NET Framework 4.8**. On Windows, open `ofrserver/Server.sln` in Visual Studio with the .NET Framework 4.8 targeting pack installed, restore dependencies, and build the solution.

Server settings are in `ofrserver/Config.json` and `ofrserver/Server/Config.json`. A compatible Free Realms PC client is required to connect.

The [original project's releases](https://github.com/Open-Source-Free-Realms/OpenSourceFreeRealms/releases) are available for reference. They are historical upstream releases, not builds of this fork.

## Credits

Free Realms Homecoming builds on the work of the [Open Source Free Realms contributors](https://github.com/Open-Source-Free-Realms/OpenSourceFreeRealms). Free Realms belongs to its respective rights holders. This is an independent fan project.
