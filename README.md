# MC-Server-Setup
1. Install [Modrinth](https://modrinth.com/app) launcher:
2. Install the [Fabulously Optimized](https://modrinth.com/modpack/fabulously-optimized?version=1.21.5#download) modpack
in Modrinth and launch Minecraft through it (Fabric v1.21.5). Fabulously Optimized can 10x ur FPS, mine went from ~150 to sometimes 1300+ fps:
![image](https://github.com/user-attachments/assets/81eeada7-3107-443e-b296-6e36af6c2825)

## Server Commands/Info
- EssentialCommands commands can be found [here](https://github.com/John-Paul-R/Essential-Commands/wiki/List-of-Commands-&-Permissions)
- Get Off My Lawn Recipes [here](https://github.com/Patbox/get-off-my-lawn-reserved/blob/1.21.5/recipes.md) (blocks that allow you to claim land), here is the first recipe:
  - ![image](https://github.com/user-attachments/assets/4f889253-2d2d-4dce-9a5f-518e651bd588)
- Hey That's Mine commands [here](https://github.com/QuiltServerTools/HeyThatsMine?tab=readme-ov-file#using-htm) (Prevents stealing of placed chests/items)

## Client-side Only Mods
You can install whichever client-side only mods you want to your 'Fabulously Optimized' instance, but here's a few suggestions:
### UI
- [Simple HUD](https://modrinth.com/mod/simplehud) - Configurable Heads Up Display that shows game information.
### Visual Mods
**Resource Packs:**
- [Default HD 128x](https://modrinth.com/resourcepack/default-hd-128x/versions) (Not as potent as shaders, barely impacts performance)
- [Dramatic Skies](https://modrinth.com/resourcepack/dramatic-skys)

**Shaders:**
- [Complementary Reimagined](https://modrinth.com/shader/complementary-reimagined)
Sample images:
![image](https://github.com/user-attachments/assets/def189a6-9266-443c-bbff-40cb64df262c)

![image](https://github.com/user-attachments/assets/4c0afb55-40e1-4987-bc3c-048f948477f6)

## Client-Server
Client-server mods need to be installed on the client and the server to function properly, however some mods like Plasmo aren't necessary to install on the client side and the server can still be accessed with a vanilla client.
- [Plasmo Voice](https://modrinth.com/plugin/plasmo-voice?version=1.21.5&loader=fabric) - Adds proximity voice chat to the game.
  - Press 'v' (default) to access Plasmo's settings, you may want to change your proximity distance along with your push-to-talk/voice settings:
![image](https://github.com/user-attachments/assets/54d8b8cb-e8ee-4ea9-8d6c-0e880b2faf8f)
  - Use [these](https://github.com/plasmoapp/pv-addon-groups?tab=readme-ov-file#commands) commands to create group voice chats which don't have proximity limits.
  - See [Issues](https://github.com/chowe99/MC-Server-Setup/edit/main/README.md#server-side-modlist)
## Known Issues
### Plasma Voice
Sometimes shaders can interact with the proximity voice mod and cause crashes, if you experience this, set entity icons to hidden:
![image](https://github.com/user-attachments/assets/25bad257-a7a7-4180-bee2-ff145eb6c097)
![image](https://github.com/user-attachments/assets/adf6eb6d-b062-494a-a08d-9db5acd8ab1b)
## Server-side modlist

- [Essential Commands](https://github.com/John-Paul-R/Essential-Commands/) - Provides essential server commands and utilities.
- [CT's Overhauled Villages](https://modrinth.com/mod/ct-overhaul-village) - Overhauls and improves village generation.
- [LuckPerms](https://modrinth.com/plugin/luckperms) - A powerful permissions management plugin.
- [Almanac](https://modrinth.com/mod/almanac) - Library mod used by other mods.
- [Roguelike Dungeons](https://modrinth.com/mod/roguelikedungeons) - Adds complex and challenging underground dungeons.
- [ScalableLux](https://modrinth.com/mod/scalablelux) - Adds more configurable light sources.
- [Plasmo Voice](https://modrinth.com/plugin/plasmo-voice) - Adds proximity voice chat to the game.
- [Actually Harvest](https://modrinth.com/mod/actually-harvest) - Allows right clicking crops to harvest.
- [Balm](https://modrinth.com/mod/balm) - Another library mod used by other mods.
- [Cristel Lib](https://modrinth.com/mod/cristel-l55) - A utility library for other mods.
- [Fabric API](https://modrinth.com/mod/fabric-api) - The core API for Fabric modding.
- [Get Off My Lawn](https://modrinth.com/mod/goml-reserved) - Adds land claiming mechanics.
- [Hey That's Mine](https://modrinth.com/mod/htm) - Prevents stealing of placed items.
- [Let Me Despawn](https://modrinth.com/plugin/lmd) - Controls mob despawning behavior.
- [Lithium](https://modrinth.com/mod/lithium) - General server-side optimization mod.
- [Lithostitched](https://modrinth.com/mod/lithostitched) - Optimizes chunk loading.
- [Mobstacker](https://modrinth.com/mod/mobstacker) - Stacks mobs together to reduce lag.
- [Nether Portal Fix](https://modrinth.com/mod/netherportalfix) - Fixes issues with Nether portal linking.
- [Plasma Voice Groups](https://modrinth.com/plugin/pv-addon-groups) - Allows for the creation of voice chat groups.
- [Spark](https://modrinth.com/mod/spark) - A performance profiling tool.
- [SS Waystones](https://modrinth.com/mod/sswaystones) - Adds placeable waystones for fast travel.
- [Towns and Towers](https://modrinth.com/mod/towns-and-towers) - Generates new and improved structures.
