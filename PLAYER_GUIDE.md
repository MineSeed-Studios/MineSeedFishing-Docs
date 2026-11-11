# MineSeedFishing — Player Guide

From quiet rivers to the lava pools of the Nether and the open void beneath End islands, MineSeedFishing gives you three realms to explore, a collection to build, and a rod you can make your own. Catch unusual species, turn your haul into coins or crafting materials, compete in daily tournaments, and return throughout the year for seasonal fishing adventures.

**Start with `/fish` or `/fishing`.** Both commands open **Fishing Menu**, your fishing dashboard, and work interchangeably for every command in this guide. `/msfish` is another alias. MineSeedFishing takes priority for `/fishing` when mcMMO is installed; use `/mcmmo:fishing` for mcMMO’s fishing skill page.

This guide describes version **1.10.0 with its default settings**. The server can change prices, rewards, recipes, dates, requirements, and available features. Check the live menus for the settings currently in use. Daily resets and seasonal dates default to **US/Eastern**, automatically following Eastern Standard Time and Eastern Daylight Time. Fish that require day, night, or particular weather follow the **Minecraft world's conditions**.

Java players browse Fishing through inventory menus. Bedrock players connecting through Geyser and Floodgate use native forms for every menu, including the dashboard, item lists, details, page navigation and confirmations. Select an entry to read its details, then choose the available action or go back. The same commands and gameplay rules apply to both clients. Sneak and right-click with a fishing rod to open your dashboard.

By default, configured menu labels, item names and message text use small capital letters, such as **ꜰɪѕʜɪɴɢ**. This guide uses regular letters for readability. Player names, numbers and usable commands retain their original text, and alphabetical lists keep their usual order. Server owners can turn this presentation off; it is separate from your personal chat settings.

## Your fishing chat settings

Use **`/fish settings`** or **`/fishing settings`**, or click **Fishing Settings** in your dashboard. Choose a notification option to turn it on or off. The card or Bedrock form button shows its current state and what your next selection will do. Your choices apply only to you and are saved across logout and server restarts.

All 16 options start enabled with the default server configuration. You can independently change:

| Option | Notifications it controls |
| --- | --- |
| Personal catches | Your catch's species, size, value and XP |
| Rare-catch announcements | Server announcements about rare catches, including your own |
| Bite Messages | Normal and extra-line bite chat |
| Bite Sounds | The personal chime for normal and extra-line bites |
| Missed bites | Fish slipping away from normal or extra lines |
| Line ready | Nether lava and End void line-ready messages |
| Level-ups | Reaching a new fishing level |
| Community events | Seasonal discoveries, guardian appearances, bindings and encounter outcomes |
| Community rewards | Your seasonal community reward notification |
| Regatta | Shared restoration stages and completion announcements |
| Fish Caller Pools | Fish Caller pool starts and expiry |
| Biome disruption | Orb throws, active zones, misses and expiry |
| Economy | Successful sales, upgrade purchases, coin exchanges and disruption purchases |
| Workshop | Rod management, augment crafting/installing/removing and salvage confirmations |
| Chat Tournaments | Tournament announcements, reminders and results |
| Reward claims | Daily quest, tournament and Regatta treasure claims |
| Physical items | Successful withdrawal and deposit confirmations |

**Bite Messages and Bite Sounds are separate, adjacent choices.** Turn off Bite Messages to keep the chime without bite chat, or turn off Bite Sounds to keep chat without the chime. Both apply to normal and extra lines. The prompt above your hotbar, bobber particles and movement remain visible. The other options change chat delivery. Your catches, XP, coins, items and Jobs credit continue normally. Muting rare-catch announcements hides them from your own chat; other players can still see announcements according to their settings.

Command help, requested profile information, permission errors, full-creel warnings, failed actions and refund or unresolved-payment notices remain visible. Messages sent by other plugins use those plugins' own settings. Server staff can customize the default choices and the menu, but an existing saved choice takes precedence over a changed server default. When upgrading from the combined Bite Alerts setting, your previous choice is initially kept for both messages and sounds; afterward you can change either independently.

The **Loot Filters** button in Fishing Settings opens your saved choices for ordinary fishing loot. Those choices affect future rewards; they are separate from chat toggles.

## Finding your way around

The main **Fishing Menu** has six choices. **Fish & Storage** holds your catches, loot, withdrawals, sales and coin exchange. **Rod & Upgrades** holds rod management, augments, account upgrades, salvage, crafting materials and biome disruption. **Fish Guide** shows where and when to find species. **Quests & Events** holds daily goals, tournaments, rankings and seasonal events. **Settings** controls sounds, messages and loot filters. **How to Fish** provides a short introduction.

Use **Back to …** to return to the matching section. Click a fish or material in the Fish Bag or Crafting Materials to withdraw it as items you can carry or trade; icons show your stored count. Crafting Materials lists year-round materials first, then each event's material in calendar order (spring, summer, Halloween, winter). Bedrock forms use the same sections, with action buttons such as **Buy next rank** or **Claim quest reward**. Direct commands in this guide still open their feature immediately.

## Your first fishing trip

1. Bring an ordinary fishing rod and play in Survival or Adventure mode.
2. Cast into overworld water, Nether lava, or a clear gap beside an End island.
3. Wait for a bite, then reel in. Lava and void fishing first display a message confirming that your line is ready.
4. Open `/fish bag` to see your catches. They go into your personal **creel**, a virtual fish bag.
5. Sell your haul for fishing coins, or salvage selected species for augment materials.
6. Check `/fish quests` for rewards you can claim, then explore `/fish upgrades` and `/fish workshop`.

**You do not need an augment to unlock any of the three realms.** Ember Affinity improves lava fishing, and Rift Attunement improves void fishing. An ordinary rod can already catch the fish used to make them.

**You can spot a bite without reading chat.** A short personal chime plays when a fish is ready if **Bite Sounds** is enabled, and **BITE! Reel in now!** appears above your hotbar while a line is ready. **Bite Messages** separately controls the chat alert. Look for particles beside the biting bobber, plus the normal water bobber dip or a repeating dip on custom lava/void lines. The same cues apply to extra lines and work on Java and Bedrock. Reel promptly; the cues do not extend the catch window. Server staff can customize or disable each cue.

## Fishing in the three realms

You can browse fishing menus while your cast remains active. Opening a Java menu or Bedrock form does not reset the wait or extend the bite deadline. For a manual rod, close the menu and reel promptly when the bite arrives. Configured automatic crate-rod recasts continue while browsing; moving or changing your rod still interrupts fishing normally.

With the updated **MineSeedJobs** integration installed, eligible catches in **water, Nether lava, and End void** also count toward the Fisherman job after you join it. Job XP, money, and points follow the server's Jobs configuration. Each successfully caught original multicast line counts by default; extra bonus copies from augments or crate rods do not.

### Overworld water

Cast into water and reel in at the normal fishing bite. Successful custom catches go straight into your creel and award fishing experience. The catch message shows the species, length, weight, value, and XP.

Different species can require different biomes, fishing levels, times of day, or weather. Explore new waters and check the **Fish Guide** when looking for a particular fish.

**Move around.** After **10 catches in a row** with your bobber in the same spot (within **3 blocks**), that spot is **overfished**: nothing bites there, so you get no fish, XP or tournament credit, and the cast is used up. You get a warning one catch before. Cast at least 3 blocks away to start fresh. This applies in all three realms.

### Nether lava

Find an actual lava pool **in the Nether** and cast into it. Your bobber should settle near the surface, followed by a **Nether lava line ready** message. Wait for **BITE!**, then reel in promptly.

Without bonuses, the default wait after settling is approximately **8–25 seconds**, with about **2.25 seconds** to reel during the bite. Lure, upgrades, and suitable augments can shorten the wait. Lava elsewhere does not activate this Nether fishing mode.

### End void

Stand near an island edge **in the End** and cast out over empty space. The hook needs a clear column of air beneath it, with no island or other blocks below. It initially falls at least eight blocks from your casting height before establishing the line.

Once you see **End void line ready**, wait for **BITE!** and reel in. The default wait is approximately **9–27.5 seconds**, with about **2.25 seconds** to respond. Stay reasonably close to the line; the default maximum distance is 30 blocks.

Casting upward over land will simply make the bobber fall again. Aim out over the gap. If there is no ready message, the line has not found a valid void fishing position.

**End portals work too.** Cast onto **end portal blocks in the End** and the bobber stops on the portal's surface and fishes the same End pool as the void, with the same ready message, waits and fish. The bobber never travels through the portal. Extra lines spread out over the same portal. This works only in End worlds; portal blocks elsewhere do not fish.

Keep the same rod held while fishing. Opening an inventory menu, switching or dropping the active rod, teleporting, changing worlds, dying, or leaving can end an unfinished cast. Rods still lose durability through fishing; durability augments can help protect them.

## Fish, rarity, and your collection

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

### Browse by habitat

Use the **Biome Browser** button in the Fish Guide, or **`/fish biomes`**, to pick a habitat. The default groups are **Warm Ocean, Cold/Ice, Swamp, Plains, Desert, Jungle, Mushroom Island, Deep Dark, Cold Ocean, and Caves**. Each card shows how many fish and bonus finds belong there. There are also quick views for **All Catches, Water, Nether Lava, End Void, and Seasonal**. Changing pages keeps your filter; the browser's return button takes you back to the page you were reading.

You can jump directly to a group, for example **`/fish catalog swamp`**, **`/fish catalog mushroom_island`**, or **`/fish catalog cold_ocean`**. Tab completion lists the available choices. All these commands also work with `/fishing`.

Fish that appear in several habitats can be caught in any of those habitats. The game checks the **biome at your hook**, so moving yourself onto a different shore does not change the pool if the hook stays in the same biome. Cold/Ice covers frozen waters and snowy biomes; Cold Ocean covers cold and deep cold ocean. Caves means **lush caves and dripstone caves**, plus sulfur caves on newer versions; Deep Dark has its own group. Plains also covers ordinary rivers and temperate land, and Warm Ocean includes regular and lukewarm oceans, so the other common fishing spots still have a pool. The server can customize every group.

Your old catches, discoveries and records are retained. Lava and void species keep their realm rules, and seasonal species still require their event and usual unlocks. A filter shows where a species belongs; it does not remove level, time, weather or seasonal requirements.

### Shells, coins and other biome finds

The guide also includes **18 bonus finds** from the installed pack: shells, coins, relics, an anchor, a pirate lamp, and a chest. Their cards say **Biome Find** and show your **Status** (**Discovered** or **Undiscovered**) and how many you have **Found**. The Found count started with the update that added it, so finds caught earlier are not included; a find still counts when your loot filters discard the item. A successful water cast in a habitat containing finds has a **4% chance** to roll one, alongside its fish. Some finds are rarer than others. Extra lines and bonus fish do not multiply this roll.

Finds are decorative keepsakes for your collection and have no coin value. They go into **Fishing Loot** (`/fish loot`) and stay virtual until manually withdrawn; withdraw one to display it (item frames work), trade it or keep it. They have their own **Biome Finds** loot filter (Keep by default), separate from vanilla treasure, and show as **Biome Finds** in Fishing Loot. Choose Discard there if you don't want them; your choice applies even to finds with custom item data. They do not add fish discoveries, length/weight records, job catches, XP or tournament score. The decorative Copper/Silver/Gold Coin items do **not** automatically add fishing coins or server money. The pack's **Copper Coin** is used for the bronze-coin entries.

Biome disruption expands the **fish** pool; these extra finds still come from the hook's actual habitat. The vault must be enabled for water rewards. Your server can change the find chance, weights, artwork, habitat membership and menu wording.

Custom fish artwork appears in the menus and on manually withdrawn fish when the server’s ItemsAdder pack and your resource pack are available. Menu icons cannot be dragged out: click a fish in the Fish Bag to withdraw it as a physical bundle instead.

## Your creel: keep, sell, or salvage

Your creel starts with space for **200 fish**; each **Deep Creel** upgrade adds room for 50 more, up to **600** with all eight levels. `/fish bag` groups catches by species and displays their quantities, largest lengths, heaviest recorded weights in kilograms, and combined value. Your saved catches remain through logout and server restarts. When your creel is full you can keep fishing: new catches go into your inventory as fish items, and if that is full too they drop at your feet, where only you can pick them up and they never despawn. You still get the XP, Fish Guide record and tournament credit. Once you have sold to make room, put them back with `/fish deposit all`.

**Heaviest recorded** is the best known weight attached to a species stack, rather than its combined weight or an individual measurement for every fish. Splitting, withdrawing or trading a stack carries that record with each portion. Older fish whose weights were never saved show **Not recorded** until a recorded catch or deposit joins the stack.

You have several uses for your haul:

- **Sell it:** **Sell Fish** in Fish & Storage or the Fish Bag lists your fish alphabetically. **Click** a fish to sell all of that kind, or **right-click** it to choose how many. **Sell All Fish**, or `/fish sell`, opens a review screen before selling your entire creel for fishing coins. On Bedrock, choose a fish, then **Sell all** or **Choose how many to sell**.
- **Salvage it:** `/fish salvage` lets you turn all stored fish of a selected species, or all eligible fish in the creel, into crafting materials. Fish are listed alphabetically, like the Fish Bag, and the Fish Guide shows what each species salvages into. Review the confirmation before committing.

Selling and salvaging consume the affected fish. A catch cannot be used for both. Its sale value is set when you catch it, so a later value upgrade helps future catches without increasing the price of fish already stored.

### Withdraw items to carry, store, or trade

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

### Deposit physical items

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

## Fishing loot, vanilla rewards, and mcMMO

Your custom fish still go to **Fish Bag**. Ordinary Minecraft supplies and special treasures have a separate **Fishing Loot** vault, opened with **`/fish loot`** or the dashboard button. Both stay virtual until you deliberately withdraw something.

### Keep the useful parts of vanilla fishing

Water fishing keeps Minecraft's original loot roll, so **Luck of the Sea**, **open-water treasure requirements**, and the actual item's enchantments and damage still matter. Cod, salmon, tropical fish, and pufferfish stack as virtual supplies. Useful finds such as enchanted books, name tags and nautilus shells are saved without scattering items into your inventory.

Nether lava and End void fishing also have a small extra-reward pool: **an 8% chance per cast** with the defaults. Lava can yield quartz, gold nuggets or blaze powder; void can yield chorus fruit or an ender pearl. These are extra supplies alongside the custom fish.

Normal Minecraft experience is awarded after a successful catch and can repair items with **Mending**. Water uses the original fishing XP; lava and void start with **1–6 XP per cast**. This is separate from your MineSeedFishing level and mcMMO skill XP.

### Choose what you keep

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

### Withdraw a usable item

Open `/fish loot`. Icons show how many of each item you have stored as their stack size (up to 99). On Java, **click** an item to withdraw all of it, or **right-click** to type an amount in the sign editor straight away. On Bedrock, choose the item, then **Withdraw all (N)** or **Choose an amount**. Items arrive as normal stacks, one stack per empty inventory slot, so withdrawing all takes only as much as fits; the rest stays in the vault. You receive ordinary usable Minecraft items with their original enchantments, damage and other data. **Withdraw All** takes everything on the page you are looking at, stack by stack, until your inventory is full; anything that does not fit stays in the vault.

You can cook the raw fish, use supplies in recipes, equip gear, or trade withdrawn loot normally. **Ordinary loot cannot be redeposited.** The sealed bundles from Fish & Storage remain a separate system for custom fish, Fishing materials and augment copies; only those bundles can be deposited there.

The vault holds **512 distinct item variants** by default. Identical variants stack virtually; different enchantments or damage can occupy separate entries. If a catch needs a new entry while the vault is full, that cast awards no catch or extra rewards. Withdraw unwanted variants to make room before continuing.

### mcMMO Fishing progression

With the updated mcMMO integration installed, successful **water, lava and void** catches can advance your mcMMO Fishing skill. Its permissions, skill levels, global XP modifiers, party sharing and anti-farming rules still apply. Use **`/mcmmo:fishing`** to view that skill; `/fishing` opens MineSeedFishing.

Treasure Hunter and Magic Hunter retain their mcMMO requirements and reward rules. Their useful items go to the same loot vault; ordinary equipment follows your filters. Master Angler improves eligible bite waits and is applied once alongside the rod's other timing rules.

A cast gets **one mcMMO treasure opportunity**. Extra multicast lines give **no additional mcMMO XP by default**, and bonus fish copies never create another treasure roll. Withdrawals, deposits, and filters do not count as catches or award another round of XP, Jobs pay or tournament progress. MineSeedFishing's level-100 progression remains independent of mcMMO's levels.

## Fishing levels and permanent upgrades

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

## The rod workshop

Augments let you specialize a particular rod. Open `/fish workshop` to craft copies, install them, remove them, salvage fish, and browse your material pouch.

### Gather materials

Salvaging gives materials instead of coins. The main materials are **Tidal Fiber**, **Prismatic Dust**, **Ember Scale**, and **Void Silk**. Nether lava catches supply Ember Scales; End void catches supply Void Silk. Higher-rarity catches generally produce richer yields. The salvage preview shows the exact return for your selected fish.

Use `/fish materials` to view your supplies, including seasonal materials. You can build up these materials with a normal rod before crafting your first augment.

### Craft and install

Open **Craft Augments** in Rod & Upgrades, or `/fish augments`, and choose **Year-round Augments**, **Seasonal Events** (pick an event to see its own blueprints) or **All Augments**. `/fish augments <category>` opens a list directly. Each lists its fishing-level requirement, recipe, crafting price, slot cost, and owned copies. Clicking a blueprint opens **Craft Augment?**, which shows the coin cost, the recipe and how many copies you already have stored; confirm to spend the coins and ingredients and create **one owned copy**.

Hold the rod you want to improve in your **main hand**, then open `/fish rod` or choose **Manage Held Rod** in **Rod & Upgrades**. There is nothing to register: the rod is set up the first time you open this page. It opens showing the augments you own; its filter button still switches to **Missing** and **All**. **Click** an augment to open **Install Augment?**, which shows the installation fee and the next level's effects; confirm to install one copy and pay the fee. **Right-click** an augment to open **Withdraw a Copy?**, which takes one unused copy out as a tradeable item. On Bedrock, choose the augment, then **Install one copy** or **Withdraw a copy as an item** on its detail form. Installing another copy of the same augment upgrades it by one level, up to its maximum.

The tooltip quotes the price of your **next rank**. With the defaults, each further rank costs three times the previous rank: Reinforced Tackle and Scholar’s Thread cost **1,000, 3,000, then 9,000 coins** to install. Fish Caller costs **15,000, 45,000, then 135,000 coins**. Seasonal augments cost **10,000–15,000 coins** for the first rank. Crafting each copy is a separate cost.

Rods start with **three augment slots** by default. Buy **Expanded Tackle** in `/fish upgrades` to add one slot to every rod you hold, up to **12 total slots** with the defaults. Purchases persist across restarts and apply to any rod you use, including rods you get later. **Branching Line and Fish Caller each use two slots**; the other default augments use one. Upgrading an installed augment does not consume extra slots. **Ember Affinity and Rift Attunement cannot share a rod** with the default settings, so use separate specialized rods if you want both; an augment's description names any augments it can't share a rod with. Additional slots preserve these conflicts and the usual level and realm requirements.

### Remove and rearrange

Use `/fish remove`, select the installed augment, and review the removal confirmation. Removal takes off **all installed levels** of that augment, returning one owned copy for each level. For example, removing a level-three augment returns three copies. The listed removal fee is charged once; previous crafting ingredients and installation fees are not refunded.

**Rods trade freely.** Installed augments stay on the rod itself, so a rod you sell or give away keeps its augments, and whoever holds it gets their bonuses and can install or remove them. The new holder takes the rod over automatically when they hold it, pick it up or open `/fish rod`; if they're mid-cast, the takeover waits until that catch has finished. Removing an augment returns its copies to whoever removes it. Renaming the rod changes nothing, and copying a rod's item can't copy its augments. Unused copies can also be withdrawn and traded from **Augment Copies** in Fish & Storage. Keep your valuable rods safe: losing the rod loses its installed augments, and there is no command to recover an installed loadout.

Sneak and right-click while holding a fishing rod in either hand to open the fishing dashboard.

## Year-round augments

Use `/fish augments standard` to browse these nine blueprints. The ownership toggle cycles **All**, **Owned**, and **Missing**, while keeping your selected category. An augment counts as owned when you have a copy in your pouch or a level installed on any of your rods. Deposit a physical copy into your pouch to include it in this view.

Augment tooltips show the **required fishing level** and **rod slots required**, and name any augments that can't share a rod with it, such as **Ember Affinity** and **Rift Attunement**. A slot requirement applies to the whole augment at every rank: Fish Caller and Branching Line each use **two slots**, even at rank three. Blueprints, rod installation, removal and stored copies appear from lowest to highest required level, including when you change category or ownership filter. Bedrock forms show both requirements in the list and the details. Newly withdrawn augment bundles also show both requirements.

| Augment | Required fishing level | Coins per copy | Augment levels | What it does |
| --- | ---: | ---: | ---: | --- |
| **Reinforced Tackle** | 8 | 15,000 | 3 | Gives a chance to prevent fishing durability loss. |
| **Scholar’s Thread** | 12 | 30,000 | 3 | Increases fishing XP earned from catches. |
| **Trophy Hunter** | 18 | 40,000 | 3 | Favors larger specimens within a species’ normal size range. |
| **Ember Affinity** | 20 | 60,000 | 3 | Shortens lava waits and improves lava rarity luck and catch value. |
| **Treasure Hunter** | 25 | 80,000 | 3 | Has a 3%, 6% or 9% chance to upgrade a qualifying non-treasure vanilla open-water roll to treasure. |
| **Rift Attunement** | 30 | 80,000 | 3 | Improves void rarity luck and fishing XP. |
| **Gold Digger** | 35 | 100,000 | 3 | Adds 15%, 30% or 50% to newly caught fish’s raw value before diminishing returns. |
| **Branching Line** | 45 | 200,000 | 2 | Each reel that catches a fish has a 25% chance to bring up 1 extra fish (rank 1) or 2 (rank 2). |
| **Fish Caller** | 50 | 200,000 | 3 | Successful catches can call a personal pool for 30 seconds; catches inside can yield a second fish. |

The rod menu shows the effects at your next installed level. Realm-specific augments work only in their listed realms.

**Your Fishing Rod** opens showing **Owned** augments, and its filter button cycles **Owned → Missing → All**. Icons show how many copies you own as their stack size (up to 99). Owned includes both pouch copies and augments installed on any of your rods, so installed augments stay visible even when you have no spare copy. Paging and successful installations retain your filter and page. A new catch while browsing can refresh the list without blocking filter or page navigation.

Fish Caller has an **8%, 12% or 16%** activation chance per successful cast, depending on its installed level. It creates one visible personal pool with a **three-block radius** for **30 seconds**. Future catches whose bobbers are inside your pool have a **15%, 25% or 35%** chance to yield a second fish. The pool stays in place, cannot stack or refresh while active, and only benefits its owner in the same realm. Bonus fish use normal creel capacity, XP and catch records; the pool does not multiply vanilla loot or mcMMO XP. **Branching Line and Fish Caller each use two slots**; the other standard augments use one. Treasure Hunter needs a qualifying native open-water cast and uses your normal loot filters. Gold Digger changes new catches’ stored value, so equipping it before selling does not increase an old stockpile’s value.

## Multicasting

**Branching Line** shows **1 extra bobber at rank 1, 2 at rank 2** beside your line. These bobbers never bite on their own: whenever you reel in a fish, there is a **25% chance** that each of them brings up an extra fish too, with a splash where it comes up. Each extra fish is rolled separately, so it can be a different species.

Branching Line and Phantom Tether add extra bobbers beside your main line, each with its own line from your rod, that never bite on their own. When you reel in a fish, they bring up their extra fish with it: Branching Line on its roll, and a triggered Phantom Tether always adds one. The spectral bobber lasts only for that cast. Together they can reach four lines (main, two Branching Line, one spectral).

**One reel collects the lines that are biting at that moment.** A line that has not bitten, has missed its window, or is obstructed does not produce a fish. Each extra bite gives an action-bar alert, and its bobber dips with particles while ready. When **Bite Sounds** is enabled, it also plays the personal chime; bites arriving together share one chime. **Bite Messages** controls extra-line chat independently. You do not need to wait for every line to bite together.

The default limit is **four fish or lines per cast**, including the original, and Branching Line's and Phantom Tether's extra fish count toward it. Several extra-line effects cannot exceed that cap, and unsuitable terrain or busy-server limits may reduce the number available. Extra bobbers are visible only to their owner by default. Ordinary rods have one line. Multicast does not add extra durability wear with the default settings.

Successful extra catches count toward your collection, quests, and tournaments. If there is room for only part of a multicatch, only the fish that fit are stored. Make space before a long fishing session.

## Daily quests and tournaments

Open `/fish quests` to follow these default daily goals:

| Quest | Goal | Reward |
| --- | --- | --- |
| **First Light** | Catch 15 water fish | 200 coins and 200 fishing XP |
| **Forge Runner** | Catch 10 lava fish | 300 coins and 300 fishing XP |
| **Beyond the Edge** | Catch 10 void fish | 350 coins and 350 fishing XP |
| **Steady Hands** | Catch 40 fish across any realms | 500 coins and 500 fishing XP |

Quest progress starts automatically; there is no need to accept a quest first. Progress comes from successful catches, so you can sell or salvage those fish afterward. A catch can advance both its realm quest and Steady Hands. **Click each completed quest to claim its reward before the daily reset.** After claiming, its Java menu icon glows and Bedrock form buttons show **Claimed today**. The menu refreshes on the same page; the glow clears when daily quests reset at midnight Eastern by default.

You also enter the daily tournament simply by fishing at spawn (the ShizukaHarbor world on MineSeed). Catches in other worlds still count for quests, XP and your collection, but not for the daily or chat tournaments. **Tournaments** in the `/fish` menu shows the current contest and standings. The default rotation has three contest types:

| Tournament | What determines your score |
| --- | --- |
| **Most Fish** | Total successful catches that day. |
| **Biggest Weight** | Your heaviest single fish that day. |
| **Longest Fish** | Your longest single fish that day. |

Weight and length contests use one best specimen, not the combined weight or length of your haul. You can sell or salvage a scored fish without losing its score.

Default prizes are **10,000 fishing coins ($10,000) for first**, **5,000 ($5,000) for second**, and **2,500 ($2,500) for third**. Each round runs from midnight to midnight Eastern. **Return to the tournament menu the following day and click to claim your prize.** That claim window lasts only through the following calendar day; prizes are not paid automatically. Exact ties use a consistent player-ID ordering rather than first-catch time.

## Chat tournaments

Every so often a **chat tournament** pops up in chat. It runs for a few minutes (ten by default), and you enter just by fishing at spawn (the tournament worlds). There are seven kinds:

| Chat tournament | How you win |
| --- | --- |
| Most Fish Caught | Catch the most fish. Every accepted catch counts, including bonus copies. |
| Longest Fish | Reel in the single longest fish. |
| Heaviest Fish | Land the single heaviest fish. |
| Shortest Fish | Reel in the single shortest fish. |
| Lightest Fish | Land the single lightest fish. Weights show in kilograms to three decimals, so tiny fish don't all read as 0. |
| Furthest Cast | Catch a fish as far away as you can. Distance is measured flat, from where you stood when you cast to your bobber, so walking away before reeling in doesn't help. After each catch, chat tells you how far that cast went and your best so far. |
| First Catch | The announcement names one fish. The **first angler to catch it wins**, and the tournament ends right then. The fish is picked at random from level-1 water fish that bite in the plains at any time and in any weather (never legendary or seasonal). Reminders repeat its name for anyone who joins late. First Catch pays **one 2,500-coin prize** by default instead of three places. |

Chat shows when one starts, posts the current leaders as it nears the end (five minutes and one minute left by default), and announces the winners when it finishes. Prizes are paid **straight into your fishing coins** the moment it ends, so there is nothing to claim. With equal scores, whoever got there first wins. On MineSeed one starts at the top of every hour. The server decides how often they run, which kinds appear, and in what order. While one runs, a bar at the top of your screen shows its name, the time left and your place. You can mute the announcements and the bar under **Chat Tournaments** in Fishing Settings; you still take part and still get paid.

**Equal gear at spawn:** while a chat tournament is running, your rod augments and your Lure, Luck and Value upgrades do nothing when you fish at spawn (the tournament worlds), so every angler competes on equal terms there. **Legendary fish don't bite at spawn** during a chat tournament either, so nobody wins on one lucky legendary; the other rarities share its chance. Bag size and augment slots still count, and everything works again as soon as the tournament ends. A chat message reminds you when you cast there.

For a longer-term view, staff can open the **Hall of Anglers** with `/fish top`, ranked by catch count. It is staff only; the challenges menu's leaderboard button shows players their own stats instead. Staff can start the leaderboard over; your lifetime stats and Fish Guide records stay. Standings refresh periodically, so a new catch may take a moment to appear.

## Seasonal voyages

Seasonal voyages add new fish, themed crafting materials and event-exclusive augment blueprints. Halloween, winter and spring each offer nine species, and summer adds fifteen. Thirteen augments are on offer: four each for Halloween, winter and spring, and one for summer. Open `/fish events` to check event status, fishing regions, currency, and community progress. Click an event to browse only its augments.

| Event | Default season | Seasonal material |
| --- | --- | --- |
| **Haunted Tides** | October 1–31 | Haunted Essence |
| **Winter’s Wake** | December 1–31 | Sleigh Sparks |
| **Blooming Tides** | March 20–April 30 | Bloom Petals |
| **Sunken Solstice** | June 1–August 31 | Sunlit Sea Glass |

Blooming Tides is the spring/Easter event and follows that annual date range; its start does not move with Easter Sunday.

The event menu identifies **ACTIVE NOW** events first. Events outside their dates are marked **NOT ACTIVE**, with **Preview only** instructions and their next opening date. Their fish, seasonal progress and event rewards are unavailable until that season begins. Server-disabled events say **NOT ACTIVE — disabled by server** and do not promise an opening date. Java menus and Bedrock forms show these notices before the event details.

In October, follow **Haunted Tides** to discover its grounds, catch seasonal species and collect Haunted Essence for blueprints. Guardian progress appears only when that encounter is enabled by the server. **The Sunken Regatta belongs to summer**: outside Sunken Solstice its title and reward option identify it as an inactive preview. You can inspect its information and blueprints, while seasonal fishing progress and reward claims wait for summer. Already-owned seasonal augments still work all year.

### Discover the seasonal fishing grounds

At the start of a season, one discovery biome is selected from that event’s possible regions. The server community needs **three successful catches in the chosen biome** for Halloween, winter or spring, or **twelve for summer**, to unlock that event’s initial fish pool for everyone. The default event menu lists the possible regions; explore them together until the discovery is announced.

After discovery, eligible catches have a default **25% chance to try the event’s fish pool**. Seasonal species still have their own fishing-level and habitat requirements. Halloween, winter and spring each include three water, three lava and three void species. Summer includes five per realm; its later species also require community progress in the Sunken Regatta.

A successful seasonal catch normally earns **one unit of that event’s material**. It is awarded when caught; salvaging stored fish does not create seasonal currency. Check your pouch or event menu to see your balance.

### Earn during the season, use all year

**New seasonal augment copies can be crafted or awarded only while their event is active.** Saving the materials does not let you craft new copies out of season.

Once earned, copies remain yours. You can install, upgrade with already-owned copies, remove, and use them throughout the year, including their visual effects. An event ending does not take away your augments or saved materials.

The thirteen seasonal blueprints, four each for Halloween, winter and spring and one for summer, unlock from **levels 45–70**, with crafting prices of **150,000–300,000 fishing coins per copy**. Their recipes retain **40 event materials and 12 Prismatic Dust**. They have three installed levels with rising installation fees, costing **10,000–15,000 coins** for the first rank. Removal still costs **500 coins** by default. Copies and existing installed ranks are preserved when defaults change, while their current level requirements still apply.

| Seasonal augment | Required fishing level | Coins per copy |
| --- | ---: | ---: |
| Hearthglow Line | 45 | 150,000 |
| Petal Drift | 45 | 150,000 |
| Soul Harvester | 45 | 150,000 |
| Frostbite Hook | 50 | 180,000 |
| Eggshell Guard | 55 | 180,000 |
| Evergreen Spool | 55 | 200,000 |
| Phantom Tether | 55 | 180,000 |
| Tidecaller’s Knot | 55 | 220,000 |
| Meadow Chorus | 60 | 220,000 |
| Witching Hour | 60 | 220,000 |
| Gift Wrap | 65 | 250,000 |
| Hare's Gambit | 65 | 250,000 |
| Trickster’s Bargain | 70 | 300,000 |

### Haunted Tides augments

| Augment | What it does |
| --- | --- |
| **Phantom Tether** | At Minecraft world night, each cast has a 15% / 30% / 45% chance (by rank) to add a spectral bobber for that cast. When you reel in a fish, it brings up one extra fish. Stacks with Branching Line. |
| **Witching Hour** | Improves rarity luck and size rolls while fishing at night in the Minecraft world. |
| **Soul Harvester** | Gives newly caught fish a chance to carry an extra salvage yield. That benefit stays with the catch until salvaged. |
| **Trickster’s Bargain** | Improves rarity luck and catch value in exchange for a shorter bite window. Be ready to reel quickly. |

Soul Harvester’s bonus is decided **when the fish is caught**. Equipping it just before salvaging an old stockpile does not add a bonus to those fish.

### Blooming Tides augments

| Augment | What it does |
| --- | --- |
| **Petal Drift** | During stormy weather, shortens waits and strongly favors larger catches. |
| **Eggshell Guard** | After a missed bite, has a 25%, 45% or 65% chance to attract a quick retry once per cast. It works independently of Mending. |
| **Meadow Chorus** | Grants bonus fishing XP during Minecraft world daytime and a chance for richer salvage on newly caught fish. |
| **Hare’s Gambit** | Offers strong rarity luck in exchange for a shorter bite window; it does not add extra lines. |

## The Sunken Regatta

Sunken Solstice also brings a shared restoration project. Open `/fish regatta` to see how the whole server is rebuilding an ancient vessel. This is a cooperative fishing objective: summer catches contribute automatically while the event is active, and each completed stage reveals more summer species in all three realms.

**The Regatta is summer-only.** Outside Sunken Solstice, the menu says **NOT ACTIVE — preview only** and gives the next summer opening date. Its contributor treasure cannot be claimed then; directly attempting a claim explains the event schedule and currently active events. Browsing its ship, rewards and blueprints remains available. If the server disables the summer event or Regatta, the notice identifies that disabled state instead of suggesting that waiting for summer will enable it.

| Stage | Total summer catches required | What opens |
| --- | ---: | --- |
| Keel of Memories | 15,000 | Golden Keelfish, Cinder Corsair and Spectral Skiff |
| Lantern Rigging | 45,000 | Lantern Lionfish, Lanternmaw and Starwake Manta |
| The Sunlit Sail | 100,000 | Solstice Crown, Solforge Leviathan and Sunless Sovereign |

The thresholds are cumulative. Species unlocked by an earlier stage stay available for the rest of that annual season, subject to their usual fishing requirements. Summer has no guardian fight by default.

Completing the final stage starts a **72-hour celebration**, while the summer event remains active, that adds **20 percentage points** to the chance of trying the summer fish pool. Its normal 25% chance becomes 45%; this is a chance to try that pool, not a guaranteed rare catch.

Players who contributed at least **100 summer catches** can then claim **25,000 fishing coins ($25,000), 10,000 XP and 75 Sunlit Sea Glass** from the Regatta menu, once per annual season. Claim before the summer event ends. Progress, contributions, completed stages and claims survive restarts. A new summer season starts a new restoration.

## Winter’s Wake community guardian

Winter’s Wake also has a shared fishing encounter: the **Frostwake Leviathan**. Catching seasonal winter fish contributes toward the community’s **100-catch target**. This contribution does not spend your Sleigh Sparks. Make at least **three seasonal catches in the current round** to qualify to participate and receive its victory reward.

Once the target is reached and a suitable fishing location and qualifying angler are available, the guardian appears near a recent catch. Gather your qualified anglers nearby:

1. **Break the three bindings by fishing.** Successful catches within 48 blocks of the guardian remove its bindings. These catches can be ordinary fish; they do not all need to be seasonal. Only qualified anglers can break bindings.
2. **Defeat the unbound guardian.** After all bindings break, qualified nearby anglers can damage it with normal attacks and their own projectiles. It has 400 health by default and uses a stationary guardian mob appearance, three times the size of a normal mob.
3. **Receive the victory reward.** Every angler with at least three seasonal contributions to that round receives **20 Sleigh Sparks**, plus an independent **10% chance of an available Christmas augment copy**. Rewards are credited automatically, including for qualified offline contributors; the last hit does not determine who wins them.

The four-minute encounter timer covers both fishing through the bindings and defeating the guardian. If time expires, no qualified angler remains nearby, or the encounter is interrupted by a restart, it ends without a victory reward. A ten-minute cooldown follows before the next contribution round. The guardian does not drop ordinary mob loot or vanilla XP.

Haunted Tides and Blooming Tides also support community guardians, **The Lanternkeeper** and **The Briarbound Keeper**, but those two encounters are disabled in the default setup. Their seasonal fish and augment crafting still work without a boss.

## Seasonal fishing effects

Usable seasonal augments retain their configured seasonal sounds year-round. The decorative circle around waiting bobbers has been removed. Bite cues and ability pools remain visible. Fish Caller marks its exact boundary with a bright cyan ring in water, yellow in lava and purple in the void, raised above the surface so it is easier to see.

## Biome disruption orbs

Want a chance at water fish from other biomes without moving to a new fishing spot? Open `/fish disrupt`, buy a charge, face the water, and throw it. The same controls are available through `/fish disrupt buy` and `/fish disrupt throw`.

With the default settings, a charge costs **5,000 fishing coins**. Landing the orb in overworld water creates a **12-block-radius zone lasting two minutes**. Water catches inside the zone can draw from fish across different biomes, and nearby anglers can share the benefit.

You can also throw a purchased charge by **sneaking and right-clicking while holding a snowball in your main hand**. The snowball is a controller and is not consumed; the purchased virtual charge pays for the throw. A normal snowball alone does not supply a charge.

Disruption bypasses the **biome requirement only**. Fish still need the correct realm, world, fishing level, time, weather, and active/discovered season. It cannot put lava or void species into water or discover an event for you. Only one pending throw or active zone per player is allowed by default, throws have a 30-second cooldown, and overlapping zones do not stack their benefits.

A launched charge is spent even if you miss or the landing is rejected. Your zone disappears if you leave the server or change worlds, and zones do not survive a server restart or plugin reload. Choose your fishing position before throwing.

## Fishing coins and server money

**Fishing coins** pay for fishing upgrades, augments, fees, and disruption charges. **Server money** is your separate Essentials balance. Open `/fish exchange` to convert fishing coins into server money.

Fishing coins appear as **whole numbers** in chat, item descriptions, Java menus and Bedrock forms, rounded to the nearest coin with halves rounded up: `12.2234` shows as `12`, and `12.5` shows as `13`. Your balance, fish values, prices and rewards keep their exact amounts behind those displays. Fractions still accumulate, and sales, purchases and exchanges use the exact saved or requested amounts. Dollar quotes and payouts keep their normal decimal precision.

Future catches use diminishing returns on their stored sale value: size, rarity and value bonuses still help, while stacked bonuses approach **75 fishing coins ($75) per fish**. Previously caught fish retain their saved dollar value. Existing balances and frozen rewards use the smaller denomination too: 1,000 old coins become 1 current coin, without losing fractional value.

The default exchange rate is **1 fishing coin = $1.00**:

| Fishing coins | Server money |
| --- | --- |
| 1 | $1 |
| 100 | $100 |
| 1,000 | $1,000 |
| 10,000 | $10,000 |
| 100,000 | $100,000 |

Menus show server money with thousands separators and leave off `.00` for whole amounts, such as **$10,000** or **$12.50**.

Choose a preset (**1, 100, 1,000, 10,000 or 100,000 coins**), click **Exchange All Coins** to convert your whole balance up to the per-exchange maximum, or use `/fish exchange 1` for a custom amount, then review and confirm the quote. The confirmation stays open after each exchange, so you can click **Confirm** again to exchange the same amount once more (one second apart by default). The default minimum is 1 coin, the maximum is 100,000 coins, and the cooldown is one second. Fractional input amounts are supported up to five decimal places and are exchanged exactly, even though the coin summary shows a whole number; the dollar payout rounds down to its configured money precision.

This exchange works from fishing coins **into** server money. It does not buy fishing coins with server money. To give fishing coins to another player, make a coin voucher with `/withdraw fishingcoins` instead. Seasonal materials are a separate resource and cannot be exchanged here.

If a payout remains pending, contact staff so they can check it. Repeated clicks will not produce additional payments, and further exchanges may stay unavailable until that payout is resolved.

### Coin vouchers

Coin vouchers are made with the server's separate **MineSeedWithdraw** plugin, not the exchange menu, which no longer has a **Make a Coin Voucher** button. Type **`/withdraw fishingcoins <amount>`**, or **`/withdraw fishingcoins all`**, to turn fishing coins into an item you can trade or give to anyone. Whoever holds the voucher redeems it by **right-clicking it twice**, and the coins go into their fishing balance.

Fishing coin vouchers made earlier with the old exchange-menu button (gold nuggets named **Fishing Coins • ×1000**, showing their amount) still work. Hold one in your **main hand and right-click**, or deposit it like a fishing bundle through **Deposit Items** (`/fish deposit`), `/fish deposit all`, or by clicking it in your inventory while a storage menu is open. Each voucher pays out only once; a copied or already-redeemed voucher is worthless. You can keep vouchers in chests or display them in item frames, but like any item they can be lost or stolen. The server can restrict redemption of these older vouchers to the player who made them.

## The Trading Post

Find the **Trading Post** NPC and click it to open the Trading Post. It has two shops:

- **Armor & Tools** sells gear for **fishing coins**.
- **Furniture** sells decorations for **crafting materials** from your material pouch (`/fish materials`), such as Tidal Fiber and Prismatic Dust.

Each item shows its own description and price. Material prices list how many of each material you have stored. **Click an item to buy it.** You pay the whole price and receive the item at once. Purchases are never half-done: if you lack coins or materials, nothing is taken. Make room in your inventory first. If your inventory fills up before the item arrives, the price is returned. Bedrock players open an item's details and choose **Buy this item**.

Server staff choose what each shop sells and what it costs, so items and prices may differ from the examples here.

## Special crate rods

Supported MineSeedCrateItems rods can retain their special fishing benefits while using this fishing system. **Use these special rods in your main hand** for their integrated bonuses, progression, and Recast. Their configured double-catch chances can add bonus fish to your creel, and supported automatic Recast rods can cast another line after a successful catch. December rod progression follows eligible original pufferfish catches. Fishing Crate and April 2026 automatic recasts keep normal fishing waits and speed bonuses; automatic casting alone does not make fish bite instantly. December’s separate level-based fishing speed remains part of that rod’s ability.

Recast starts a **new cast after the previous catch**; multicasting supplies extra lines **within one cast**. A Recast rod does not need Branching Line, and Recast alone should not create a second simultaneous bobber. You still need to reel at the bite. Switching rods, moving to another world, or making an intervening manual cast can cancel a queued automatic recast.

Bonus copies can count toward collection, daily quests, tournaments, and resale value. They do not repeat the original fish’s fishing XP, seasonal currency, progress. The specific crate rod’s description determines its chances and unlocks; not every special rod has every effect.

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
