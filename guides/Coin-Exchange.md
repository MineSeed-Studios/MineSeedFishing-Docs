# Coin Exchange

> Based on MineSeedFishing 1.10.0 defaults. Check the server’s menus for customized requirements, prices, and rewards. Calendar dates use US/Eastern by default.

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

## Coin vouchers

Coin vouchers are made with the server's separate **MineSeedWithdraw** plugin, not the exchange menu, which no longer has a **Make a Coin Voucher** button. Type **`/withdraw fishingcoins <amount>`**, or **`/withdraw fishingcoins all`**, to turn fishing coins into an item you can trade or give to anyone. Whoever holds the voucher redeems it by **right-clicking it twice**, and the coins go into their fishing balance.

Fishing coin vouchers made earlier with the old exchange-menu button (gold nuggets named **Fishing Coins • ×1000**, showing their amount) still work. Hold one in your **main hand and right-click**, or deposit it like a fishing bundle through **Deposit Items** (`/fish deposit`), `/fish deposit all`, or by clicking it in your inventory while a storage menu is open. Each voucher pays out only once; a copied or already-redeemed voucher is worthless. You can keep vouchers in chests or display them in item frames, but like any item they can be lost or stolen. The server can restrict redemption of these older vouchers to the player who made them.

---

[Wiki home](Home.md) · [Previous: Biome Disruption](Biome-Disruption.md) · [Next: The Trading Post](Trading-Post.md)
