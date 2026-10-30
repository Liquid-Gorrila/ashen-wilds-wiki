# Survival

You have three meters in the top left of the screen: health, stamina and hunger. Keep hunger up and health mostly takes care of itself.

<div class="aw-stats" markdown>
<div><strong>10</strong><span>health</span></div>
<div><strong>11</strong><span>stamina</span></div>
<div><strong>100</strong><span>hunger</span></div>
</div>

| Meter | How it works |
| --- | --- |
| :material-heart: Health | Lost to attacks and starvation. After a hit you are invulnerable for 1.1 s. At 0, the run is over. |
| :material-lightning-bolt: Stamina | A roll costs 3 and a chop costs 4. Refills at 3.5 per second after a 0.6 s pause. |
| :material-food-apple: Hunger | Drains 0.32 per second: about 5 minutes from full to empty. The bar turns red below a quarter. |

## Healing and starving

- **Regeneration:** while hunger is at 60 or more, you heal 1 health every 10 seconds.
- **Food:** most foods heal you as well as filling you up. See [Food](food.md).
- **Starvation:** at 0 hunger you lose 1 health every 5 seconds.

## Desert heat

In the open Desert or the Scorched Badlands during the day, hunger drains 1.6 times faster and the HUD reads "scorching".

!!! tip "Your base is shade"
    Standing within a few cells of any structure you've built cancels the heat penalty.

## Buffs

Resting by your campfire, eating Serum and eating Elixir each grant a timed boost. See [Buffs](buffs.md).

## Death

When health reaches 0 the run ends and your save is deleted. There's no respawn: start a new game from the title menu.
