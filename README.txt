💡This datapack handles all world generation configuration to integrate the different mods adding biomes and structures.

It does that by introducing a range of exclusion/avoid tags (see below).
These sets are included in all/most structure files of the individual mods.

For example:
All structures from "Dungeons Arise" have an exclusion zone for "Villages (all)".
This avoids any hostile structures spawning (too) close to villages.

💡This datapack also disables the spawning of some structures that are not in line with the server vision (or pose a conflict with another mod).

💡Finally, this datapack updates the biome tag files of all structure mods to account for the range of biome mods in this pack.

A separate CHANGELOG.txt is included to track all future adjustments and changes.

========================================

🏷️ Villages (all)
minecraft:villages
skyvillages:skyvillage
create_sky_village:skyvillage
create_structures_arise:createminiskyvillage

🏷️ Villages and Oceans (all)
minecraft:villages
skyvillages:skyvillage
create_sky_village:skyvillage
create_structures_arise:createminiskyvillage
dungeons_arise_seven_seas:unicorn_galleon
dungeons_arise_seven_seas:pirate_junk
dungeons_arise_seven_seas:small_yacht
dungeons_arise_seven_seas:victory_frigate
dungeons_arise_seven_seas:corsair_corvette

🏷️ Sky Villages
skyvillages:skyvillage
create_sky_village:skyvillage
create_structures_arise:createminiskyvillage

🏷️ Nether Structures
minecraft:bastion_remnant
minecraft:nether_fortress

🏷️ Nether Structures (Prioritized: Minecraft > Incendium > MNS > Biome Mods)
minecraft:bastion_remnant
minecraft:nether_fortress (betterfortresses:fortress)
incendium:greater_structures
incendium:lesser_structures

🏷️ End Structures
minecraft:end_city

🏷️ End Structures (Prioritized: Minecraft > MES > Nullscape)
minecraft:end_city
enderkeep_courtyard
enderwatch_tower
monolith
phantom_citadel
starlight_voyager
manuscript_shrine
mystical_archway
ender_spire