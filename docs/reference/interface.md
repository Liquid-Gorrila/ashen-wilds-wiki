# Interface and settings

![The HUD on day 1: vitals, objective, compass, day and biome, and the inventory bar](../assets/images/start.png)

## The HUD

| Where | What it shows |
| --- | --- |
| Top left | A large health bar, with stamina and hunger bars side by side beneath it. Hunger turns red below a quarter. |
| Under the bars | Active [buffs](../survival/buffs.md), each with its seconds remaining |
| Left side | Your current [objective](../start/objectives.md), its part, and progress when a goal needs several |
| Top centre | The compass. During a boss fight, the boss's name and health bar sit just below it. |
| Top right | The day number, the biome you're in ("scorching" in desert heat, "Sandstorm!" during a storm, "Cave" underground), and a sky dial for the time of day: the sun arcs across by day and the moon by night, and the sky turns orange at dawn and red at dusk |
| Middle of the screen, below the compass | Short messages: warnings, finished goals and events |
| Left, lower | Item pick-up notices |
| Bottom centre | What you can use nearby, then your inventory bar (hidden while you carry nothing). Point at an item to see its name and count. |

The title screen shows only the menu; the HUD appears when you start playing.

## In the world

- **Gold outline:** the thing you'd use with ++e++ (a chest, bush, merchant, machine, racer, relic or cave) gets a pulsing gold outline. The bottom of the screen says what using it will do.
- **Progress bubble:** a small bubble over a working quarry, kiln, refinery, greenhouse or bio lab fills up as it works through its current item. Over a planter, it fills as the crop grows towards its next stage.
- **Red no-power icon:** a machine that wants power but has none. See [Power](../building/power.md).

## Compass

The compass ribbon covers a full circle, with north (screen up) in the middle. Markers sit at their direction from you, labelled with their distance.

| Marker | Points to |
| --- | --- |
| :material-home:{ style="color:#6fcf7a" } Home | Your workbench, or your first campfire if you have no workbench yet |
| :material-tent:{ style="color:#e8a33d" } Camp | The starting camp. Hidden once Home is right next to it. |
| :material-motorbike:{ style="color:#e8743a" } Racer | The nearest Speed Racer nobody is riding |
| :material-skull:{ style="color:#e05050" } Boss | The [Dust Jumper](../combat/boss.md), while it's hunting you |
| :material-pillar:{ style="color:#d99bff" } Relic | The nearest [ancient relic](../world/relics.md) you haven't beaten yet, up to three regions away |
| :material-exit-run:{ style="color:#f0d890" } Exit | Inside a [cave](../world/caves.md), the way back up. The only marker underground. |

Markers you're standing on disappear. When two labels would overlap, one drops to a second row.

## Title menu

The game opens with a short StonePath Games splash. Press any key or click to skip it.

| Option | What it does |
| --- | --- |
| Continue (day N) | Loads your saved run. Only shown when a save exists. |
| New game | Starts a fresh world and deletes any old save. |
| Settings | Opens the settings screen. |
| Quit | Closes the game. |
| Credits | Who made the art, sound and engine. |

## Pause menu

| Option | What it does |
| --- | --- |
| Resume | Back to the game |
| Save game | Saves now, then resumes |
| Settings | Opens the settings screen |
| Save and quit to title | Saves, then returns to the title menu |

The pause screen also shows the day, how many raiders you've slain and any relic [boons](../combat/boons.md) you have.

## Pack

Press ++i++ to open your pack. The world waits while it's open.

The grid shows everything you carry, with counts, and the header totals it up. The panel beside it describes the chosen item: where it comes from, what it does when eaten, burned in a generator, smelted or thrown, and everything it's used for (buildings, blade upgrades and station crafts).

Choose a food and press ++e++ to eat that one rather than the best food. Plain food won't be eaten when your hunger and health are both full, but serum and elixir still will, for their buffs. Choosing a bottle and pressing ++e++ closes the pack and throws it.

## Build menu

![The build menu on the Production tab, with the Quarry selected](../assets/images/build-menu.png)

The header shows the current category and its number (for example 3/6). Each row says **ready** when you can afford it and are near the right station, or **needs** and a station name when you aren't. Below the list: the selected item's cost (green when you can afford it, red when you can't), what it does, and the keys.

## Settings

Settings are remembered between sessions. Sliders show their level as a percentage, and the switches read On or Off.

| Setting | Default | Effect |
| --- | --- | --- |
| Master volume | 80% | All sound |
| Music volume | 35% | The themes for day, night, caves, sandstorms and boss fights |
| Effects volume | 80% | Combat, footsteps, machines, campfires, wind, the desert ambience, menus and everything else |
| Fullscreen | Off | Fullscreen or windowed |
| Screen shake | On | Camera shake on hits and explosions |
| Show FPS | Off | Frame-rate counter in the top right (also ++f3++) |
| Show compass | On | Hides or shows the compass |
| Show objectives | On | Hides or shows the objectives panel |
