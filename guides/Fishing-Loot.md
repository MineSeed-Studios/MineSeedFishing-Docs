# Fishing Loot and mcMMO

> Based on MineSeedFishing 1.10.0 defaults. Check the server’s menus for customized requirements, prices, and rewards. Calendar dates use US/Eastern by default.

Your custom fish still go to **Fish Bag**. Ordinary Minecraft supplies and special treasures have a separate **Fishing Loot** vault, opened with **`/fish loot`** or the dashboard button. Both stay virtual until you deliberately withdraw something.

## Keep the useful parts of vanilla fishing

Water fishing keeps Minecraft's original loot roll, so **Luck of the Sea**, **open-water treasure requirements**, and the actual item's enchantments and damage still matter. Cod, salmon, tropical fish, and pufferfish stack as virtual supplies. Useful finds such as enchanted books, name tags and nautilus shells are saved without scattering items into your inventory.

Nether lava and End void fishing also have a small extra-reward pool: **an 8% chance per cast** with the defaults. Lava can yield quartz, gold nuggets or blaze powder; void can yield chorus fruit or an ender pearl. These are extra supplies alongside the custom fish.

Normal Minecraft experience is awarded after a successful catch and can repair items with **Mending**. Water uses the original fishing XP; lava and void start with **1–6 XP per cast**. This is separate from your MineSeedFishing level and mcMMO skill XP.

## Choose what you keep

Use **`/fish loot filters`**, or open **Loot Filters** from Fishing Settings or your loot vault. Click a category to cycle through **Keep**, **Recycle**, and **Discard**. **Recycle** is offered only for **biome finds**; every other category switches between Keep and Discard. Choices save for your player across restarts.

| Category | Default | What it does |
| --- | --- | --- |
| Vanilla fish | Keep | Save ordinary fish as virtual supplies. |
| Vanilla treasure | Keep | Save useful vanilla finds and the lava/void bonus supplies. |
| Biome finds | Keep | Save the shells, coins and relics from Fish Guide habitats, or recycle them. |
| mcMMO treasure | Keep | Save special mcMMO finds that are not ordinary equipment. |
| Ordinary equipment | Discard | Low-tier armor, tools and weapons, enchanted or not. |
| Junk | Discard | Low-value odds and ends. |

Recycling a biome find gives **1 Prismatic Dust and 2 Tidal Fiber** instead of storing it. Discard gives nothing. Changing a choice affects **future catches only**; existing vault contents remain unchanged.

Items with custom persistent data are **always kept**, even if their category says Recycle or Discard. Valuable equipment (diamond and netherite armor and tools, tridents, elytra, maces and diamond horse armor) is kept while you leave Ordinary Equipment on the server's default. Pick a filter yourself and it applies to that gear too: if the menu already shows Discard, click it to Keep and back to Discard. Staff can customize these protections and conversion yields. Automatically recycling loot does not grant mcMMO Salvage XP.

## Withdraw a usable item

Open `/fish loot`. Icons show how many of each item you have stored as their stack size (up to 99). On Java, **click** an item to withdraw all of it, or **right-click** to type an amount in the sign editor straight away. On Bedrock, choose the item, then **Withdraw all (N)** or **Choose an amount**. Items arrive as normal stacks, one stack per empty inventory slot, so withdrawing all takes only as much as fits; the rest stays in the vault. You receive ordinary usable Minecraft items with their original enchantments, damage and other data. **Withdraw All** takes everything on the page you are looking at, stack by stack, until your inventory is full; anything that does not fit stays in the vault.

You can cook the raw fish, use supplies in recipes, equip gear, or trade withdrawn loot normally. **Ordinary loot cannot be redeposited.** The sealed bundles from Fish & Storage remain a separate system for custom fish, Fishing materials and augment copies; only those bundles can be deposited there.

The vault holds **512 distinct item variants** by default. Identical variants stack virtually; different enchantments or damage can occupy separate entries. If a catch needs a new entry while the vault is full, that cast awards no catch or extra rewards. Withdraw unwanted variants to make room before continuing.

## mcMMO Fishing progression

With the updated mcMMO integration installed, successful **water, lava and void** catches can advance your mcMMO Fishing skill. Its permissions, skill levels, global XP modifiers, party sharing and anti-farming rules still apply. Use **`/mcmmo:fishing`** to view that skill; `/fishing` opens MineSeedFishing.

Treasure Hunter and Magic Hunter retain their mcMMO requirements and reward rules. Their useful items go to the same loot vault; ordinary equipment follows your filters. Master Angler improves eligible bite waits and is applied once alongside the rod's other timing rules.

A cast gets **one mcMMO treasure opportunity**. Extra multicast lines give **no additional mcMMO XP by default**, and bonus fish copies never create another treasure roll. Withdrawals, deposits, and filters do not count as catches or award another round of XP, Jobs pay or tournament progress. MineSeedFishing's level-100 progression remains independent of mcMMO's levels.

---

[Wiki home](Home.md) · [Previous: Your Creel](Your-Creel.md) · [Next: Levels and Upgrades](Levels-and-Upgrades.md)
