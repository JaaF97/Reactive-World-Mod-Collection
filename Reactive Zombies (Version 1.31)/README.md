# Reactive World: Reactive Zombies
Zombie attributes and behavior change with your actions. Too aggressive? Zombies become stronger and tougher. Too passive? They get smarter.

## Description:
After months of slaying zombie after zombie, you may feel like they're too weak, they don't respond to your actions, they're just walking/sprinting things wanting to eat your brain, but that's it. They won't change, their strength is the same at day 1 and day 365. If they are about to die, they behave the same as if nothing is happening. Well, time to change all that!.

This mod is part of my [**mod collection**](https://steamcommunity.com/sharedfiles/filedetails/?id=2969507692), which goal is to make the world as reactive to your actions and playstyle as possible. Check it out!.
[![](https://i.ibb.co/W5PkHbn/Promo.png)](https://steamcommunity.com/sharedfiles/filedetails/?id=2969507692)

## Mod Content & Mechanics:
Zombie attributes and behavior are now dynamic. Long gone are the days where zombies were just the same on day 1 and after 6 months. First, let me explain what mechanics the mod use for zombie attributes and behavior to change with time:
- **Demolisher Mode:** If a player isn't seen by zombies in a day, make the zombies more destructive (these stats revert a stage if the player is seen by zombies again);
- **Last Resort:** If a zombie is about to die, there's a chance it becomes stronger and faster, as a last resort to try to survive.
    - Last Resort can happen if a hit zombie's HP is below 100;
    - Base probability is 1%;
    - Probability increases if:
        - *Chasing Zombies:* If chased by 3 or less zombies, increase probability by 1%-2%-3% as zombies chasing goes down to 1;
        - *Player Health:* Increase chance by 2% for every 25% HP the player loses (up to 6%, 75% max HP loss);
        - *Player Weapon:* If the player hit the zombie with a ranged weapon, increase chance by 2%;
        - *Player Wounds:* Every unbandaged wound increases chance by 3% (12% max), if it's bandaged, it's 1% (4% max).
- **Player Playstyle:**
    - Zombies can become stronger on a X:1 kills/days survived ratio (customizable in Sandbox Settings);
    - Zombies can become tougher on a X:1 kills/days survived ratio (customizable in Sandbox Settings).
- **Smartness**
    - Every X days, if you don't kill zombies, all their behavior attributes (found in Advanced Zombie Options) will evolve.
- **Time elapsed:**
    - If enabled, each day there's a probability that zombie fire resistance increases to a maximum (customizable in Sandbox Settings). Zombies take x4 damage to fire at the start of the game;
    - If enabled, each day there's a probability that zombie mortality increases, making zombification faster (customizable in Sandbox Settings);
- **Time of Day:** At night, zombies see less;
- **Weather:** Zombies may be more blind, slower and less perceptive during stormy, foggy, rainy and snowy days.

Every zombie attribute (strength, toughness, cognition, etc.) and behavior depends on these mechanics.

## Compatibility
Reactive Zombies, as of Version 1.22, is now compatible with [CDDA_Zomboid](https://steamcommunity.com/sharedfiles/filedetails/?id=2914016243), [Night Sprinters](https://steamcommunity.com/sharedfiles/filedetails/?id=2683677702), [Personalized Zombies](https://steamcommunity.com/sharedfiles/filedetails/?id=2851295427) and [Random Zombies](https://steamcommunity.com/sharedfiles/filedetails/?id=2818577583).
- You **MUST** use [ModManager](https://steamcommunity.com/sharedfiles/filedetails/?id=2694448564) for this to work. This way we make sure these mods load before Reactive Zombies. Mod order should be:
    - other mods;
    - ...;
    - CDDA_Zomboid *OR* Personalized Zombies *OR* Random Zombies;
    - Night Sprinters *(if used)*;
    - The Darkness Is Coming! *(if used)*;
    - Reactive Zombies *OR* Reactive Zombies - CDDA_Zomboid Patch.
- **CDDA_Zomboid:** Enable the CDDA_Zomboid Patch version. **DO NOT ENABLE THE MAIN VERSION OF MY MOD. ONLY ENABLE THIS ONE**;
- **TDiC:** The Darkness Is Coming has a sandbox option called "Update zombie lore on start of events". If this is true, TDiC will handle zombie attributes, my mod will handle zombie behavior, else, my mod will handle Zombie Lore;
- **NS, PZ, RZ:** Built-in compatibility. All zombie attributes will be handled by them, zombie behavior will be handled by Reactive Zombies.

## More information
**Reactive Zombies** is currently **SP-only** compatible. For more information about
- Changelog;
- Compatibility;
- Mod Mechanics.
Check Reactive Zombies (Version x) in [**GitHub**](https://github.com/JaaF97/Reactive-World-Mod-Collection)

## Help! This doesn't work:
- Make sure you are subscribed and **ENABLED** my mod to my mod;
- If you started a world with this mod enabled, and the mod updated, don't worry, it's **save compatible**.

## Planned Features:
- **Add** save compatibility with already created saves; **DONE**
- **Add** compatibility with **POPULAR** mods. Suggest in the comments sections mods I should make compatible with this!;
- **Add** a new mechanic: If a player is badly injured, nearby zombies become faster to try to kill him (AKA Forced Last Resort);
- **Add** compatibility with other mods. These are mods that aren't that popular, so compatibility issues won't be solved as fast as popular mods.

# Support me:
[![](https://storage.ko-fi.com/cdn/brandasset/kofi_bg_tag_dark.png?_gl=1*p432j*_ga*NzY5MDg3NjU4LjE2ODI4NDA5MjU.*_ga_M13FZ7VQ2C*MTY4MjkxMjgyOC4zLjEuMTY4MjkxNDQ5OS41MS4wLjA.)](https://ko-fi.com/julianfvm)

# Credits:
- **The Indie Stone**, for making this beautiful game;
[](https://i.imgur.com/3oySiKz.gif)