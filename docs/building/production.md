# Production

Powered machines work in cycles, holding up to 12 items in their input and output buffers. A full output buffer stops the machine until it's emptied.

![A small base: a quarry feeding a filter belt and kiln, a greenhouse, solar panels, a generator and battery, all linked by power cables](../assets/images/factory.png)

Feeding
:   Use a machine to load inputs from your inventory, or deliver them by [conveyor](logistics.md).

Emptying
:   Use a machine to collect its output, or place a conveyor next to it pointing away. Machines push finished goods onto any such belt automatically.

## Powered machines

| Machine | Cycle | Power | Input | Output |
| --- | --- | --- | --- | --- |
| Quarry | 5 s | 2 | — | Stone (about 60%) or a local ore (about 40%). 4% chance of a deep seam: gold, cobalt or amethyst. |
| Advanced Quarry | 4 s | 3 | — | Local ore (60%), coal (15%) or stone. 10% chance of a deep seam. |
| Kiln | 5 s | 2 | 1 Copper, Gold or Cobalt Ore | 1 matching bar |
| Fuel Refinery | 6 s | 2 | 2 Coal | 1 Fuel |
| Greenhouse | 12 s | 1 | — | 2 Berries (40%), 1 Vegetables (30%) or 2 Wood (30%) |
| Bio Lab | 8 s | 2 | 1 Vegetables + 1 Bone | 1 Serum |

!!! info "Quarries dig what's under them"
    A quarry's local ore depends on the biome it stands in (see [biomes](../world/index.md#biomes)). Build quarries in different biomes to get different ores. Coal comes from quarries in the Desert or the Badlands.

## Unpowered

| Structure | What it does |
| --- | --- |
| Planter | Grows a random crop through three stages, about 45 s each. Harvest when ripe for 2 Vegetables. |
| Campfire | Cooks up to 5 Raw Meat into Cooked Meat at a time. Also lights the area and makes you [Rested](../survival/buffs.md). |
| Forge, Advanced Forge | Upgrade your sword. See [Sword upgrades](defense.md#sword-upgrades). |
