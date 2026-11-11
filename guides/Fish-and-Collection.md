# Fish and Collection

> Based on MineSeedFishing 1.10.0 defaults. Check the server’s menus for customized requirements, prices, and rewards. Calendar dates use US/Eastern by default.

The default collection contains **273 species**: **231 year-round species** and **42 seasonal species**. Fish range from **Common** through **Uncommon, Rare, Epic, and Legendary**. Some discoveries require a higher fishing level or particular conditions. Luck improves your odds of rarer catches but does not guarantee them or bypass their requirements.

Each catch has its own length, physical weight, and sale value. Larger specimens of the same species are generally worth more, while rarity and species also matter. Legendary fish are the rarest (about 1 in 400 catches before luck), need fishing level 20, and are announced to the server by default.

Open `/fish catalog` to browse the **Fish Guide**. It shows each species’ realm, rarity, required level, habitat, time and weather conditions, possible size range, discovery status, total caught, and your largest recorded length. Each entry also says what the fish salvages into, such as **Salvages into 2 Tidal Fiber**, or **nothing** when it has no salvage yield. Seasonal fish begin with a **✦ Seasonal event:** line naming their event. A Nether or End fish limited to particular biomes names them as biomes, such as **Nether Wastes Biome** or **End Highlands Biome** (the central island reads **Main End Island**), while **Nether Lava** and **End Void** mean anywhere in that realm. This is also your collection journal: selling or salvaging a fish does not erase the discovery or record.

The Fish Guide and your creel are alphabetized by fish display name, ignoring colors. Habitat filters and pages keep that order. In the Fish Guide, biome finds are listed first, followed by the fish.

**Sort and filter with the sort button.** In the Fish Bag, Sell Fish and the Fish Guide, click the sort button to move to the next choice:

| Choice | What it shows |
| --- | --- |
| **Show All** | Everything, alphabetically. |
| **Discovered** / **Undiscovered** | Fish Guide only: species you have or haven't caught yet. |
| **Rarity** | Common first, up to Legendary. |
| **Overworld Fish** | Water fish, grouped by habitat. |
| **Nether Fish** / **End Fish** | Only lava or only void fish. |
| **Seasonal Fish** | Only seasonal event fish. |
| **Length** / **Weight** | Longest or heaviest first. The Fish Guide uses each species' largest possible size. |

Realm, seasonal and discovery choices hide everything else, and the page count follows. The Fish Bag and the Fish Guide remember their choices separately until you log out.

## Browse by habitat

Use the **Biome Browser** button in the Fish Guide, or **`/fish biomes`**, to pick a habitat. The default groups are **Warm Ocean, Cold/Ice, Swamp, Plains, Desert, Jungle, Mushroom Island, Deep Dark, Cold Ocean, and Caves**. Each card shows how many fish and bonus finds belong there. There are also quick views for **All Catches, Water, Nether Lava, End Void, and Seasonal**. Changing pages keeps your filter; the browser's return button takes you back to the page you were reading.

You can jump directly to a group, for example **`/fish catalog swamp`**, **`/fish catalog mushroom_island`**, or **`/fish catalog cold_ocean`**. Tab completion lists the available choices. All these commands also work with `/fishing`.

Fish that appear in several habitats can be caught in any of those habitats. The game checks the **biome at your hook**, so moving yourself onto a different shore does not change the pool if the hook stays in the same biome. Cold/Ice covers frozen waters and snowy biomes; Cold Ocean covers cold and deep cold ocean. Caves means **lush caves and dripstone caves**, plus sulfur caves on newer versions; Deep Dark has its own group. Plains also covers ordinary rivers and temperate land, and Warm Ocean includes regular and lukewarm oceans, so the other common fishing spots still have a pool. The server can customize every group.

Your old catches, discoveries and records are retained. Lava and void species keep their realm rules, and seasonal species still require their event and usual unlocks. A filter shows where a species belongs; it does not remove level, time, weather or seasonal requirements.

## Shells, coins and other biome finds

The guide also includes **18 bonus finds** from the installed pack: shells, coins, relics, an anchor, a pirate lamp, and a chest. Their cards say **Biome Find** and show your **Status** (**Discovered** or **Undiscovered**) and how many you have **Found**. The Found count started with the update that added it, so finds caught earlier are not included; a find still counts when your loot filters discard the item. A successful water cast in a habitat containing finds has a **4% chance** to roll one, alongside its fish. Some finds are rarer than others. Extra lines and bonus fish do not multiply this roll.

Finds are decorative keepsakes for your collection and have no coin value. They go into **Fishing Loot** (`/fish loot`) and stay virtual until manually withdrawn; withdraw one to display it (item frames work), trade it or keep it. They have their own **Biome Finds** loot filter (Keep by default), separate from vanilla treasure, and show as **Biome Finds** in Fishing Loot. Choose Discard there if you don't want them; your choice applies even to finds with custom item data. They do not add fish discoveries, length/weight records, job catches, XP or tournament score. The decorative Copper/Silver/Gold Coin items do **not** automatically add fishing coins or server money. The pack's **Copper Coin** is used for the bronze-coin entries.

Biome disruption expands the **fish** pool; these extra finds still come from the hook's actual habitat. The vault must be enabled for water rewards. Your server can change the find chance, weights, artwork, habitat membership and menu wording.

Custom fish artwork appears in the menus and on manually withdrawn fish when the server’s ItemsAdder pack and your resource pack are available. Menu icons cannot be dragged out: click a fish in the Fish Bag to withdraw it as a physical bundle instead.

---

[Wiki home](Home.md) · [Previous: Fishing Settings](Fishing-Settings.md) · [Next: Your Creel](Your-Creel.md)
