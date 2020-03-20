**This server has rules. Read them.**
https://github.com/XanTheDragon/OriDiscordMCStuff/blob/master/RULES.MD

# Setting Up
## Big Step 1: Java
If you don't have it installed already, install Java. You can get Java [HERE (click here)](https://java.com/en/download/win10.jsp) if you don't have it.

## Big Step 2: Minecraft Forge
You need Minecraft Forge 1.12.2 for this to work.

**Step 1:** Launch Minecraft 1.12.2 at least once (so that a 1.12.2 version is created in your game directory).

**Step 2:** Download the Forge installer for 1.12.2 (which you can get [HERE (click here)](https://files.minecraftforge.net/maven/net/minecraftforge/forge/1.12.2-14.23.5.2847/forge-1.12.2-14.23.5.2847-installer.jar)). **Run this with Java** (Do *NOT* open with WinRAR / 7zip!), and select *Install Client* (not Server or Extract) and click OK. Wait for it to finish, then move on when it says it's done.

## Big Step 3: The Mods

**Step 1:** Go to your Minecraft install folder (usually `%appdata%\.minecraft`). Keep this folder open, as you will need it regardless of which way you decide to do this.

You need the official mods to join this server.

### Big Step 3-A: Automatic Downloader (easy way)
If you don't trust yourself with downloading mods, I have written an EXE file that will do it for you.

You can download that EXE from the releases tab, or [HERE (click here)](https://github.com/XanTheDragon/OriDiscordMCStuff/releases/download/1b/MCAutoDownloader.exe). **Put this EXE into the .minecraft folder.**

### Big Step 3-B: Manual Install

The link to all of the mods and configuration files: [HERE (click here)](https://github.com/XanTheDragon/OriDiscordMCStuff/releases/download/1/ORI_SERVER_MODS_AND_CONFIG.zip).

**Step 1:** Download + open the ZIP file from the line just above. You will see two folders inside: `config` and `mods`.

**Step 2:** Go to your Minecraft install folder (usually `%appdata%\.minecraft`). Drag both of the folders from the .zip file into the `.minecraft` folder. *If a `mods` folder already exists, make sure it is empty, or just rename it (e.g. to `mods-old`) if you had mods you want to keep already.*

**Step 3:** If any files prompt you to replace them, replace the files. This should probably not be the case, but it might happen if you've already modded Minecraft.

**IMPORTANT NOTE:** If you already installed mods from this server and you are installing new mods, **MAKE SURE YOU DELETE THE OLD ONES FIRST.** I may change versions of mods at any time an you might end up having duplicate mods. All .jar files for mods should be in `mods\1.12.2` (not in the main `mods` folder, but instead the folder named `1.12.2` that's *inside* of the mods folder.)

# Congratulations! You're done!
After you've finished the steps above, you should be able to join the server.

When you enter the game, you will spawn in a dark box with a pressure plate at the bottom. If this pressure plate doesn't trip (teleporting you to the surface), try jumping a few times.

# Info

## Known Bugs
- At times you may randomly die out of nowhere and still have health. If this happens, **click Respawn, then re-log from the server.** This is a desync issue. You aren't actually dead, but if you don't click respawn and log back in, the server will think you're dead and you won't be able to do anything. **This bug has become incredibly rare, but it may still happen.**
- At other times, you may be unable to click Respawn after dying. If this happens, go to the Title Screen, log back in, and try respawning once more.

## Gamerules & Mechanics
When playing this server, several rules are set:
- PvP is OFF
- Fire ticking is OFF (no spread, but also no automatic extinguishing except for in rain)
- Mob Griefing is OFF
- Keep Inventory is TRUE
- Difficulty is NORMAL
- Betweenlands Decay is ON
- Betweenlands Corrosion is ON
- All Betweenlands Events are ON, but may be manipulated if there is any RP going on or something. This is generally avoided (so if we get a blood sky when people are RPing outside and don't want it, it may be disabled)

## The Betweenlands
**Here's a short comprehensive guide:** 
https://github.com/XanTheDragon/OriDiscordMCStuff/blob/master/GUIDE.MD

**Some important stuff:**
- https://the-betweenlands.fandom.com/wiki/Sap_Tree_Log
- https://the-betweenlands.fandom.com/wiki/Decay
- https://the-betweenlands.fandom.com/wiki/Mobs

## Other Features
- You can use `/mpm name yourNameHere` to set a custom name via MorePlayerModels. Please use this sparingly.

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

## Certain Mods Have Been Changed / Custom Made
### EtiCore
- Appends Spirit Guardians as a mob (which has no AI, as it is used in the Morph mod as a playermodel). 
- Appends a "Spirit Light" item, which can be used with OptiFine to glow so long as you hold it (It is recommended to have it in your off-hand. It does not show as a held item when you hold it, so it won't get in the way). *This requires dynamic lights to be on.*

### EnderZoo
- Basically every feature has been disabled. It's just here for the owls, which do not spawn naturally for the time being. This may not be enabled.

### Morph
- Since it is required that you use the Spirit playermodel on the server, this modified version of Morph ensures that you are using it.

### The Betweenlands
- Wights can no longer enter their volatile state (where they attack you as a ghost). This is due to incompatibilities with the spirit playermodel.
- By extension of above, Wights can no longer possess swamp hags to buff them.
- Biome colors are no longer hardcoded and instead reference vanilla foliage colors. This may be leveraged via a server resource pack in the future.
- Life Crystals can be recharged by right clicking with them. It will take 16 levels to bring a Life Crystal from 0% to 100% (Each level restores 6.25%)
