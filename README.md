# Cozy Cafe Modpack
This repository is purely for the notes related to the Cozy Cafe Modpack patch notes, it's download link, and instructions on installation.

## Table of Contents
- [Patch Notes (0.6.2)](#patch-notes-v062)
- [Patch Notes (0.6.1)](#patch-notes-v061)
- [Patch Notes (0.6)](#patch-notes-v06)
- [Patch Notes (0.5) (Initial Release)](#patch-notes-v05)
- [Download Links](#download)
- [Installation Instructions](#installation)

<details>
  <summary><h2>Patch Notes (v0.6.2)</h2></summary>

### Server Configuration Changes
- The virus has altered! Zoids that have lived long enough appear to have become deaf, but their vision has become rapidly better. They act more like visual hunters now.
- Zoids do not appear to migrate as they once have, repopulating areas. It seems, for now, it is possible to clear out safe spaces. Who knows for how long, though.

### Mod Changes
- **Shake It Up** and **Just Sleep** mods have been removed from the server. Neither work as intended and throw errors on boot-up, confusing players.
- **More Bags** has been patched to properly address an experience issue causing errors on boot-up. This error was not player-affecting and generally could be ignored, but better to have it patched out for clarification.
- The *Make Sack* recipe from **More Bags**, specifically, had its experience application altered. It should now properly award Tailoring experience.

### Removing Mods 📌
Two mods have been **removed** from this patch. This is not something I can do for you, so I will note below how to accomplish this. Note, you can avoid this entirely by deleting ALL mods from your system and applying the Full modpack, as well.
1. Open your Mods folder (based on your operating system, see [Installation Instructions](#installation) below for where to find this)
2. Select and delete the following folders: **ShakeItUp**, **just-sleep**, and **More Bags**.
3. Download the *Modpack Patch* found at [Download Links](#download).
4. Extract the modified version of **More Bags** from the modpack patch ZIP and add it to your Zomboid Mods folder from step 1.

![Installation Example](https://github.com/Ashlay-Paladin/CozyCafePZModpack/blob/main/RemoveMods_0.6.2.png?raw=true)

</details>

<details>
<summary><h2>Patch Notes (v0.6.1)</h2></summary>
  
### Mod Changes
- Reading skill books will grant an experience bonus **and** a skill multiplier.
- Sleep with Friends should now properly allow you to keep sleeping after you are fully rested
</details>
<details>
<summary><h2>Patch Notes (v0.6)</h2></summary>

### New Mods
**Chip a Stone**: Allows players to use Hammer or Stone Hammer to turn regular Stone into Chipped Stone for spears and crafting.

**Read While Walking**: Allows players to read.. while walking. Press R to cancel reading (hotkey is configurable).

**Medicine Moodles**: New Moodles to visualize the effects of medicine, such as Beta Blockers and Antidepressents. Should help visualize when you need to take more medicine.

**Just Sleep**: Allows players to sleep regardless of pain, tiredness, panic, or when they last attempted to sleep. Prevents automatically waking up so everyone can wake at the same time.

**Sleep on It**: Sleeping slowly reduces your depression and anxiety.

**Sleep with Friends**: Adjusts sleep formula for recovery. Shortens the time necessary to sleep to recover fatigue.

**Nocturnal Zombies**: Updates to Zoid behavior at different times of night. More specific notes below.

**Reading is not Boring**: Reading *any* book will reduce boredom, including skill manuals and technical magazines.

**Read Faster While Sitting**: Plant yourself on the ground with a good book! Your read time will increase. Reading as a vehicle passenger has the same effect.

**Rain Wash**: Rain will effectively wash your character and vehicle.

**True Actions**: A series of several mods that add emotes to the game. This will also allow you to sit and lay down on furniture.

**True Crouching**: Sneaking and shooting while crouched will have better animations.

### Server Changes
- Sleeping should now take less time to reduce fatigue. It should also help with stress and depression.
- Zoids become faster, strong, and more aggressive as the night progresses from 10PM to 5AM, but begins to taper off between 5AM - 8AM.
- Due to the new reading options and bonuses, base reading speed has been decreased from 1.15 minutes per page to 2.45 minutes per page.
### Documentation Changes
- A Patch ZIP will be available for those who have already installed the original mods. This will include only the new mods and be a much smaller download.
- An updated ZIP containing ALL mods will be available for anyone joining new.

</details>
<details>
<summary><h2>Patch Notes (v0.5)</h2></summary>

### General Configuration
- Enjoy 12 Additional Character Trait points during character creation! These will combine with the points already provided if you do not choose a profession. This should allow you to experiment with more traits!
- Global Chat has been disabled. Only local, faction, and radio style chats are enabled. Admins are able to utilize specific server-wide chats, if needed.
- Regardless of spawn point chosen, players will spawn in front of the Fire Hall in Rosewood.
- PvP is enabled by default. You will not be specifically indicated in any way.
- Currently, there is a 16 player limit on the server. I do not anticipate this will be an issue, but if so, it can be expanded in the future.
- Every 48 in-game hours, any container that has no items in it will spawn new items. These containers must not be player built OR contained in a building that has player construction (barricades, etc.).
- Due to changes made to skill books, the speed of reading has been slightly lowered from 1.0 to 1.15 minutes per page.
- Your survivor will get tired and require sleep. How often is largely dependent on your traits. You should be able to sleep on beds and larger furniture items, such as a couch.
- Trash Bins can be used to delete items. A "Delete All" button should be available on any trash bin. These items cannot be restored in any way.
- Players are capable of knocking each other when running through one another.
- Starting date is now May 1 at 7am, as opposed to mid-July (the default)
- Water and Electric shutdown has been extended from 0-30 days, to 2-6 months, although the exact time and date is still random.

### Zoids
- Zoids are fast, but weak and fragile.
- Zoid numbers are greater than normal!
- Zoids are much better at hearing than they are at seeing!
- Zoids can lose focus more easily if you cut off their line of sight.
- Zoids are more active at night. During the day they are slower.

### Mods
**AmmoCraft**
- Allows players to craft ammunition using casings, bullet tips, and gunpowder.
- Has compatibility with the Firearms mod, detailed further down

**Authentic Z**
- Adds more zombie outfits and models that were unused by Indie Stone
- Adds new zombie outfits akin to the George Romero style of zombie
- Adds several new features, such as Fat Zombies, new clothes, backpack attachments, clown zombies, and additional map areas, such as a Crystal Lake camp near Riverside, where horror icons may be hanging out.

**Better Sorting**
- Adds more categories to items for more appropriate sorting of items.

**Backpack Attachments**
- Allows players to find and upgrade backpacks with the ability to attach items such as water bottles and walkie talkies.

**Better Clothing Info Comparison**
- Allows players to view all information related to clothing, such as insulation and protection levels.

**Brita's Armor Pack**
- Additional Armor and Clothing options

**Broken Arm**
- Adds a new trait at character start for Broken Arm. Start with a broken arm in a splint for additional trait points.

**Common Sense**
- Adds various changes to the game, such as being able to craft sheets from scraps, open cans with various objects, among others.

**Dante Collectables**
- Adds new items, such as weapons and plush animals, to be found about the map

**Drunken Traits**
- Adds more traits related to drinking. Be a Light Drinker who is much more susceptable to alcohol, or a Heavy Drinker who is much less affected.

**Firearms**
- Adds several new firearms to the game for players to find and maintain

**First Aid Overhaul**
- Greatly expands the First Aid skill, adding new medicines and treatment options that are unlocked as your First Aid skill increases. Test on zoid corposes to further your first aid.
- Earn First Aid much faster by performing medicine on other players.
- The version used on this server does NOT have the antizen syringe, which instantly heals the Knox Virus.

**First Aid Vaccines**
- Expands the First Aid skill to allow for the development of vaccines. Take blood samples from fallen zoids, boil the samples, and put the result into syringes to administer to others.
- Vaccines are more potent and protect better the higher your First Aid level.
- Vaccines do not CURE the Knox virus, but prevent it. More potent vaccines have a higher level of protection, but your protection is not permanent.

**Fluffy Hair**
- Adds hair models and rebuilds the hair system.
- Used by other mods in this list to expand the hair options in-game

**Hemophilia**
- Adds a new trait that makes stopping bleeding take longer
- Extreme Hemophilia requires specific medicine to stop bleeding

**Immersive Lore**
- Find Tattered Sheets littered throughout Kentucky. Read them for lore related to the various peoples affected by the Knox virus.

**Improved Hair Menu**
- UI changes to expand on character creation and hair stylings

**More Traits**
- Many more positive and negative traits added to character creation

**Moodle Quarters**
- Changes the moodles to add more corners (up to a full square) to show how far along your moodle has progressed.

**More Bags**
- Additional bag types to be found, including the Fireman's Backpack, Ruck Sack, and Sling bag

**Physiks Data and Sync Optimizer**
- Makes packet improvements in the backend to help prevent desyncing between players, as well as various other network-related improvements.

**Profession Framework**
- Provides framework for new professions and changes to existing professions. Does nothing on its own.

**Schizophrenia Trait**
- See and hear things that may or may not be there. More stress means hallucinations are more likely.
- Night terrors and attacks may make it difficult to sleep when untreated.
- Seeing a comrade die with this trait will immediately place you into mental breakdown
- Treat yourself with Chlorpromazine to keep hallucinations at bay, but careful not to overdose

**Schoolbags Bundle**
- Modify your schoolbag with new styles using the crafting menu

**Shake It Up**
- Adds new clothing item to the game

**Simple Skill Books**
- Changes how skill books work. Finishing a skill book provides a block of experience. However, it removes the skill gain multiplier that books previously provided.

**Simple Traits**
- Adds several new traits to choose from during character creation

**Spongie Clothing**
- Adds many new clothing items to the game

**Spongie Hair**
- Adds various new hair styles to character creation and hair styling menus

**Spongie Hair API**
- Provides framework for expanding hair system. Does nothing on its own.

**Spongie Character Customization**
- Expands the character creation models to improve fidelity and options

**Spongie Open Jackets**
- Wear your jacket around your hips or open them up

**Stat Tweaks Library**
- Provides a framework for other mods to extend and change skill values

</details>

## Download
- [Full Modpack (v0.6.2)](https://mlcgaming-my.sharepoint.com/:u:/g/personal/ashlay_cozycafe_org/EV3_If9752hPjXQqdjNah-YB_D9CM9UwPXFZSW4lAxKKUw?e=T247q0)
- [Modpack Patch (v0.6 to v0.6.2)](https://mlcgaming-my.sharepoint.com/:u:/g/personal/ashlay_cozycafe_org/EUy7yNbw-_1CiJ5YL9aFjqQBDSQ9DnHNwsIuzUZC6DNu7g?e=42ybFX)

## Installation
Unpack the ZIP file and drag all folders in the 'mods' folder into your own mods folder location. This will depend largely on your installation, but the default locations tend to be as listed below.
- NOTE: These mods are NOT installed in your SteamApps program folder! If you place them in the mods folder inside of SteamApps, the modpack will NOT work!
![Installation Example](https://github.com/Ashlay-Paladin/CozyCafePZModpack/blob/main/ScreenMods.png?raw=true)

📌 **Windows Default Mod Folder:**
```
C:\Users\%username%\Zomboid\mods\
```

📌 **Linux Default Mod Folder:**
```
~/.zomboid/mods/
```

📌 **Mac Default Mod Folder:**
```
~/Zomboid/mods/
```

Once installed, your mods folder should look something like this (using Windows as an example, for the user AshlayPaladin):
```
C:\Users\AshlayPaladin\Zomboid\mods
├── AmmoCraft
├── AmmoCraft Firearms PATCH
├── Authentic Z - Current
└── etc...
```
