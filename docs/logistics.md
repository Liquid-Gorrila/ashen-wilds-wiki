# Logistics

Conveyor belts move items between machines without you carrying them. Belts need no power. Press R in the build menu to rotate a belt, transporter, filter or splitter before placing it; the ghost shows the arrow.

| Piece | What it does |
| --- | --- |
| Conveyor | Carries one item at a time in its arrow's direction, about 1.6 cells per second. Hands the item to whatever is in the next cell. |
| Transporter | Pulls one finished item out of the machine or storage behind it every 0.6 s and sends it forward. |
| Crosser | Passes items straight through in the direction they arrived, so two belt lines can cross. |
| Filter Belt | Items of its chosen type go straight on; every other item turns right. Press E on it to cycle the chosen item. Until you choose one, everything goes straight on. Shown as a cyan funnel with the chosen item's icon above it. |
| Splitter | Sends items alternately to its left and right. If one side is blocked, the item goes to the other. Shown as an orange junction. |
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

## Sorting with filters

A line only works if everything on it is accepted at the end: an item a machine will not take waits at the end of the belt and blocks everything behind it. Filter Belts fix this by pulling one item type off a mixed line.

Left and right are from the belt's point of view, looking the way its arrow points.

## Example: a self-running base

1. Build a Generator, load it with coal, and put a Coil nearby to reach further machines.
2. Quarry → conveyors → a **Filter Belt set to Copper Ore** → conveyors → **Kiln**.
3. From the filter's right side (everything that is not copper) → conveyors → **Storage** for stone and other ore.
4. Kiln → conveyors → a second **Storage**, which fills with copper bars.
5. Greenhouse → a **Filter Belt set to Wood** → Storage for timber; its right side → a second Storage for berries and vegetables.
6. To share one line between two chests, put a **Splitter** in front of them: it alternates items left and right.

Chain filters to sort several items: each one takes its own item and passes the rest on.
