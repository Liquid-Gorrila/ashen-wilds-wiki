# Power

Most machines and all powered defenses need electricity. Power structures that stand close together link into a network, drawn as faint cyan cables, and every machine plugs into the nearest network within reach.

| Structure | Role | Details |
| --- | --- | --- |
| Generator | Produces 4 power | Burns fuel items you load (E) or deliver by belt. Each Fuel lasts 60 s, Coal 25 s, Wood 10 s. Only burns while power is needed or a battery has room. |
| Solar Panel | Produces 2 power | Free, but only during the day, and only 30% during a [sandstorm](sandstorms.md). |
| Battery Bank | Stores up to 300 | Charges from surplus, covers shortfalls at night. Its lights show the charge level. |
| Coil | Relay | Links power across a long gap. |

## Range

| Link | Reach |
| --- | --- |
| Power structure to power structure | about 6 cells |
| Either end is a Coil | about 12 cells |
| Machine to the nearest power structure | about 6 cells |

## Shortages

When demand exceeds supply plus stored battery power, the network browns out instead of failing completely:

1. Defenses are powered first.
2. Then the cheapest machines, until the power runs out.
3. Everything left over switches off and shows a blinking red no-power icon.

Defenses only draw power while a raider is within their range, so an idle turret costs nothing. Machines only draw power while they have work to do.
