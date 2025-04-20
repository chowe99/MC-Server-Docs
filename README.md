# Minecraft Server Documentation

## Initial Setup
<ol>
  <li>Install the <a href="https://modrinth.com/app">Modrinth</a> launcher.</li>
  <li>
    <details>
      <summary>Install <a href="https://modrinth.com/modpack/fabulously-optimized?version=1.21.5#download">Fabulously Optimized</a> in Modrinth and launch Minecraft through it (Fabric v1.21.5).</summary>
      <ul>
        <li><b>Fabulously Optimized</b> is a modpack whose name speaks for itself; It can 10x your FPS, mine went from ~150 to sometimes 1300+ fps.</li>
        <li>See FPS in image below:</li>
        <li><img src="https://github.com/user-attachments/assets/81eeada7-3107-443e-b296-6e36af6c2825" width="750"/></li>
      </ul>
    </details>
  </li>
  <li>Install prerequisite client-side mods to your Fabulously Optimized instance in Modrinth:
    <ul>
      <li><a href="https://modrinth.com/mod/easy-magic?version=1.21.5&loader=fabric">Easy Magic</a></li>
      <li><a href="https://modrinth.com/mod/toms-storage?version=1.21.5&loader=fabric#download">Tom's Simple Storage</a> - short guide <a href="https://youtu.be/nW5ElcWiC3c">here</a></li>
    </ul>
  </li>
</ol>

## Server Commands/Info
<ul>
  <li><b>EssentialCommands</b> commands are <a href="https://github.com/John-Paul-R/Essential-Commands/wiki/List-of-Commands-&-Permissions">here</a></li>
  <li>
    <details>
      <summary><b>Get Off My Lawn</b> recipes are <a href="https://github.com/Patbox/get-off-my-lawn-reserved/blob/1.21.5/recipes.md">here</a> (blocks that allow you to claim land)</summary>
      <ul>
        <li>The first claim anchor recipe is below (wood, stone and an ender pearl):</li>
        <li><img src="https://github.com/user-attachments/assets/4f889253-2d2d-4dce-9a5f-518e651bd588" width="300"/></li>
      </ul>
    </details>
  </li>
  <li><b>Hey That's Mine</b> commands are <a href="https://github.com/QuiltServerTools/HeyThatsMine?tab=readme-ov-file#using-htm">here</a> (Prevents stealing of placed chests/items)</li>
  <li><b>InventorySorter</b> has a client-side mod available <a href="https://modrinth.com/mod/inventory-sorting?version=1.21.5">here</a>, but if you don't want it you can sort chests by double-clicking empty tiles.</li>
  <li><b>Neo Enchant+</b> enchantment's <a href="https://github.com/Hardel-DW/NeoEnchant?tab=readme-ov-file#neo-enchantments-list">list</a></li>
</ul>

## Optional
### Mods
- <details>
  <summary><a href="https://modrinth.com/plugin/simple-voice-chat">Simple Voice Chat</a> - You won't be able to use proximity voice chat without this.</summary>
  <ul>
    <ul>
      <li>Try downloading it with the Modrith client first, but it's likely you won't be able to add it to your <b>"Fabulously Optimized"</b> instance.</li>
      <li>To download it manually, use <a href="https://modrinth.com/plugin/simple-voice-chat?version=1.21.5&loader=fabric">this link</a>.</li>
      <li>Then, place it inside your <b>"Fabulously Optimized"</b> instance's mod folder.</li>
      <ul>
        <li>(Windows) <code>%APPDATA%\ModrinthApp\profiles\Fabulously Optimized\mods</code></li>
        <li>(Linux) <code>~/.local/share/ModrinthApp/profiles/Fabulously\ Optimized/mods</code></li>
      </ul>
      <li>Once you've loaded it in-game:</li>
      <ul>
        <li>Press <code>v</code> (default) to access SVC's settings, make sure you select the correct input and output devices.</li>
        <li>Type <code>/voicechat</code> to see it's commands (<code>/voicechat invite &lt;PLAYERNAME&gt;</code> is the most relevant).</li>
      </ul>
    </ul>
  </ul>
</details>

- [Simple HUD](https://modrinth.com/mod/simplehud) - Configurable Heads Up Display that shows game information.

### Resource Packs
- [Default HD 128x](https://modrinth.com/resourcepack/default-hd-128x/versions) (Not as potent as shaders, but barely impacts performance)
- [Dramatic Skies](https://modrinth.com/resourcepack/dramatic-skys)

### Shaders
<details>
  <summary><a href="https://modrinth.com/shader/complementary-reimagined">Complementary Reimagined</a></summary>
  <ul>
    <li>Sample images:
      <ul>
        <li><img src="https://github.com/user-attachments/assets/def189a6-9266-443c-bbff-40cb64df262c" alt="image"></li>
        <li><img src="https://github.com/user-attachments/assets/4c0afb55-40e1-4987-bc3c-048f948477f6" alt="image"></li>
      </ul>
    </li>
  </ul>
</details>





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

