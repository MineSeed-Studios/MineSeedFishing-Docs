# Your Creel

> Based on MineSeedFishing 1.10.0 defaults. Check the server’s menus for customized requirements, prices, and rewards. Calendar dates use US/Eastern by default.

Your creel starts with space for **200 fish**; each **Deep Creel** upgrade adds room for 50 more, up to **600** with all eight levels. `/fish bag` groups catches by species and displays their quantities, largest lengths, heaviest recorded weights in kilograms, and combined value. Your saved catches remain through logout and server restarts. When your creel is full you can keep fishing: new catches go into your inventory as fish items, and if that is full too they drop at your feet, where only you can pick them up and they never despawn. You still get the XP, Fish Guide record and tournament credit. Once you have sold to make room, put them back with `/fish deposit all`.

**Heaviest recorded** is the best known weight attached to a species stack, rather than its combined weight or an individual measurement for every fish. Splitting, withdrawing or trading a stack carries that record with each portion. Older fish whose weights were never saved show **Not recorded** until a recorded catch or deposit joins the stack.

You have several uses for your haul:

- **Sell it:** **Sell Fish** in Fish & Storage or the Fish Bag lists your fish alphabetically. **Click** a fish to sell all of that kind, or **right-click** it to choose how many. **Sell All Fish**, or `/fish sell`, opens a review screen before selling your entire creel for fishing coins. On Bedrock, choose a fish, then **Sell all** or **Choose how many to sell**.
- **Salvage it:** `/fish salvage` lets you turn all stored fish of a selected species, or all eligible fish in the creel, into crafting materials. Fish are listed alphabetically, like the Fish Bag, and the Fish Guide shows what each species salvages into. Review the confirmation before committing.

Selling and salvaging consume the affected fish. A catch cannot be used for both. Its sale value is set when you catch it, so a later value upgrade helps future catches without increasing the price of fish already stored.

## Withdraw items to carry, store, or trade

**All catches, materials and newly earned augment copies start in your virtual fishing profile.** Nothing becomes a physical item automatically. When you want to carry something yourself, click the item itself in the **Fish Bag** (`/fish bag`), **Crafting Materials** (`/fish materials`) or **Augment Copies**. All three are in **Fish & Storage** (`/fish storage`; `/fish items` and `/fish withdraw` open it too).

1. Leave free inventory slots: items come out in stacks of up to **64**, one slot per stack.
2. On Java, click a species, material, or unused augment copy you own:
   - **Click** (or shift-click) withdraws all of it, up to **1,024** at a time by default and only as much as fits in your free slots.
   - **Right-click** asks for an amount: enter a whole number on the first line of the sign editor and select **Done**.
3. On Bedrock, choose the item, then **Withdraw all (N)**, or **Choose an amount** and enter the amount in the quantity form.
4. The amount leaves virtual storage straight away and arrives as ordinary-looking stacks, with the count shown on each stack. There is no separate confirmation step.

Menu icons show how many you have stored as their stack size (up to 99). They are menu buttons, not real items, so they cannot be dragged out.

**Each item counts as one unit**, so a stack showing 32 is worth 32. You can split stacks, give part of a stack to another player, keep them in chests or display them in item frames; trading is enabled by default, but the server can restrict redemption to the original owner. Withdrawn fish and materials are all identical, so they stack with anyone's and can be traded and deposited by any player; a deposited fish is worth the average value of that species still out. Augment copies join a stack of the same augment you already carry, so taking them out one at a time still stacks; augment stacks you received from another player stay separate. Fish withdrawn before this change keep their old stacks: deposit them and withdraw again to make them stack. Items withdrawn before stacks were introduced still work: each is a single item showing its amount in its name (such as ×64), and it deposits as before.

Only **unused augment copies** can be withdrawn. An installed augment stays attached to its rod. Use `/fish remove` and pay its usual removal fee first if you want those levels returned as copies, then withdraw the returned copies. A received augment still needs to be deposited and installed normally before it provides any benefit.

## Deposit physical items

**Quickest:** type **`/fish deposit all`**, or click **Deposit Everything** (in the Deposit Items menu, the Fish Bag, Crafting Materials or Augment Copies), to return every fishing bundle you carry at once, with one summary message.

**Choose what to deposit:** type **`/fish deposit`** or click **Deposit Items** in Fish & Storage. The **Deposit Items** menu lists every fishing bundle you carry. **Click** a bundle to deposit all of it; **right-click** asks how many to deposit, and the rest stays in your inventory.

On Java, you can also open Fish & Storage (`/fish storage`), the Fish Bag, Crafting Materials or Augment Copies, then **click a fishing bundle in your own inventory** with an empty cursor. **Left-click or shift-click deposits the whole bundle.** **Right-click** asks how many to deposit; enter a whole number in the sign editor and the rest stays in your inventory.

On Bedrock, the Deposit Items form lists the fishing bundles you carry. Choose one, then **Deposit the whole bundle** or **Choose an amount** and enter the amount in the quantity form. You do not need to move the item into a chest window.

Leave the sign input blank or close the input form to cancel; quantity input expires after 60 seconds. Put bundles in your normal inventory or hotbar first if they are in your offhand or another container. Ordinary Minecraft fish and lookalike items cannot be deposited; the bundle must have been withdrawn through this plugin.

Depositing **10 from a stack of 20** returns 10 to virtual storage and leaves 10 in the stack. Each item pays out exactly one unit, so one half of a split stack deposits only its half. Your creel needs enough free space only for the fish you deposit; materials and augment copies return to their own balances. If there is not enough space, the bundle stays physical. Refresh or reopen the menu if you moved your items after opening it.

Deposit bundles before selling or salvaging fish, using materials in recipes, or installing augment copies. Bundles are protected from normal cooking, eating, placing and crafting uses, and dispensers can't use them. **Droppers can drop them**, the same as a player dropping one, so hopper and dropper fish sorters work. They are still physical possessions: keep them safe from loss, destruction and unintended trades.

Depositing restores ownership only. It gives **no additional fishing XP, discoveries, catch records, daily quest progress, tournament score, seasonal catch rewards or fishing-job credit**. It also does not reset a seasonal crafting window. A traded fish can be sold or salvaged after depositing, but the original angler keeps their catch records.

Fish retain their stored sale value and salvage bonuses through transfers. The creel stores species totals, so partial withdrawals and deposits divide those totals without creating extra value. Any displayed largest length describes the original species group; a bundle is not a record of individually measured specimens.

If a server crash interrupts a transfer, contact staff rather than trying to copy or rename the bundle. Each withdrawal can return its value only once, however its stacks are split or copied. Staff can investigate an uncertain delivery; copying the item cannot create another valid reward.

---

[Wiki home](Home.md) · [Previous: Fish and Collection](Fish-and-Collection.md) · [Next: Fishing Loot and mcMMO](Fishing-Loot.md)
