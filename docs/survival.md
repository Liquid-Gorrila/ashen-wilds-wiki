# Survival

You have three meters, shown top-left: health, stamina and hunger. Keep hunger up and health takes care of itself.

| Meter | Maximum | How it works |
| --- | --- | --- |
| Health | 10 | Lost to attacks and starvation. After a hit you are invulnerable for 1.1 s. |
| Stamina | 11 | A roll costs 3, a chop costs 4. Refills at 3.5 per second after a 0.6 s pause. |
| Hunger | 100 | Drains 0.32 per second, about 5 minutes from full to empty. |

- **Regeneration:** while hunger is at 60 or more and you are hurt, you heal 1 health every 10 seconds.
- **Starvation:** at 0 hunger you lose 1 health every 5 seconds.
- **Desert heat:** in open Desert or Scorched Badlands during the day, hunger drains 1.6× faster and the HUD reads "scorching". Standing near any of your structures counts as shade and removes the penalty.
- **Rolling:** a roll makes you invulnerable for 0.35 s, enough to dodge most blows and the Dust Jumper's slam.

## Food

Press F to eat. You always eat the best food you carry, in this order:

| Food | Hunger restored | Health restored | How to get it |
| --- | --- | --- | --- |
| Elixir | 15 | 6 | Alchemy Table |
| Serum | 25 | 3 | Bio Lab |
| Cooked Meat | 35 | 2 | Campfire, chests, merchants |
| Vegetables | 22 | 1 | Planter, Greenhouse |
| Berries | 12 | 0 | Bushes, Greenhouse |
| Raw Meat | 8 | 0 | Hunting |

See [Items and how to get them](items.md#food) for every food source.
