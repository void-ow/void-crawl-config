# Void's Config for Dungeon Crawl Stone Soup v. 0.21

_Eventually this readme will not look like shit_

## What's in it:

### 0. [Main file](../config/main.txt)
File loading every other config file.

Allows for enabling/disabling specific parts of the config
### 1. [Colors for items](../config/colors/items.txt)
Adds color codes for items, depending on their usefullness
### 2. [Colors for messages](../config/colors/messages.txt)
Adds color coding for messages, depending on their usage/importance
### 3. [Damage Log](../config/scripts/damage.txt)
Adds per-turn damage log, displaying changes in HP, Mana and XP
### 4. [Open Skills](../config/scripts/openSkills.txt)
Opens skills at game start, redundant if you use advancedOptioneering
### 5. [Autofight Settings](../config/settings/autofight.txt)
Various autofight changes - autothrow, autocast, etc.
### 6. [Automacro Settings](../config/settings/automacro.txt)
Automatically creates macros for buttons 1-4 F1-F2 for the current background's spells

**will not work without spellslots**
### 7. [Autopickup Settings](../config/settings/autopickup.txt)
Various autopickup settings

Armor/weapon improvements autopickup **currently in beta, please let me know if it does stupid shit**
### 8. [Autotravel Settings](../config/settings/autotravel.txt)
Various autotravel-related settings, additional ignores while autotravelling
### 9. [Basic Settings](../config/settings/basic.txt)
Various basic settings - race-specific butchering, changes to interace, etc.
### 10. [Chardump Settings](../config/settings/cdump.txt)
Additional data to chardump, copy of HDA's
### 11. [More-prompt settings](../config/settings/more.txt)
Adds additonal messages to prompt *more*, copy of HDA's
### 12. [Spellslot settings](../config/settings/more.txt)
Spellslots for every basic book
### 13. [Font size changes](../config/settings/font/size.txt)
Fluff, changes the size of the font to fit more on screen

## How to install
1. Unpack the config folder into crawl/settings folder
2. Add include = config/main.txt to the init.txt

## Acknowlegements

Big shoutout to HDA (https://github.com/HilariousDeathArtist/DCSSConfigFile), for his config was basically the basis for this one. A lot of things have been changed, but more/autotravel/cdump are basically his.

## Yo, what's the plan?
1. Fixing up this readme
2. Reevaluate colors
3. Polish Damage Log a bit - remove +1 HP spam
4. Test up autopickup and defenitely change things up for armor autopickup
5. Probably change things up in More - remove obsolete entries, add new ones
6. Add spellslots for every spell in the game
