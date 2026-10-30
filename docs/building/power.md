# Power

Most machines and all powered defenses need electricity. Power structures that stand close together link into a network, drawn as faint cyan cables, and every machine plugs into the nearest network within reach.

| Structure | Role | Details |
| --- | --- | --- |
| :material-engine: Generator | Produces 4 | Burns fuel you load or deliver by belt: each Fuel lasts 60 s, Coal 25 s, Wood 10 s. Only burns while power is needed or a battery has room. |
| :material-solar-panel: Solar Panel | Produces 2 | Free, but only by day, and only 30% during a [sandstorm](../world/sandstorms.md). |
| :material-battery-high: Battery Bank | Stores up to 300 | Charges from surplus and covers shortfalls at night. Its lights show the charge. |
| :material-transmission-tower: Coil | Relay | Links power across a long gap. |

## Range

| Link | Reach |
| --- | --- |
| Power structure to power structure | about 6 cells |
| Either end is a Coil | about 12 cells |
| Machine to the nearest power structure | about 6 cells |

## Shortages

When demand is more than supply plus battery charge, the network browns out instead of failing completely:

1. Defenses are powered first.
2. Then the cheapest machines, until the power runs out.
3. Everything left over switches off and shows a blinking red no-power icon.

!!! tip "Idle costs nothing"
    Defenses only draw power while a raider is in range, and machines only while they have work to do. An idle turret is free.
