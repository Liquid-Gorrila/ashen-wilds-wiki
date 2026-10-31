# Saving

Ashen Wilds keeps a single save slot. Continue your run from the title menu.

## When the game saves

- :material-weather-sunset-up: **Automatically at every dawn.**
- :material-pause: **From the pause menu:** *Save game*, or *Save and quit to title*.

## What is saved

The world is rebuilt from its seed, so the save only records what you changed:

- every structure you built, with its health, contents, fuel, battery charge and filter setting
- trees you felled, deposits you mined, chests you opened and bushes you picked
- caves you've silenced
- Speed Racers and their fuel
- your position, health, stamina, hunger, thirst, active buffs and ailments, and inventory
- sword upgrades, the day and time, raiders slain and tutorial progress

Raiders on the map aren't saved; a loaded game starts with none nearby. If you save in a cave, you load at its entrance.

## Death is permanent

!!! danger
    When you die, your save is deleted. Starting a **New game** also replaces any existing save.

## Where the files live

On Windows, the save and settings are in `%APPDATA%\Godot\app_userdata\Ashen Wilds\` as `ashen_save.json` and `settings.cfg`.
