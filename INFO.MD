# Gamerules & Mechanics
When playing this server, several rules are set:
- PvP is OFF
- Fire ticking is OFF (no spread, but also no automatic extinguishing except for in rain)
- Mob Griefing is OFF
- Keep Inventory is TRUE
- Difficulty is NORMAL
- Betweenlands Decay is ON
- Betweenlands Corrosion is ON
- All Betweenlands Events are ON, but may be manipulated if there is any RP going on or something. This is generally avoided (so if we get a blood sky when people are RPing outside and don't want it, it may be disabled)

# Mod Information

## Mods Included In The Pack
- EtiCore
- OptiFine
- EnderZoo (Modified)
- Hwyla
- iChunUtil
- JustEnoughItems (For Recipes)
- JourneyMap
- MorePlayerModels
- Morph (Modified)
- The Betweenlands (Modified)
- Trash Slot
- Vein Miner
- Simple Homes
- Wall-Jump!

## Known Bugs
- At times you may randomly die out of nowhere and still have health. If this happens, **click Respawn, then re-log from the server.** This is a desync issue. You aren't actually dead, but if you don't click respawn and log back in, the server will think you're dead and you won't be able to do anything. **This bug has become incredibly rare (no recent cases), but it may still happen.**
- At other times, you may be unable to click Respawn after dying. If this happens, go to the Title Screen, log back in, and try respawning once more.

### The Betweenlands
**Here's a short comprehensive guide:** 
https://github.com/XanTheDragon/OriDiscordMCStuff/blob/master/GUIDE.MD

**Some important stuff:**
- https://the-betweenlands.fandom.com/wiki/Sap_Tree_Log
- https://the-betweenlands.fandom.com/wiki/Decay
- https://the-betweenlands.fandom.com/wiki/Mobs

### Other Features
- You can use `/mpm name yourNameHere` to set a custom name via MorePlayerModels. Please use this sparingly.

# Details Of Mods
## EtiCore
### Features
- Appends Spirit Guardians as a mob (which has no AI, as it is used in the Morph mod as a playermodel). 
- Appends a "Spirit Light" item, which can be used with OptiFine to glow so long as you hold it (It is recommended to have it in your off-hand. It does not show as a held item when you hold it, so it won't get in the way). *This requires dynamic lights to be on.*
- Enforces that players use the Spirit Guardian mob with the Morph mod from the server-end (so even if you don't use this server's version of Morph, you have to use it.)

### Planned Updates
- :heavy_multiplication_x: Spirit Customization (make your own texture)
- :heavy_multiplication_x: Armor Models / Held Items (and the ability to choose whether or not you want to display them)
- :heavy_check_mark: A way for spirits to glow, either by held item or naturally.

## EnderZoo
### Changes
- Basically every feature has been disabled. It's just here for the owls, which do not spawn naturally for the time being. This may not be enabled.

## Morph
### Changes
- Since it is required that you use the Spirit playermodel on the server, this modified version of Morph ensures that you are using it on the clientside by disabling keybinds.

## The Betweenlands
### Changes
- Wights can no longer enter their volatile state (where they attack you as a ghost). This is due to incompatibilities with the spirit playermodel.
- By extension of above, Wights can no longer possess swamp hags to buff them.
- Biome colors are no longer hardcoded and instead reference vanilla foliage colors. This may be leveraged via a server resource pack in the future.
- Life Crystals can be recharged by right clicking with them. It will take 16 levels to bring a Life Crystal from 0% to 100% (Each level restores 6.25%)
- My mod has appended a "Locked Weedwood Trapdoor" item which can be crafted by placing a weedwood trapdoor inside of a crafting table. Place a locked trapdoor into a crafting table to get a normal trapdoor. This only works for weedwood trapdoors.
