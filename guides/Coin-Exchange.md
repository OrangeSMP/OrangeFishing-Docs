# Doubloon Exchange

> Based on OrangeFishing 1.0.0 defaults. Check the server’s menus for customized requirements, prices, and rewards. Calendar dates use US/Eastern by default.

**Doubloons** pay for fishing upgrades, augments, fees, and disruption charges. **Server money** is your separate Essentials balance. Open `/fish exchange` to convert doubloons into server money.

Doubloons appear as **whole numbers** in chat, item descriptions, Java menus and Bedrock forms, rounded to the nearest doubloon with halves rounded up: `12.2234` shows as `12`, and `12.5` shows as `13`. Your balance, fish values, prices and rewards keep their exact amounts behind those displays. Fractions still accumulate, and sales, purchases and exchanges use the exact saved or requested amounts. Dollar quotes and payouts keep their normal decimal precision.

Future catches use diminishing returns on their stored sale value: size, rarity and value bonuses still help, while stacked bonuses approach **75 doubloons ($150) per fish**. Previously caught fish retain their saved dollar value. Existing balances and frozen rewards use the smaller denomination too: 1,000 old doubloons become 1 current doubloon, without losing fractional value.

The default exchange rate is **1 doubloon = $2.00**:

| Doubloons | Server money |
| --- | --- |
| 1 | $2 |
| 100 | $200 |
| 1,000 | $2,000 |
| 10,000 | $20,000 |
| 100,000 | $200,000 |

Menus show server money with thousands separators and leave off `.00` for whole amounts, such as **$10,000** or **$12.50**.

Choose a preset (**1, 100, 1,000, 10,000 or 100,000 doubloons**), click **Exchange All Doubloons** to convert your whole balance up to the per-exchange maximum, or use `/fish exchange 1` for a custom amount, then review and confirm the quote. The confirmation stays open after each exchange, so you can click **Confirm** again to exchange the same amount once more (one second apart by default). The default minimum is 1 doubloon, the maximum is 100,000 doubloons, and the cooldown is one second. Fractional input amounts are supported up to five decimal places and are exchanged exactly, even though the doubloon summary shows a whole number; the dollar payout rounds down to its configured money precision.

This exchange works from doubloons **into** server money. It does not buy doubloons with server money. To give doubloons to another player, make a doubloon voucher with `/withdraw fishingcoins` instead. Seasonal materials are a separate resource and cannot be exchanged here.

If a payout remains pending, contact staff so they can check it. Repeated clicks will not produce additional payments, and further exchanges may stay unavailable until that payout is resolved.

### Doubloon vouchers

Doubloon vouchers are not made from the exchange menu. If your server runs a withdraw plugin that supports doubloons, use its command to turn doubloons into an item you can trade or give to anyone; the doubloons go back into a fishing balance when the voucher is redeemed.

Doubloon vouchers made earlier with the old exchange-menu button (gold nuggets named **Doubloons • ×1000**, showing their amount) still work. Hold one in your **main hand and right-click**, or deposit it like a fishing bundle through **Deposit Items** (`/fish deposit`), `/fish deposit all`, or by clicking it in your inventory while a storage menu is open. Each voucher pays out only once; a copied or already-redeemed voucher is worthless. You can keep vouchers in chests or display them in item frames, but like any item they can be lost or stolen. The server can restrict redemption of these older vouchers to the player who made them.

---

[Wiki home](Home.md) · [Previous: Biome Disruption](Biome-Disruption.md) · [Next: Commands and Help](Commands-and-Help.md)
