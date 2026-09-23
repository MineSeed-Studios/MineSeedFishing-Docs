# Fishing Loot and mcMMO

> Based on MineSeedFishing 1.8.0 defaults. Check the server’s menus for customized requirements, prices, and rewards. Calendar dates use US/Eastern by default.

Your custom fish still go to **Your Creel**. Ordinary Minecraft supplies and special treasures have a separate **Fishing Loot** vault, opened with **`/fish loot`** or the dashboard button. Both stay virtual until you deliberately withdraw something.

### Keep the useful parts of vanilla fishing

Water fishing keeps Minecraft's original loot roll, so **Luck of the Sea**, **open-water treasure requirements**, and the actual item's enchantments and damage still matter. Cod, salmon, tropical fish, and pufferfish stack as virtual supplies. Useful finds such as enchanted books, name tags and nautilus shells are saved without scattering items into your inventory.

Nether lava and End void fishing also have a small extra-reward pool: **an 8% chance per cast** with the defaults. Lava can yield quartz, gold nuggets or blaze powder; void can yield chorus fruit or an ender pearl. These are extra supplies alongside the custom fish.

Normal Minecraft experience is awarded after a successful catch and can repair items with **Mending**. Water uses the original fishing XP; lava and void start with **1–6 XP per cast**. This is separate from your MineSeedFishing level and mcMMO skill XP.

### Choose what you keep

Use **`/fish loot filters`**, or open **Loot Filters** from Fishing Settings or your loot vault. Click a category to cycle through **Keep**, **Recycle**, and **Discard**. Choices save for your player across restarts.

| Category | Default | What it does |
| --- | --- | --- |
| Vanilla fish | Keep | Save ordinary fish as virtual supplies. |
| Vanilla treasure | Keep | Save useful vanilla finds and the lava/void bonus supplies. |
| mcMMO treasure | Keep | Save special mcMMO finds that are not ordinary equipment. |
| Ordinary equipment | Recycle | Convert low-tier unenchanted armor, tools and weapons into materials. |
| Junk | Recycle | Convert low-value odds and ends into materials. |

With the defaults, each recycled equipment or junk item gives **one Tidal Fiber**, rather than coins. Discard gives nothing. Changing a choice affects **future catches only**; existing vault contents remain unchanged.

Enchanted items, enchanted books, items with custom persistent data, and configured valuable equipment are **always kept with the default protection settings**, even if their category says Recycle or Discard. Protected equipment includes diamond and netherite armor/tools, tridents, elytra, maces and diamond horse armor. Staff can customize these protections and conversion yields. Automatically recycling loot does not grant mcMMO Salvage XP.

### Withdraw a usable item

Open `/fish loot`, select a stored item, then select a quantity. Default quantity choices are **1, 16 and 64**, limited by what you own and the item's real stack size. Leave one empty inventory slot. You receive an ordinary usable Minecraft item with its original enchantments, damage and other data.

You can cook the raw fish, use supplies in recipes, equip gear, or trade withdrawn loot normally. **Ordinary loot cannot be redeposited.** The sealed bundles from `/fish items` remain a separate system for custom fish, Fishing materials and augment copies; only those bundles belong in `/fish deposit`.

The vault holds **512 distinct item variants** by default. Identical variants stack virtually; different enchantments or damage can occupy separate entries. If a catch needs a new entry while the vault is full, that cast awards no catch or extra rewards. Withdraw unwanted variants to make room before continuing.

### mcMMO Fishing progression

With the updated mcMMO integration installed, successful **water, lava and void** catches can advance your mcMMO Fishing skill. Its permissions, skill levels, global XP modifiers, party sharing and anti-farming rules still apply. Use **`/mcmmo:fishing`** to view that skill; `/fishing` opens MineSeedFishing.

Treasure Hunter and Magic Hunter retain their mcMMO requirements and reward rules. Their useful items go to the same loot vault; ordinary equipment follows your filters. Master Angler improves eligible bite waits and is applied once alongside the rod's other timing rules.

A cast gets **one mcMMO treasure opportunity**. Extra multicast lines give **no additional mcMMO XP by default**, and bonus fish copies never create another treasure roll. Withdrawals, deposits, and filters do not count as catches or award another round of XP, Jobs pay or tournament progress. MineSeedFishing's level-100 progression remains independent of mcMMO's levels.

---

[Wiki home](Home.md) · [Previous: Your Creel](Your-Creel.md) · [Next: Levels and Upgrades](Levels-and-Upgrades.md)
