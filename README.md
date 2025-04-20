# Minecraft Server Documentation

1. Install the [Modrinth](https://modrinth.com/app) launcher.
2. Install [Fabulously Optimized](https://modrinth.com/modpack/fabulously-optimized?version=1.21.5#download) in Modrinth and launch Minecraft through it (Fabric v1.21.5). 
    - **Fabulously Optimized** is a modpack whose name speaks for itself; It can 10x your FPS, mine went from ~150 to sometimes 1300+ fps.
    - See FPS in image below:
    - <img src="https://github.com/user-attachments/assets/81eeada7-3107-443e-b296-6e36af6c2825" width="750"/>
3. Install prerequisite client-side mods to your Fabulously Optimized instance in Modrinth:
    - [Easy Magic](https://modrinth.com/mod/easy-magic?version=1.21.5&loader=fabric)
    - [Tom's Simple Storage](https://modrinth.com/mod/toms-storage?version=1.21.5&loader=fabric#download)


## Server Commands/Info

- **EssentialCommands** commands are [here](https://github.com/John-Paul-R/Essential-Commands/wiki/List-of-Commands-&-Permissions)

- **Get Off My Lawn** recipes are [here](https://github.com/Patbox/get-off-my-lawn-reserved/blob/1.21.5/recipes.md) (blocks that allow you to claim land)
  - The first claim anchor recipe is below (wood, stone and an ender pearl):
  - <img src="https://github.com/user-attachments/assets/4f889253-2d2d-4dce-9a5f-518e651bd588" width="300"/>
 
- **Hey That's Mine** commands are [here](https://github.com/QuiltServerTools/HeyThatsMine?tab=readme-ov-file#using-htm) (Prevents stealing of placed chests/items)

- **InventorySorter** has a client-side mod available [here](https://modrinth.com/mod/inventory-sorting?version=1.21.5), but if you don't want it you can sort chests by double clicking empty tiles.


## Client-Side Only Mods

You can install whichever client-side-only mods you want to your **"Fabulously Optimized"** instance, but here are a few suggestions:

### UI
- [Simple HUD](https://modrinth.com/mod/simplehud) - Configurable Heads Up Display that shows game information.

### Visual Mods
**Resource Packs:**
- [Default HD 128x](https://modrinth.com/resourcepack/default-hd-128x/versions) (Not as potent as shaders, but barely impacts performance)
- [Dramatic Skies](https://modrinth.com/resourcepack/dramatic-skys)

**Shaders:**
- [Complementary Reimagined](https://modrinth.com/shader/complementary-reimagined)
  - Sample images:
    - ![image](https://github.com/user-attachments/assets/def189a6-9266-443c-bbff-40cb64df262c)
    - ![image](https://github.com/user-attachments/assets/4c0afb55-40e1-4987-bc3c-048f948477f6)

## Client-Server Mods

Client-server mods need to be installed on the client and the server to function properly, however some mods like `Simple Voice Chat` aren't necessary to install on the client side ~~and the server can still be accessed with a vanilla client~~.

- [Simple Voice Chat](https://modrinth.com/plugin/simple-voice-chat) - Adds proximity voice chat to the game.
    - Try downloading it with the Modrith client first, but it's likely you won't be able to add it to your **"Fabulously Optimized"** instance.
    - To download it manually, use [this link](https://modrinth.com/plugin/simple-voice-chat?version=1.21.5&loader=fabric).
    - Then, place it inside your **"Fabulously Optimized"** instance's mod folder.
        - (Windows) `%APPDATA%\ModrinthApp\profiles\Fabulously Optimized\mods`
        - (Linux) `~/.local/share/ModrinthApp/profiles/Fabulously\ Optimized/mods`
    - Once you've loaded it in-game:
      - Press `v` (default) to access SVC's settings, make sure you select the correct input and output devices.
      - Type `/voicechat` to see it's commands (`/voicechat invite <PLAYERNAME>` is the most relevant).    


## Known Issues
Nil

## Server-Side Mod List
- [Essential Commands](https://github.com/John-Paul-R/Essential-Commands/) - Provides essential server commands and utilities.
- [CT's Overhauled Villages](https://modrinth.com/mod/ct-overhaul-village) - Overhauls and improves village generation.
- [LuckPerms](https://modrinth.com/plugin/luckperms) - A powerful permissions management plugin.
- [Almanac](https://modrinth.com/mod/almanac) - Library mod used by other mods.
- [Roguelike Dungeons](https://modrinth.com/mod/roguelikedungeons) - Adds complex and challenging underground dungeons.
- [ScalableLux](https://modrinth.com/mod/scalablelux) - Adds more configurable light sources.
- [Actually Harvest](https://modrinth.com/mod/actually-harvest) - Allows right clicking crops to harvest.
- [Balm](https://modrinth.com/mod/balm) - Another library mod used by other mods.
- [Cristel Lib](https://modrinth.com/mod/cristel-l55) - A utility library for other mods.
- [Fabric API](https://modrinth.com/mod/fabric-api) - The core API for Fabric modding.
- [Get Off My Lawn](https://modrinth.com/mod/goml-reserved) - Adds land claiming mechanics.
- [Hey That's Mine](https://modrinth.com/mod/htm) - Prevents stealing of placed items.
- [Let Me Despawn](https://modrinth.com/plugin/lmd) - Controls mob despawning behavior.
- [Lithium](https://modrinth.com/mod/lithium) - General server-side optimization mod.
- [Lithostitched](https://modrinth.com/mod/lithostitched) - Optimizes chunk loading.
- [Nether Portal Fix](https://modrinth.com/mod/netherportalfix) - Fixes issues with Nether portal linking.
- [Dungeons and Taverns](https://modrinth.com/datapack/dungeons-and-taverns)
- [Spark](https://modrinth.com/mod/spark) - A performance profiling tool.
- [Towns and Towers](https://modrinth.com/mod/towns-and-towers) - Generates new and improved structures.
- [Detect AFK](https://modrinth.com/datapack/detect-afk)
- [AFK sleep](https://modrinth.com/datapack/afk-sleep)
- [Forge conflict API Port](https://modrinth.com/mod/forge-config-api-port)
- [Easy Magic](https://modrinth.com/mod/easy-magic)
- [Puzzles Lib](https://modrinth.com/mod/puzzles-lib)
- [Cloth Config API](https://modrinth.com/mod/cloth-config)
- [Inventory Sorter](https://modrinth.com/mod/inventory-sorting)
- [Clumps XP](https://modrinth.com/mod/clumps)
- [Mine Spawners](https://modrinth.com/mod/mine-spawners)
- [Homing XP](https://modrinth.com/datapack/simple-homing-xp)
- [Mine Treasure](https://modrinth.com/datapack/mine-treasure)
- [Neo Enchant+](https://modrinth.com/datapack/neoenchant) 

