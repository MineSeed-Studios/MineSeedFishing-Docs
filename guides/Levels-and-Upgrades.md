# Levels and Upgrades

> Based on MineSeedFishing 1.10.0 defaults. Check the server’s menus for customized requirements, prices, and rewards. Calendar dates use US/Eastern by default.

Fishing XP is separate from vanilla Minecraft experience. You start at **fishing level 1** and can reach **level 100**. Each new level requires more XP than the last; the default total for level 100 is **9,702,990 fishing XP**. Catching fish, and claiming quests earn fishing XP. Higher levels unlock more species and augment blueprints.

XP is cumulative: reaching a level does not spend it. Default milestones are **7,290 XP at level 10**, **138,240 at level 25**, **1,176,490 at level 50**, and **4,052,240 at level 75**. Multicasting, luck, XP augments, rod bonuses and augments affect how quickly you advance. The defaults target about **200–400 hours of active fishing** for a developed angler to reach level 100; missed bites, travel and building your rod can add time.

Hover over your player head in `/fish` to see your **XP progress bar**. It shows progress through your current level, along with the XP earned toward its requirement and a percentage. Reaching a new level starts that bar again; your total fishing XP stays saved. At the level cap, the bar is full and marked **Maximum level reached**.

Use **`/fish info`** to display your fishing profile directly in chat: level and XP progress, fishing coins, lifetime catches, collection, your **longest** and **heaviest fish ever caught** (with their measurements and species), and total fishing XP. These records are kept even after you sell or salvage the fish. **`/fish info <player>`** shows another angler’s saved profile, including when they are offline. Use their last saved player name or UUID; unknown players do not receive an empty profile. Names are matched without case sensitivity, and a UUID can distinguish players when a saved name is ambiguous. `/fishing info` works the same way. The server can restrict looking up other players, and console users must provide a player name or UUID.

The upgrades in `/fish upgrades` belong to your **player profile**, so they continue working when you change rods. Each purchase increases that upgrade by one level, and later levels cost more.

| Upgrade | Benefit per level | Default maximum | First purchase |
| --- | --- | --- | --- |
| **Quickline** | 3% shorter base fishing waits | 5 levels; 15% reduction | 5,000 coins |
| **Lucky Current** | Increased rarity luck | 5 levels | 8,000 coins |
| **Fine Catch** | +10% raw value before diminishing returns | 5 levels; +50% value | 7,000 coins |
| **Deep Creel** | Space for 50 additional fish | 8 levels; 600 total capacity | 4,000 coins |
| **Expanded Tackle** | One additional augment slot on every rod you hold | 9 levels; 12 total slots | 10,000 coins |

If the server adopts a harder level curve, your displayed level can change while your accumulated fishing XP remains saved. The live menus always use the server’s current requirements.

The menu displays your current level, benefit per level, and next purchase price. Click an upgrade to open **Buy Upgrade?**, which shows the next level, its cost and your coins; confirm to buy it. An upgrade at its maximum level shows **Maximum level reached** instead of a price, and Bedrock offers no buy button for it. Some upgrades stop at a fixed maximum (Fine Catch at 5, for example); a higher fishing level does not add more ranks. **Expanded Tackle** also shows your current and next rod capacity. Its default price grows by 1.75× per level. Buying an account upgrade does not occupy an augment slot on your rod.

---

[Wiki home](Home.md) · [Previous: Fishing Loot and mcMMO](Fishing-Loot.md) · [Next: Rod Workshop](Rod-Workshop.md)
