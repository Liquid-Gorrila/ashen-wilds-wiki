# Power

Most machines and all powered defenses need electricity. Power structures that stand close together link into a network, drawn as faint cyan cables, and every machine plugs into the nearest network within reach.

| Structure | Role | Details |
| --- | --- | --- |
| :material-engine: Generator | Produces 4 | Burns fuel you load or deliver by belt: each Fuel lasts 60 s, Coal 25 s, Wood 10 s. Only burns while power is needed or a battery has room. |
| :material-solar-panel: Solar Panel | Produces 2 | Free, but only by day, and only 30% during a [sandstorm](../world/sandstorms.md). |
| :material-battery-high: Battery Bank | Stores up to 300 | Charges from surplus and covers shortfalls at night. It sparks while it holds charge. |
| :material-transmission-tower: Coil | Relay | Links power across a long gap. |

## Range

Reach is a distance on screen, so on the diamond grid it covers more rows up and down than tiles side to side.

| Link | Reach | Side to side | Up and down |
| --- | --- | --- | --- |
| Power structure to power structure | 80 px | about 5 tiles | about 10 rows |
| Either end is a Coil | 160 px | about 10 tiles | about 20 rows |
| Machine to the nearest power structure | 100 px | about 6 tiles | about 12 rows |

!!! tip "Let the rings show you"
    While you place a machine or a power structure, blue rings show how far each of your power structures reaches, and a green cable previews what it will connect to. A machine whose ghost turns amber would sit out of reach. You can still build it, but you'll get a warning.

## Why a machine has no power

Use a machine (++e++) to read its status, or look at its prompt as you walk up:

| Status | What to do |
| --- | --- |
| too far from a generator | Move it inside a power structure's reach (dismantle it with ++x++ for a full refund, then rebuild), or bridge the gap with a Coil. |
| the generator needs fuel | Load Fuel, Coal or Wood into the generator, or feed it by belt. |
| the solar panels need sun | Wait for day, or add a battery or generator for the night. |
| not enough to go round | Add generators, solar panels or batteries. See Shortages below. |

A generator with fuel but nothing connected reads "fuelled, nothing drawing power": it waits, burning nothing, until a machine plugs in.

## Shortages

When demand is more than supply plus battery charge, the network browns out instead of failing completely:

1. Defenses are powered first.
2. Then the cheapest machines, until the power runs out.
3. Everything left over switches off and shows a blinking red no-power icon.

!!! tip "Idle costs nothing"
    Defenses only draw power while a raider is in range, and machines only while they have work to do. An idle turret is free.
