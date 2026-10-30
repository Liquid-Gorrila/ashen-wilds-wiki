# Logistics

Conveyor belts move items between machines without you carrying them. Belts need no power. Press R in the build menu to rotate a belt before placing it; the ghost shows the arrow.

| Piece | What it does |
| --- | --- |
| Conveyor | Carries one item at a time in its arrow's direction, about 1.6 cells per second. Hands the item to whatever is in the next cell. |
| Transporter | Pulls one finished item out of the machine or storage behind it every 0.6 s and sends it forward. |
| Crosser | Passes items straight through in the direction they arrived, so two belt lines can cross. |
| Storage | Accepts any item a belt delivers, with no limit. Press E to take everything. |

## Delivery rules

- A belt delivers into a machine only if that machine accepts the item and has room. Otherwise the item waits at the end of the belt.
- Machines push their output onto any adjacent belt that leads away from them, never onto one that points back in.
- A belt never accepts items from the cell it feeds into.

## What each machine accepts by belt

| Machine | Accepts |
| --- | --- |
| Kiln | Copper, Gold and Cobalt Ore |
| Fuel Refinery | Coal |
| Bio Lab | Vegetables, Bone |
| Generator | Fuel, Coal, Wood |
| Storage | Anything |

## Example: a self-running base

Belts have no item filters, so a line only works if everything on it is accepted at the end. A quarry's mixed output must go into Storage, never straight into a Kiln.

1. Build a Generator, load it with coal, and put a Coil nearby to reach further machines.
2. Quarry → conveyors → Storage. Empty this chest by hand and load the ore into the Kiln.
3. Kiln → conveyors → a second Storage, which fills with bars.
4. Greenhouse → conveyors → a third Storage, which fills with food and wood.
