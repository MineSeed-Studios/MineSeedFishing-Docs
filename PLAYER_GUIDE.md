# MineSeedFishing — Player Guide

From quiet rivers to the lava pools of the Nether and the open void beneath End islands, MineSeedFishing gives you three realms to explore, a collection to build, and a rod you can make your own. Catch unusual species, turn your haul into coins or crafting materials, compete in daily tournaments, and return throughout the year for seasonal fishing adventures.

**Start with `/fish` or `/fishing`.** Both commands open **Angler’s Haven**, your fishing dashboard, and work interchangeably for every command in this guide. `/msfish` is another alias. MineSeedFishing takes priority for `/fishing` when mcMMO is installed; use `/mcmmo:fishing` for mcMMO’s fishing skill page.

This guide describes version **1.6.0 with its default settings**. The server can change prices, rewards, recipes, dates, requirements, and available features. Check the live menus for the settings currently in use. Daily resets and seasonal dates default to **US/Eastern**, automatically following Eastern Standard Time and Eastern Daylight Time. Fish that require day, night, or particular weather follow the **Minecraft world’s conditions**.

## Your first fishing trip

1. Bring an ordinary fishing rod and play in Survival or Adventure mode.
2. Cast into overworld water, Nether lava, or a clear gap beside an End island.
3. Wait for a bite, then reel in. Lava and void fishing first display a message confirming that your line is ready.
4. Open `/fish bag` to see your catches. They go into your personal **creel**, a virtual fish bag.
5. Sell your haul for fishing coins, or salvage selected species for augment materials.
6. Check `/fish quests` for rewards you can claim, then explore `/fish upgrades` and `/fish workshop`.

**You do not need an augment to unlock any of the three realms.** Ember Affinity improves lava fishing, and Rift Attunement improves void fishing. An ordinary rod can already catch the fish used to make them.

## Fishing in the three realms

With the updated **MineSeedJobs** integration installed, eligible catches in **water, Nether lava, and End void** also count toward the Fisherman job after you join it. Job XP, money, and points follow the server's Jobs configuration. Each successfully caught original multicast line counts by default; extra bonus copies from augments or crate rods do not.

### Overworld water

Cast into water and reel in at the normal fishing bite. Successful custom catches go straight into your creel and award fishing experience. The catch message shows the species, length, weight, value, and XP.

Different species can require different biomes, fishing levels, times of day, or weather. Explore new waters and check the **Field Guide** when looking for a particular fish.

### Nether lava

Find an actual lava pool **in the Nether** and cast into it. Your bobber should settle near the surface, followed by a **Nether lava line ready** message. Wait for **BITE!**, then reel in promptly.

Without bonuses, the default wait after settling is approximately **8–25 seconds**, with about **2.25 seconds** to reel during the bite. Lure, upgrades, and suitable augments can shorten the wait. Lava elsewhere does not activate this Nether fishing mode.

### End void

Stand near an island edge **in the End** and cast out over empty space. The hook needs a clear column of air beneath it, with no island or other blocks below. It initially falls at least eight blocks from your casting height before establishing the line.

Once you see **End void line ready**, wait for **BITE!** and reel in. The default wait is approximately **9–27.5 seconds**, with about **2.25 seconds** to respond. Stay reasonably close to the line; the default maximum distance is 30 blocks.

Casting upward over land will simply make the bobber fall again. Aim out over the gap. If there is no ready message, the line has not found a valid void fishing position.

Keep the same rod held while fishing. Opening an inventory menu, switching or dropping the active rod, teleporting, changing worlds, dying, or leaving can end an unfinished cast. Rods still lose durability through fishing; durability augments can help protect them.

## Fish, rarity, and your collection

The default collection contains **273 species**: **231 year-round species** and **42 seasonal species**. Fish range from **Common** through **Uncommon, Rare, Epic, and Legendary**. Some discoveries require a higher fishing level or particular conditions. Luck improves your odds of rarer catches but does not guarantee them or bypass their requirements.

Each catch has its own length, physical weight, and sale value. Larger specimens of the same species are generally worth more, while rarity and species also matter. Legendary catches are announced to the server by default.

Open `/fish catalog` to browse the **Field Guide**. It shows each species’ realm, rarity, required level, habitat, time and weather conditions, possible size range, discovery status, total caught, and your largest recorded length. This is also your collection journal: selling or salvaging a fish does not erase the discovery or record.

Custom fish artwork appears in the menus and on manually withdrawn fish when the server’s ItemsAdder pack and your resource pack are available. Menu icons are previews: use Angler Storage to withdraw an item instead of dragging an icon out.

## Your creel: keep, sell, or salvage

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

## Fishing levels and permanent upgrades

Fishing XP is separate from vanilla Minecraft experience. You start at **fishing level 1** and can reach **level 100**. Each new level requires more XP than the last; the default total for level 100 is **9,801,000 fishing XP**. Catching fish, claiming quests, and completing certain activities earn fishing XP. Higher levels unlock more species and augment blueprints.

XP is cumulative: reaching a level does not spend it. Default milestones are **81,000 XP at level 10**, **576,000 at level 25**, **2,401,000 at level 50**, and **5,476,000 at level 75**. Multicasting, luck, XP augments, rod bonuses and activities affect how quickly you advance.

Hover over your player head in `/fish` to see your **XP progress bar**. It shows progress through your current level, along with the XP earned toward its requirement and a percentage. Reaching a new level starts that bar again; your total fishing XP stays saved. At the level cap, the bar is full and marked **Maximum level reached**.

Use **`/fish info`** to display your fishing profile directly in chat: level and XP progress, fishing coins, lifetime catches, collection, and total fishing XP. **`/fish info <player>`** shows another angler’s saved profile, including when they are offline. Use their last saved player name or UUID; unknown players do not receive an empty profile. Names are matched without case sensitivity, and a UUID can distinguish players when a saved name is ambiguous. `/fishing info` works the same way. The server can restrict looking up other players, and console users must provide a player name or UUID.

The upgrades in `/fish upgrades` belong to your **player profile**, so they continue working when you change rods. Each purchase increases that upgrade by one level, and later levels cost more.

| Upgrade | Benefit per level | Default maximum | First purchase |
| --- | --- | --- | --- |
| **Quickline** | 8% shorter fishing waits | 5 levels; 40% reduction | 500 coins |
| **Lucky Current** | Increased rarity luck | 5 levels | 800 coins |
| **Fine Catch** | 10% more value on future catches | 5 levels; +50% value | 700 coins |
| **Deep Creel** | Space for 50 additional fish | 8 levels; 500 total capacity | 400 coins |

If the server adopts a harder level curve, your displayed level can change while your accumulated fishing XP remains saved. The live menus always use the server’s current requirements.

The menu displays your current level, benefit per level, and next purchase price. Buying an account upgrade does not occupy an augment slot on your rod.

## The rod workshop

Augments let you specialize a particular rod. Open `/fish workshop` to craft copies, install them, remove them, salvage fish, and browse your material pouch.

### Gather materials

Salvaging gives materials instead of coins. The main materials are **Tidal Fiber**, **Prismatic Dust**, **Ember Scale**, and **Void Silk**. Nether lava catches supply Ember Scales; End void catches supply Void Silk. Higher-rarity catches generally produce richer yields. The salvage preview shows the exact return for your selected fish.

Use `/fish materials` to view your supplies, including seasonal materials. You can build up these materials with a normal rod before crafting your first augment.

### Craft and install

Browse `/fish augments` to see the available blueprints. Each lists its fishing-level requirement, recipe, crafting price, slot cost, and owned copies. Clicking a craftable blueprint spends the displayed coins and ingredients to create **one owned copy**.

Hold the rod you want to improve in your **main hand**, then open `/fish rod` or choose **Register Held Rod** in the workshop. This binds the rod to your fishing profile. Select an augment to install a copy and pay its installation fee. Installing another copy of the same augment upgrades it by one level, up to its maximum.

Rods have **three augment slots** by default. **Branching Line uses two slots**; every other default augment uses one. Upgrading an installed augment does not consume extra slots. **Ember Affinity and Rift Attunement cannot share a rod** with the default settings, so use separate specialized rods if you want both. The server can configure other conflicts.

### Remove and rearrange

Use `/fish remove`, select the installed augment, and review the removal confirmation. Removal takes off **all installed levels** of that augment, returning one owned copy for each level. For example, removing a level-three augment returns three copies. The listed removal fee is charged once; previous crafting ingredients and installation fees are not refunded.

Installed augments belong to the registered rod’s owner. Another player can fish normally with that rod but does not receive its augment benefits or gain permission to modify them. Renaming the rod does not change its ownership. Unused copies can be withdrawn and traded through Angler Storage. Keep your valuable rods safe: losing the rod loses access to its installed augments, and there is no player command to transfer or recover an installed loadout.

## Year-round augments

Use `/fish augments standard` to browse these six blueprints.

| Augment | Required fishing level | Augment levels | What it does |
| --- | --- | --- | --- |
| **Branching Line** | 5 | 2 | Adds one extra fishing line at level one and two extra lines at level two. Each line has its own bite timing. |
| **Trophy Hunter** | 3 | 3 | Favors larger specimens within a species’ normal size range. Useful when hunting personal records and large tournament catches. |
| **Ember Affinity** | 4 | 3 | Shortens lava waits and improves lava rarity luck and catch value. |
| **Rift Attunement** | 4 | 3 | Improves void rarity luck and fishing XP. |
| **Reinforced Tackle** | 2 | 3 | Gives a chance to prevent fishing durability loss. It does not make the rod unbreakable. |
| **Scholar’s Thread** | 2 | 3 | Increases the fishing XP earned from catches. |

The rod menu shows the effects at your next installed level. Realm-specific augments work only in their listed realms.

## Multicasting

With Branching Line or a successful seasonal extra-line effect, additional bobbers spread out beside your main line. These are independent fishing lines: each needs a suitable location and gets its own wait and bite window.

**One reel collects the lines that are biting at that moment.** A line that has not bitten, has missed its window, or is obstructed does not produce a fish. Watch for the extra-line bite message; you do not need to wait for every line to bite together.

The default limit is **three total lines per cast**, including the original. Several extra-line effects cannot exceed that cap, and unsuitable terrain or busy-server limits may reduce the number available. Extra bobbers are visible only to their owner by default. Ordinary rods have one line. Multicast does not add extra durability wear with the default settings.

Successful extra catches count toward your collection, quests, and tournaments. If there is room for only part of a multicatch, only the fish that fit are stored. Make space before a long fishing session.

## Daily quests and tournaments

Open `/fish quests` to follow these default daily goals:

| Quest | Goal | Reward |
| --- | --- | --- |
| **First Light** | Catch 15 water fish | 20 coins and 200 fishing XP |
| **Forge Runner** | Catch 10 lava fish | 30 coins and 300 fishing XP |
| **Beyond the Edge** | Catch 10 void fish | 35 coins and 350 fishing XP |
| **Steady Hands** | Catch 40 fish across any realms | 50 coins and 500 fishing XP |

Quest progress starts automatically; there is no need to accept a quest first. Progress comes from successful catches, so you can sell or salvage those fish afterward. A catch can advance both its realm quest and Steady Hands. **Click each completed quest to claim its reward before the daily reset.** Quests reset at midnight Eastern by default.

You also enter the daily tournament simply by fishing. `/fish tournaments` shows the current contest and standings. The default rotation has three contest types:

| Tournament | What determines your score |
| --- | --- |
| **Most Fish** | Total successful catches that day. |
| **Biggest Weight** | Your heaviest single fish that day. |
| **Longest Fish** | Your longest single fish that day. |

Weight and length contests use one best specimen, not the combined weight or length of your haul. You can sell or salvage a scored fish without losing its score.

Default prizes are **1,000 coins for first**, **500 for second**, and **250 for third**. Each round runs from midnight to midnight Eastern. **Return to the tournament menu the following day and click to claim your prize.** That claim window lasts only through the following calendar day; prizes are not paid automatically. Exact ties use a consistent player-ID ordering rather than first-catch time.

For a longer-term competition, `/fish top` opens the **Hall of Anglers**, ranked by lifetime catch count. Standings refresh periodically, so a new catch may take a moment to appear.

## Seasonal voyages

Seasonal voyages add new fish, themed crafting materials and event-exclusive augment blueprints. Halloween, winter and spring each offer nine species and four augments; summer adds fifteen species and five interactive augments. Open `/fish events` to check event status, fishing regions, currency, and community progress. Click an event to browse only its augments.

| Event | Default season | Seasonal material |
| --- | --- | --- |
| **Haunted Tides** | October 1–31 | Haunted Essence |
| **Winter’s Wake** | December 1–31 | Sleigh Sparks |
| **Blooming Tides** | March 20–April 30 | Bloom Petals |
| **Sunken Solstice** | June 1–August 31 | Sunlit Sea Glass |

Blooming Tides is the spring/Easter event and follows that annual date range; its start does not move with Easter Sunday.

### Discover the seasonal fishing grounds

At the start of a season, one discovery biome is selected from that event’s possible regions. The server community needs **three successful catches in the chosen biome** for Halloween, winter or spring, or **twelve for summer**, to unlock that event’s initial fish pool for everyone. The default event menu lists the possible regions; explore them together until the discovery is announced.

After discovery, eligible catches have a default **25% chance to try the event’s fish pool**. Seasonal species still have their own fishing-level and habitat requirements. Halloween, winter and spring each include three water, three lava and three void species. Summer includes five per realm; its later species also require community progress in the Sunken Regatta.

A successful seasonal catch normally earns **one unit of that event’s material**. It is awarded when caught; salvaging stored fish does not create seasonal currency. Check your pouch or event menu to see your balance.

### Earn during the season, use all year

**New seasonal augment copies can be crafted or awarded only while their event is active.** Saving the materials does not let you craft new copies out of season.

Once earned, copies remain yours. You can install, upgrade with already-owned copies, remove, and use them throughout the year, including their activities and visual effects. An event ending does not take away your augments or saved materials.

All seventeen default seasonal blueprints require **fishing level 5**. Halloween, winter and spring copies cost **40 of their event’s material, 12 Prismatic Dust and 4,000 fishing coins**. Summer copies cost **60 Sunlit Sea Glass, 20 Prismatic Dust and 4,000 fishing coins**. All have a **100-coin installation fee** and **50-coin removal fee**. Halloween and spring augments have three levels; winter and summer activity augments have one. Each copy supplies one installed level.

### Haunted Tides augments

| Augment | What it does |
| --- | --- |
| **Phantom Tether** | Gives a chance to add an extra independently timed line, within the normal multicast limits. |
| **Witching Hour** | Improves rarity luck and size rolls while fishing at night in the Minecraft world. |
| **Soul Harvester** | Gives newly caught fish a chance to carry an extra salvage yield. That benefit stays with the catch until salvaged. |
| **Trickster’s Bargain** | Improves rarity luck and catch value in exchange for a shorter bite window. Be ready to reel quickly. |

Soul Harvester’s bonus is decided **when the fish is caught**. Equipping it just before salvaging an old stockpile does not add a bonus to those fish.

### Blooming Tides augments

| Augment | What it does |
| --- | --- |
| **Petal Drift** | Shortens waits and gently favors larger catches. |
| **Eggshell Guard** | Gives a chance to prevent fishing durability loss. |
| **Meadow Chorus** | Grants more fishing XP and a chance for extra salvage on newly caught fish. |
| **Hare’s Gambit** | Offers an extra-line chance and improved rarity luck, with a shorter bite window. |

### Winter’s Wake augments and rod activities

The four winter augments unlock activities with their own goals. Hold the registered rod with the matching augment installed, open `/fish activities`, and select it. The detail menu shows your target, progress, remaining time, and available actions.

Activities have time limits, cooldowns, and a default limit of **six starts per hour for each activity augment**. Timers continue while you are offline. Keep using the rod tied to the activity, and read the current target before making your next catch.

**Star Stitcher — follow a constellation.** First make a nearby catch so the activity has a fishing location to use. Begin the activity in a sufficiently open area, then cast and catch at each marked star position in order. The default challenge has three targets. After the final target, make **one more successful catch** before the timer expires to collect the constellation reward. This final catch gets a luck boost and automatically awards **20 coins, 200 fishing XP, and 2 Prismatic Dust**. Particle markers help you aim, and the detail menu shows the target coordinates. The default time limit is five minutes, with a five-minute cooldown measured from starting.

**Krampus’ Bargain — bank your reward or risk another stage.** Keep a fish from your most recently caught species in the creel, then begin. Starting consumes one of those fish as the stake. Complete the required realm catches to reach a reward offer. At that point, choose **Bank Wager** to collect your winnings and stop, or **Risk Another Stage** to put the offered reward at risk for a larger payout.

The realm cycle is **water → lava → void → water**, starting in the next realm after your last catch. Default stages require one, then two, then three catches. Each new stage gives you five minutes. The first stage adds **20 coins, 200 XP, and 2 Prismatic Dust** to your stake’s value; later stages add larger rewards. Completing all three and banking pays the stake value plus **120 coins, 1,200 XP, and 12 Prismatic Dust**. The stake is valued at the average stored sale value of that species in your creel. The menu shows your actual bankable reward.

Bank promptly: even an offered reward can expire. Cancelling while an unexpired offer is available banks it; abandoning an unfinished challenge loses the committed stake. Other fish and the rest of your coin balance are not wagered. The default cooldown is five minutes from starting.

**Toymaker’s Thread — turn catches into a collection.** Choose a toy recipe while you have at least one required ingredient fish in your creel. Starting consumes one available ingredient. You then need to catch the remaining required species fresh; matching catches are woven into the recipe automatically and do not also enter your bag for sale. Completing the recipe grants its listed coins, XP, and materials and increases its completion count. Toys are recorded collectibles in the activity menu, rather than physical inventory items.

| Toy recipe | Total ingredients, including the starting fish | Completion reward |
| --- | --- | --- |
| **Clockwork Minnow** | 1 Reed Darter, 1 Cinder Guppy, 1 Dusk Minnow | 30 coins, 200 XP, 8 Tidal Fiber |
| **Astral Kite** | 2 Glass Perch, 1 Soulglass Ray, 1 Nebula Ray | 50 coins, 350 XP, 8 Prismatic Dust |

Both recipes take you across the three realms. The default time limit is ten minutes, with a one-minute cooldown from starting. Cancellation or expiry does not return consumed ingredients. Having every ingredient stored beforehand does not complete the toy instantly: only the first comes from your bag.

**Ribbon Relay — complete a shared challenge.** Both anglers need the relay augment installed on their rods. Invite a partner with `/fish relay invite PlayerName`; they accept with `/fish relay accept YourName` within 60 seconds. Follow the activity menu to see whose turn it is and which realm is required. The inviter takes the first turn in their current realm, then turns alternate while the target cycles through water, lava, and void. Only the correct player’s catch in the required realm advances it.

The default relay requires three successful turns within five minutes, with a five-minute cooldown from starting. Once complete, **each player must claim their own reward** from the activity menu: **20 coins, 200 fishing XP, and 2 Prismatic Dust each**. A completed relay reward remains claimable after the challenge timer or a logout. Cancelling an unfinished relay ends the shared challenge.

You can open an individual activity directly with `/fish activity star_stitcher`, `/fish activity krampus_bargain`, `/fish activity toymakers_thread`, or `/fish activity ribbon_relay`.

### Sunken Solstice augments and activities

These five augments turn successful fishing into personal choices and longer projects. Craft them during Sunken Solstice, install one on your registered rod, and use `/fish activities` or `/fish activity <augment_id>` to check its progress. Keep that same rod held when choosing or collecting rewards. Their abilities remain usable all year after you have earned the copies.

**Siren’s Bargain — choose your next discovery.** Successful catches have a default **4% chance** to offer two eligible species. Open the Siren’s Bargain activity, choose one, then catch it with the same rod before the **ten-minute offer window** expires. Choosing does not immediately award a fish: you still have to fish successfully, and the species must remain eligible for your realm, biome, level, time, weather and seasonal unlocks. A change of conditions can mean waiting or returning to the right spot.

**Stormglass — save a personal surge.** Build charge with **twelve successful catches**, then activate the ability from its menu. For up to **three minutes or eight eligible catches**, your line draws from a special configured fish pool under a private storm. Its weather requirement is evaluated as stormy even when the world is clear; other players’ weather does not change. Realm, world, biome, time, level, seasonal calendar, discovery and Regatta unlock requirements still apply. Charging and spending charge are separate choices.

**Pearl Diver — open now or grow a better reward.** Each successful catch has a **5% chance** to find a virtual oyster, with room for **three oysters**. Open one immediately for **75 coins, 100 XP and 3 Tidal Fiber**, or keep it through **twelve further successful catches** to mature it. A mature oyster awards **250 coins, 350 XP, 5 Prismatic Dust and 8 Tidal Fiber**. The menu shows each oyster’s growth and lets you choose which to open. Oysters remain virtual and cannot be withdrawn or traded. Their rewards enter your fishing profile first; eligible material and augment rewards can later be withdrawn through Angler Storage.

**Prismatic Current — collect a spectrum.** Catch fish from **three different rarities**, then choose one temporary benefit for your next **eight successful catches**: favor eligible undiscovered species, favor larger sizes, or add one salvage unit to newly caught fish. The discovery choice has a default **50% chance per catch** to prefer unseen eligible species; it cannot unlock a forbidden habitat or guarantee a legendary. The size choice adds a size bias of **0.4**. The salvage choice stays attached to the affected catch until you salvage it. Every successful original catch spends one of the eight uses, including catches whose species is selected by Siren’s Bargain or Stormglass. After the benefit runs out, build a new spectrum.

**Message in a Bottle — follow a fishing trail.** A successful catch has a **2.5% chance** to uncover a personal voyage. You have **one hour** to complete its clues in order: catch three water fish, two Nether lava fish, then one End void fish at least 20 cm long. Check the activity menu for the current clue. Once all clues are finished, claim the cache there. The cache is selected when the voyage begins and can be claimed once; reopening the menu does not reroll it.

| Bottle cache | Default chance | Reward |
| --- | ---: | --- |
| Mariner’s Satchel | 60% | 500 coins, 500 XP, 12 Tidal Fiber and 4 Prismatic Dust |
| Ember Coffer | 25% | 1,000 coins, 750 XP, 8 Ember Scale and 8 Void Silk |
| Tidekeeper’s Cache | 15% | 1,750 coins, 1,000 XP and 12 Prismatic Dust |

These activities count successful original catches. Bonus copies do not repeat their progress or rewards. Timed opportunities keep their deadlines through logout or restart; saved oyster growth, charge and completed claimable caches remain in your profile.

The menu’s **Discard progress and unclaimed rewards** action permanently forfeits that activity’s saved progress, unused effects, unclaimed oysters or completed cache. It grants no replacement reward. This can clear an activity left behind by a lost rod: hold another rod you own with the same usable augment installed, open its activity and discard the old state. Claim or open earned rewards first if you want to keep them. You still need a held, usable copy of the matching augment to perform this action.

## The Sunken Regatta

Sunken Solstice also brings a shared restoration project. Open `/fish regatta` to see how the whole server is rebuilding an ancient vessel. This is a cooperative fishing objective: summer catches contribute automatically while the event is active, and each completed stage reveals more summer species in all three realms.

| Stage | Total summer catches required | What opens |
| --- | ---: | --- |
| Keel of Memories | 15,000 | Golden Keelfish, Cinder Corsair and Spectral Skiff |
| Lantern Rigging | 45,000 | Lantern Lionfish, Lanternmaw and Starwake Manta |
| The Sunlit Sail | 100,000 | Solstice Crown, Solforge Leviathan and Sunless Sovereign |

The thresholds are cumulative. Species unlocked by an earlier stage stay available for the rest of that annual season, subject to their usual fishing requirements. Summer has no guardian fight by default.

Completing the final stage starts a **72-hour celebration**, while the summer event remains active, that adds **20 percentage points** to the chance of trying the summer fish pool. Its normal 25% chance becomes 45%; this is a chance to try that pool, not a guaranteed rare catch.

Players who contributed at least **100 summer catches** can then claim **5,000 fishing coins, 10,000 XP and 75 Sunlit Sea Glass** from the Regatta menu, once per annual season. Claim before the summer event ends. Progress, contributions, completed stages and claims survive restarts. A new summer season starts a new restoration.

## Winter’s Wake community guardian

Winter’s Wake also has a shared fishing encounter: the **Frostwake Leviathan**. Catching seasonal winter fish contributes toward the community’s **100-catch target**. This contribution does not spend your Sleigh Sparks. Make at least **three seasonal catches in the current round** to qualify to participate and receive its victory reward.

Once the target is reached and a suitable fishing location and qualifying angler are available, the guardian appears near a recent catch. Gather your qualified anglers nearby:

1. **Break the three bindings by fishing.** Successful catches within 48 blocks of the guardian remove its bindings. These catches can be ordinary fish; they do not all need to be seasonal. Only qualified anglers can break bindings.
2. **Defeat the unbound guardian.** After all bindings break, qualified nearby anglers can damage it with normal attacks and their own projectiles. It has 400 health by default and uses a stationary guardian mob appearance.
3. **Receive the victory reward.** Every angler with at least three seasonal contributions to that round receives **20 Sleigh Sparks**, plus an independent **10% chance of an available Christmas augment copy**. Rewards are credited automatically, including for qualified offline contributors; the last hit does not determine who wins them.

The four-minute encounter timer covers both fishing through the bindings and defeating the guardian. If time expires, no qualified angler remains nearby, or the encounter is interrupted by a restart, it ends without a victory reward. A ten-minute cooldown follows before the next contribution round. The guardian does not drop ordinary mob loot or vanilla XP.

Haunted Tides and Blooming Tides also support community guardians, **The Lanternkeeper** and **The Briarbound Keeper**, but those two encounters are disabled in the default setup. Their seasonal fish and augment crafting still work without a boss.

## Seasonal fishing effects

Usable seasonal augments add atmosphere around your fishing spot: a spooky purple ring for Halloween, drifting snowflakes for winter, cherry petals for spring and sparks for summer, with matching sounds. These effects can continue year-round with augments you already own.

By default, only the angler sees their augment effects. If several seasonal styles are equipped, one matching style is shown. These are visual effects around the line; they do not change water blocks, biome colors, or terrain.

## Biome disruption orbs

Want a chance at water fish from other biomes without moving to a new fishing spot? Open `/fish disrupt`, buy a charge, face the water, and throw it. The same controls are available through `/fish disrupt buy` and `/fish disrupt throw`.

With the default settings, a charge costs **500 fishing coins**. Landing the orb in overworld water creates a **12-block-radius zone lasting two minutes**. Water catches inside the zone can draw from fish across different biomes, and nearby anglers can share the benefit.

You can also throw a purchased charge by **sneaking and right-clicking while holding a snowball in your main hand**. The snowball is a controller and is not consumed; the purchased virtual charge pays for the throw. A normal snowball alone does not supply a charge.

Disruption bypasses the **biome requirement only**. Fish still need the correct realm, world, fishing level, time, weather, and active/discovered season. It cannot put lava or void species into water or discover an event for you. Only one pending throw or active zone per player is allowed by default, throws have a 30-second cooldown, and overlapping zones do not stack their benefits.

A launched charge is spent even if you miss or the landing is rejected. Your zone disappears if you leave the server or change worlds, and zones do not survive a server restart or plugin reload. Choose your fishing position before throwing.

## Fishing coins and server money

**Fishing coins** pay for fishing upgrades, augments, fees, and disruption charges. **Server money** is your separate Essentials balance. Open `/fish exchange` to convert fishing coins into server money.

The default exchange rate is **1,000 fishing coins = $1.00**:

| Fishing coins | Server money |
| --- | --- |
| 1,000 | $1.00 |
| 10,000 | $10.00 |
| 100,000 | $100.00 |

Choose a preset or use `/fish exchange 1000` for a custom amount, then review and confirm the quote. The default minimum is 1,000 coins, the maximum is 1,000,000 coins, and the cooldown is five seconds. Fractional amounts are supported up to two decimal places; the payout rounds down to the displayed money precision.

This exchange works from fishing coins **into** server money. It does not transfer coins to another player or buy fishing coins with server money. Seasonal materials are a separate resource and cannot be exchanged here.

If a payout remains pending, contact staff so they can check it. Repeated clicks will not produce additional payments, and further exchanges may stay unavailable until that payout is resolved.

## Special crate rods

Supported MineSeedCrateItems rods can retain their special fishing benefits while using this fishing system. **Use these special rods in your main hand** for their integrated bonuses, progression, and Recast. Their configured double-catch chances can add bonus fish to your creel, and supported automatic Recast rods can cast another line after a successful catch. December rod progression follows eligible original pufferfish catches. Fishing Crate and April 2026 automatic recasts keep normal fishing waits and speed bonuses; automatic casting alone does not make fish bite instantly. December’s separate level-based fishing speed remains part of that rod’s ability.

Recast starts a **new cast after the previous catch**; multicasting supplies extra lines **within one cast**. A Recast rod does not need Branching Line, and Recast alone should not create a second simultaneous bobber. You still need to reel at the bite. Switching rods, moving to another world, or making an intervening manual cast can cancel a queued automatic recast.

Bonus copies can count toward collection, daily quests, tournaments, and resale value. They do not repeat the original fish’s fishing XP, seasonal currency, or activity progress. The specific crate rod’s description determines its chances and unlocks; not every special rod has every effect.

## Command reference

Every command below also works with `/fishing` in place of `/fish`.

| Command | Opens or performs |
| --- | --- |
| `/fish` | Angler’s Haven dashboard and profile. |
| `/fish info [player]` | Your profile in chat, or another saved angler’s profile by name or UUID, including offline players. |
| `/fish bag` | Your creel. |
| `/fish items`, `/fish withdraw` | Angler Storage: withdraw fish, materials or unused augment copies. |
| `/fish deposit` | Choose a physical fishing bundle to return to virtual storage. |
| `/fish catalog` | Field Guide, discoveries, and personal records. |
| `/fish sell` | Full-creel sale confirmation. |
| `/fish upgrades` | Permanent player upgrades. |
| `/fish quests` | Daily quest progress and reward claims. |
| `/fish tournaments` | Today’s contest and yesterday’s prize claim. |
| `/fish top` | Lifetime catch leaderboard. |
| `/fish workshop` | Rod workshop hub. |
| `/fish salvage` | Species or whole-creel salvage previews. |
| `/fish materials` | Your crafting-material pouch. |
| `/fish augments` | All augment blueprints. |
| `/fish augments standard` | Year-round blueprints. |
| `/fish augments halloween` | Haunted Tides blueprints. |
| `/fish augments christmas` | Winter’s Wake blueprints. |
| `/fish augments spring` | Blooming Tides blueprints. |
| `/fish augments summer` | Sunken Solstice blueprints. |
| `/fish regatta` | Summer community restoration, fish unlocks and reward claim. |
| `/fish rod` | Register/manage the rod in your main hand and install copies. |
| `/fish remove` | Augment removal and copy recovery. |
| `/fish events` | Seasonal Voyages. `/fish seasonal` opens the same menu. |
| `/fish activities` | Interactive rod activities. |
| `/fish activity <augment_id>` | One activity’s details and controls. |
| `/fish relay invite <player>` | Invite an angler to Ribbon Relay. |
| `/fish relay accept <player>` | Accept that angler’s invitation. |
| `/fish disrupt` | Disruption charge menu. |
| `/fish disrupt buy` | Buy one charge. |
| `/fish disrupt throw` | Throw one purchased charge. |
| `/fish exchange` | Coin exchange menu. |
| `/fish exchange <coins>` | Preview a custom conversion. |
| `/fish help` | In-game command help. |

Activity actions also have direct commands: append `start`, `cancel`, `bank`, `raise`, or `claim` to `/fish activity <augment_id>` as appropriate. Toy recipes use `/fish activity toymakers_thread recipe <recipe_id>`, such as `clockwork_minnow`. The menus provide the same activity controls without requiring you to remember these IDs.

## When something is not working

**“No fish are biting here.”** Check your fishing level and the species’ realm, biome, time, and weather requirements. A catalog entry is a discovery goal, not a guarantee that the fish can currently be caught.

**The hook keeps sinking or falling.** Look for the ready message. Lava fishing needs contact with Nether lava; void fishing needs a clear gap below an End island. Stay within range and keep your rod held.

**A recipe needs Ember Scales or Void Silk.** Fish in Nether lava or End void with a normal rod, then salvage the catches. The matching realm augment comes afterward.

**An augment does nothing.** Make sure the rod belongs to you, the copy is installed, you meet its level requirement, and you are in a supported realm or condition. Owning a copy in your pouch does not apply its effect.

**An activity is unavailable.** Hold the registered rod with its matching augment installed. Check its cooldown, remaining time, and start limit. Seasonal ownership permits year-round use, but the augment still needs to be enabled by the server.

**A menu asks you to review again.** Your bag, balance, or rod changed after the preview opened. Read the refreshed details and confirm the new preview.

**An item will not withdraw or deposit.** Use Survival or Adventure and wait for any current transfer to finish. Withdrawal needs an empty inventory slot; a fish deposit needs space for the whole bundle in your creel. Only genuine Fishing bundles can be deposited, and only unused augment copies can be withdrawn. The server can disable transfers or particular item categories.

**You cannot cast at all.** Make room in your creel, use Survival or Adventure, wait for your fishing profile to finish loading, and try an allowed fishing area. Server permissions and protected regions can restrict fishing.
