# Forgotten-Armament

[![Latest Release](https://img.shields.io/github/v/release/gibberlings3/Forgotten-Armament?include_prereleases)](https://github.com/Gibberlings3/Forgotten-Armament/releases/latest)
[![Github downloads (all releases)](https://img.shields.io/github/downloads/gibberlings3/Forgotten-Armament/total.svg?color=informational)](https://github.com/gibberlings3/Forgotten-Armament/releases)
![Language](https://img.shields.io/static/v1?label=language&message=english%20%7C%20french&color=informational)
![Platform](https://img.shields.io/static/v1?label=platform&message=windows%20%7C%20macos%20%7C%20linux&color=informational)

[A Gibberlings Three Mod](https://www.gibberlings3.net/)

**Author**: [morpheus562](https://www.gibberlings3.net/profile/11591-morpheus562/)

**On the Web**: [Home Page](https://www.gibberlings3.net/mods/items/forgotten_armament/) and [Discussion Topic](https://www.gibberlings3.net/forums/topic/33923-forgotten-armament-beta/)

## Introduction

Forgotten Armament aims to bring many low to mid-tier magical weapons, armors, and items into the games of Baldur's Gate: Enhanced Edition, Baldur's Gate II: Enhanced Edition, and the Enhanced Edition Trilogy (EET). The focus is to bring competitive mid-tier items, inspired by IWD and NWN2, into the game. One aspect of this mod is to ensure all weapons, armor, and items are equally represented and have steady progression paths for players throughout the series. Additionally throughout the games, many a mid-level enemy is poorly equipped with either non-magical or generically magical (+1 non-named) weapons and armor while similarly leveled players have +2/+3 weapons and gear. Forgotten Armament will provide many of these enemies with unique +1/+2/+3 weapons and gear providing for improved encounters with properly equipped foes.   

Through time, this has also branched into a more of an all-encompassing item mod for me. With this, I update all items to fall more in-line with their NWN2 versions (3.5 edition) and move away from the traditional Baldur's Gate style of setting an ability score to "x" amount and instead incrementing.

## Components

### Install Forgotten Armament Items

This installs all new items throughout the game. 

A list of the item descriptions is [here](https://github.com/Gibberlings3/Forgotten-Armament/blob/main/ITEM-DESCRIPTIONS.md).

A list of the item locations is [here](https://github.com/Gibberlings3/Forgotten-Armament/blob/main/ITEM-LOCATIONS.md).

### Update Existing Items

This component updates many weapons, armors, and items within the game. The current changes to items can be found [here](https://github.com/Gibberlings3/Forgotten-Armament/blob/main/UPDATED-ITEM-DESCRIPTIONS.md).

### Replace Boots of Speed (Paws of the Cheetah)

This component replaces Boots of Speed (Paws of the Cheetah) with other boot options.

### Add Breach Scrolls to Sorcerous Sundries

This component adds a couple of Breach scrolls to Sorcerous Sundries.

### Add Ruby Ray Scrolls to Trademeet Store

This component adds a couple Ruby Ray scrolls to one of the merchants at Trademeet.

### NWN2 Style Weapons

This component updates all weapons to match weapons in NWN2 to include damage, damage type, and critical threat range/damage. This includes all weapons added by mods. A detailed description of the new base weapon stats is [here](https://github.com/Gibberlings3/Forgotten-Armament/blob/main/NWN2_STYLE_WEAPONS.md).

Please Note: You can update the ini file prior to install if you do not want some of the weapon changes. All weapons are defaulted to update (1), but changing to 0 will ensure they remain untouched.

### Update Items Setting an Ability Score to Increment the Increase

This component updates all items to increment increases to ability scores instead of setting them. For example, the Belt of Hill Giant normally sets Strength to 19. This component will update the item to increment Strength by +2. All items that set ability scores, included those added by other mods, will be updated to increment with this component.

### Nerf APR Increasing One-Handed Melee Weapons

This component will update the following melee weapons to provide an extra 1/2 attack per round instead of one extra attack per round:
- Belm +2
- Kundane
- Ninjato of the Scarlet Brotherhood
- Monkey Paw of Discipline
- Long Sword of Action +4
- Vipers Edge +2

### Update Critical Hit Immunity

This component removes Critical Hit Immunity from Helmets and makes Shields immune to Critical Hits. Additionally, the following items will receive Critical Hit Immunity: Horned Helm of the Rock, Claw of Kazgaroth, Gargoyle Boots, Sensate Amulet, Blessed Bracers, Big Metal Unit, and Imaskari Bracer's of Immortality. Finally, the player will have the option to either allow or remove the Critical Hit Immunity many bosses and difficult foes have.

### Add Set Bonuses to Items

This component adds item set bonuses to many of the items throughout the series. When a character wears multiple items of the same set, the character will receive additional bonuses. A detailed descriptions of the sets can be found [here](https://github.com/Gibberlings3/Forgotten-Armament/blob/main/ITEM-SET-BONUSES.md).

PLEASE NOTE: AI scripts need to be enabled for this component to work.

### Armor Overhaul

This component is yet another armor overhaul component for players to choose. I understand there are a myriad of other options; however, I do things a little bit differently that may be enticing to some players. The biggest difference between my armor overhaul compared to others that exist is I am setting the armor user's Dex so it cannot go beyond the max Dex the armor allows, akin to 3.5e. Other mods will either reduce Dex by x amount or y percent while mine prohibits going over the max via repeating effects. This means the player can't equip Plate Mail which drops a character's max Dex to 14 then equip gloves of Dexterity to boost Dex to 18. It will still be limited and no amount of Dex increasing items, abilities, or spells will raise it beyond the max. Below will be the new values I am looking at: 

Full Plate Mail
- Max Dex: 15
- Physical Damage Resistance: +30% 

Plate Mail
- Max Dex: 14
- Physical Damage Resistance: +20% 

Scale
- Max Dex: 17
- Physical Damage Resistance: +15% 

Splint
- Max Dex: 15
- Physical Damage Resistance: +15% 

Chain
- Max Dex: 16
- Physical Damage Resistance: +10% 

Hide
- Max Dex: 18
- Physical Damage Resistance: +5% 
  
Studded Leather
- Max Dex: 20
- Physical Damage Resistance: +5% 

Leather
- Max Dex: 22
- Physical Damage Resistance: +5% 

PLEASE NOTE: Mithral and Elven chain armors allow an increase to max Dex by +1. 

## Compatibility

If you are upgrading from an earlier version of this mod, I recommend uninstalling all mod components and replacing all files with the new ones before doing a fresh install.

NWN2 Style Weapons, Update Items Setting an Ability Score to Increment the Increase, and my Armor Overhaul components should be installed AFTER any mods that add new weapons or items to the game.

Do not install the NWN2 Style Weapons component with other mods that alter weapons like Scales of Balance.

Do not install the Armor Overhaul component with other mods that perform an armor overhaul like Item Revisions and YARAS.

## Special Thanks

- Auve for support in the creation, inspiration, testing, and feedback for this mod.
- Bubb and CamDawg_G3 for their usual expertise, guidance, and assistance with coding.
- Suy for providing code to toggle critical hit immunity.
- Ardanis for ADD_SPELL_HEADER code in the macros.tpa.
