# Survival

You have five meters in the top left of the screen: health, then stamina, hunger, thirst and cool side by side. Keep hunger and thirst up, stay out of the midday sun, and health mostly takes care of itself.

<div class="aw-stats" markdown>
<div><strong>10</strong><span>health</span></div>
<div><strong>11</strong><span>stamina</span></div>
<div><strong>100</strong><span>hunger</span></div>
<div><strong>100</strong><span>thirst</span></div>
<div><strong>100</strong><span>cool</span></div>
</div>

| Meter | How it works |
| --- | --- |
| :material-heart: Health | Lost to attacks, poison, starvation and thirst. After a hit you are invulnerable for 1.1 s. At 0, the run is over. |
| :material-lightning-bolt: Stamina | A roll costs 3 and a chop costs 4. Refills at 3.5 per second after a 0.6 s pause. |
| :material-food-apple: Hunger | Drains 0.32 per second at base: about 5 minutes from full to empty. The bar turns red below a quarter. |
| :material-water: Thirst | Drains 0.3 per second at base, but the sun and heat change that a lot (see below). The bar turns red below a quarter. |
| :material-white-balance-sunny: Cool | Refills on its own, but drains under the midday sun. Low cool makes you Overheated, and empty cool gives you Heatstroke. See [Heat and shade](heat.md). |

Point at a meter to see its value, how fast it's moving and everything that's speeding it up or slowing it down right now.

## What drains you faster

Your surroundings scale how fast each meter moves. Everything that applies multiplies together.

| When | Hunger | Thirst | Stamina refill |
| --- | --- | --- | --- |
| Daytime | | ×1.25 | |
| Night | | ×0.6 | |
| Scorching heat | ×1.3 | ×1.5 | |
| Sandstorm | ×1.5 | ×1.3 | |
| In a cave | | ×0.5 | |
| Thirst below a quarter (parched) | | | ×0.6 |
| Overheated (cool below a quarter) | | ×1.4 | ×0.5 |
| Hunger empty (starving) | | | ×0.5 |

**Scorching heat** is the open Desert, the Scorched Badlands and the Bloodfields during the day. The HUD reads "scorching". Out there by day, thirst empties in about 3 minutes, so plan your trips between water.

!!! tip "Get into the shade"
    Standing under an [Awning](heat.md#finding-shade), or right up against a tall building, cancels the heat. The midday sun also wears down your [cool](heat.md).

## Water

- **Oasis pools** are the only wild water in the desert. Use one (++e++) to drink your fill and top up your waterskins. Drinking your fill also leaves you [Refreshed](buffs.md) (thirst drains at half speed for 90 seconds) and cools you off. Your camp has a pool, and more lie deep in the living oases, the wet Mire most of all. A sandstorm silts pools up: you can drink, but not fill waterskins.
- **Waterskins:** a pool fills you up to 3 Water. Each restores 45 thirst and 20 cool.
- **Wells and condensers** make water at your base, and keep your crops watered. See [Water](water.md).
- **Food:** berries, vegetables, serum and elixir all restore a little thirst too. See [Food](food.md).
- ++f++ eats or drinks whatever you need most.

## Healing, starving and thirst

- **Regeneration:** while hunger and thirst are both at 60 or more, you heal 1 health every 10 seconds.
- **Food:** most foods heal you as well as filling you up.
- **Starvation:** at 0 hunger you lose 1 health every 5 seconds.
- **Dying of thirst:** at 0 thirst you lose 1 health every 4 seconds.
- **Poison:** a spitter's acid, or bad raw meat, poisons you: 1 health a second until it wears off. See [Buffs and ailments](buffs.md).

## Death

When health reaches 0 the run ends and your save is deleted. There's no respawn: start a new game from the title menu.
