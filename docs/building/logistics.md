# Logistics

Conveyor belts move items between machines so you don't have to carry them. Belts need no power. Rotate a belt, transporter, filter or splitter in the build menu before placing it; the ghost shows the arrow.

| Piece | What it does |
| --- | --- |
| Conveyor | Carries one item at a time in its arrow's direction, about 1.6 cells per second, and hands it to whatever is in the next cell. |
| Transporter | Pulls one finished item out of the machine or storage behind it every 0.6 s and sends it forward. |
| Crosser | Passes items straight through in the direction they arrived, so two belt lines can cross. |
| Filter Belt | Items of its chosen type go straight on; everything else turns right. Use it to cycle the chosen item. Until you choose one, everything goes straight on. Looks like a cyan funnel with the chosen item's icon above it. |
| Splitter | Sends items alternately left and right. If one side is blocked, the item goes to the other. Looks like an orange junction. |
| Storage | Accepts any item a belt delivers, with no limit. Use it to take everything. |

Left and right are from the belt's point of view, looking the way its arrow points.

## Delivery rules

- A belt delivers into a machine only if the machine accepts the item and has room. Otherwise the item waits at the end of the belt.
- Machines push their output onto any adjacent belt that leads away from them, never onto one pointing in.
- A belt never accepts items from the cell it feeds into.

| Machine | Accepts by belt |
| --- | --- |
| Kiln | Copper, Gold and Cobalt Ore |
| Fuel Refinery | Coal |
| Bio Lab | Vegetables, Bone |
| Generator | Fuel, Coal, Wood |
| Storage | Anything |

## Sorting with filters

A line only works if everything on it is accepted at the end. An item a machine won't take waits at the end of the belt and blocks everything behind it. Filter Belts fix this by pulling one item type off a mixed line. Chain filters to sort several items: each takes its own and passes the rest on.

!!! example "A self-running base"
    1. Build a Generator, load it with coal, and add a Coil to reach further machines.
    2. **Quarry** → belts → **Filter Belt (Copper Ore)** → belts → **Kiln** → belts → **Storage** for copper bars.
    3. From the filter's right side (stone and other ore) → belts → a second **Storage**.
    4. **Greenhouse** → **Filter Belt (Wood)** → Storage for timber; its right side → a Storage for berries and vegetables.
    5. To share one line between two chests or two kilns, put a **Splitter** in front of them.
