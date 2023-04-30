# StreamsniperMaps: Dota 2 Minimap Overlays

StreamsniperMaps is a project that provides semi-transparent stream overlays for the Dota 2 minimap. These overlays can be used by streamers to enhance their streams and provide additional information to viewers. This README provides instructions on how to create these overlays in-game using various console commands and chat commands.

## How to Create Minimap Overlays

### Initial Setup

1. Start a Dota 2 game and pick the hero Marci.
2. Pause the game.

### In-Game Chat Commands

Enter the following commands in the in-game chat to disable creep spawning, kill all existing creeps, and enable all-vision:

```sh
-disablecreepspawn
-killcreeps all
-allvision
```

### Console Commands

Open the console and enter the following commands to enable cheats, kill all buildings, remove runes and hero icons from the minimap, and prevent creep spawning:

```sh
sv_cheats true
dota_kill_buildings
dota_minimap_rune_size 0
dota_minimap_hero_size 0
dota_creeps_no_spawning true
dota_kill_creeps true
```

#### Optional: Removing Fog of War

To remove the fog of war from the minimap, enter the following command in the console:

```sh
dota_minimap_draw_fow false
```

### In-Game Chat Commands (Continued)

Enter the following commands in the in-game chat to teleport to the enemy base, level up, acquire items, and use Marci's ultimate ability to kill the remaining buildings:

```sh
-wtf
-rapgod
-teleport
```

While focused on the ally base, use the following commands to create an enemy Marci bot, level it up, and give it items:

```sh
-createhero marci enemy
-levelbots 30
-givebots item_rapier
-givebots item_rapier
-givebots item_rapier
-givebots item_rapier
```

### Warding

Blink around the map and place observer wards. Enabling fog of war is recommended for this step.

### Taking Screenshots

1. Move the camera to the bottom left corner of the map.
2. Crop the screenshot to the outline of the minimap.
3. Set the opacity of each image to 70% (or use a 30% opacity eraser).

#### Image Sizes and Settings

The following table provides specific settings for different minimap sizes (Small, Large, XLarge) and styles (Simple, Complex). Adjust the size of the Ancient and fountain icons accordingly.

| Minimap Size | Style   | Ancient Size | Radiant Fountain Size | Dire Fountain Size | Console Commands |
|--------------|---------|--------------|-----------------------|--------------------|------------------|
| Small        | Simple  | 14px         | 125px                 | 140px              | `dota_minimap_simple_background true`<br>`dota_hud_extra_large_minimap 0`<br>`dota_minimap_draw_fow true` |
| Small        | Complex | 14px         | 125px                 | 140px              | `dota_minimap_simple_background false`<br>`dota_hud_extra_large_minimap 0`<br>`dota_minimap_draw_fow true` |
| Large        | Simple  | 15px         | 150px                 | 165px              | `dota_minimap_simple_background true`<br>`dota_hud_extra_large_minimap 1`<br>`dota_minimap_draw_fow true` |
| Large        | Complex | 15px         | 150px                 | 165px              | `dota_minimap_simple_background false`<br>`dota_hud_extra_large_minimap 1`<br>`dota_minimap_draw_fow true` |
| XLarge       | Simple  | 24px         | 225px                 | 255px              | `dota_minimap_simple_background true`<br>`dota_hud_extra_large_minimap 2`<br>`dota_minimap_draw_fow true` |
| XLarge       | Complex | 24px         | 225px                 | 255px              | `dota_minimap_simple_background false`<br>`dota_hud_extra_large_minimap 2`<br>`dota_minimap_draw_fow true` |

## Conclusion

By following the instructions provided in this README, you can create semi-transparent overlays for the Dota 2 minimap in different sizes and styles. These overlays can be used to enhance your live streams and provide additional information to your viewers. Enjoy creating your custom minimap overlays with StreamsniperMaps!
