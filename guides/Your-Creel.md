# Your Creel

> Based on MineSeedFishing 1.8.0 defaults. Check the server’s menus for customized requirements, prices, and rewards. Calendar dates use US/Eastern by default.

Your creel starts with space for **100 fish**. `/fish bag` groups catches by species and displays their quantities, largest lengths, and combined value. Your saved catches remain through logout and server restarts. A full creel prevents further custom fishing until you make room.

You have several uses for your haul:

- **Sell it:** `/fish sell` opens a review screen before selling your entire creel for fishing coins.
- **Salvage it:** `/fish salvage` lets you turn all stored fish of a selected species, or all eligible fish in the creel, into crafting materials. Review the confirmation before committing.
- **Keep ingredients:** some rod activities use fish already in your creel to begin a recipe or wager.

Selling and salvaging consume the affected fish. A catch cannot be used for both. Its sale value is set when you catch it, so a later value upgrade helps future catches without increasing the price of fish already stored.

### Withdraw items to carry, store, or trade

**All catches, materials and newly earned augment copies start in your virtual fishing profile.** Nothing becomes a physical item automatically. Open **Angler Storage** from the dashboard, or use `/fish items` or `/fish withdraw`, when you want to carry something yourself.

1. Choose **Withdraw Fish**, **Withdraw Materials**, or **Withdraw Augments**.
2. Select a species, material, or unused augment copy you own.
3. Choose a quantity. Defaults offer **1, 16, 64**, plus your available amount up to **1,024**. Only choices you can afford appear.
4. Leave an empty inventory slot. Clicking the quantity removes that amount from virtual storage and gives you **one sealed physical bundle**.

A bundle uses one slot even when its label says ×64. It cannot stack or split into separate inventory units. To split a large bundle, deposit it and withdraw the smaller quantities you want. You can keep bundles in chests or give them to another player; trading is enabled by default, but the server can restrict redemption to the original owner.

Only **unused augment copies** can be withdrawn. An installed augment stays attached to its registered rod. Use `/fish remove` and pay its usual removal fee first if you want those levels returned as copies, then withdraw the returned copies. A received augment still needs to be deposited and installed normally before it provides any benefit.

### Deposit a physical bundle

Open `/fish deposit`, then **click the bundle you want to deposit** in the menu. The menu previews fishing bundles in your normal inventory and hotbar. Put a bundle there first if it is in your offhand or another container. Ordinary Minecraft fish and lookalike items cannot be deposited; the bundle must have been withdrawn through this plugin.

The whole selected bundle returns to virtual storage and its physical item is removed. A fish bundle needs enough free space for its entire quantity in your creel; materials and augment copies return to their own balances. If there is not enough space, the bundle stays physical. Refresh the menu if you moved your items after opening it.

Deposit bundles before selling or salvaging fish, using materials in recipes, or installing augment copies. Bundles are protected from normal cooking, eating, placing and crafting uses. They are still physical possessions: keep them safe from loss, destruction and unintended trades.

Depositing restores ownership only. It gives **no additional fishing XP, discoveries, catch records, daily quest progress, tournament score, seasonal catch rewards or fishing-job credit**. It also does not reset a seasonal crafting window. A traded fish can be sold or salvaged after depositing, but the original angler keeps their catch records.

Fish retain their stored sale value and salvage bonuses through transfers. The creel stores species totals, so partial withdrawals divide those totals without creating extra value. Any displayed largest length describes the original species group; a bundle is not a record of individually measured specimens.

If a server crash interrupts a transfer, contact staff rather than trying to copy or rename the bundle. Each bundle can return its value only once. Staff can investigate an uncertain delivery; copying the item cannot create another valid reward.

---

[Wiki home](Home.md) · [Previous: Fish and Collection](Fish-and-Collection.md) · [Next: Fishing Loot and mcMMO](Fishing-Loot.md)
