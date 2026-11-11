# Commands and Help

> Based on MineSeedFishing 1.10.0 defaults. Check the server’s menus for customized requirements, prices, and rewards. Calendar dates use US/Eastern by default.

## Command reference

Every command below also works with `/fishing` in place of `/fish`.

| Command | Opens or performs |
| --- | --- |
| `/fish` | Fishing Menu dashboard and profile. |
| `/fish settings` | Choose which fishing chat messages you want to see. Choices are saved for your player. |
| `/fish info [player]` | Your profile in chat, or another saved angler’s profile by name or UUID, including offline players. |
| `/fish bag` | Your creel. |
| `/fish loot` | Browse and withdraw usable vanilla supplies and special treasures. |
| `/fish loot filters` | Choose Keep, Recycle or Discard for future loot categories. |
| `/fish storage`, `/fish items`, `/fish withdraw` | Open Fish & Storage: click stored items to withdraw them, or carried bundles to deposit them. |
| `/fish deposit` | Deposit Items: choose which carried bundles to return to storage. |
| `/fish deposit all` | Return every fishing bundle you are carrying to storage at once. |
| `/fish catalog [filter]` | Fish Guide with optional habitat, realm or seasonal filter. |
| `/fish biomes` | Browse habitat cards, fish counts and bonus finds. |
| `/fish sell` | Review selling your whole creel. To sell one kind of fish, use **Sell Fish** in Fish & Storage or the Fish Bag. |
| `/fish upgrades` | Permanent player upgrades. |
| `/fish quests` | Daily quest progress and reward claims. |
| `/fish workshop` | Rod workshop hub. |
| `/fish salvage` | Species or whole-creel salvage previews. |
| `/fish materials` | Your crafting-material pouch. |
| `/fish augments` | Craft Augments: choose Year-round Augments, Seasonal Events or All Augments. |
| `/fish augments owned`, `/fish augments missing` | Browse owned or missing augments across all categories. |
| `/fish augments <category> <all\|owned\|missing>` | Combine a seasonal or standard category with an ownership filter. |
| `/fish augments standard` | Year-round blueprints. |
| `/fish augments halloween` | Haunted Tides blueprints. |
| `/fish augments christmas` | Winter’s Wake blueprints. |
| `/fish augments spring` | Blooming Tides blueprints. |
| `/fish augments summer` | Sunken Solstice blueprints. |
| `/fish regatta` | Summer community restoration, fish unlocks and reward claim. |
| `/fish rod` | Manage the rod in your main hand: install copies or withdraw unused copies. |
| `/fish remove` | Augment removal and copy recovery. |
| `/fish events` | Event Guide: what each seasonal event is, when it runs and how to earn its material. `/fish seasonal` opens the seasonal blueprint list. |
| `/fish disrupt` | Disruption charge menu. |
| `/fish disrupt buy` | Buy one charge. |
| `/fish disrupt throw` | Throw one purchased charge. |
| `/fish exchange` | Coin exchange menu, including Exchange All Coins. |
| `/fish exchange <coins>` | Preview a custom conversion. |
| `/fish help` | In-game command help. |


### Staff commands

These commands require `mineseedfishing.admin`, which defaults to server operators. They work from console and accept a saved player name or UUID, including offline players. `/fishing` and `/msfish` use the same commands. Use tab completion for configured item IDs.

| Command | Effect |
| --- | --- |
| `/fish admin` or `/fish admin help` | Show the staff command reference. |
| `/fish admin addxp <player> <amount>` | Add fishing XP. |
| `/fish admin removexp <player> <amount>` | Remove fishing XP, stopping at zero. |
| `/fish admin setxp <player> <amount>` | Set total fishing XP exactly; `0` resets it. |
| `/fish admin setlevel <player> <level>` | Set fishing XP to the start of that level. |
| `/fish admin addlevels <player> <amount>` | Advance from the current fishing level to the start of the new level. |
| `/fish admin removelevels <player> <amount>` | Drop from the current fishing level to the start of a lower level, stopping at level 1. |
| `/fish admin giveaugment <player> <augment_id> [amount]` | Give unused copies in the player's augment pouch; amount defaults to one. |
| `/fish admin removeaugment <player> <augment_id> [amount]` | Remove unused copies from the augment pouch, stopping at zero; amount defaults to one. |
| `/fish admin setaugment <player> <augment_id> <amount>` | Set how many unused copies are in the augment pouch; `0` clears them. |
| `/fish admin givematerial <player> <material_id> [amount]` | Give materials in the player's material pouch; amount defaults to one. |
| `/fish admin removematerial <player> <material_id> [amount]` | Remove materials from the material pouch, stopping at zero; amount defaults to one. |
| `/fish admin setmaterial <player> <material_id> <amount>` | Set how many of a material are in the pouch; `0` clears them. |
| `/fish admin givecoins <player> <coins>` | Add fishing coins, accepting up to five decimal places. |
| `/fish admin removecoins <player> <coins>` | Remove fishing coins, stopping at zero. |
| `/fish admin setcoins <player> <coins>` | Set the fishing coin balance exactly; `0` empties it. |
| `/fish admin giveaugmentitem <player> <augment_id> [amount]` | Give an online player augment copies as items straight into their inventory. If they can't take them (full inventory, wrong game mode), the copies stay in their pouch and you are told. |
| `/fish admin givedisruptor <player> <charges>` | Give biome disruption charges. |
| `/fish admin removedisruptor <player> <charges>` | Remove disruption charges, stopping at zero. |
| `/fish admin setdisruptor <player> <charges>` | Set disruption charges exactly; `0` clears them. |
| `/fish admin tournament start [type]` | Start a chat tournament now: `most-caught`, `longest-fish`, `heaviest-fish`, `furthest-cast`, `shortest-fish`, `lightest-fish` or `first-catch` (random when left out). |
| `/fish admin tournament end` / `cancel` | End the running chat tournament now and pay the winners, or cancel it without prizes. |
| `/fish admin tournament status` | Show the running chat tournament, or how long until the next one. |
| `/fish top` | Lifetime catch leaderboard (staff only). |
| `/fish admin leaderboard reset` | Start the `/fish top` leaderboard over (asks you to add `confirm`). Lifetime stats, the Fish Guide and everything else stay. |
| `/fish admin tradingpost <player>` | Open the Trading Post for an online player (name or UUID). Meant for an NPC: have it run this from console with the clicking player, for example `fish admin tradingpost {player}` in Citizens or ZNPCsPlus. Console gets no reply on success. `/fish tradingpost` opens it for yourself. |

For example, `/fish admin addxp Alex 5000`, `/fish admin setlevel Alex 25`, `/fish admin giveaugment Alex trophy_hunter 2`, `/fish admin givematerial Alex tidal_fiber 64`, and `/fish admin givecoins Alex 2500.50`; `/fish admin removecoins Alex 100`, `/fish admin setmaterial Alex tidal_fiber 0` and `/fish admin removelevels Alex 5` take things away. Removals only touch the pouches and balances, never augments already installed on a rod. Augment copies still need installing on a rod. Staff may grant configured seasonal copies out of season; normal level, slot and enabled-effect requirements still apply. Level changes respect the server's configured maximum and reset progress within the chosen level. These commands affect Fishing progression and storage, and preserve catches, collections and quest progress. Minecraft XP, mcMMO XP and external economy money have their own commands.

Unknown saved names are rejected. If more than one saved profile uses a name, use the correct player's UUID. Changes are saved immediately and recorded for staff review; deliberately running a grant again grants it again.

An online player is told in chat when they receive coins, XP, levels, augment copies, materials or disruption charges, with the amount and their new balance. Several grants run from console in the same moment (for example by a voucher or crate) run one after another, so every one of them applies.

## When something is not working

**“No fish are biting here.”** Check your fishing level and the species’ realm, biome, time, and weather requirements. A catalog entry is a discovery goal, not a guarantee that the fish can currently be caught.

**The hook keeps sinking or falling.** Look for the ready message. Lava fishing needs contact with Nether lava; void fishing needs a clear gap below an End island or an end portal surface in the End. Stay within range and keep your rod held.

**A recipe needs Ember Scales or Void Silk.** Fish in Nether lava or End void with a normal rod, then salvage the catches. The matching realm augment comes afterward.

**An augment does nothing.** Make sure the copy is installed on the rod in your hand and you are in a supported realm or condition. Owning a copy in your pouch does not apply its effect. During a chat tournament, augments are switched off at spawn for everyone.

**I caught the tournament fish but didn't win.** Chat tournaments only count catches at spawn (the tournament worlds). Catches elsewhere still give XP, quest progress and collection credit.

**A menu asks you to review again.** Your bag, balance, or rod changed after the preview opened. Read the refreshed details and confirm the new preview.

**An item will not withdraw or deposit.** Use Survival or Adventure and wait for any current transfer to finish. Withdrawal needs a free inventory slot for each stack of up to 64; a fish deposit needs space only for the selected quantity in your creel. Open **Deposit Items** (`/fish deposit`) and click the bundle to deposit all of it, or right-click it to choose a smaller amount. On Java you can also click the bundle in your inventory with an empty cursor while Fish & Storage is open. On Bedrock, choose the bundle in the Deposit Items form. Only genuine Fishing bundles can be deposited, and only unused augment copies can be withdrawn. The server can disable transfers or particular item categories.

**Fishing asks for a compatible mcMMO integration.** Staff need to install the matching updated mcMMO build alongside MineSeedFishing and restart. Fishing pauses managed casts while an older incompatible mcMMO is installed. A server without mcMMO does not need that companion.

**You cannot cast at all.** Make room in your creel, use Survival or Adventure, wait for your fishing profile to finish loading, and try an allowed fishing area. Server permissions and protected regions can restrict fishing.

---

[Wiki home](Home.md) · [Previous: Special Crate Rods](Special-Crate-Rods.md)
